git是什么？
    版本控制工具，用于管理代码


    区别:
        git分布式管理
        svn集中式管理
    

    流程:
        1、(未初始化的情况下)初始化  git init
        2、添加文件到本地仓库     git add '文件名'
        3、提交文件到本地仓库     git commit -m '说明自此提交修改了哪些文件，主要做了哪些操作'
        4、(假如远程仓库已经存在)把本地仓库文件推送到远端  git push


    分支:
        拉取远端代码并进行更新 git pull = (git fetch拉去远端代码 + git merge 合并代码)

        切换分支: git checkout '分支名'

        查看分支: git branch -a