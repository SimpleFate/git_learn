# git
> to learn git

- git 流程  
    1. 本地修改
    2. add
    3. commit
    4. pull
    5. push
 - 命令

       git status 查看仓库状态  
       git diff
           #between state 1 & state 2
           git diff 查看未add的修改

           #between state 2 & state 3 
           git diff --cached 查看add未commit的修改

           #查看已提交的版本和本地修改后的版本的区别 
           git diff HEAD 上面两条的合并