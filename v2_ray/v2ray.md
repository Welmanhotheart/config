command: 
    docker run -d --name=v2ray -p 1088:10800 -p 1089:10809 v2ray/official
    docker cp config.json  v2ray:/etc/v2ray/
config_file:
    config.json
    