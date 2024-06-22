# BlogAssets
（[我的博客](https://blog.helloallen.cn/)）的静态资源

## 如何通过 Github + jsDelivr + PicGo 打造一个稳定快速、高效免费的图床
[搭建手册](https://blog.helloallen.cn/2023/12/54ac777ea276.html)

## 在没有PicGo工具时，如何手动操作Github静态资源库
#### 1. github上如何创建一个空文件夹
因为github不允许创建空文件夹，所以我们`Create new file`之后，在文件夹名称后面添加一个`/`。然后随便输入一个空文件，该文件夹就创建成功。

#### 2. 外部如何调用此处的静态资源
通过这种方式：  
`https://cdn.jsdelivr.net/gh/user/repo@latest/file`  
例如：  
`https://cdn.jsdelivr.net/gh/HelloAllenW/BlogAssets@latest/images/2020/04/jsdelivr-1.png`

## 说明
jsdelivr国内网络不能访问，暂时未找到解决方案（2024.6.22）
