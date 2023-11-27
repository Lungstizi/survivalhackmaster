---
layout: post
title: You're up and running!
published: true
---

/Users/barryclark/Code/jekyll-now
├─ CNAME # Contains your custom domain name (optional)
├─ _config.yml # Jekyll's configuration flags
├─ _includes # Snippets of code that can be used throughout your templates
│  ├─ analytics.html
│  └─ disqus.html
├─ _layouts
│  ├─ default.html # The main template. Includes <head>, <navigation>, <footer>, etc
│  ├─ page.html # Static page layout
│  └─ post.html # Blog post layout
├─ _posts # All posts go in this directory!
│  └─ 2014-3-3-Hello-World.md
├─ _site # After Jekyll builds the website, it puts the static HTML output here. This is what's served!
│  ├─ CNAME
│  ├─ LICENSE
│  ├─ about.html
│  ├─ feed.xml
│  ├─ index.html
│  ├─ sitemap.xml
│  └─ style.css
├─ about.md # A static "About" page that I created.
├─ feed.xml # Powers the RSS feed
├─ images # All of my images are stored here.
│  ├── first-post.jpg
├─ index.html # Home page layout
├─ scss # The Sass style sheets for my website
│  ├─ _highlights.scss
│  ├─ _reset.scss
│  ├─ _variables.scss
│  └─ style.scss
└── sitemap.xml # Site map for the website

 
---
<article class="post">

  <h1>{{the mystic Ai top }}</h1>

  <div class="entry">
    {{ things supposed to change as per selected module this is a testing phase  }}
  </div>

  <div class="date">
    Written on {{ 2023 | date: 11-27 }}
  </div>

  <div class="comments">
    {% include disqus.html disqus_identifier=page.disqus_identifier %}
  </div>
</article>

