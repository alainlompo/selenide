<ul class="main-menu-pages">
  <li><a href="{{ BASE_PATH }}/quick-start.html">Quick start</a></li>
  <li><a href="{{ BASE_PATH }}/documentation.html">Documentation</a></li>
  <li><a href="https://github.com/codeborne/selenide/wiki" target="_blank">Wiki</a></li>
  <li><a href="{{ BASE_PATH }}/javadoc/2.3" target="_blank">Javadoc</a></li>
  <li><a href="{{ BASE_PATH }}/users.html">Testimonials</a></li>
  <li style="display:none;"><a href="{{ BASE_PATH }}/quotes.html">What users say?</a></li>
  <li><a href="{{ BASE_PATH }}/contacts.html">Feedback</a></li>
  <li style="display:none;"><a href="{{ BASE_PATH }}/thanks.html">Our thanks</a></li>
</ul>

<h3 style="display:none">Blog</h3>
<div class="archive" style="display:none">
  {% assign posts_collate = site.posts %}
  {% include JB/posts_collate %}
  <a href="{{ BASE_PATH }}/archive.html" class="right small">Blog archive</a>
</div>