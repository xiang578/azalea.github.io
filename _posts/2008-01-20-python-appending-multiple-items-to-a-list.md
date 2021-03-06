---
layout: post
title: 'Python: Appending Multiple Items to a List'
tags:
- programming
- python
status: publish
type: post
published: true
meta:
  views: '510'
---
The <code class="syn">extend()</code> method can be used to append multiple items to the end of a list. Executing the following statements
 
 

<font color="#3366ff">listA = <span class="br0">[</span> <span class="nu0">0</span>, <span class="nu0">1</span>, <span class="nu0">2</span>, <span class="nu0">3</span> <span class="br0">]</span>
listB = listA.<span class="me1">extend</span><span class="br0">(</span> <span class="br0">[</span> <span class="nu0">4</span>, <span class="nu0">5</span>, <span class="nu0">6</span> <span class="br0">]</span> <span class="br0">)</span>
<span class="kw1">print</span> listB</font>
produces as output
 

<pre class="escaped">[0, 1, 2, 3, 4, 5, 6 ]</pre>
The <code class="syn">extend()</code> method takes a single argument which must be list object. The entire contents of the argument is appended to the end of the list for which the method was invoked.
reference:
<a href="http://www.cs.wlu.edu/~necaise/python/Collections/AdvancedListFeatures" target="_blank">Python for Java Programmers</a>