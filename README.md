# TeemoOverlaySkin

一个简单的Overlay Skin

支持 OverlayPlugin 与 ACTWebsocket

直接调用模版URL（支持http与https）

http://act.teemo.name


可以直接使用overla_pro调用显示

例如 http://act.teemo.name/?HOST_PORT=ws://127.0.0.1:10501

注意 按照浏览器强制规定

在https+actwebsocket下需要使用tls websocket（wss）


插件本身限制使用frp穿透的时候

服务端判断Host不符会返回404错误

可以使用Nginx反代重写Host

配置文件例子已经提供在nginx文件夹中


如果不想显示宠物信息

可以使用如下URL

http://act.teemo.name/nopet.html


效果预览

![image](https://github.com/reusu/TeemoOverlaySkin/raw/master/simple.png)
