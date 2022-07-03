## 一鍵部署 Gost(ss+mws) 到 heroku  [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

> 1. 服務端部署後，應`open app` ，顯示`404 page not found`，則部署完成。

> 2. 客服端代理，編輯`client.vbs`，後雙擊執行，或直接運行命令。
> ```
> Const CommandLine = "gost.exe -L=:1080 -F=ss+mwss://chacha20:ss123456@appname.herokuapp.com:443"
> ```

> 3. Chrome安裝[SwitchyOmega](https://github.com/FelisCatus/SwitchyOmega/releases)插件，配置[GFWList](https://github.com/gfwlist/gfwlist)。

> 4. Android安装[Shadowsocks](https://github.com/shadowsocks/shadowsocks-android)和[ShadowsocksGostPlugin](https://github.com/xausky/ShadowsocksGostPlugin)。

[下載](https://github.com/xiaokaixuan/gost-heroku/releases/tag/v2.11.1)

### 附加> 1. 一鍵部署 Gost(ss+mws) 到 [KubeSail](https://kubesail.com/template/Creamcakhopen/trsdog/)。

### 參考文獻 
*https://github.com/ginuerzh/gost*

*https://github.com/gfwlist/gfwlist*

*https://github.com/xausky/ShadowsocksGostPlugin*
