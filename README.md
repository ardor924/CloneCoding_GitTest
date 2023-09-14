# GitHub


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
