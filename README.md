## Study-Git
Git과 GitHub 시작하기 (호눅스) 강의

## git 명령어 요약
 - clone: 원격 저장소 (github) 을 내 컴퓨터에 복사해 온다.
 - add: 내 컴퓨터에서 작업한 파일들을 스테이지에 추가
 - commit: 스테이지에 올라온 파일들을 가지고 내 컴퓨터에 저장 (세이브와 같다.)
 - push: 커밋들을 원격 저장소에 업로드

## 파일의 내용 되돌리기
 - 특정 파일의 내용을 마지막 커밋으로 되돌리고 싶다면 해당 파일 선택 후 '코드 뭉치 버리기' 선택


## 브랜치 변경하기
 - 브랜치 : 기존 내용을 유지한 채 새로은 내용을 추가하고 싶을 때 사용한다.
 - 체크아웃 : 특정 브랜치(혹은 커밋)으로 돌아가고 싶을 때 사용
 - 소스트리의 체크아웃 : 브랜치 이름을 더블클릭 하는 것 만으로 체크아웃이 가능하다.


## 병합하기1
 - 헤드 브랜치에 변경사항이 없고 
 - 병합 대상 브랜치가 헤드로부터 시작된 경우
 - 아주 쉽게 병합 가능 = fast-forward 


 ## 병합하기2
 - 헤드 브랜치에 추가적인 커밋이 생기는 경우
 - 진짜 병합이 필요해진다.
 - 충돌이 안나면 좋은데, 충돌이 나도 겁내지 마라. 


 ## 충돌해결하기
 - 제일 중요한점 : 겁내지 말기!!!
 - 같은 파일을 병합 대상 두 커밋에서 동시 수정했을 경우 충돌이 날 확률이 높다!
 - 에디터 사용, 혹은 SourceTree를 사용해서 충돌 해결 가능하다.


 ## 커밋되돌리기

 ## reset 사용하기

 - 장점 : 쉽다
 - 단점 : 커밋이 날아간다. 그리고 강제 푸시가 필요하다.


 ## branch 만들어서 되돌리기
  - reset과는 달리 내용이 살아지지 않는다.
  - 장점 : 쉽다.
  - 단점 : 트리가 지저분해진다.