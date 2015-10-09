# ios-staticLibrary
a demo about creating a static library in ios

#完成编码后：
选择设备为真实设备和模拟器各build一次，然后show in finder找到编译后的.a文件，使用lipo命令合并两个文件，命令为 lipo -create /xxx/yourLib.a /yyy/yourlib2.a -output /zzz/lib.a
