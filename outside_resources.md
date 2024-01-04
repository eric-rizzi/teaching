---
layout: page
title: "List of Outside Resources"
---

# List of Outside Resources

Here's a list of outside resources I've found/used:

{% for resource in site.outside_resources_posts %}
- [{{ resource.title }}]({{ site.baseurl }}{{ resource.url }})
{% endfor %}
