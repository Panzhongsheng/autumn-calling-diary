### Git提交代码

步骤：

1. git init
2. **git remote add origin 链接(gittee链接)**
3. **git pull origin master**
3. **git add .**
4. **git commit -m '说明’**
5. **git push origin master**



#### Github中master和main分支合并

```sh
$ git checkout -b main
# Switched to a new branch 'main'
$ git branch
# * main
#  master
$ git merge master # 将master分支合并到main上
# Already up to date.
$ git pull origin main --allow-unrelated-histories # git pull origin main会报错：refusing to merge unrelated histories
$ git push origin main
```

