## xray/trojan一键脚本



## 脚本集合内容：

-    安装Xray-VMESS
-    安装Xray-VMESS+mKCP
-    安装Xray-VMESS+TCP+TLS
-    安装Xray-VMESS+WS+TLS
-    安装Xray-VLESS+mKCP
-    安装Xray-VLESS+TCP+TLS
-    安装Xray-VLESS+WS+TLS(可过cdn)
-    安装Xray-VLESS+TCP+XTLS
-    安装trojan
-    安装trojan+XTLS



## 安装方式 
## 注：安装前先更新系统为最新，安装过程中如有问题先卸载脚本再重新安装

`wget --no-check-certificate "https://github.com//jackmoo1/xray/raw/main/xray.sh" && chmod +x xray.sh && ./xray.sh`

快捷启动`./xray.sh`


## 2021.9.8

- 修复域名无法解析 
- 修复xray无法更新 


## 2021.10.13
-  XTLS协议的配置，添加路由分流规则
-  路由规则文件可参考[**Loyalsoldier**](https://github.com/Loyalsoldier/v2ray-rules-dat)大佬的说明和使用方法
-  路规则文件`geoip.dat`和`geosite.dat`所在位置`/usr/local/share/xray`，可自行替换更新

## 2021.11.4
-  添加了证书状态查询，可查看证书申请和到期时间，方便自住更新和添加自由证书的朋友
  【`脚本卸载后会保留原域名生成的证书，所以卸载重装为相同域名时，非重新生成证书而是重装`】
-  XTLS协议增加DNS解锁配置，安装xray后，再次重启脚本，设置可解锁DNS地址（需配合`geosite.dat`文件注意及时更新，与添加解锁`netflix`，`hbo`，`hulu`，`disney`，`fox`，`bbc`，`bilibili`等网站，需解锁其他网站自行在配置文件里修改）



## 更多玩法以及打算自己折腾的小伙伴
-  ## 可参考Xray各部分配置说明[**配置说明**](https://xtls.github.io/config/)和[**使用指南**](https://xtls.github.io/document/)，配置成自己的Xray! ##

【介于目前Xray/Trojan的稳定性，后期Xray/Tojan无重大更新，或者脚本无问题，更新佛系！】




