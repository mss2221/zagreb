---
layout: default
title: "Zagreb"
---
# Repository of Symbolic Music Data

Corpus of MEI and MusicXML files for computer-assisted analysis from

[_Музика и речи из ризнице Митрополита Загребачког Дамаскина (Грданичког)_](http://arhiva.spc.rs/sr/muzika_rechi_iz_riznice_mitropolita_zagrebachkog_damaskina_grdanichkog.html){:target="_blank"}
_Music and Words from the Treasury of Metropolitan Damaskin (Grdanički) of Zagreb_

A demonstration of encoded repository materials that can be searched, displayed, and played in the browser. Scores encoded as MEI, using Verovio web tools for playback.

Created with Jekyll template "[Ed.](https://elotroalex.github.io/ed/)" for digital editions.
<hr>

<div class="toc">
  <h2><b>Hymns</b></h2>
  <ul class="texts">
  {% for item in site.texts %}

    <li class="text-title">
      <a href="{{ site.baseurl }}{{ item.url }}">
        {{ item.title }}
      </a>
    </li>
  {% endfor %}
  </ul>
</div>

<!-- Encoding and site design: [Mark Saccomano](https://mss2221.github.io/saccomano/) -->
