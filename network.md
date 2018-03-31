# network
這裡收集一些簡單使用輕巧的網路函式庫.  

## 網路
| library                                                               | API |files| description | stars
| --------------------------------------------------------------------- |:---:|:---:| ----------- | -----------
|**[zed_net](https://github.com/Smilex/zed_net)**                       |C/C++|**1**| cross-platform socket wrapper | ![GitHub stars](https://img.shields.io/github/stars/Smilex/zed_net.svg?style=social&label=Star)
|**[sts_net](https://github.com/kieselsteini/sts)**                     |C/C++|**1**| cross-platform socket wrapper (socket sets and packet API) | ![GitHub stars](https://img.shields.io/github/stars/kieselsteini/sts.svg?style=social&label=Star)
|  [znet](https://github.com/starwing/znet)                             |C/C++|**1**| cross-platform networking w/ Lua binding | ![GitHub stars](https://img.shields.io/github/stars/starwing/znet.svg?style=social&label=Star)
|  [mm_web.h](https://github.com/vurtun/mmx)                            |C/C++|**1**| lightweight webserver, fork of webby | [![GitHub stars](https://img.shields.io/github/stars/vurtun/mmx.svg?style=social&label=Star)](https://github.com/vurtun/mmx)
|  [evpp](https://github.com/Qihoo360/evpp)                             |C/C++|     |
|  [dyad](https://github.com/rxi/dyad)                                  |C/C++|     |
|  [librws](https://github.com/OlehKulykov/librws)                      |C/C++|     | Tiny, cross platform websocket client C library | ![GitHub stars](https://img.shields.io/github/stars/OlehKulykov/librws.svg?style=social&label=Star)

[如何深刻理解reactor和proactor？](https://www.zhihu.com/question/26943938)  
[sleep 跨平台](https://github.com/vurtun/mmx/blob/f0ef47edc2077bc498880f7d3032c37e68f79219/tests/web_test.c#L52)  
[doAccept](https://github.com/starwing/znet/blob/2e0efcb2e937cec098d5366d95fd01b8a1b01324/znet.hpp#L93)  
[close() 與 shutdown()](http://beej-zhtw.netdpi.net/05-system-call-or-bust/5-9-close-and-shutdown)  
[https://github.com/libimobiledevice/libusbmuxd/blob/master/src/libusbmuxd.c](https://github.com/libimobiledevice/libusbmuxd/blob/master/src/libusbmuxd.c)  

跨平台寫法
```c
#if defined( _WIN32 )
    
#elif defined( __linux__ ) || defined( __APPLE__ ) || defined( __ANDROID__ )

#else 
        #error Unknown platform.
#endif
```

## 參考
[single_file_libs](https://github.com/nothings/single_file_libs)  
