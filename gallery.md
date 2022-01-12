---
layout: default
title: Gallery
permalink: /gallery
order: 2
---
<div class="page-banner">
    <h2>Gallery</h2>
    Shot on Pixel 4XL and edited on Snapseed or Lightroom.
</div>
<br/>

<div class="insta-gallery">
{% jekyllgram 18 %}
  <div class="photo">
    <div class="cover">
        {%- if photo.media_type == "IMAGE" or photo.media_type == "CAROUSEL_ALBUM" -%}
        <img src="{{ photo.media_url }}" />
        {%- else-%}
        <video id="IG-video-{{ photo.id }}" width="100%" height="100%">
            <source type="video/mp4" src="{{ photo.media_url }}" />
        </video>
        {%- endif -%}
    </div>
    <div class="meta">
        <div class="caption">{{ photo.caption }}</div>
        <div class="likes">{{ photo.likes }}</div>
    </div>
    <a class="link" href="{{ photo.permalink }}" id="IG-{{ photo.id }}"></a>
  </div>
  
{% endjekyllgram %}
</div>