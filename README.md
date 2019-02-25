
# mzlibs


[![](https://jitpack.io/v/io.github.mohamed-zaitoon/mzlibs.svg)](https://jitpack.io/#io.github.mohamed-zaitoon/mzlibs)

An Android library that provides most of used in one Class.


## Download

```java
android {
    /* Android Gradle Plugin 3.0.0+ is required to support Java 8 desugaring */
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
}
repositories {
    maven { url 'https://jitpack.io' }
}
dependencies {


 implementation 'io.github.mohamed6zaitoon:mzlibs:1.0.1'
 
}
```
## Tutorial
 For Tutorial Visit:
 [Docs](https://mohamed-zaitoon.github.io/mzlibs/docs)
 
## Progaurd
 In progaurd-rules.pro add this lines:
 ```txt
-keepclassmembers class com.tony.** {*; }
-keep public class com.tony.** { *;}
-keepclassmembers interface com.tony.** {*;}
-keep public interface com.tony.** {*;}
 
```

## License 
```txt
  MIT License

Copyright (c) 2019 Mohamed Zaitoon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

 
 

