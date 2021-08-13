---
layout: default
title: Authors
permalink: /authors/
---
# Authors
{% for author in site.authors %}
---
<br/>
## {{ author.name }}
### {{ author.position }}
{{ author.content }}
<br/>
{% endfor %}
