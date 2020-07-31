此文件夹为GITHUB测试文件夹
20200718
学习git config --global user.name 添加用户名称
学习git config --global user.email 添加用户邮箱
学习git init命令：创建仓库
学习git add “file” 命令，上传修改文件
学习git commit -m “comment” 命令，提交修改文件
学习git status 命令，检查是否有文件修改
学习git diff 命令，常看文件修改变化
学习git log 命令，检查提交日志
学习git reflog 命令，检查文件回滚日志
学习git reset --hard HEAD 命令，实现提交文件的回滚
学习git reset --hard “id” 命令，实现文件回滚的撤销
20200719
学习git checkout 命令，下载上次上传的原始文件
    新版本使用git restore “file” 实现上述功能
学习git reset HEAD 命令，撤销提交的修改
    新版本使用git restore --staged “file” 实现上述功能
学习git rm "file" 命令，实现对文件跟踪的删除
20200731
学习远程仓库使用
    github.com网站建立账号
    创建repository，对应本机git init
    使用ssh-keygen 创建密钥对用于访问
    使用git remote add origin 命令添加本地库与远程库的关联
    使用git remote remove origin 命令删除本地库与远程库的关联
    关联方式可以使用https或者ssh，使用ssh需要密钥对
    使用git push -u origin master 进行首次上传仓库，以后不用-u
    使用git clone 命令可以从远程库下载至本地库
学习git branch 命令查看当前分支
学习git switch -c 命令创建分支
学习git switch “name” 命令更改当前分支
