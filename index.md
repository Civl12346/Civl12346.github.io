---
layout: default
---

# What is Froggo Bloggo?

Froggo Bloggo is a place for me to store random stories, essays, and other miscellaneous writing. I hope that it offers interesting reading to anyone that comes across this site, and I hope to put up decent quality work that serve as a brief insight into whatever I feel like is worthing writing about at the time. It's also just fun to make a website. I've made a few before (its been a long while though) and they never really had much of a purpose, so I never kept them around too long. We'll see how this one goes. Anyways, if you've stumbled onto this site have a look around. I hope that it is interesting.

# What to Expect From Froggo Bloggo?

I'm not entirely sure myself. It will mostly be essays of various topics which I end up being passionate enough to write about and which I feel like I have something to contribute regarding the topic. I will probably also upload random stories that I write. Usually, I'm inspired to an idea by something and then feel like writing a short story around the idea. I write in all kinds of genres and try not to write the same thing twice. Hopefully, they will be worth reading and over time there will be a nice collection to read from, but we shall see.

# Here is a List of Posts:
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

