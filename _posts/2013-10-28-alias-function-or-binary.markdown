---
layout: post
title:  "Get a command type with bash"
date:   2013-10-28
categories: notes
tags:   bash snippets
---
How to know if a command is alias or builtin function instead of binary?
Use `type` for bash

{% highlight bash %}
type ls
{% endhighlight %}

or `which`

{% highlight bash %}
which ls
{% endhighlight %}



