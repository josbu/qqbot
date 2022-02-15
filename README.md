QQbot备份
```
docker pull asupc/qqbot
mkdir qqbot1
cd /root/qqbot1 && git clone https://ghproxy.com/https://github.com/josbu/qqbot.git app
docker run --name qqbot1 -v /root/qqbot1/app:/app -p 5910:5010 asupc/qqbot -restart:always  
docker restart qqbot1
```

