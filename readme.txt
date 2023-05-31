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

//查看提交日志:HEAD指针指向的是当前版本
git log

//版本回退:会修改文件内容以及提交日志的内容
git reset --hard HEAD~1  //回退到上一个版本
git reset --hard HEAD~10 //回退到10个版本前

//回到未来:根据commit id来判断指向的版本，版本号只需提供前几位
git reset --hard <commit id>

//查看命令日志：包含每一次提交、版本变换
git reflog