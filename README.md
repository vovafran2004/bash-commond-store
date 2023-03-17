# 常用Bash命令

网络

```sh
//查看网卡信息
ifconfig
ip addr 
//启动关闭网卡
sudo ip link set eth0 up
sudo ip link set eth0 down
//设置mtu值
sudo ip link set eth0 mtu 8000
//编辑netplan
sudo nano /etc/
```

服务

```sh
//新建服务


//编辑服务内容


// 开启服务
sudo systemctl start myapp.service
// 重启服务
sudo systemctl restart myapp.service
// 停止服务
sudo systemctl stop myapp.service
//查看log
sudo journalctl -u myapp.service
// 重载
sudo systemctl daemon-reload
```

装pip包

```sh

```

装载大恒相机驱动