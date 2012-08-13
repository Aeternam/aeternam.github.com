---
layout : page
title : insane =>
tagline : index
---
{% include JB/setup %}

##关于我
###简要
杭州某电商公司SA(SRE)。90不前不后，青岛人，处于未实名状态。

###技术
openSUSE,KDE,emacs,Linux C ,{c,e}lisp,Python,Ruby,bash

###联系

你可以通过这个和我邮件或者Google Talk
`anVzdGZhbi5iQGdtYWlsLmNvbQo=`

###Twitter
[insane_idiot](https://twitter.com/insane_idiot "insane_idiot")
##所有的文章归档

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

