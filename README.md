# Aria2 Configures

自用aria2配置

## Sources

- GUI: [Aria2NG](https://github.com/mayswind/AriaNg)
- Core: [aria2](https://github.com/aria2/aria2)
- HideRun.vbs: [p3terx](https://p3terx.com/archives/use-aria2-under-windows.html)
- aria2 client: [Aria2 & YAAW 使用说明](https://aria2c.com/usage.html)
	- [说明](#Aria2---CLI-Metalink/BitTorrent-Client)

## Files

Aria2NG.html	GUI
HideRun.vbs		隐藏运行
Kill.vbs		结束运行
aria2.conf		aria2配置
aria2.exe		taskbar运行
aria2.log		日志
aria2.session	进度(只保存未完成)
aria2c.exe		core program
dht.dat			DHT file
dht6.dat		DHT file with ipv6


Aria2 - CLI Metalink/BitTorrent Client
========

使用说明
--------
    运行 aria2.exe
    访问 http://aria2c.com/ 查看状态
    下载后的文件保存在 Aria2Data 文件夹中

文件说明
--------
    Aria2Data     # 下载目录 默认下载文件会保存在这里
    aria2.conf    # 配置文件 可以自己根据说明修改
    aria2.exe     # 启动文件 使用这个来启动 aria2
    aria2.session # 任务保存文件 未完成任务会保存在这里
    aria2c.exe    # 命令行主程序
    README.md     # README
