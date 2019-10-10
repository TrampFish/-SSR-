# -SSR-
1、控制面板安装debian82系统，安装系统后修改debian82的DNS  修改DNS方法：    打开/etc/resolv.conf,比如内容如下：  nameserver 192.168.10.1  改成一组解析服务器即可：  nameserver 8.8.8.8  nameserver 8.8.4.4    2、修改后开始SSH连接，执行命令：wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubi/doubi/master/ssr.sh &amp;&amp; chmod +x ssr.sh &amp;&amp; bash ssr.sh
