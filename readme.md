# git使用方法

* `git init`将文件夹变成git仓库

* add到暂缓区

  - `git add readme.md`添加单个文件
  - `git add .`添加所有的文件(不包括空文件夹)
  - `git add *.md`添加所有的.md文件
  - `git add -A`添加所有状态的文件


* `git status`查看是否有文件没有提交到暂缓区

    - 如果未提交文件,运行`git diff readme.md`查看修改了什么

* `git commit -m '说明' -a`提交全部文件的说明
* `git commit -m '说明' -readme.md`提交单个文件的说明

* `git log --pretty=oneline`将历史提交版本在一行显示出来
* `git reset --hard HEAD~1`或者`git reset --hard HEAD^`进行版本的回退

* `git remote add origin http://github.com/Lee908105576/XXXX.git`添加github上的版本库地址
* `git push -u origin master`提交到远程版本库并和版本库关联在一起

* `git branch dev`创建dev分支，是从master分出来的(里面的内容相同)
* `git checkout dev`切换到dev分支
* `git merge dev`在当前的分支上合并dev分支
* `git branch -d dev`删除dev分支
* `git branch`查看现在有哪些分支.
