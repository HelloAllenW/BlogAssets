# BlogAssets
（[我的博客](https://helloallenw.github.io/)）的静态资源

# 如何通过 Github + jsDelivr + PicGo 打造一个稳定快速、高效免费的图床
[搭建手册](https://helloallenw.github.io/2023/12/12/Github%20+%20jsDelivr%20+%20PicGo%20%E6%89%93%E9%80%A0%E7%A8%B3%E5%AE%9A%E5%BF%AB%E9%80%9F%E3%80%81%E9%AB%98%E6%95%88%E5%85%8D%E8%B4%B9%E7%9A%84%E5%9B%BE%E5%BA%8A!/)

# 在没有PicGo工具时，如果手动操作Github静态资源库
## github上如何创建一个空文件夹
因为github不允许创建空文件夹，所以我们`Create new file`之后，在文件夹名称后面添加一个`/`。然后随便输入一个空文件，该文件夹就创建成功。

## 外部如何调用此处的静态资源
通过这种方式：  
`https://cdn.jsdelivr.net/gh/user/repo@latest/file`  
例如：  
`https://cdn.jsdelivr.net/gh/HelloAllenW/BlogAssets@latest/images/2020/04/jsdelivr-1.png`
