ABIs [armeabi] are not supported for platform. Supported ABIs are [armeabi-v7a, arm64-v8a, x86, x86_64]
起因：
使用最新ndk编译出现了异常
原因：
    ndk（v17）已不在支持mips、armeabi等CPU架构
    只支持armeabi-v7a, arm64-v8a, x86, x86_64。
    
https://blog.51cto.com/4789781/2116935


Android Studio CMake错误查找
https://blog.csdn.net/MoSee/article/details/88355178
