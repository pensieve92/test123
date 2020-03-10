
현재 디렉토리에 clone  
git clone https://github.com.pensieve92/test123.git .

------------------------------------------------------------------------

git init

git status

git add README.md

git commmit -m "first commit"

git config --global user.email "pensieve92@gmail.com"

git config --global user.name "byeonghyeon jeon"

git config --global --list

git config --list

git remote add origin https://github.com.pensieve92/test123.git

git push -u origin master

------------------------------------------------------------------------
git commit 취소  
git log (나오기 [q])  
git reset --soft HEAD~1 마지막 1개 취소  

------------------------------------------------------------------------

git checkout -b beta

git branch


git add . 

git commit -m "create branch"

git push -u origin beta

------------------------------------------------------------------------

git checkout master

git branch

git merge beta

git push

------------------------------------------------------------------------
git add . warning  
warning: LF will be replaced by CRLF in pensieve-frontend/package.json.  
The file will have its original line endings in your working directory  
os 마다 차이가 있어서 발생한다고 함

git config --global core.autocrlf false

https://bnzn2426.tistory.com/33

------------------------------------------------------------------------

파일명 변경
git mv homePage.js HomePage.js
git status
git commit -m "rename file name"

------------------------------------------------------------------------
