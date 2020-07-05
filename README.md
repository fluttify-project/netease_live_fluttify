![Logo](https://github.com/fluttify-project/fluttify-core-example/blob/develop/other/Logo-Landscape.png?raw=true)

# 网易云信 Flutter插件

[![pub package](https://img.shields.io/pub/v/netease_live_fluttify.svg)](https://pub.Flutter-io.cn/packages/netease_live_fluttify)

**专业版为付费插件, 如有需要请联系qq 382146139**

**专业版为付费插件, 如有需要请联系qq 382146139**

**专业版为付费插件, 如有需要请联系qq 382146139**

## 依赖
```yaml
dependencies:
  flutter:
    sdk: flutter
  netease_live_fluttify: ^x.x.x
```

## 配置
### Android
1. 无需配置, 只要有推流地址即可开始推流;

### iOS
1. 推流需要摄像头和麦克风权限, 并且需要配置为UiKitView使能, 在Info.plist中添加:
```xml
<key>NSMicrophoneUsageDescription</key>
<string>需要麦克风</string>
<key>NSCameraUsageDescription</key>
<string>需要相机</string>
<key>io.flutter.embedded_views_preview</key>
<string>YES</string>
```

## 导入
```dart
import 'package:netease_live_fluttify/netease_live_fluttify.dart';
```

## 使用
参考[wiki](https://github.com/fluttify-project/netease_live_fluttify/wiki).

|       | 社区版 | 专业版 |
|:-----:|:-----:|:-----:|
|  预览  |  ✅ |  ✅   |
|  推流  |  ✅ |  ✅   |
|  恢复推流  |  ✅ |  ✅   |
|  停止推流  |  ✅ |  ✅   |
|  停止预览  |  ✅ |  ✅   |
|  切换摄像头  |  ✅ |  ✅   |
|  设置滤镜  |  ✅ |  ✅   |
|  设置滤镜强度  |  ✅ |  ✅   |
|  设置磨皮强度  |  ✅ |  ✅   |
|  打开/关闭 闪光灯  |  ✅ |  ✅   |
|  摄像头缩放 |  ✅ |  ✅   |
|  调节曝光度 |  ✅ |  ✅   |
