### adbpuller: run's adb pull with the ability to use wildcards

Usage: 

```adbpuller <filespec> [/sdcard/is/default]```

Example, get the camera images for 20240809 that are on /sdcard:

```adbpuller "20240809*jpg"```

Example, get appmanager.conf from /system/etc:

```adbpuller appmanager.conf system/etc```

