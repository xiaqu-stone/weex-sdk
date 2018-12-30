


## 说明

适配项目应用的再打包,基于官方 `0.9.4`

### gradle

```
implementation "com.stone.kuainiugroup:weex-sdk:1.0.3"
```

### Proguard

```
-keep class com.taobao.weex.** {*;}
-keep public class * extends com.taobao.weex.common.WXModule{*;}
-keep public class * extends com.taobao.weex.ui.component.WXComponent{*;}
```