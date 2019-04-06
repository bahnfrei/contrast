---
title:  Photo Gallery
categories: photos
---

some cakes...

<ul class="photo-gallery">
  {%- for image in site.static_files %}
      {%- if image.path contains 'assets/images/2019-04-01-Photo-Gallery/01/thumb_' %}
        <li>
          <a href="{{ site.baseurl }}{{ image.path | remove: "thumb_" }}" data-lightbox="01">
              <img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }}" class="img-thumbnail" />
          </a>
        </li>
      {%- endif %}
  {%- endfor %}
</ul>



some lakes...

<ul class="photo-gallery">
  {%- for image in site.static_files %}
      {%- if image.path contains 'assets/images/2019-04-01-Photo-Gallery/02/thumb_' %}
        <li>
          <a href="{{ site.baseurl }}{{ image.path | remove: "thumb_" }}" data-lightbox="02">
              <img src="{{ site.baseurl }}{{ image.path }}" alt="{{ image.basename }}" class="img-thumbnail" />
          </a>
        </li>
      {%- endif %}
  {%- endfor %}
</ul>



and a local embedded video...

{% include video.html id="/assets/videos/2019-04-01-Photo-Gallery/PexelsVideos1110140" %}
