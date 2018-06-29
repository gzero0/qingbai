安装git


git init

创建文件


把文件添加到仓库
git add 文件名

查看状态
git status

git commit -m "提交注释"

创建文件
touch 文件名

查看文件内容
cat 文件名


删除文件
rm 文件名

查看提交记录
git log

回到上一个版本
git reset --hard HEAD^

^单个表示上一个版本 (几个箭头就代表返回几个版本)
回到~此符号后边填多少 就回到前几个版本
git reset --hard HEAD~100


如果又想回到刚才的版本，只要命令窗口没关掉就可以用 版本号返回，版本号只写前几位就可以了
git reset --hard 3628164

查看命令历史
git reflog