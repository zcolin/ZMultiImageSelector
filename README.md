# MultiImageSelectorLib
##图片选择库.

####基于 https://github.com/lovetuzitong/MultiImageSelector v1.2图片选择库，，将原作者的Picasso替换为Glide

Gradle
=
app的build.gradle中添加
```
dependencies {
    compile 'com.github.zcolin:ZMultiImageSelector:1.0.5'
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
