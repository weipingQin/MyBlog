#git命令的一些小技巧 
今天发现了一个很有用的小命令 
## 忽略提交的一些文件
```
touch .gittignore 

## 在提交的时候碰到这个问题 带有分支的git的项目 比如我的博客 

```
fatal: 'gh-pages' does not appear to be a git repository
fatal: Could not read from remote repository.

* 命令用错了 

```
 git pull origin gh-pages 
 git push origin gh-pages
* 我用的时候一不小心 写成了git pull gh-pages 少了origin 
 

## 命令行工具 
下载地址 http://git-scm.com/download/
小技巧 : 在windows下 命令行下不能直接ctrl+V来实现复制 这个时候 按下键盘上的Insert来复制 
配置环境变量
将git的安装目录加进相应的环境变量中去 
D:\SoftWareInstall\git\cmd 

接下来要配置你的开源中国账号的git设置了 
参考这篇文章 step by step 记住：耐心
http://git.oschina.net/oschina/git-osc/wikis/%E5%B8%AE%E5%8A%A9
配置完了之后 你可以自己测试一下账号是否有问题 可不可以提交 
然后有一套完整的git教程 你可以慢慢学习慢慢看 
http://www.yiibai.com/git/home.html
但是基本的几个命令要熟记于心 
git init 
git add .
git status 
git commit -m "first commit" 记住 每次提交的时候 -m m代表message 就是提交时候的日志 而且是必须写的 
git pull origin master 
git push origin master 
当你第一次提交的时候 还需要把远程的链接加入进去 
git add remote origin URL链接 
分享一些小经验:
github提交代码时候，出现 fatal:Could not read from remote repository

>使用 git remote rm origin 就OK了  

推荐个git详细教程 
<a>http://www.hanshuliang.com/?post=8</a>
不会的到那里去看 

