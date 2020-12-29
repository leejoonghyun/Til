# Git command

> Git 명령어 정리



### 0. init

- `git init`

- `.git/ ` 폴더를 생성 해준다.

![image-20201229151404914](command.assets/image-20201229151404914.png)

- `.git`폴더가 생성된 경우 오른쪽에 `master`라는 포시가 나온다.

- 폴더당 최초의 한번만 적용하면 된다.



### 1. add

- `git add <추가하고싶은 파일>`
  - `git add .` : 현재 폴더의 모든 파일과 폴더를 add
- working directory => staging area 로 파일 이동



### 2. config

- `git config --global user.email "myemail@gmail.com"`
  - 이메이플의 경우 Github에 올릴경우 잔디가 심어지는 기준이므로 정확한 입력 필요.
- `git config --global user.name "myname"`
- 최초의 한번만 하면 된다.



### 3. commit

- `git commit -m "message"`
- 스냅샷을 찍는 동작
- add 되어있는 하나의 묶음으로 저장

- 메세지에 들어가는 내용은 기능 단위로 작성



### 4. remote

- `git remote add origin "adress"`
- 원격 저장소와 현재 로컬 저장소를 연결



### 5. push

- `git push origin master`
- ''깃아 올려줘 origin으로 master를''
- 원격저장소에 로컬 저장소의 데이터를 전송



### 6. status

- `git status`
- 현재 git 상태를 출력




