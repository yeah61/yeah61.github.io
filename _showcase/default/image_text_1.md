---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---
<div>
  <img data-src="{{ 'assets/images/covers/cover1.jpg' | relative_url }}" class="lazy w-100 rounded-xl" src="{{ '/assets/images/empty_300x200.png' | relative_url }}">

  <div class="card-img-overlay" style="overflow: scroll; background: rgb(255,255,255,0.8)">
    <h5 class="card-title">Teaching Experience</h5>
    <p class="card-text">
      <li> EECS 268: Programming II </li>
      <li> EECS 447: Introduction to Database Systems </li>
      <li> EECS 565: Introduction to Information and Computer Security </li>
      <li> EECS 569: Computer Forensics </li>
    </p>
    <p class="card-text">
      {% raw %}
      <code>&lt;img data-src=&quot;[Image URL]&quot; class=&quot;lazy w-100 rounded-xl&quot; src=&quot;{{ '/assets/images/empty_300x200.png' | relative_url }}&quot;&gt;</code>
      {% endraw %}
    </p>
  </div>
</div>
