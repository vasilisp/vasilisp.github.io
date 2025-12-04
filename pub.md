---
layout: default
title: Publications
permalink: /pub/
---

<!-- Leave a non-include first line; avoids an old Jekyll excerpt bug -->

{% capture readme %}
{% include_relative pub/README.md %}
{% endcapture %}

{{ readme | markdownify }}
