---
layout: page
title: ""
---

# Hi! Good to meet you.

My name is René.

I believe digital tools can bring academic research out of the ivory tower and into the lives of the people to whom it matters.

I'm currently a PhD candidate at [Yale University](https://complit.yale.edu/people/rene-kooiker). My academic research is about Caribbean literature in the 20th century. Specifically, I've been writing about the Caribbean Festival of the Arts (Carifesta), one of the most important cultural events in the region. I wrote an article about the first edition of the festival for the journal [archipelagos](http://archipelagosjournal.org/issue06/kooiker-carifesta.html).

To make my work more accessible, I'm creating a website called Carifesta Stories. This website will feature interactive maps, timelines, an oral history archive, and other audiovisual content. A preview of what that might look like is this interactive [Story Map](https://storymaps.arcgis.com/stories/6022d40207de4b9199c3eaa07aa2f024).

I've also begun keeping a database of archives around the world that contain Carifesta materials. I've mapped them [here](https://rjkooiker.shinyapps.io/carifesta-archives/).

I'm building relationships with librarians, archivists, community storytellers, and other researchers to make Carifesta Stories a reality.

On this page you'll find my updates about the project. If I'm going to help steward these stories, accountability and transparency are indispensable.

My [Linktree](https://linktr.ee/renekooiker) has all my publications. Check out my traditional cv and resume here.

Let's chat! Find my email, LinkedIn, and GitHub in the sidebar.

## My blog posts

{% for post in site.posts | sort: 'date' %}
  <h2>{{ post.date }}: {{ post.title }}</h2>
  {{ post.excerpt }}
  <p><a href="{{ post.url }}">Read more</a></p>
{% endfor %}