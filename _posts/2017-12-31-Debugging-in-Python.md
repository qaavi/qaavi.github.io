---
layout: post
title: "Debugging in Python"
date: 2017-12-31 11:00:00 +0500
permalink: 2017/12/31/debugging_in_python/
comments: true
categories: python
tags: python debugging pdb Tracer() set_trace() IPython Jupyter notebook
---


Previously, we would debug Python code with following 

```#   from IPython.core.debugger import Tracer; Tracer()()```

But this method is `DEPRECIATED` since IPython 5.1. 

Now if you want to debug your python code, use below.


```  from IPython.core.debugger import Pdb  
	 debugger = Pdb()```
	 
Now wherever you want to add breakpoint, add the line below:

```debugger.set_trace()```


Here are couple commands you can use to debug:

``` n - Next -  Go to next line```
    s - Step into - Step into the function
    c - Continue - Continue to next breakpoint
    q - Quit - Quit the program execution ```

For complete list of commands, use 

```h -  Help```
This will print complete list of commands you can use to debug your Python code in `Jupyter Notebook`


**Happy Python coding and debugging !**