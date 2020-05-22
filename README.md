# EasyProtector
## download
[easyprotector-v1.1.3.jar](https://raw.githubusercontent.com/Aabbye1234/EasyProtector/master/easyprotector-v1.1.3.jar)
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
