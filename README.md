# gittips
some git tips.
初始化 git init 
文件添加到git 第一步 git add 可以多次使用，添加多个。
			  第二部 git commit -m 'xx' 把add的文件提交到git 增加说明
使用git status 查看工作区的状态
如果工作区有文件修改 使用git diff 查看区别 直接git diff 可以查看，如果没有修改无返回
git reset --hard id(oed1) git恢复到提交id的状态
git log可以查看每次commit的注释和id 方便 git reset --hard 回复到某个id
git reflog 可以查看版本回退的id 向前恢复
git的暂存区 如果忘记 查看 https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/0013745374151782eb658c5a5ca454eaa451661275886c6000
git diff HEAD -- xx.txt命令可以查看工作区和版本库里面最新版本的区别
git checkout --file 可以撤销工作区的修改
git rm  删除工作区的文件，git commit   
查看分支 git branch
创建分支 git branch <name>
切换分支 git checkout <name>
创建+切换分支 git checkout -b <name>
合并某个分支到当前分支 git merge <name> 
删除分支 git branch -d <name>
关联远程库 git remote add origin git@server-name:path/repo-name.git
关联库之后，git push -u origin mastrer 第一次推送
git push origin master 提交修改
