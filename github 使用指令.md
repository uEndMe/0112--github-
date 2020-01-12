# github使用指南

* 准备

```
系统配置：npm,git,github...
git配置：git config...
仓库地址：https://github.com/uEndMe/0112--github-instruction.git
```

* 建仓库

```js
git init
//新建初始代码----
git add .
git commit -m "初始化"
git remote add origin pathxx
	//断开旧连接
	//git remote remove origin
git push origin master
```



* 分支操作

```js
git clone pathxx
cd xx/
//新建分支
git checkout -b water
	//拉取分支（有的话）
	//git fetch origin water:water
	//git checkout water
```

```js
//编辑初始版本 
git add.
git commit -m "初始分支"
git push origin water
```