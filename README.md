# 🔒Check Your SSL Every Day ! 
无后端每日检查特定网站的SSL证书状况

~~利用Travis-CI定时检测SSL状态并输出~~

使用Github Actions定时检测SSL状态并输出

# 开始

1. Fork 本项目，添加Secrets `DOMAIN`为你要绑定的域名、`SERVERS`为你要检测的网站，隔一个空格一个 eg.:`google.com baidu.com github.com ....`
2. 若绑定域名，请前往NS添加CNAME。
3. 前往Actions开启这个项目
4. 随便Push一下，比如把这个笑脸😊删掉
5. 打开Github Pages，并配置域名

## Demo：https://ssl.stevelbr.top

## 原作者项目：[SukkaLab/ssl](https://github.com/SukkaLab/ssl)
