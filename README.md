
# Github教程(示例)


- 1.安装 step
- 2 配置
    -  username useremail  


    git config --local user.name Anonymous
    git config --local user.email doitnow@email.com
    
        行尾 颜色
     
    git config --global core.autocrlf  true
    git config --global core.autocrlf input
    git config --global color.ui quto
    
    
- 3.init    

       本地仓库创建
        git init  
        git status<!--状态空间 -->
        
        git  add 
        云端创建仓库
    
- 4.commit    
#### 完整流程
    

    git init 
    
    git add
    
    git status
    
    git commit
    
    
    git .gitigore<!--在文件中添加不想要提交的文件 -->
    
    git branch login <!-- 创建另一个分支 login-->
    git commit -m 'another change'<!--提交  -->
    git checkout login<!--转到另外一个分支 -->
    
    <!--合并分支 -->
    git merge login
    
    
   -  提交到云端服务器 
    
    打开github.com登录 创建新仓库 复制仓库地址
    
    本地远程仓库
    git remote
    git remote add origin https://github.com/crowluya/website.git
    git remote 
    
    git push -u origin master
    <!-- 这里输入自己的github名字与密码-->

    touch README.md
    git add . <!-- 添加到空间-->
    git commit -m " ADDED README"<!--本地已经提交 远程仓库没有提交 -->
    git  push 
    
    git pull





