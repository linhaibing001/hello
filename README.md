
#  telegram 简单应用列子


[ngork 官网链接] (https://dashboard.ngrok.com/get-started)    
[ telegram 聊天软件官网Api] ( https://core.telegram.org/bots/api)   
[图片托管平台 ]         ( https://postimages.org/)    

### 第一步
1.1ngork  作用： 本地映射为http 或https
![](https://s33.postimg.cc/w6fosbo9b/ngrok.jpg)
启动成功：
![](https://s33.postimg.cc/fwpipd0pr/ngrok.jpg)

域名：（看结果决定）
Forwarding                    http://e390d735.ngrok.io -> localhost:80
Forwarding                    https://e390d735.ngrok.io -> localhost:80



### 第二步
telegram，下载telegram，创建bot机器人，


### 第三步 
@<机器人> /<自己说的话>         列子： @DiaoMao_bot  /666666666666666

# 第四步  
浏览器接受发给机器人的语句
列子： 浏览器： https://api.telegram.org/bot618555463:AAHRfBvb-WQcRN7gEtm-tEDeG2hAWvM3AXo/getUpdates?offset=LAST_UPDATE_ID

后台服务器接受机器人语法可以使用：setWebhook 
(setWebhook 設定 webhook 在有人傳送訊息給您的 bot (或加入、離開群組等) 時， Telegram 將會使用 JSON 格式 POST 到您的伺服器)

# 第五步
后台服务器给机器人发送信息
