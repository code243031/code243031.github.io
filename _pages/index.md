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
아래 영상은 테스트를 위해 임시로 넣은 영상입니다.  
{% include /youtube/main.html id="https://youtu.be/1UweEFUVj3s" %}  

### 최근 게시글

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}


