## react-native android-start

```
# 安装 Android Studio

# 设置 Android SDK 环境变量
export ANDROID_HOME="/Users/$user_name/Library/Android/sdk"

# 启动 Android SDK Manager
sudo ln -s $ANDROID_HOME/tools/android /bin/sdk-man
sdk-man

# 启动 avd 创建设备，巨慢无比
sdk-man avd

# 启动 abd
sudo ln -s $ANDROID_HOME/platform-tools/abd /bin/abd
abd -h

# 默认初始化项目依赖运行环境版本 android-23，编译工具版本 build-tools 23.0.1

react-native run-android
```

### Android 模拟器


