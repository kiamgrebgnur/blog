---
layout: post
title:  "Use Spaces instead of Tab in vim"
date:   2013-10-16 10:11
categories: notes
tags:   vim snippets
---

To use spaces instead of tabs especially for python programming:

    :set expandtab

Every tab will become space(s)
To be safe use also the following:

    " every tab is 4 spaces
    :set tabstop=4
    
    " width for auto indentation
    :set shiftwidth=4

Use `Ctrl-V<Tab>` to insert the old tab.

Hint: < and > for indentation
