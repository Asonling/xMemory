# xMemory 家用云服务器


## 【项目缘起】

中国大陆 80后开始的年轻人过年回家三大技术工作 —— 修电脑、存照片、下电影……

父母辈的人在我们童年接触电脑、互联网时大多正值工作繁忙的壮年，因此退休后直接“跨越式”地直接步入移动互联网 —— 智能手机、平板电脑 微信耍起、照片拍起、视频看起……

但因 **移动设备**依然有一些短板，需要 PC 来辅助 ——

 1. 无论 机身内置、TF 扩展卡、个人公有云服务，存储空间都较小，迁移、备份不方便
 2. 至今都无方便整理、查阅大量 照片、录音、视频的 App
 3. 众多非院线影片国内无版权，迅雷（移动版）资源搜索、下载速度 相较 PC 版也有更大限制
 4. SeaFile、ownCloud 等开源私有云存储服务器 安装、使用、维护较为复杂

所以，作为一个准全栈工程师，带着十多年的技术思考，我在 2017年正月的家中写下了本项目的第一份代码 —— 让老妈躺在沙发上抱着平板电脑开心地看了一部电影~


## 【技术栈】

 - 编程语言：HTML 5、CSS 3、JavaScript(ES 5+)
 - UI 框架：[EasyWebUI](//git.oschina.net/Tech_Query/EasyWebUI)
 - 前端基础库：Require.js、jQuery
 - SPA 引擎：[EasyWebApp](//git.oschina.net/Tech_Query/EasyWebApp/tree/String_Template)
 - 后端引擎：Node.JS
 - HTTP 服务器：[EasyREST.js](//git.oschina.net/Tech_Query/EasyREST.js)


## 【安装方法】

 1. 下载 [Node.JS 最新 LTS 版](https://nodejs.org/zh-cn/)，并安装
 2. 下载 [xMemory 最新公测版](https://github.com/TechQuery/xMemory/archive/master.zip)，并解压到一个新文件夹
 3. 在上述文件夹中执行 `npm install  &&  npm start` 命令
 4. 服务器启动后，即可在网页浏览器中用 `//localhost:8081/` 访问


## 【使用方法】

### 视频点播

| 操作系统 | MP4 | RMVB | AVI | MKV |
|:-------:|:---:|:----:|:---:|:---:|
| MIUI    | √   | √    | √   | √   |
| iOS     | √   |      |     |     |