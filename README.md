# BaiduPCS-Web

这个项目基于BaiduPCS-Go, 可以让你高效的使用百度云

![avatar](https://user-images.githubusercontent.com/8407297/44954655-ba346e00-aed7-11e8-835d-59014e155aa7.png)
![avatar](https://user-images.githubusercontent.com/8407297/44954613-19de4980-aed7-11e8-963e-6366025bd9d7.png)
![avatar](https://user-images.githubusercontent.com/8407297/44954618-2e224680-aed7-11e8-8413-3a092f8ef9b6.png)

腾讯视频: https://v.qq.com/x/page/e0774xoeatv.html

## 安装
```bush
// install dependencies
npm install
```
## 运行
### 开发环境
```bush
// For the first time, run init to create index.html
npm run init
npm run dev
```
### 生产环境(Build)
```bush
npm run build
```

### 运行BaiduPCS-Go
程序已经打包好放在 [release](https://github.com/liuzhuoling2011/baidupcs-web/releases) 页面, Windows版本直接双击就可以使用

对于 Linux 和 Mac 版本:
```
打开终端: 
1. cd 到软件所在的目录
2. chmod a+x BaiduPCS-Go
3. ./BaiduPCS-Go
4. 打开浏览器, 在地址栏输入: localhost:5299 就可以看到界面了
```

### 运行出错
如果遇到程序启动错误, 应该是端口占用导致的, 可以指定端口运行

```./BaiduPCS-Go-xxx web --port 12345```

### 对于老版登陆后没有内容, 只显示 "No permission to do this operation"
登陆后在右上角的设置里面把appid设置为```266719```就可以正常使用了



