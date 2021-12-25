```
flutter_color_plugin
```
### 使用方法
```
To get a color 
Color color1 = ColorUtil.color('#f2f2f2');
Color color2 = ColorUtil.color('f2f2f2');
print(color1 == color2); //true

Color color3 = ColorUtil.color('#a1FF5733');
Color color4 = ColorUtil.color('a1FF5733');
print(color3 == color4); //true
To get a int color 
//The following is the same
int colorInt1 = ColorUtil.intColor('#f2f2f2');
int colorInt2 = ColorUtil.intColor('f2f2f2');
int colorInt3 = ColorUtil.intColor('#fff2f2f2');
int colorInt5 = ColorUtil.intColor('fff2f2f2');
```
### Use this package as a library
### 安装
Depend on it

Run this command:

With Flutter:
```
 $ flutter pub add flutter_color_plugin
 ```
This will add a line like this to your package's pubspec.yaml (and run an implicit flutter pub get):

dependencies:
  flutter_color_plugin: ^1.1.0
Alternatively, your editor might support or flutter pub get. Check the docs for your editor to learn more.

Import it
Now in your Dart code, you can use:
```
import 'package:flutter_color_plugin/flutter_color_plugin.dart';
```