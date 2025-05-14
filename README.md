### JitPack:
Step 1. Add the JitPack repository in your root build.gradle at the end of repositories:

```gradle
allprojects {
    repositories {
        ...
        mavenCentral()
        maven { url "https://jitpack.io" }
    }
}
```

Step 2. Add the dependency

```gradle
dependencies {
    implementation 'com.github.MrDon94:AndroidUtilCode:v1.30.6'
}
```
