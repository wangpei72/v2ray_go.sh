# v2ray_go.sh
==go.sh offline_version==

本脚本可以实现离线（本地，有v2ray.zip文件即可，已经放在本仓库里）安装v2ray内核.
推荐搭配Ｑv2ray实现ui界面.

需要的依赖，请执行以下命令

```shell
sudo apt-get install curl
```



1. 将v2ray.zip软件包放在 "/tmp/v2ray/"  路径下(没有v2ray文件夹的时候就自己新建一个),或者放在你自己能找到的地方,选择后者则需要修改在脚本文件中对应的文件路径语句

2. 在脚本文件所在目录下打开终端,运行 sudo bash go_offline.sh

3. 安装成功后,v2ray一般默认的可执行文件路径在 /usr/bin/v2ray/v2ray  资源目录: /usr/bin/v2ray 

4. 配置qv2ray,是Appimage文件直接点开执行，配置内核路径（参见上面），配置入站设置（可以更改端口号），输入订阅地址，链接服务器，科学上网

   喜欢请点个star，thank you!