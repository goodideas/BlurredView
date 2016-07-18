# BlurredView

![demo][1]
Dynamic blur of Image Views for Android. 
Includes library and small example project.

## How to use 

```XML
<com.qiushui.blurredview.BlurredView
      app:src="@drawable/dayu"
      app:move="true"
      android:layout_width="match_parent"
      android:layout_height="match_parent"/>
```

## Enable RenderScript support mode:

```Groovy
 defaultConfig {
        renderscriptTargetApi 19
        renderscriptSupportModeEnabled true
  }
```


[1]: http://7xook5.com1.z0.glb.clouddn.com/demo.gif