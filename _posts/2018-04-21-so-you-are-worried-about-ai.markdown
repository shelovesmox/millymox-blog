---
layout: post
title:  So you are worried about AI?
description: The state of AI and why newbies should do less worrying.
date:   2023-11-17 15:01:35 +0300
image:  '/images/post1.jpg'
tags:   [Software Engineering, AI]
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