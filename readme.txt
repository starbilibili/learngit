how to use git

//初始化git仓库:必须到想要建仓库的目录下
git init

//添加文件到git仓库:分两步，第二步的message是本次提交的说明
git add <file>
git commit -m <message>

//查看是否有文件被修改过
git status

//查看修改的内容
git diff