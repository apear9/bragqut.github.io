---
layout: post
title: Test Post with a little R Code
---


<div class="message">
  So we can put an introductory message here introducing our code snippet e.g. what it's for if it requires a certain package.
</div>

### Dependencies
i.e. any `library( )` calls you need to make

### Code Snippet
<pre><code>
Pointless.func <- function(x = rnorm(50),y = rnorm(50)){
                     if(length(x) == length(y)){
		          col.v = rainbow(length(x))
		          plot(x, y, col = col.v)} else{
		          print('please supply numeric vectors of the same length to arguments x and y')}}
</code></pre>

How do I get the indenting to work? In my IDE I have the line starting <code>col.v =<\code> indented so that the <code>c<\code> of <code>col.v<\code> is directly below the <code>n<\code> of the <code>length<\code> of the line above.  I'm doing this indenting with spaces but it doesn't work. Any ideas? (Is there some equivalent to the <code>\verbatim<\code> environemt of LaTeX?
		  
### Images

How should be do these - it's bad practise to have files that can't be merged in a Git repository I believe so we should host the images somewhere else?