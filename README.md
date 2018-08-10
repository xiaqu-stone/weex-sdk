


## 说明

适配项目应用的再打包

### gradle

```
implementation "com.stone.kuainiugroup:weex-sdk:1.0.0"
```

### Proguard

```
-keep class com.taobao.weex.** {*;}
-keep public class * extends com.taobao.weex.common.WXModule{*;}
-keep public class * extends com.taobao.weex.ui.component.WXComponent{*;}
```