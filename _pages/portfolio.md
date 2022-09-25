---
layout: archive
title: "Personal life/个人生活"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

About me/关于我
======
有人说：偷走一个人的钱包，这个人会贫穷一个星期；而教会一个人物理，这个人会贫穷一辈子。
我很乐于分享作为一个平凡贫穷的普通人的一点生活片段。

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

