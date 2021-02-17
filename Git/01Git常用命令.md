## 创建 && 提交
```sh
git init
git add .
git commit -m "first commit"
git remote add origin 地址
git push -u origin master
```


## 提交到远程
```sh
git remote add origin https://github.com/kuzank/Program.git
git push -u origin master
```


## Remote  地址迁移后的处理
```sh
git remote rm origin
git remote add origin 地址
git remote update origin --prune
git branch --set-upstream-to=origin/分支名称 分支名称
```

