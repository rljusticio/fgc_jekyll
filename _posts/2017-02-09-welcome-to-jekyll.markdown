`` 
located below is yaml front matter
this block must be the first thing in your files
we set variables in this block

layout specifies the layout file to use for this post
permalink allows us to customize the url for our post
published allows us to set a boolean value that determines if the post will show up when the site is published

we can also set custom variables in the frontmatter

predefined variables for posts
- date: overrides the date included with the name of the post
- category/categories: specify one or more categories that the post belongs to
- tags: behave similarly to categories

``
---
layout: post
title:  "Welcome to Jekyll!"
date:   2017-02-09 15:21:27 -0500
categories: jekyll update
---
You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
