# git使用方法简约版

## 下载安装

### Ubuntu Linux

```
sudo apt update
sudo apt install git
```

### windows



#### Mac OS

```
homebrew install git
```



## 主要使用方法

### 将修改后的文件添加到暂存区

```
git add <file>  #添加单个指定文件
git add .       #添加所有修改的文件
git checkout -- <file> #丢弃对指定文件的修改
git reset --hard #清除所有文件的修改
git reset HEAD <file> #将已经通过git add添加到暂存区的修改踢出暂存区,但是文件修改未丢弃
```

### 暂存区的修改贡献到本地

```
git commit -m "用于标注此次贡献的注明"
```

### 将本地的贡献推送到远程仓库

```
git push origin master #推送到远程origin的master分支
```

