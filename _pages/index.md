---
layout: defaults/page
permalink: index.html
narrow: true
title: J의 블로그에 온 것을 환영합니다.
---

## J, 누구냐 넌

{% include components/intro.md %}

[Here's the full feature list and some quick examples of what it can do.]({{ site.baseurl}}{% link _pages/about.md %})

## 주요 관심사

{% include _includes/youtube/main.html id="https://youtu.be/1UweEFUVj3s" %}  
[The documentation]({{ site.baseurl }}{% link list/projects.md %}) covers the basics of installing and using it, and is an example of how you could write documentation about your own projects.  
  
[The blog]({{ site.baseurl }}{% link list/posts.html %}) has a bunch of tips about how to use Friday Theme. These show how the blog works, including the tags. There's the three most-recent posts below included below.

<hr />

### 최근 게시글

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


