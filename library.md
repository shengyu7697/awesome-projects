# library
這裡收集一些簡單使用輕巧的函式庫.  

## 網路
| library                                                               | API |files| description
| --------------------------------------------------------------------- |:---:|:---:| -----------
|**[zed_net](https://github.com/Smilex/zed_net)**                       |C/C++|**1**| cross-platform socket wrapper
|**[sts_net](https://github.com/kieselsteini/sts)**                     |C/C++|**1**| cross-platform socket wrapper (socket sets and packet API)
|  [znet](https://github.com/starwing/znet)                             |C/C++|**1**| cross-platform networking w/ Lua binding
|  [mm_web.h](https://github.com/vurtun/mmx)                            |C/C++|**1**| lightweight webserver, fork of webby

[sleep 跨平台](https://github.com/vurtun/mmx/blob/f0ef47edc2077bc498880f7d3032c37e68f79219/tests/web_test.c#L52)  
[doAccept](https://github.com/starwing/znet/blob/2e0efcb2e937cec098d5366d95fd01b8a1b01324/znet.hpp#L93)  

跨平台寫法
```
#if defined( _WIN32 )
    
#elif defined( __linux__ ) || defined( __APPLE__ ) || defined( __ANDROID__ )

#else 
        #error Unknown platform.
#endif
```

## 參考
[single_file_libs](https://github.com/nothings/single_file_libs)  
