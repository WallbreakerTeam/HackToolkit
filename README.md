# HackToolkit use
①导入插件：<br/>
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/toolkit-1-1.jpg' /><br/>
②会出现一个NotePad选项卡，打开它:<br/>
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/toolkit-1-2.jpg'/><br/>
③里面有很多按钮，只要是国人应该都可以理解意思。<br />
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/notepad-1-1.jpg'/><br/>
④在Proxy—>Intercept截包，右键可以看到go to HackToolkit里面包含了三个选项：<br/>
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/go-to-HackToolkit-1-1.jpg'/><br/>
a.New Text Document（新建文本）：New Text Document主要是把Intercept和HTTP history页面的request和response请求发送到NotePad页面记录，不需要通过saved items保存（因为会进行base64加密）。<br/>
b.go to Nmap（打开Nmap可视化界面）：<a href='https://github.com/WallbreakerTeam/BurpNmap'>前文已有介绍</a><br/>
c.go to Dirbuster（打开目录爆破页面）：<br/>
填入爆破目标：<br/>
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/dir1-1.jpg'/><br/>
正在爆破：<br/>
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/dir1-2.jpg'/><br/>
网站目录树：<br/>
<img src='http://www.whitecell-club.org/wp-content/uploads/2016/10/dir1-3.jpg'/><br/>

相对于上次的TomcatBrute，这次的BurpNmap和HackToolkit独立出一个窗口，而且程序也不会崩溃，多次导入也不会失败，还加入了多线程，使程序处理更快，不过有一点需要注意的是BurpNmap取消了自动获取域名IP。<br/>

原文：http://www.whitecell-club.org/?p=1391
