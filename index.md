---
layout: home
---

<div class="home">

## 2015 UW eScience Python Seminar

Increasingly, scientific research in many fields is driven by computational
approaches to large datasets, but graduate students are often expected to pick
up these essential computational skills on their own. To help address this, UW
eScience is offering a fall quarter Python bootcamp and seminar, aimed at
helping first-year graduate students in scientific domains brush-up on the types
of tools that drive computational research.

This effort is a continuation of the Astro 599 and AMATH 500 seminar courses
which were offered in
[2013](http://www.astro.washington.edu/users/vanderplas/Astr599/) and
[2014](http://www.astro.washington.edu/users/vanderplas/Astr599_2014/);
in 2015 we are dropping the course number and offering this content through a
more informal weekly seminar.

  <h1 class="page-heading">Posts</h1>

  <ul class="post-list">
    {% for post in site.posts %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

  <p class="rss-subscribe">subscribe <a href="{{ "/feed.xml" | prepend: site.baseurl }}">via RSS</a></p>

</div>
