- 更新flutter
```
flutter channel master && flutter upgrade 
```
- 安装 webdev
```
flutter pub global activate webdev
webdev --help
```
- 配置环境变量
```
windows：
C:\Users\<your-username>\AppData\Roaming\Pub\Cache\bin
mac或linux
$FLUTTER_HOME/.pub-cache/bin
```
- 运行
```
flutter pub upgrade
webdev serve web:8081 --hostname 192.168.3.108 -r
```
