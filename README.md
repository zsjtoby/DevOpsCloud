
#欢迎使用极云监控系统
极云监控系统实现了跳板机应有的功能。基于ssh协议来管理，客户端无需安装agent。
支持常见系统:
 1. CentOS, RedHat, Fedora, Amazon Linux
 2. Debian
 3. SUSE, Ubuntu
 4. FreeBSD
 5. 其他ssh协议硬件设备


首页
 
![webterminal](https://github.com/ibuler/static/raw/master/jumpserver3/index.jpg)

WebTerminal:

![webterminal](https://github.com/ibuler/static/raw/master/jumpserver3/webTerminal.gif)

Web批量执行命令

![WebExecCommand](https://github.com/ibuler/static/raw/master/jumpserver3/webExec.gif)

录像回放

![录像](https://github.com/ibuler/static/raw/master/jumpserver3/record.gif)

跳转和批量命令

![跳转](https://github.com/ibuler/static/raw/master/jumpserver3/connect.gif)

命令统计

![跳转](https://github.com/ibuler/static/raw/master/jumpserver3/command.jpg)


### 安装

cd /opt

git clone https://github.com/zsjtoby/DevOpsCloud

cd DevOpsCloud/install

python install.py

### 特点

* 完全开源，GPL授权
* Python编写，容易再次开发
* 实现了跳板机基本功能，认证、授权、审计
* 集成了Ansible，批量命令等
* 支持WebTerminal
* Bootstrap编写，界面美观
* 自动收集硬件信息
* 录像回放
* 命令搜索
* 实时监控
* 批量上传下载
* 权限控制
