# SpechtLite
适用于SpechtLite的规则

## 使用 
默认的配置文件目录为 ~/.SpechtLite

下载：

	git clone https://github.com/silence0201/SpechtLite

添加服务器设置：

```
- id: Tokyo   // 服务器的名字  
    type: ss   // 服务类型  
    host: 127.0.0.1   // 地址  
    port: 8080  // 端口
    method: AES-256-CFB // 加密方式
    password: 123456  // 密码
```
手动将所有文件复制到~/.SpechtLite或利用下面脚本
      
给setup脚本添加执行权限：
 	
 	chmod u+x *.sh
 	
执行：
 
 	./setup.sh
 
 	
## 说明
主要配置文件包括下面几个：

- [🏃Auto.yaml](🏃Auto.yaml):适用于多服务器配置，所有的服务器会自动选择
- [🇯🇵Tokyo.yaml](🇯🇵Tokyo.yaml):单服务器配置,日本服务器配置
- [🇭🇰Hong_Kong.yaml](🇭🇰Hong_Kong.yaml):单服务器配置,香港服务器配置
- [pollutedip](pollutedip):根据[Wikipedia](https://zh.m.wikipedia.org/zh-cn/域名服务器缓存污染)被污染DNS得出的被污染IP列表
- [directlist](directlist):直连域名列表
- [directiprange](directiprange):直连ip列表
- [proxylist](proxylist):代理域名列表
- [proxyiprange](proxyiprange):代理ip列表
- [rejectlist](rejectlist):需要屏蔽的域名列表
- [rejectiprange](rejectiprange):需要屏蔽的ip列表

## SpechtLite
SpechtLite is available under the MIT license. See the LICENSE file for more info.

 
 
 
      