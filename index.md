---
---

## Welcome

I’m **ASCE**, a cybersecurity enthusiast and Hack The Box player.

This site contains:
- HTB machine write-ups
- Web security challenge analysis
- Notes on logic flaws and exploitation

### Latest Posts
{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}
