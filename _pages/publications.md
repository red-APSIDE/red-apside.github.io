---
title: RED APSIDE - actividades
layout: gridlay
excerpt: RED APSIDE -- actividades.
sitemap: false
permalink: /activities/
---
# Actividades

## Actividades destacadas

**Puedes encontrar la [lista de publicaciones](#lista-de-publicaciones-de-la-red) al final de la pagina.**

## Lista de publicaciones de la red

{% for publi in site.data.publist %}
  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>
{% endfor %}

