# About
zero-config - header-only library. Contains base configuration for all zeroEngine modules

# Requirements
 - C++ 14
 - CMake

# Examples
```c++
#include <zero/cfg/zero_api.hpp> /// zero-config
#include <zero/core/utils/Log.hpp> /// zlog

int main()
{
#ifdef ZERO_ANDROID /// ANDROID
    zLog::debug(u8"Hello LogCat !");
#endif /// ANDROID

    return 0;
}
```
