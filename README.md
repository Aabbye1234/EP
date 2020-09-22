# EP
## features
一行代码检测XP/调试/多开/模拟器/root
## download
[easyprotector-v1.3.5.jar](https://raw.githubusercontent.com/Aabbye1234/EasyProtector/master/easyprotector-v1.3.5.jar)
## use
``` java
//init first
EasyProtectorLib.init(context);
//after
EasyProtectorLib.checkIsDebug();
EasyProtectorLib.checkIsRoot();
EasyProtectorLib.checkIsBeingTracedByJava();
EasyProtectorLib.checkIsXposedExist();
EasyProtectorLib.checkIsRunningInEmulator();
EasyProtectorLib.checkIsRunningInVirtualApk();
EasyProtectorLib.checkIsHttpProxy();
EasyProtectorLib.checkIsBatteryCharging();
```
