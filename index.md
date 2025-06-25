---
layout: default
---

<!-- your photo -->
<p align="center">
  <img src="assets/img/avatar.jpg" alt="Your Name" width="200" style="border-radius:50%;">
</p>

## Hi, I'm Your Name 🎓

A brief intro about your background, current role, research interests, etc.

### 🔗 Links
<p>
  <a href="{{ site.google_scholar }}" title="Google Scholar"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/google/google-original.svg" width="24"></a>
  <a href="{{ site.linkedin }}" title="LinkedIn"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="24"></a>
  <a href="{{ site.twitter }}" title="Twitter"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/twitter/twitter-original.svg" width="24"></a>
  <a href="{{ site.semantic_scholar }}" title="Semantic Scholar"><img src="https://raw.githubusercontent.com/semantic-scholar/art/master/s2-logo/s2-logo-dark-background.svg" width="24"></a>
</p>

### 📚 Publications
<ul>
{% assign pubs = site.data.publications %}
{% for p in pubs %}
  <li>
    <strong>{{ p.title }}</strong><br>
    <em>{{ p.authors }}</em>, <em>{{ p.venue }}</em>. <a href="{{ p.url }}">[PDF]</a>
  </li>
{% endfor %}
</ul>
