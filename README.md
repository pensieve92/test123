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

error: failed to push some refs to 'https://github.com/pensieve92/test123.git'

local과 remote의 상태가 달라서 pull을 먼저 해줘야한다.

git pull
