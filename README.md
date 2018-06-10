# PCMode
---
## 硬件准备
- Mate10
- Dock
- Dell S2817Q 4K显示器
- ThinkPad KT-1525带小红点键盘

---
## 基于应用场景的PC化办公最佳实践  
在我看来，随着网络的建设(5G的到来)，会有越来越多的应用是处在云端的。  
各种类型的终端将无处不在，没有人需要随身带着手机。  
只要用身边的任何一个终端，采用自己的生物ID进行认证，就能接入处在云端的服务。  
所以，一下的所有推荐，都基于以下原则：  
1. 优先推荐web服务  
2. 其次，是推荐完美适配PC模式的Android应用  
3. 最后是一些奇淫技巧，比如Termux和Linux Deploy

### 写Markdown(SimpleMarkdown)  
SimpleMarkdown是目前发现的最好用的markdown编辑器，它支持实时显示。  
这篇指导将完全用SimpleMarkdown编写。

### Office办公  
其实不管是Microsoft还是Google，现在的云端办公已经做的非常好了，完全可以替代传统的PC本地Office，说不定还能有别的惊喜。  
当然因为墙的原因(微软的服务器也因为国外，国内访问不太顺畅)，最好能够翻墙，我用的是[Google的云端办公工具](https://docs.google.com/document/u/0/)。

### 阅读  
学习对我来说是一件非常重要的事情，我会选择看一下PDF格式的电子书，当然Android本身就有很多很好用的PDF阅读器。  
不过我始终认为web应用才是未来的方向，我推荐的是叫[kamihq](https://web.kamihq.com/web/viewer.html)的在线PDF阅读器，它能够同时访问Google硬盘和打开本地文件。并且拥有非常优秀的标注功能。  
如果你用chrome打开这个网页，你还可以将它添加到桌面，就像一个本地应用一样使用它，因为它是一个PWA应用。

### 浏览网页 (星尘浏览器) 

### 听音乐(网易云音乐)

### 本地网上邻居视频

### 看代码(Vim)

### 思维导图  

---
## 如果这还无法满足你的要求
### Linux环境(termux、Linux Deploy)  
一般情况下，termux能够满足大多数linux能够完成的任务。  
它的优点在于，1)可以通过包管理工具pkg安装大部分在Linux下的工具，如：Vim、git、python等。  2)它本质上是个普通的APP，模拟了安卓环境而已，你无需对手机做root等不安全操作。
> [Termux is an Android terminal emulator and Linux environment app that works directly with no rooting or setup required.](https://wiki.termux.com/wiki/Main_Page)  

如果Termux仍无法满足你的需求，还有两个方案：  
1) 通过Linux Deploy在手机上chroot一个完整的Linux系统
> 这么做的缺点是，需要root手机，这既不安全，又很麻烦，不推荐。  

2)ssh/vnc到一台正常的LinuxPC  
这篇文章会将所有工作都在非root的手机上完成。

### Windows  
如果你非要使用Windows系统，也不是完全没有办法：

- **TeamViewer**：连接到你的WindowsPC。
- **华为云电脑**：华为云电脑是华为提供的云化PC服务，只要有网络，就能够连接到云上的PC去完成传统的PC能做的所有事情。
