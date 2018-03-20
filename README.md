# WEBAPP
运行系统为Ubuntu 16.04 x86_64

先在服务器端安装以下服务
```
sudo apt-get install python3-pip
sudo apt-get install nginx supervisor mysql-server
```
再利用pip安装python插件
```
pip3 install jinja2 aiomysql aiohttp
```
然后在开发机器端安装fabric（windows上需要安装cygwin）,实现自动上传更新