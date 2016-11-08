> Push :直译过来就是「推」的意思，什么意思呢？如果你本地代码有更新了，那么就需要把本地代码推到远程仓库，这样本地仓库跟远程仓库就可以保持同步了。

> 代码示例： git push origin master

> Pull：直译过来就是「拉」的意思，如果别人提交代码到远程仓库，这个时候你需要把远程仓库的最新代码拉下来，然后保证两端代码的同步。


> 代码示例： git pull origin master

> 意思就是把远程最新的代码更新到本地。一般我们在 push 之前都会先 pull ，这样不容易冲突。

> 友情提醒，在提交代码之前先要设置下自己的用户名与邮箱，这些信息会出现在所有的 commit 记录里，执行以下代码就可以设置：

> git config --global user.name "stormzhang"

> git config --global user.email "stormzhang.dev@gmail.com"

> Log 查看
>  git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit --date=relative  

> 给 Git 输出着色，输入如下命令即可：

> git config --global color.ui true

> git config --global core.quotepath false # 设置显示中文文件名

> git diff <$id1> <$id2>   # 比较两次提交之间的差异

> git diff <branch1>..<branch2> # 在两个分支之间比较 

> git diff --staged   # 比较暂存区和版本库差异

> 我们知道 checkout 一般用作切换分支使用，比如切换到 develop 分支，可以执行：

> git checkout develop

> 我们知道 merge 分支是合并的意思，我们在一个 featureA 分支开发完了一个功能，这个时候需要合并到主分支 master 上去，我们只需要进行如下操作：


> git checkout master

> git merge featureA

> 查看本地分支列表

> git branch 

> 查看远程分支列表

> git branch -r 

> 删除本地分支

> git branch -d develop

> git branch -D develop (强制删除) 

> 删除远程分支

> git push origin :develop

> 如果远程分支有个 develop ，而本地没有，你想把远程的 develop 分支迁到本地：

> git checkout develop origin/develop

> 同样的把远程分支迁到本地顺便切换到该分支： 

> git checkout -b develop origin/develop


