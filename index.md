---
layout: default
title: "Zagreb"
---
# Repository of Symbolic Music Data

Corpus of MEI and MusicXML files for computer-assisted analysis from

[_Музика и речи из ризнице Митрополита Загребачког Дамаскина_](http://www.spc.rs/sr/muzika_rechi_iz_riznice_mitropolita_zagrebachkog_damaskina_grdanichkog)

Music and Words from the Treasury of Metropolitan Damaskin of Zagreb

A demonstration of encoded repository materials that can be searched, displayed, and played in the browser. Scores encoded as MEI, using Verovio web tools for playback.

Encoding and site design: [Mark Saccomano](https://mss2221.github.io/saccomano/).

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
