---
title: Hello World!
---
I ***finally*** did it. My blog is up and running. First and foremost, [Drew MacNeil](http://www.d22l.com/) needs a big shout out for helping me get the blog hosted on GitHub Pages using [Jekyll](https://jekyllrb.com/). Jekyll is a cool tool used to write blogs in Markdown which automatically get built into HTML pages according to templates. My current template is based heavily on the [Emerald](https://github.com/KingFelix/emerald) theme by Jacopo Rabolini. Thanks dude for making a nice minimalist theme. For those that don't know, its part of the programmer ethos to credit those whose work you copy/modify. Finally, my blog (and website) is being hosted on GitHub for free! For those that are curious, [here](https://pages.github.com) is the link that shows you how to host your blog on GitHub.

So at this point, you're probably wondering what will my blog be about. I plan to basically have three different categories of posts. The first will be my musings on life. Here I'll post things primarily on things going on in my life such as my travels and current activities. For example, if I had my blog in September, I would have wrote about my move to Princeton and what I'm studying. I'll post a blog post on this in the near future. Second, I hope to have a weekly series on cool math problems. I hope to make them accessible to the average reader yet rigorous to be appreciated by those in the math community. My first post in this series will be on the German Tank Problem which has roots during WWII and somewhat related to the movie Imitation Game. My goal is to write on interesting math problems while providing historical and/or interesting insight to make them enjoyable by all. So if you see something like this on my blog, don't be worried, try to give it a read:

$$
  \begin{gather*}
    f(x^k) - f(x^*) \geq \frac{3 L \lVert x^0 - x^* \rVert}{32 (k+1)^2}
  \end{gather*}
$$

The mathematically inclined reader will notice that this equation is the convergence rate of gradient descent, a very important optimization algorithm used in find the minimum/maximum value of a function. This is used in many different engineering applications to find the "best" answer to the problem at hand. This brings us to the third type of post on my blog. This will also will be a more technical area where I post things on engineering topics. Most of these will be on software and maybe a few on hardware. I don't intend to make these accessible to the average user. They will be targeted towards other software engineers and will be used to highlight different algorithms and technological improvements. Really, I'm using it as a reason to study algorithms and to force myself to fully understand it by writing a blog post on it. So you'll be seeing things like this around the blog:

{% highlight ruby linenos %}

# Calculate the nth Fibonacci number
def fib(n)

  if n == 1 || n == 2
    return 1
  end

  a_curr = 1
  a_prev = 1

  i = 3

  while i <= n
    temp = a_curr
    a_curr = a_curr + a_prev
    a_prev = temp
    i += 1
  end

  return a_curr
end

{% endhighlight %}

The TL;DR is that I have a blog and I'll be writing about

1. My life
2. Math
3. Computer stuff

Cheers, Zach