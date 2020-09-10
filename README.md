# RN-learn-problem
react-native 踩坑日记

1 gradle版本的问题   一般跟虚拟机或者真机的android版本也有关  

需要修改的内容是reactNative\android\gradle\wrapper\gradle-wrapper.properties中的distributionUrl 

原来是distributionUrl=https\://services.gradle.org/distributions/gradle-6.0.1-all.zip

报错是Deprecated Gradle features were used in this build, making it incompatible with Gradle 7.0.

修改为distributionUrl=https\://services.gradle.org/distributions/gradle-5.6.4-all.zip运行成功

虚拟机使用的android  API 是24
