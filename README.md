# SpechtLite
适用于SpechtLite的规则

## 使用 
默认的配置文件目录为 ~/.SpechtLite

下载：

	git clone https://github.com/silence0201/SpechtLite

添加服务器设置：

	- id: Tokyo   // 服务器的名字
    	type: ss   // 服务类型
    	host: 127.0.0.1   // 地址
    	port: 8080  // 端口
      method: AES-256-CFB // 加密方式
      password: 123456  // 密码
 
 手动将所有文件复制到~/.SpechtLite或利用下面脚本
      
 给setup脚本添加执行权限：
 	
 	chmod u+x *.sh
 	
 执行：
 
 	./setup.sh
 
      