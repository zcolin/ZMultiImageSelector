# MultiImageSelectorLib
# [deprecated] 此库原作者已停止维护，所以转向知乎阵营了。https://github.com/zcolin/Matisse
## 图片选择库.

#### 基于 https://github.com/lovetuzitong/MultiImageSelector v1.2图片选择库，，将原作者的Picasso替换为Glide

Gradle
=
app的build.gradle中添加
```
dependencies {
    compile 'com.github.zcolin:ZMultiImageSelector:1.0.6'
}
```
工程的build.gradle中添加
```
allprojects {
        repositories {
            ...
            maven { url 'https://jitpack.io' }
        }
    }
```
