---
layout: page
title: Thoughts from my desk
tagline: Frontpage to my head
comments: False
---
{% include JB/setup %}

##About this site

Here lies the accumulated concious of a graduate student as I continue to fight the good fight. For the last decade I've worked in analytics and applied mathematics problems in a field of engineering. I explain it that way because I'm not a typical engineer as I don't build machines or work in a factory. I mostly work on decision problems in Operations Research. My thesis focuses on improved uses of computers in chemistry, more specifically cheminformatics. I've been looking into network analysis of literature and physicochemical data to improve the design process through automation, prediction, and data mining. I do this on "Big Data".

Some past projects focused on Emergency Department resource management. Associated papers are available from Google Scholar. Briefly, we looked at providing probabilistic predictions of Emergeny Severity Index (ESI) levels for patients during triage. Our hope is that nurses may find these algorithms (through some yet-to-be-created interface) useful in performing their tasks.


I've used a lot of different analytic tools and programming languages over the years. In this blog I hope to add some relevant nuggets of information to the occasional Google-er.


If you are interested in getting in contact with me for <fill in the blank>. You can contact me through comments on the posts or through GitHub where my handle is seifu.







<!---
Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

 Update Author Attributes

In `_config.yml` remember to specify your own data:
    
    title : My Blog =)
    
    author :
      name : Name Lastname
      email : blah@email.test
      github : username
      twitter : username

The theme should reference these variables whenever needed.
    
 Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

     rm -rf _posts/core-samples

Here's a sample "posts list".

--->

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<!---
## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
--->

<a href="http://seifu.github.com{{ page.url }}#disqus_thread" data-disqus-identifier="{{ page.url }}"></a>

