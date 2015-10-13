---
layout: post
published: true
description: ""
headline: ""
modified: ""
categories: null
tags: ""
imagefeature: ""
mathjax: false
featured: false
comments: false
title: Starting a blog
---

## Blog in the modern web

In our time starting a blog should be as easy as 123, but hey, there are so many ways! you could sign up at some blogging website like [tumblr](https://www.tumblr.com/) or even google's [blogger](https://www.blogger.com/) but something doesn't feel right... what is it? oh! you don't feel the code, that's what it is... is it? it sure is for me. And when I recently done some research for some friends for possibilities to get some content on the web, preferably for free, I've well remembered our beloved github's invention [github pages](http://pages.github.com).

## Dynamic?

What made me go out and search is the fact that I have realized that websites done with [wordpress](http://wordpress.com/) are so popular, to a point where i even don't understand why, such a simple website which requires a set of static files, needs the ugly database behind it what benefit does it give, and the sad truth is that for the use case of blog posts and other web uses there is really NONE! And what is the alternative? **[static website generators](https://www.staticgen.com/)!** in it's full beauty. So how can a static website generator give me a dynamic website? easy, all it does is goes through the contents you supply it with and it chews everything up into a static website ready to be served over the web, with no need to cache it or anything like that. Amazing!


## How does it work?

So basically instead of having PHP engine reading the databse of posts and creating web responses you have a program like [Jekyll](https://jekyllrb.com/) which is a ruby gem, and it has its own template mechanism called [Liquid](https://github.com/Shopify/liquid/wiki). Great but how do you structure the files? So jekyll was built so smart, looking at an [example](https://github.com/hmfaysal/Notepad) website code shows that using a `_config.yml` file starting the whole process, saving some global variabless allowing you to do all the magic wordpress does with a few lines of YAML and for each file you could add more meta data in something called [Front Matter](https://middlemanapp.com/basics/frontmatter/) which is just a few more lines of code before the actual content. Whats there? well the layout it uses goes there, its navbar where it belongs to, you name it! if you want to tag this file to be listed in some special list or to tag it as having comments in its end, just add a line give that variable a value, it's **THAT** simple

## HTML?
You want to have simple life, they thought of that too and actually any content file, weather its a post or a static file lying wherever you want it to be you just save it with the desired extension such as `.md` or `.html` but on other flavors of jekyll i've seen [Jade](http://jade-lang.com/) where [DocPad](http://docpad.org/) is a very intersting one to name, and you can mix them all in the same website, that's SO convenient!

## Difficult
Wait a minute, I know I said i'm a coder, but working on a website that's hosted on something like [GitHub](https://github.com/) would require me to clone it locally and edit it or find SOME way of editing it... doesn't it? well it does but there are guys (thankfully, and i'm sure girls too) that thought about everything and there's an editor for Jekyll based projects called [prose](http://prose.io) (I told you code is potery?) that just hooks to your github account and edits your files directly on github(yes, better than the github interface) and functions pretty much like a normal posts editor you might know from Wordpress and its friends, and it commits the changes so you can go back if you really need to. sweet! It even can edit your meta data according to predefined categories and anything you want just throw it in the `_config.yml` file, **really** worths a try, and if you're not working with the github pages but rather working on your own instance or locally you can run prose there too.

## Help

Ofcourse there are a few downsides, if you need a form to be posted and a server side to receive it you will need to use some altern [alternatives](https://formspree.io/) and you might like them or might not and decide to devise your own solution. Or wait, Comments? thats not static, well there's some great [solution](https://disqus.com) for that too, oh and what about the amazing amount of Wordpress templates that you won't be able to just use out of the box? well, turns out there are quite a [few] (https://github.com/jekyll/jekyll/wiki/Themes) out there to test out, or hell, you could take any template and put some work on it to convert it.

## Conclusion

If you haven't got it until here, then yes the conclusion is that this blog you are reading was started as a simple clone of [https://github.com/hmfaysal/Notepad](https://github.com/hmfaysal/Notepad) and doing a few tweaks here and there got me to present to you with this quick results. I did spend a bit of time figuring out some things, but the result is a nicely looking rich-functional blog for free under github pages hosting and no tools were even used offline, unless you call a browser an offline tool.

Go ahead and start your blog and most importantly, enjoy, and throw a comment while you're at it!

