# Git


## 1. git 초기설정

### 1.1 깃 생성
`git init `

### 1.2 터미널 코드 자동완성 여부
`git config --global core.autocrlf true`

### 1.3 유저이름 설정
`git config --global user.name '유저명'`

### 1.4 유저이메일 설정
`git config --global user.email '깃허브이메일주소'`

### 1.5 설정확인
`git config --global --list`


## 2. git 등록절차
### 2.1 파일 업로드(로컬)
`git add .`

### 2.2 파일 커밋(로컬)
`git commit -m "커밋내용"`

### 2.3 커밋 로그 확인
`git log`

### 2.4 깃허브 레포지토리에 연결
`git remote add origin 레포지토리URL주소` 
> origin 은 연결할 레포지토리의 이름으로 통상 origin이지만 다른이름을 써도 가능

### 2.5 깃허브 레포지토리에 업로드
`git push origin master`


## 3. git 수정

### 3.1 수정변경 상황이 있는지 상태확인
`git status` `git add . `  <- 초기 스테이터스는 빨간색 add 하면 초록색으로 바뀜
`git log` <- 이전 커밋내역 확인가능


## 4. git 브랜치관리

### 4.1 브랜치목록 확인
`git branch`
`git branch -a` <- 원격저장소(빨간색)의 브랜치도 확인가능

### 4.2 브랜치생성
`git branch 브랜치명`

### 4.3 브랜치변경
`git checkout 브랜치명`
=======
`git checkout 브랜치명`

### 4.4 브랜치 생성후변경
`git checkout -b 브랜치명`


## 5. git 원격 레포지토리 다운로드

### 5.1 원격저장소 정보 가져오기
`git fetch origin 브랜치명`

### 5.2 원격저장소정보 로컬브랜치와 병합
`git merge origin 브랜치명/master브랜치`

> 로그를 확인하여 head 주소값을 가져와 병합할수도 있음

### 5.3 레포지토리 통합 다운
`git pull origin 브랜치명`
