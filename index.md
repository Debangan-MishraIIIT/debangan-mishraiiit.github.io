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

## Hi, I'm Debangan 🎓

I’m an undergraduate researcher working on how to make AI systems and models safer for all. My interests lie in interpretability, explainability, and machine unlearning. I am also fascinated by multimodal models, NLP and geometric deep learning. I enjoy building principled approaches to make AI systems more transparent, secure, and aligned with human intent. Cheers to a safer and more responsible future of artificial intelligence 🥂.


### 🔗 Links
<div class="social-icons" align="center">
  <a href="https://scholar.google.com/citations?user=PnRWab4AAAAJ&hl=en" title="Google Scholar">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/googlescholar.svg" alt="Google Scholar" />
  </a>
  <a href="https://www.linkedin.com/in/debangan-mishra-1a1a34209/" title="LinkedIn">
    <img src="https://cdn.jsdelivr.net/npm/simple-icons@v11/icons/linkedin.svg" alt="LinkedIn" />
  </a>
  <a href="https://x.com/DebanganM10375/" title="Twitter">
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
