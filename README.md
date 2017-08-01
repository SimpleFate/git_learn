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


       git log
           #查看commit历史记录
           git log
           git log --pretty=oneline
           git log --graph
        
       git reflog
           #查看命令历史

- 版本回退 将工作区改为某个版本  
    ```git reset --hard HEAD```  
    1.HEAD HEAD^/HEAD~1 HEAD^^/HEAD~2  
    2.commit id  

    ![](F:/code/git_repo/git_learn/gitreset.jpg)
- 管理修改  
  git 管理的是修改。
  add、commit都是对**修改**进行添加，提交。

- git checkout  
```
  #在add之前，丢弃工作区的更改
  git checkout --file

  #在commit之前，丢弃工作区的更改
  git reset HEAD file
  git checkout --file
  
  ```
this is on branch dev.
