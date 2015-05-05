---
layout: page
title: Introduction 
subtitle: The homepage of Bryce Mitchell
---
Under construction. This is a page all about my adventures in the land of
fortune and opportunity. I will include things on this page that I am
interested in, working on, or otherwise obligated to discuss. I hope you
find something to your liking someday.

{% if site.posts.size > 0 %}
### Recent Blog Posts
{% for post in site.posts %}
* [{{ post.title }}]({{ post.url | prepend: site.baseurl }})\\
  <small>{{ post.date | date: "%b %-d, %Y" }}</small>

{% endfor %}
{% endif %}

Here I will have a list of things I am doing. As soon as I'm doing
any things.

### Projects
* coming soon
