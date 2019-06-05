# git commands

### Frequent use for everyone:
* add        加入文件到缓冲区
* branch     显示列表，创建，或删除 分支。
* checkout   检出分支 或 根据git目录地址切换到相应的工作区
* clone      克隆一个仓库到新的目录 （可以是本地仓库，也可以是远程仓库）
* commit     记录提交到版本库的更改
* diff       显示版本差异 （可以根据commit_id,tag,branch等等）
* fetch      从其他仓库中获取 文件和引用
* merge      合并分支 （可以是两个或多个）
* pull       =fetch + merge
* push       把本地仓库修改推送到远程关联仓库
* log        显示提交日志 Show commit logs
* status     显示当前工作区的状态
### Frequent use for me:
* stash
* stash pop
### Maybe useful:
* blame
* rebase     Forward-port local commits to the updated upstream head
* reset      重置当前指针到特定的状态
* grep       从git仓库中搜索匹配到的文字或文件
* init       创建一个空的Git仓库或重新初始化现有仓库
* mv         重命名文件，目录或符号链接
* rm         从当前工作区中删除文件
* show       显示各种类型的对象信息 （一次提交，一个tag，一个分支等等）
* tag        创建，删除，显示或者验证 标签


# Practice

### E1
```
git init --bare share.git
```
### E2
git clone url
### E3
git checkout -b test
### E4
vim .gitignore
git add
git commit -m'First commit'
git push origin test:test
### E5
git reset
### E6
git diff
git merge
### E7
git blame
### E8
git pull
git push
