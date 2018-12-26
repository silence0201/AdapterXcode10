# AdapterXcode10


适配Xcode10去除libstdc++问题



| 平台        | 文件夹    | 文件名  | 路径 |
| --------   | :-----:   | :----: |:---- |
| 模拟器运行  | CoreSimulator|libstdc++.6.0.9.dylib|/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/Library/CoreSimulator/Profiles/Runtimes/iOS.simruntime/Contents/Resources/RuntimeRoot/usr/lib/ |
| 模拟器编译 | iPhoneSimulator |ibstdc++.6.0.9.tbd|	/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneSimulator.platform/Developer/SDKs/iPhoneSimulator.sdk/usr/lib/|
| iOS真机  | iPhoneOS |libstdc++.6.0.9.tbd|	/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS.sdk/usr/lib/|
| macOS    | MacOSX |libstdc++.6.0.9.tbd|	/Applications/Xcode.app/Contents/Developer/Platforms/MacOSX.platform/Developer/SDKs/MacOSX.sdk/usr/lib/|
--------------------- 