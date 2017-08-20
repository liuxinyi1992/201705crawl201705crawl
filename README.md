## 记住自己的IP
```
101.37.80.83
```

## 连接服务器
先打开gitbash
连接服务器
```
ssh root@101.37.80.83
``
是否要连接时选择yes
输入密码时输入 Zfpx2017
> 密码输入时不显示的，直接输入然后回车即可
出现以下提示就表示成功了
```
Welcome to Alibaba Cloud Elastic Compute Service !
```
## 升级操作系统
```
apt-get update
```

## 安装npm
npm是node包管理器
```
apt-get install npm
```

## 安装`n`
n是一个node模块，可以用来安装node
```
npm install n -g
```

## 安装node
```
n latest
```

## 安装git
```
apt-get install git
```
## 安装mongodb
```
apt-get install mongodb
```
> mongdb 安装完成后会自动启动，不需要手工启动了


## 在服务器上把代码下载下来
```
git clone https://github.com/zhufengnodejs/201705crawl201705crawl.git
```

## 启动服务器
进入项目所在的目录
```
cd 201705crawl201705crawl
```
下载依赖的模块
```
npm install
```
设置日志的环境变量
```
export DEBUG=crawl:*
```
启动项目
```
node tasks/main.js
```


