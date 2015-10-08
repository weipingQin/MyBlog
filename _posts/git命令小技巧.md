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
 