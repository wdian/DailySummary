vim .ssh/config 添加主机信息:如下所示

Host $name
Hostname 192.168.3.91
Port 22
User $user

然后执行：

ssh-copy-id $name 键入密码

