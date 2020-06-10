## cocos2d-js 版本3.17  
### 配置说明  
* android端横竖屏，修改`frameworks/runtime-src/proj.android/app/AndroidManifest.wxml`文件中
  screenOrientation，值portrait为竖屏, landscape为横屏
* 桌面窗口大小，修改`frameworks/runtime-src/Classes/AppDelegate.cpp`中的`glview = cocos2d::GLViewImpl::createWithRect("Gambling", Rect(0,0,375,667));`，后面两个数字为窗口大小