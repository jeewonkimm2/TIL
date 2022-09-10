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
- 브랜치 병함 -> 현재 작업중인 브랜치에 합칠 commit을 지정해서 병합
- <commit> 위치에는 주로 병합할 브랜치 이름을 넣고, commit checksum을 넣어도 됨
  
12. ```git checkout develop```
- 브랜치 전환
- ex) 현재 feature 브랜치에서 작업을 하다가 develop 브랜치로 전환을 하려면 위와 같은 명령어를 실행하면 


  
  
  
---
  
  
  
  
  
### Footprint ###
  
2022.09.08 : [BOAZ Spark RDD 발제 준비][TILlink]

[TILlink]: https://github.com/jeewonkimm2/TIL/blob/main/220908_Spark_RDD_Presentation.ipynb

2022.09.09 : [AIFFEL 1강][TILlink1]

[TILlink1]: https://github.com/jeewonkimm2/TIL/blob/main/1_딥러닝한테_손글씨_숫자_가르쳐주기_(1)_모델_설계.ipynb

2022.09.10 : [AIFFEL 2강][TILlink2]

[TILlink2]: https://github.com/jeewonkimm2/TIL/blob/main/2_%EB%94%A5%EB%9F%AC%EB%8B%9D%ED%95%9C%ED%85%8C_%EC%86%90%EA%B8%80%EC%94%A8_%EC%88%AB%EC%9E%90_%EA%B0%80%EB%A5%B4%EC%B3%90%EC%A3%BC%EA%B8%B0_(2)_%EB%AA%A8%EB%8D%B8_%ED%95%99%EC%8A%B5.ipynb
