---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /
  - /about/
  - /about.html
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}
