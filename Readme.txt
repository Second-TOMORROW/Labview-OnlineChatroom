1.这是一个基于Labview的即时通讯聊天室程序
	可以创建聊天室并发布，可以加入别人创建的聊天室
	可设置网名，并且可以显示在线成员的名字。
2.作者：TOMORROW；主页：www.tomorrow.wiki
3.开发环境：Labview2016 ，程序框图有密码保护，
	如需查看或修改程序框图，请参考：http://www.tomorrow.wiki/archives/764
4.该工程包含文件：Client.vi;addstring.vi;Server.vi 。
	其中Client.vi为主程序，addstring.vi和Server.vi为子程序，
	主程序需要依赖子程序才能运行；一般情况下放置同一文件路径下，
	运行Client.vi即可
5.使用时，需要由一个客户端来创建聊天室(端口默认为20058)，然后其他
	客户端根据创建聊天室的电脑的IP地址来加入到聊天室；需要注意的是，
	客户端直接必须在同一局域网内，并且需要注意有没有被电脑的防火墙屏蔽了
6.该程序只是作者开发用于娱乐与学习，有许多设计不合理的地方；不用太在意哈哈
7.更多关于此工程详细的说明和信息请参考：http://www.tomorrow.wiki/archives/764

