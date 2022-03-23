# 自启管理

## 安装

```shell
sudo pip3 install supervisor
# or
# sudo apt-get install supervisor
# sudo yum install supervisor
```

## 查看配置文件 

```shell
cat  /etc/supervisor/supervisord.conf
```

## 添加启动文件

- program: <项目名(唯一)>
- directory: <工作目录>
- command: <执行命令>
- autostart: <自启>
- autorestart: <退出重启>
- user: <用户>
- stdout_logfile: <日志文件>
- https://www.jianshu.com/p/0b9054b33db3

```shell
[program:gateway_fast]
directory = /home/toybrick/
command = gateway_fast
autostart = true
autorestart = true
user = toybrick
stdout_logfile = /home/toybrick/gateway_fast.log
```

## 使用

```shell
# 更新配置文件
sudo supervisorctl update
# 查看所以进程状态
sudo supervisorctl status
# 重启、启动、停止
sudo supervisorctl restart(全部)
sudo supervisorctl stop(全部)
sudo supervisorctl start(全部)

sudo supervisorctl start xx (某个)
```
