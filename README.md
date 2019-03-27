### 使用

编辑 `ehforward_config/profiles/default/blueset.telegram/config.yaml `
```
token: "你的机器人token"
admins:
- 你的tgid
```

编辑 `docker-compose.yml`
```
- VNC_PASSWD=你的密码
- COOLQ_ACCOUNT=你的qq账号
```

执行 `docker-compose up -d`

打开 `ip:9801` 登陆novnc后完成coolq登陆操作

`docker logs -f qqbot` 
Scan the QRCode to login

打开手机微信扫码，扫描屏幕上的二维码，然后确认登录。
