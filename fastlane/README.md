fastlane documentation
================
# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```
xcode-select --install
```

Install _fastlane_ using
```
[sudo] gem install fastlane -NV
```
or alternatively using `brew install fastlane`

# Available Actions
## iOS
### ios lint_code
```
fastlane ios lint_code
```
语法检查
### ios format_code
```
fastlane ios format_code
```
格式化代码
### ios build_dev_app
```
fastlane ios build_dev_app
```
编译开发版本
### ios tests
```
fastlane ios tests
```
单元测试
### ios download_matchs
```
fastlane ios download_matchs
```
下载证书和描述文件
### ios renew_certs
```
fastlane ios renew_certs
```
生成证书
### ios renew_profiles
```
fastlane ios renew_profiles
```
重新生产描述文件
### ios create_new_profiles
```
fastlane ios create_new_profiles
```
创建证书和描述文件
### ios nuke_profiles
```
fastlane ios nuke_profiles
```
销毁证书和描述文件
### ios add_device
```
fastlane ios add_device
```
添加设备
### ios archive_internal
```
fastlane ios archive_internal
```
打包演示版
### ios archive_release
```
fastlane ios archive_release
```
打包预发布版
### ios archive_appstore
```
fastlane ios archive_appstore
```
打包商店版

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.
More information about fastlane can be found on [fastlane.tools](https://fastlane.tools).
The documentation of fastlane can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
