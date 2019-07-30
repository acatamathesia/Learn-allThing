# Git使用流程

## Git init

使用git init会在当前目录下，添加git控制，也就是.git

![1564476293133](C:\Users\nkd20\AppData\Roaming\Typora\typora-user-images\1564476293133.png)

## 添加控制后，使用git add . （或者文件名）

```git
git add Readme.md
// 使用 . 会将当前目录下所有的文件添加到缓存中
git add .
```

## 使用Commit提交

```git
// 添加文件到本地仓库中
git commit -m "描述信息"
// 如果不添加描述信息，会vim
git commit
```

## 连接远程仓库

```git
// 注意 使用ssh需要将你在本地生成的密钥注册到你的github中
git remote add origin https (or SSH)

```

## 拉取

```git
// 从主分支中拉去项目信息
git pull origin master
```

## 提交

```git
// 将选中的文本提交到远程仓库中
git push origin master
```

## 分支

### 创建分支

```git
// 创建分支
git branch 分支名称
```

### 查看分支

```git
// 查看分支
git branch
```

### 选择分支

```git
// 
git checkout 分支名称
```

### 合并分支

```git
// 将其他分支内容合并到主分支上
git merge 其他分支名称
```

### 删除分支

```git
git branch -D 分支名称
```



## 冲突

### 查看冲突

```git
git diff //查看冲突
```

