## react-native

## 环境准备

```
# mac OS X 10.11.16
npm install react-native-cli
react-native init myRNProject
cd myRNProject
```

## ios

```
react-native run-ios
```

## android

```
# 安装 Android Studio

# 设置 Android SDK 环境变量
export ANDROID_HOME="/Users/$user_name/Library/Android/sdk"

# 启动 Android SDK Manager
$ANDROID_HOME/tools/android

# 安装 RN 运行环境依赖版本 android-23
# 安装 RN 运行编译工具依赖版本 build-tools 23.0.1

# 启动 Android avd and create
$ANDROID_HOME/tools/android avd

react-native run-android
```
