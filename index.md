---
layout: default
---

<style>
.social-icons a {
  margin: 0 10px;
  display: inline-block;
}
.social-icons img {
  width: 28px;
  height: 28px;
  vertical-align: middle;
}
</style>

<!-- your photo -->
<p align="center">
  <img src="assets/img/face.jpeg" alt="Debangan Mishra" width="200" style="border-radius:50%;">
</p>

## Hi, I'm Debangan 🎓

A brief intro about your background, current role, research interests, etc.

### 🔗 Links
<div class="social-icons" align="center">
  <a href="https://scholar.google.com/citations?user=PnRWab4AAAAJ&hl=en" title="Google Scholar">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/googlescholar.svg" alt="Google Scholar" />
  </a>
  <a href="https://www.linkedin.com/in/YOUR-LINKEDIN/" title="LinkedIn">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/linkedin.svg" alt="LinkedIn" />
  </a>
  <a href="https://twitter.com/YOUR-TWITTER/" title="Twitter">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/twitter.svg" alt="Twitter" />
  </a>
  <a href="mailto:debangan.mishra40@gmail.com" title="Gmail">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/gmail.svg" alt="Gmail" />
  </a>
</div>


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
