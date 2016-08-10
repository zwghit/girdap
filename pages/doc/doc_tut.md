---
title: Tutorials
permalink: doc_tut.html
sidebar: mydoc_sidebar
tags: [tutorials]
keywords: about, install, coding
last_updated: August 10, 2016
folder: doc
---

Following examples will help you start using _girdap_. Examples below should be considered as the driving code that use _girdap_ library. You can create your own `main.cpp` or modify one of `main_xxx.cpp` files which can be found in the `girdap_rootdir/src` directory.

Any code using *girdap* should include girdap header file placed in ```girdap_rootdir``` before the `main()` function; 

{% highlight c++ linenos %}

#include <girdap_rootdir/grdap>
#include <stdio>

int main(int argc, char *argv[]) {
    // examples should be placed here
    // --> begin here
    
    // --> end here 
    exit(0); 
}
    
{% endhighlight %}
  
## Examples

1. [Tutorial 01](tut01-grid/): Grid generation/adaptation
2. [Tutorial 02](tut02-var/): Field variables
3. [Tutorial 03](tut03-heat/): Heat equation
4. [Tutorial 04](tut04-advdiff/): Transient advection/diffusion equation
5. [Tutorial 05](tut05-incomp/): Incompressible fluid flow
	 
	   




