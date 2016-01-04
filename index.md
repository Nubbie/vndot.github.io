---
layout: default
---

### What is VNDOT

VNDOT is the most powerful, smooth and lightweight Agar.io extension. VNDOT is
built to help team playing together easily in party mode.

VNDOT is created by GS clan from Vietnam. See us playing in Oceania server.

### Why do you need VNDOT?

- Play with your friends easier
- Great performance, much smoother than other extensions
- Beautiful drawing, suppport custom skin and skin from other extensions
- Very easy to use

### How can I get VNDOT?

VNDOT was used privately by GS clan but now we decided to public it
(full feature version). You can get it by clicking on download links above.

Read [How to][how-to] to install and use the extension.

### How can I contribute to VNDOT?

We are going to open source VNDOT extension, that means every one can contribute
to VNDOT, we can make it more excellent together. What you can do is:

- Suggest ideas
- Report bugs
- Join us programming
- Write documentation, record video to help other people to use VNDOT

Getting started by clicking [here][vndot-github].

<div class="home">

  <h1 class="page-heading">What's new?</h1>

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

</div>

[vndot-github]: https://github.com/vndot
[how-to]: /vndot/blog/2016/01/05/how-to.html
