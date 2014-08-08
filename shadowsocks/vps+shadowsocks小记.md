##vps+shadowsocks小记

###准备工作
* 有一台可用的vps。(比如我选择了[linode])

###在vps上安装shadowsocks

* 参考[这里]：

###在vps上安装supervisor

监控shadowsocks运行。
如此可使shadowsocks开机启动等。安装过程也见上面链接。


###本地为ubuntu系统
* 安装shadowsocks在本地机器上
* 使用和服务端一样的配置，使用`sslocal`来启动客户端
	* 可参考[配置客户端]
* 给浏览器安装扩展
	* 在chrome上安装扩展`switchysharp`,请自行baidu/google
	* 在firefox上推荐使用`foxyproxy`,这里[有个教程]

###本地系统为windows/macosx
* 安装一个shadowsocks的windows版本,你可以[从这里取到]。
* 简单配置后，你就可以给浏览器安装扩展了。操作方法同上。

**如此完毕，在浏览器输入www.youtube.com，恭喜你爬出来了。其实偶是程序员，偶只为了google~~**


注：如果你使用我文中的链接注册了linode,使用3个月后，我可以获得官方给的$20，你可以找我平分：）于人有利，于已无损，不妨为之。）


[linode]: https://www.linode.com/?r=3cf6f5721f63883d30708715bbc6a608adc2fcf4
[这里]: http://www.inkrope.com/archives/1622
[配置客户端]: http://www.6zou.net/tech/shadowsocks-how-to.html
[有个教程]: http://www.97world.com/archives/2684
[从这里取到]: http://sourceforge.net/projects/shadowsocksgui/