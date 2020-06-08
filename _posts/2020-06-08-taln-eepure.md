---
layout: post
title: "Muzeeglot: a Web Interface for Visualizing Multilingual Music Genre Embedding Spaces"
date: 2020-06-08 00:00:00 +0200
category: Publication
author: eepure
readtime: 4
people:
 - eepure
 - gsalha
 - fvoituret
 - mbaranes
 - rhennequin
publication_type: conference
publication_title: "Muzeeglot : cross-lingual multi-source music item annotation from music genre embeddings"
publication_year: 2020
publication_month: June
publication_authors: E. V. Epure, G. Salha,  F. Voituret, M. Baranes, R. Hennequin
publication_conference: JEP-TALN-RECITAL
publication_preprint: https://jep-taln2020.loria.fr/article-156/ 
publication_code: "https://github.com/deezer/muzeeglot"
publication_demo: "https://research.deezer.com/muzeeglot"
---

We present <i>Muzeeglot</i>, a propotype aiming at illustrating how multilingual music genre embedding space representations can be leveraged to generate cross-lingual music genre annotations for <a href="https://wiki.dbpedia.org">DBpedia</a> music entities (artists, albums, tracks...).

<div class="publication-illustration">
    <img
        style="width: 90%; filter: drop-shadow(0 0 0.75rem crimson);"
        src="{{ '/static/images/publis/epure20taln/epure20taln.png' | prepend: site.url }}"
        alt="Muzeeglot"/>
</div>

<i>Muzeeglot</i> includes a web interface to visualize these multilingual music genres embeddings.

Based on annotations from one or several sources languages, our system automatically predicts the corresponding annotations in a target language. Languages supported: 

<ul>
    <li>French (fr)</li>
    <li>English (en)</li>
    <li>Spanish (es)</li>
    <li>Dutch (nl)</li>
    <li>Czech (cs)</li>
    <li>Japanese (ja)</li>
</ul>

<i>Muzeeglot</i> will be presented as a demonstration at the <a href="https://jep-taln2020.loria.fr">JEP-TALN-RECITAL 2020</a> conference.