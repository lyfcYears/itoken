git init 初始化
git add readme.txt 加载到缓冲区  
git add . 添加全部文件
git commit -m "first commit"   加载到存储区
// 认证
 ssh-keygen -t rsa -C "youremail@example.com"  然后把pub添加到远程仓库

git remote add origin git@github.com:lyfcYears/itoken.git  添加远程仓库之前需要进行ssh认证 也就是密钥


git push -u origin master 
-u ，就是创建 upStream 上传流，如果没有这个上传流就无法将代码推送到 github；同时，这个 upStream 只需要在初次推送代码的时候创建，以后就不用创建了

---多人开发 先git pull
再git push 默认推送origin master

