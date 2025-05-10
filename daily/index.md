---
layout: default
title: Daily Tasks
---

# Daily Tasks

{% assign daily_posts = site.posts | where: "categories", "daily" %}
{% for post in daily_posts %}
  <div class="daily-entry">
    <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
    <div class="post-date">{{ post.date | date: "%B %d, %Y" }}</div>
  </div>
{% endfor %}

<style>
.daily-entry {
  margin: 1rem 0;
  padding: 1rem;
  border: 1px solid #e1e4e8;
  border-radius: 6px;
  background-color: #f6f8fa;
}

.daily-entry h2 {
  margin: 0;
}

.daily-entry a {
  color: #0366d6;
  text-decoration: none;
}

.daily-entry a:hover {
  text-decoration: underline;
}

.post-date {
  color: #666;
  font-size: 0.9em;
  margin-top: 0.5rem;
}
</style> 