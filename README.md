# Personal VPN
## Shadowsocks+V2Ray-plugin

Click the button below to deploy, and remember to order a Star if it works:

[![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy?template=https://github.com/Ximerixx/vpnlikeaherokuu)
---

Native V2Ray deployment: <https://github.com/ygcaicn/v2ray-heroku>

---
## 0. Client Configuration

QR code address: https://test.herokuapp.com/qr/vpn.png

(Change test to your own app name. If you changed the QR_Path (path to qr png, filled during deployment) variable, also change the corresponding qr_img to the modified one)

Use the client (Shadowsocks recommended) to scan the QR code.

**or**

Use Configuration file -> Address: https://test.herokuapp.com/qr/

(Change test to your own app name)

Copy the details after opening and import it to the client.

**or**

Manual configuration:

```sh
Server: test.herokuapp.com (change test to your app name)
Port: 443
Password: The password filled in during deployment
Encry Method: RC4-MD5 (or other methods you fill in)
Plugin: v2ray
Plugin Transport mode: websocket-tls
Hostname: Same as Server
Path: The path you filled in during deployment
```

Those without a client can also download from here (Android):

[shadowsocks](https://github.com/shadowsocks/shadowsocks-android/releases/latest/download/shadowsocks--universal-5.1.9.apk)

[v2ray-plugin](https://github.com/shadowsocks/v2ray-plugin-android/releases/latest/download/v2ray-arm64-v8a-1.3.1.apk)

windows:

<https://github.com/shadowsocks/shadowsocks-windows/wiki/Shadowsocks-Windows-%E4%BD%BF%E7%94%A8%E8%AF%B4%E6%98%8E>