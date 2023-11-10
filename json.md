---
layout: page
title: JSON file
permalink: /json/
---


{% raw %}
{% include db.json %}
{% endraw %}


{% raw %}
Name: {{ site.db.productName }}
Description: {{ site.db.description | join: ", " }}
Size: {{ site.db.size}}
Price {{ site.db.price}}
{% endraw %}

```json
{% raw %}
{% include db.json %}
{% endraw %}
