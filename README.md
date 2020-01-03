### Add 2 Compat Function

**1. Pick photo without chooser**

in some device chooser is not work 

```
 CropImage.activity()
         .pickWithoutChooser()
         .start(this)
```

**2. Pick photo with capture**

compat implementation 

**requrire** App compat File Provider after Android 7

```
 CropImage.activity()
         .capturePhoto()
         .start(this)
```