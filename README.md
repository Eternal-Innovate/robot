### 一、电脑端基本设置

##### 1.打开热点

![image-20250409224959245](image-20250409224959245.png)

##### 2.右键网络图标选择 打开网络设置

![image-20250409225146521](image-20250409225146521.png)

##### 3.选择更改适配器选项

![image-20250409225158510](image-20250409225158510.png)

##### 4.右键WLAN 选择状态

![image-20250409225211170](image-20250409225211170.png)

##### 5.点击属性

![image-20250409225220337](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225220337.png)

##### 6.选择共享

![image-20250409225228776](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225228776.png)

##### 7.选择允许共享

![image-20250409225236758](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225236758.png)

##### 8.家庭网络连接选择热点所在(本地连接**2一类)*

![image-20250409225244451](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225244451.png)

##### 9.（热点所在网络 一般为本地连接*2）可在通过关开热点查看来确定.

![image-20250409225253820](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225253820.png)

## 二、Clash配置

##### 1.启用配置中的局域网连接和TUN连接

![image-20250409225731527](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225731527.png)

![image-20250409225743836](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409225743836.png)

##### (记得正常启用clash --打开系统代理)


## 三、手机端设置

##### 1.选择连接电脑热点 (如果直接连接, 选择删除热点, 重新连接)

##### 2.选择热点连接设置中的代理 - 手动 

##### 3.在电脑端 开机界面输入cmd 查看命令提示符

![image-20250409230203584](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409230203584.png)

##### 4.在其中输入 命令ipconfig

##### ![image-20250409230259855](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409230259855.png)

##### 5.找到无线局域网适配器的Ipv4地址

![image-20250409230334499](C:\Users\HUAWEI\AppData\Roaming\Typora\typora-user-images\image-20250409230334499.png)

##### 6.在手机代理的服务器主机名中输入上方ipv4地址

##### 7.服务器端口 输入7890

##### 8.输入密码 连接, 检查是否成功代理(浏览外网)
