# FRP客户端和服务端一键安装脚本

#### 介绍
frpc一键搭建服务端和客户端脚本
支持一键卸载
支持开机自启动



#### 安装教程
方法1
```shell
wget https://gitee.com/liushuheng-666/frp/releases/download/0.44.0/frp.sh && chmod +x frp.sh && ./frp.sh
```
方法二
```shell
curl https://gitee.com/liushuheng-666/frp/releases/download/0.44.0/frp.sh && chmod +x frp.sh && ./frp.sh
```
如果都不行请手动下载frp.sh文件并上传到服务器然后赋予可执行权限chmod +x frp.sh 然后请输入./frp.sh执行

#### 使用说明
客户端启动指令 systemctl start gujiu.service<br>
客户端停止指令 systemctl stop gujiu.service<br>
客户端重启指令 systemctl restart gujiu.service<br>

服务端启动指令 systemctl start frps.service<br>
客户端停止指令 systemctl stop frps.service<br>
客户端重启指令 systemctl restart frps.service<br>


#### 参与贡献

1.  Fork 本仓库
2.  新建 Feat_xxx 分支
3.  提交代码
4.  新建 Pull Request
