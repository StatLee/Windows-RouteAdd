# Windows-RouteAdd
腾讯云Windows Server 手动添加路由小工具

功能简述：
route add的图形化工具，支持客户指定某个IP(单IP，非网段)或域名(不支持动态域名，即带有CDN的域名) 通过 某个网卡 进行通讯，场景一般是客户需要某个域名通过特定路由通讯。

开发语言：

PowerShell v2.0

适用平台：

Windows Server 2008 R2 、 Windows Server 2012/2012R2 、 Windows Server 2016/2019
Wndows 7 SP3、Windows 8、Windows 10

版本：v1.3

功能信息：

1、支持输入IP或域名自动解析

2、支持列出带有网关信息的网卡并提供选择

3、可视化的路由添加过程

4、支持回滚操作

下载成品链接：

https://platform01-1252076932.cos.ap-chengdu.myqcloud.com/statli_tools/RouteAddV1.2.exe

若运行时闪退可能是因为PowerShell策略限制，可手动运行该命令进行解锁：

powershell "Set-ExecutionPolicy -ExecutionPolicy Unrestricted -force |Out-null"


