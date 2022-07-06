

原本只有三种上网方式:DHCP动态获取/PPPoe拨号/静态地址 

新版本增加IPV6 和旁路由. 

### 源码仓库：  

## git clone  https://github.com/sirpdboy/luci-app-wizard


## 2022.7.7  设置向导 更新日志：

 1。 升级设置向导1.2 
 2.  增加自动判断设置网卡，路由模式最后一个网卡为WAN口，其它口为LAN口。 旁路由模式将绑定全部网卡为LAN口。
 3.  修复IPV6 有时候修改不生效问题。
 
 
## 2022.6.10  设置向导 更新日志：

 1。 升级设置向导1.1 
 
 2.  增加旁路由和IPV6功能。
 
 3.  在原版的基本上重写代码和界面分布功能。
 
 
 
 致谢：
 
x-wrt：https://github.com/x-wrt/com.x-wrt/tree/master/luci-app-wizard

kiddin9：https://github.com/kiddin9/luci-app-wizard
