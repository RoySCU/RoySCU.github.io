---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Conference  
======
* 2018
  * Zhiyi Zhang, Edward Lu, Yanbiao Li, Lixia Zhang, **Tianyuan Yu**, Davide Pesavento, Junxiao Shi, Lotfi Benmohamed, NDNoT: a framework for named data network of things. Proceedings of the 5th ACM Conference on Information-Centric Networking (ICN) 2018.