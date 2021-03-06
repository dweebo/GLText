GLText
=========

A library for easily rendering Text in OpenGL ES 2 on Android.

All credit for this work goes to [**d3kod**](https://github.com/d3kod/Texample2) who created an
OpenGL ES 2 port of the code by **fractious** - [Rendering Text in OpenGL on Android](http://fractiousg.blogspot.com/2012/04/rendering-text-in-opengl-on-android.html).

I just repackaged it as an Android .aar library for easier reuse.

Licensed under CC0 1.0 public domain license, so use it freely, no restrictions at all.

Installation
----------
Add
```
compile 'dental.beam:gltext:1.0.0'
```
To your app's build.gradle file in the dependencies section

How to use
----------
For more information, see [the original post](http://fractiousg.blogspot.com/2012/04/rendering-text-in-opengl-on-android.html) by **fractious**. Most of the syntax is unchanged.

For maintainers
----------
If you need to release a new version build and then run 
```
$ ./gradlew bintrayUpload
```
To release the library to bintray and jcenter


