# 220414

- branch

가지를 나눠서 main에 영향을 주지 않고
새로운 브랜치에서 개발하여 운영에 영향을 끼치지 않고
자유롭게 개발가능

git branch - 브랜치를 새로 만들거나 브랜치 검색할 때
git switch - 브랜치 변경
git merge - 다른 브랜치의 파일을 합친다.

conflict가 발생할 시 기존거를 지우던지 새로운걸 지우던지 재조립을 해서
다시 commit 


- git flow practice
운영서버와 개발서버를 나누고따로 관리하여 혀율적으로 관리

git flow init - develop 브랜치에서 작업
git flow feature start 이름
파일 수정
git add
git commit
git flow feature finish 이름
git flow release start v0.1
git flow release finish v0.1


##
git push -u origin develpo

-u 는 다른게 아니고 같은거라고 알려주는 것

커밋은 리셋은 하지 말고 리버트를 사용



