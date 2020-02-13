# software_backup
一些常用的linux软件备份，以免以后不好下载了。
所有的docker镜像均用docker save导出并使用gz压缩，请解压后再用docker导入镜像。

#### calicoctl
```console
./calicoctl_1.6.5
# calico-docker网络初始化必须要用的软件
./quay.io_calico_node_v2.6.12.tar.gz
# calico-docker-node容器镜像
```

#### phpipam（docker镜像）
```console
./phpipam-cron_v1.4.tar.gz
./phpipam-www_v1.4.tar.gz
# IP地址管理软件的docker镜像
```

#### openvpn（docker镜像）
```console
./kylemanna-openvpn.tar.gz
# openvpn的docker镜像，软件版本OpenVPN 2.4.7，OpenSSL 1.1.1c
./openvpn-install-2.4.8-I601-Win10.exe
# openvpn win10客户端，自带中文
```
