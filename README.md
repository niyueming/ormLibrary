# ormLibrary
LiteORM
这只是个Android Studio的Module，不能独立运行。使用了[android-lite-orm](https://github.com/litesuits/android-lite-orm)。
### build.gradle
该文件中的rootProject.ext.*定义在被依赖项目中的build.gradle，如：

-------
    ext {
        compileSdkVersion = 25
        targetSdkVersion = compileSdkVersion
        minSdkVersion = 16
        buildToolsVersion = '24.0.2'
        supportLibVersion = '25.1.0'
        playServicesVersion = '9.4.0'
    }

### My Build Enviroment
- Common
 - MacOS Sierra 版本10.12.2
- Android 25
 - Java 1.8
- [Android Studio 2.2.3](https://developer.android.com/studio/index.html)

