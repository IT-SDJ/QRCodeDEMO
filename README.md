# 二维码扫描功能DEMO

使用 [APICloud](https://www.apicloud.com) 平台技术，完成二维码扫描功能的开发。可以使用 HTML 代码自定义二维码扫描页面的样式

## 使用必读

### 使用模块:[FNScanner](https://docs.apicloud.com/Client-API/Func-Ext/FNScanner)

FNScanner 模块是一个二维码/条形码扫描器。在 iOS 平台上本模块底层集成了系统自带扫码功能。

注意：使用本模块前，需在云编译页面勾选添加访问摄像头权限，若要访问相册也需沟通申请访问相册权限

### DEMO 的安装运行流程说明

- 登录 APICloud 控制台新建一个应用

- 使用 APICloudStudio2 或第三方 SVN 工具软件将应用代码下载到本地

- 下载本 DEMO 的源码覆盖新建的应用代码

- 将新的应用代码同步到云端

- 在控制台将 FNScanner 模块从模块商店添加到本应用

- 进行云编译

- 扫描编译成功后的二维码，安装应用，体验运行效果