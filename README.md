# TIL : Today I learned

1Day 1Commit 을 위한 용어 정리

1. Local Repository 로컬 저장소
- 내 PC의 저장소 (해당 디렉토리로 가서 커멘트창에 ```git init```)

2. Remote Repository 원격 저장소
- ```git clone``` 명령어로 기존 원격 저장소를 로컬에 받을 수 있음

3. Working Directory 작업폴더
- 작업이 일어나는 폴더

4. Staging Area(Index)
- 작업 폴더에서 작업한 변경 내용을 기록하는 곳(git 저장소에 commit하기 전에 올려두는 공간)
- Stage에서 commit을 하게 되면 git 저장소로 변경 내용이 저장됨

5. ```git status```
- 파일의 상태를 확인하는 명령어

6. ```git add```, ```git add 파일1, 파일2```,```git add .```
- 작업 폴더에서 작업한 변경을 stage에 올릴 때 사용하는 명령어

7. ```git commit```
- ```git add``` 명령어로 스테이지에 추가한 수정 파일을 git 저장소에 저장

8. ```git push origin master```
- commit한 파일을 원격 저장소에 올리는 명령어
- ```git push <원격 저장소 이름> <브랜치 이름>```

9. ```git fetch origin```
- 로컬에는 없지만 원격 저장소에 올라가 있는 데이터를 모두 가져옴(업데이트라고 생각하면 됨)
- ```git fetch <원격 저장소 이름>```

10. ```git pull origin master```
- git pull은 원격 저장소에서 업데이트된 내용이 있는지 확인하고 내 로컬 소스에 반영하는 기능

11. ```git merge <commit>```
- 브랜치 병 -> 현재 작업중인 브랜치에 합칠 commit을 지정해서 병합
- <commit> 위치에는 주로 병합할 브랜치 이름을 넣고, commit checksum을 넣어도 됨
  
12. ```git checkout -b JWK```
- JWK이라는 브랜치 생성
- ex) 현재 feature 브랜치에서 작업을 하다가 JWK 브랜치로 전환을 하려면 위와 같은 명령어를 실행하면
- ```git checkout main``` : main으로 가서 동기화 해야됨
- Pull requests 해야함

13. ```git clean -fd```
- git이 추적하지 않는 untracked files 한꺼번에 삭제
