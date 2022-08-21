# 2022_소웨경_myVer

Git 사용법
-초기 설정
1. 개발을 진행할 local 위치에서 git clone하기
git clone https://github.com/KSJ0128/-.git

-개발 진행(branch 없는 경우)
1. 새로운 브랜치 생성
git checkout -b {name} 

2. 브랜치에서 기능 구현하며 구현 단위 별로 commit 하기 
git commit -m "로그인 구현"

3. 개발 완료 후 해당 브랜치를 main에 push 하기
git push origin {name}

4. PR 요청하기


-개발 진행(branch 있는 경우)
remote repo(github)의 master를 pull 하기

1. master 브랜치로 이동하기
git checkout master

2. main 브랜치 업데이트 하기 (변경사항 업데이트)
git pull origin main

3. 개발 브랜치로 이동하기
git checkout -b {name}

4. 개발 브랜치에 변경사항 적용
git merge main
