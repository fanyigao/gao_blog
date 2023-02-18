git add .//添加所有文件
git commit -m "第n次提交"
git push origin main

git pull origin main //[仓库名] [分支名]
git remote add origin [仓库url]  //本地仓库连接远程仓库
git origin -v
git remote rm origin
git remote add origin [仓库url]

git config --global https.proxy
git config --global --unset https.proxy
