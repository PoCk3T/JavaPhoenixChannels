# Phoenix Channel Client for Java and Android

Fork of enginegl/JavaPhoenixChannels

Implement 2 enhancements :
- Support of request headers for websocket to connect (such as Authorization token header when connecting to Phoenix Channel web socket), at Socket constructor level
- Support of a debug mode (OkHttpClient HTTP interceptor), using socket.setDebuggable(true)
