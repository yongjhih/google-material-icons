# google-material-icons

[![JitPack](https://img.shields.io/github/tag/yongjhih/google-material-icons.svg?label=JitPack)](https://jitpack.io/#yongjhih/google-material-icons)
[![Build Status](https://travis-ci.org/yongjhih/google-material-icons.svg)](https://travis-ci.org/yongjhih/google-material-icons)

![](art/screenshot.png)

Imports vector drawable icons.

## Usage

```xml
<ImageView
  ...
  app:srcCompat="@drawable/ic_wifi_black_24dp"
/>
```

And you can also apply color tint:

```xml
<ImageView
  app:srcCompat="@drawable/ic_wifi_black_24dp"
  android:tint="@android:color/yellow"
/>
```

## Installation

```gradle
repositories {
    maven { url "https://jitpack.io" }
}

dependencies {
    compile 'com.github.yongjhih:google-material-icons:-SNAPSHOT'
}
```

## Credit & References

* https://github.com/google/material-design-icons/
* https://design.google.com/icons/
* https://developer.android.com/guide/topics/graphics/vector-drawable-resources#vector-drawables-backward-solution

## LICENCE

apache-2.0
