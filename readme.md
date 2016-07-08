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
