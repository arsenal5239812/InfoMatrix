---
banner: "![[Backup/Figures/湖雨.png]]"
banner-radius: 17
banner-height: 450
pixel-banner-flag-color: black
---
## Day 05
### 1. HTTPS 和 HTTP 有哪些区别？
HTTP 是一个在计算机世界里专门在**两点**之间之间**传输**文字、图片和视频等**超文本**数据的**约定和规范**。
如果**安全**放入概念是指信息是否会被泄漏的话，GET 使用 URL 传输，数据会在浏览器地址栏容易看到；由于 HTTP 传输的内容都是明文的，虽然在浏览器地址栏看不到 POST 提交的 body 数据，但是只要抓个包就都能看到了。
所以要避免传输过程中数据被窃取，就要使用 HTTPS 协议，这样所有 HTTP 的数据都会被加密传输。