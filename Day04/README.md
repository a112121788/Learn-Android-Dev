# 学习要点

- Kotlin
- anko
- Android KTX（目前不是太完善，观察中）

## 如果在Android开发中更好地使用Kotlin
依App module为例
```
apply plugin: 'com.android.application'
apply plugin: 'kotlin-android'
apply plugin: 'kotlin-android-extensions'
```

```
dependencies {
    implementation "org.jetbrains.kotlin:kotlin-stdlib-jre7:$kotlin_version"
    implementation "org.jetbrains.anko:anko:$anko_version"
}
```

简言之，kotlin kotlinx anko 全上
