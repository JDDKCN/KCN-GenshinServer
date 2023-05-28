# KCN-GenshinServer

![Github](https://socialify.git.ci/JDDKCN/KCN-GenshinServer/image?description=1&forks=1&issues=1&language=1&logo=https%3A%2F%2Favatars.githubusercontent.com/u/103011451?v=4&name=1&owner=1&pulls=1&stargazers=1&theme=Light)

> 以GC为基础制作的原神一键GUI多功能服务端。

---

### 关于软件
- 软件还不完善，就多谢大家debug&提issues了！将来可能会写一些方便的新功能，敬请期待喵~ 
 > 当前服务端版本：3.7.0

### 软件下载：
- 请到最新[Releases](https://github.com/JDDKCN/KCN-GenshinServer/releases/)处下载。

### 软件截图 ： 
- v0.1.0-Beta 2023/05/29
![APP_CN](Doc/image01.png)

### 更新日志 ： 
- v0.1.0-Beta
  1. 发布了软件。

### 程序使用说明：
- 首次启动(单机模式)
  1. 选择你的原神客户端路径。
  2. 点击<一键启动服务>按钮。这会启动数据库以及服务端进程。
  3. 点击<启动游戏>按钮。这会启动代理进程及游戏。如果程序没有在您的计算机上检测到mimproxy的CA证书，程序将会打开安装程序。请您在弹出的安装证书对话框中点击安装。
  4. 您可以开始游戏了。Enjoy it😊
- 联机(本地服务器)
  1. 选择联机模式按钮。(基础信息-左上角)
  2. 在基础信息-服务器IP文本框中，填入本机内网/公网IP地址。如果您不知道IP，请点击查看IP按钮，将IP地址复制到文本框中。
  3. 在客户端代理-服务器IP/域名文本框中，填入刚才输入的IP地址。如果不知道，请不要勾选<使用SSL>单选框。本端的本地GC服务默认为Http协议，无需勾选。
  4. 点击<一键启动服务>按钮，此时你已经可以在局域网/公网中联机了。
  5. 点击客户端代理-测试连接按钮。如果服务启动成功，您会看到连接成功的提示。
  6. 点击<启动游戏>按钮，开启代理并进入游戏。
- 联机(远程服务器)
  1. 选择联机模式按钮。(基础信息-左上角)
  2. 在客户端代理中输入要连接的远程服务端IP/域名。不要输入http(s)://,如果您的连接是Https连接，那么请勾选<使用SSL>单选框。如果您的连接是Http连接，则请不要勾选。
  3. 点击<测试连接>按钮。如果远程服务器可用，您会看到连接成功的提示。
  4. 点击<启动游戏>按钮，开启代理并进入游戏。
- 注入Mod(3dmigoto)
  1. 请点击3dmigoto-一键注入按钮。程序将启动注入程序及原神主程序。如果在启动后看见程序上下边栏出现绿色的字母/数字，则说明注入成功。
  2. 请点击3dmigoto-打开mod文件夹按钮，把解压好的mod放入文件夹中，重启游戏即可。
- GM工具
  1. 请前往[GrasscutterTools](https://github.com/jie65535/GrasscutterCommandGenerator)项目查看使用方法。

### 免责声明：
- 本程序是基于Github开源项目[Grasscutter](https://github.com/Grasscutters/Grasscutter)制作的原神一键GUI多功能服务端，仅供研究交流用，禁止用于商业及非法用途。使用本软件造成的事故与损失，与作者无关。本程序完全免费，如果您是花钱买的，说明您被骗了。请尽快退款，以减少您的损失。

### 联系方式：
- [前往我的B站首页](https://space.bilibili.com/475547854/)
- [前往我的Twitter账号](https://twitter.com/2233KCN)