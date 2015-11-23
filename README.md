# 台泥資訊Big Data 課程


## 啟用Cloudera Manager (獨立設置一台)

### 關閉selinux
- $ sudo vi /etc/selinux/config
- SELINUX = disabled

### 關閉防火牆
- sudo setup

### 修改 SWAP 設定
- $ sudo vi /proc/sys/vm/swappiness
- vm.swappiness=0

### 設定NTP Server
- sudo service ntpd start

### 產生ssh key
- ssh-keygen -t rsa
- cat ~/.ssh/id_rsa.pub >> ~/.ssh/authroized_keys

### 修改HOSTNAME
- sudo vi /etc/hosts
- chkconfig iptables off
- sudo vi /etc/sysconfig/network

### 重啟伺服器
- sudo reboot

## 啟用Hadoop 機器




