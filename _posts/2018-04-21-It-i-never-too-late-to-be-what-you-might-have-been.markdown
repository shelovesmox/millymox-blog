---
layout: post
title:  Reverse Engineering Reddit Pt. 1
description: Finding how reddit makes their hmac signature header.
date:   2023-11-17 15:01:35 +0300
image:  '/images/20.png'
tags:   [Reverse Engineering, Android, Ghidra]
---
coming soon lol...

{% highlight js %}
Java.perform(function () {
    var System = Java.use("java.lang.System");

    // Hook the loadLibrary method
    System.loadLibrary.overload('java.lang.String').implementation = function (libraryName) {
        console.log("System.loadLibrary called with: " + libraryName);
        
        // Call the original method
        this.loadLibrary(libraryName);
    };
});
{% endhighlight %}