---
layout: page
title: All Stickers
---

<div class="stickers">
  {% for sticker in stickers %}
    <a href="{{ site.baseurl }}{{ sticker.url }}">
      <h2>{{ sticker.title }}</h2>
      <div class="stickers-preview">
        <img src="{{ site.baseurl }}/public/stickers/{{ sticker.name }}/1.png" />
        <img src="{{ site.baseurl }}/public/stickers/{{ sticker.name }}/2.png" />
        <img src="{{ site.baseurl }}/public/stickers/{{ sticker.name }}/3.png" />
        <img src="{{ site.baseurl }}/public/stickers/{{ sticker.name }}/4.png" />
        <img src="{{ site.baseurl }}/public/stickers/{{ sticker.name }}/5.png" />
        <img src="{{ site.baseurl }}/public/stickers/{{ sticker.name }}/6.png" />
      </div>
    </a>
  {% endfor %}
</div>
