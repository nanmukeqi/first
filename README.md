如何上传文件https://zhuanlan.zhihu.com/p/193140870<br>
生成密钥：ssh-keygen -t rsa -C “自己的邮箱”，（注：之后直接按回车就行，无需密码，过于麻烦），看是否生成成功看看对应文件夹下有没有id_rsa.pub这个文件，从而得到公钥<br>
创建本地文件夹，cd到本地文件夹，之后初始化，初始化之后会多出一个隐藏的.git文件夹，之后就进行添加（git add .），（git commit -m "引号中是注释"），最后进行关联远程仓库，并进行上传。<br>
git init //把这个目录变成Git可以管理的仓库<br>
　　git add README.md //文件添加到仓库<br>
　　git add . //不但可以跟单一文件，还可以跟通配符，更可以跟目录。一个点就把当前目录下所有未追踪的文件全部add了 <br>
　　git commit -m "first commit" //把文件提交到仓库<br>
　　git remote add origin git@github.com:wangjiax9/practice.git //关联远程仓库<br>
　　git push -u origin master //把本地库的所有内容推送到远程库上<br>
  
