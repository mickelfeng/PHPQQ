PHPQQ
=====

这是一个终端版QQ客户端，用PHP完成, 访问QQ服务器的方式与WebQQ一样，所以如果WebQQ更新，本客户端将无法使用

###依赖的PHP扩展

  * 1.JSON扩展，如果时默认安装的最新版本PHP一般都有
  * 2.PCNTL扩展
  * 3.Ncurses扩展，编译时你必须激活--enable-ncursesw选项，否则中文乱码

###目前状态
  * 1.能获取好友列表，以及在线列表，
  * 2.能接收到好友信息，
  * 3.发送信息的方法已经实现，只是由于界面问题无法使用

###最终实现：
  * 将发送消息完成，
  * 实现好友分组，
  * 实现在线状态显示，
  * 文件发送与接收
