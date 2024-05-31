> # hiddify next config
[![Hiddify](https://img.shields.io/badge/Download-Hiddify-cyan?style=plastic)](https://github.com/hiddify/hiddify-next)

[![Termux](https://img.shields.io/badge/Download-Termux-orange?style=plastic)](https://github.com/termux/termux-app/releases/tag/v0.118.0)

> [!NOTE]
> ### The code below in run to Thermox
> #### gives you the 3 parameter

```bash
curl -sL "https://api.zeroteam.top/warp?format=sing-box" | grep -Eo --color=never '"2606:4700:[0-9a-f:]+/128"|"private_key":"[0-9a-zA-Z\/+]+="|"reserved":\[[0-9]+(,[0-9]+){2}\]'
```
---

> [!NOTE]
> ### Paste the values ​​obtained in the above code into the below json script
> #### Convert Reversed Decimal to Base64 and ==> [Reversed Converter](https://ptechgithub.github.io/abzar)
```json
{
  "outbounds": 
  [
    {
      "type": "wireguard",
      "tag": "Warp-IR",
      "server": "162.159.195.93",
      "server_port": 2506,

      "local_address": [
        "172.16.0.2/32",
        "2606:4700:110:81ce:ac8:6185:22b4:2e93/128"
      ],
      "private_key": "uGMI0FLxhgioJLcFoXXHBIS8nKNaxAkZfa619pp4UG0=",
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": "x771",

      "mtu": 1280,
      "fake_packets": "5-10"
    },
    {
      "type": "wireguard",
      "tag": "ÐΛɌ₭ᑎΞ𐒡𐒡🇩🇪",
      "detour": "Warp-IR",
      "server": "162.159.195.93",
      "server_port": 2506,
      
      "local_address": [
          "172.16.0.2/32",
          "2606:4700:110:8c70:3022:5217:1309:dc1f/128"
      ],
      "private_key": "mLlO/qw3toC/hKG+SYSmla6IA+11RNQRCwxYPxOLmhQ=",
      "peer_public_key": "bmXOC+F1FxEMF9dyiK2H5/1SUtzH0JuVo51h2wPfgyo=",
      "reserved": "SyUQ",  

      "mtu": 1120,
      "fake_packets": "5-10"
    }
  ]
}
```
---

> ### Finally, copy the code in the add from clipboard to hiddify next program

> ## 👨‍💻[Json Above Code](https://github.com/mansor427/workers/blob/main/WoW.json)
---
> ### Convert to mini json ==> [minijson](https://jsonformatter.org/json-minify)
---
> credit converter ==> [ptechgithub](https://github.com/Ptechgithub/abzar)
