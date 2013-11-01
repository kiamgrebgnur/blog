---
layout: post
title:  "How to sum Numbers with Bash"
date:   2013-10-24
categories: notes
tags:   bash snippets
---

How to add Numbers in a File or from a pipe with simple bash magic?
{% highlight bash %}
paste -sd+ <file> | bc
{% endhighlight %}
or
{% highlight bash %}
<some cmd with output> | paste -sd+ | bc
{% endhighlight %}  
  
    
<h3>AWK to the rescue</h3>

Is the list to big for bc use awk

{% highlight awk %}
awk '{ sum += $1; } END { print sum; }'
{% endhighlight %}


[via stackoverflow](http://stackoverflow.com/questions/3096259/bash-command-to-sum-a-column-of-numbers/)

