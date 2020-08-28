# Git新建或导入库
create a new repository on the command line
```
echo "# WebBlog" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:wangyuetingtao/WebBlog.git
git push -u origin master
```         
or push an existing repository from the command line
```
git remote add origin git@github.com:wangyuetingtao/WebBlog.git
git branch -M master
git push -u origin master
```