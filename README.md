QQbot备份
`docker pull asupc/qqbot

docker run --name qqbot1 -v /root/qqbot1/app:/app -p 5010:5010 asupc/qqbot -restart:always  

cd /root/qqbot1

git clone https://ghproxy.com/https://github.com/afwfv/qqbot.git app

docker restart qqbot1`
