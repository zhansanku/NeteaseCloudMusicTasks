进入容器
docker exec -it qinglong bash
拉取方法一
ql repo https://ghproxy.com/https://github.com/chen310/NeteaseCloudMusicTasks.git "index.py" "" "py"&&task chen310_NeteaseCloudMusicTasks/ql_update.py
方法二
ql repo https://ghproxy.com/https://github.com/chen310/NeteaseCloudMusicTasks.git "index.py" "" "py"
创建任务
task chen310_NeteaseCloudMusicTasks/ql_update.py
安装依赖
apk add python3-dev gcc libc-dev
pip3 install requests json5 pycryptodomex
