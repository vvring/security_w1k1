## MITM攻击流量劫持
- https://github.com/Ettercap/ettercap    //C。Linux下网络中间人攻击欺骗。
- https://github.com/bettercap/bettercap    //Go。中间人欺骗，网络攻击以及监控的瑞士军刀。该工具支持多种模块，比如中间人钓鱼框架、ARP/DNS欺骗、TCP以及数据包代理等。GREATJOB。
- https://github.com/Binject/backdoorfactory    //Go。bettercap的二次开发拓展，用于将shellcode插入到网络上所有类型的二进制文件中。G:/secretsquirrel/the-backdoor-factory;--
- https://github.com/mitmproxy/mitmproxy    //Py。中间人攻击，支持SSL拦截，进行https流量代理。greatjob。15k。
- https://github.com/qiyeboy/BaseProxy    //Py3。异步http/https代理，楼上简化版。可以作为中间人工具，比如说替换网址图片等
- https://github.com/LionSec/xerosploit    //中间人攻击测试工具包
- https://github.com/infobyte/evilgrade    //一个模块化的脚本框架，使攻击者在不知情的情况下将恶意更新注入到用户更新中
- https://github.com/AlsidOfficial/WSUSpendu    //可以自主创建恶意更新，并将其注入到WSUS服务器数据库中，然后随意的分发这些恶意更新
- https://github.com/quickbreach/smbetray    //专注于通过文件内容交换、lnk交换来攻击客户端，以及窃取任何以明文形式传输的数据
- https://github.com/mrexodia/haxxmap    //对IMAP服务器进行中间人攻击
- https://github.com/SySS-Research/Seth    //PY3/BASH。Linux下MitM RDP远程服务中间人攻击。G:/citronneur/rdpy rdp远程服务模拟开启
- http://ntwox.sourceforge.net    //ntwow多协议伪造，网络测试工具集
- https://github.com/Ekultek/suddensix    //Bash。SLAAC（无状态地址自动配置）攻击自动化脚本，可用于在IPv4基础架构上构建IPv6覆盖网络，以执行中间人攻击。
### WiFi中间人攻击
- https://github.com/wifiphisher/wifiphisher    //Py。中间人攻击，FakeAp恶意热点，WIFI钓鱼，凭证窃取。goodjob,7k。
- https://github.com/1N3/PRISM-AP    //自动部署RogueAP(恶意热点) MITM攻击框架
- https://github.com/sensepost/mana    //Wifi劫持工具，可以监听计算机或其他移动设备的Wifi通信，并能够模仿该设备
- https://github.com/deltaxflux/fluxion    //bash,Py。对使用wpa协议的无线网络进行MiTM攻击
- https://github.com/DanMcInerney/LANs.py    //Py。无线网络劫持ARP欺骗
### 近源中间人攻击
- https://github.com/tenable/router_badusb    //利用路由器USE上网口和DHCP协议，使用树莓派连接VPN模拟流量转发进行中间人攻击。
### 工业协议中间人
- https://github.com/reidmefirst/modbus-vcr    //利用Ettercap插件对Modbus系统执行MITM攻击。记录10秒钟的Modbus通信后重放。