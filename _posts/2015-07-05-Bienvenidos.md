---
layout: post
title: Migrando
published: true
tags: [localhost]
image:
  feature: migrantes.jpg
---

Desde que los sitios en drupal6 empezaron a necesitar actualizaciones de urgencia, sitios que tienen escasos cambios desde que fueron creados, me empezaron a dar algo de dolor de cabeza. Empece a buscar alternativas para convertirlos en sitios basados en HTML, y despreocuparme de las bases de datos, el php y las actualizaciones de seguridad.

Lo primero que hice fue "fosilizar" los sitios con un comando simple de wget que encontre en [drupal.org](http://drupal.org) a través de [koumbit.org](https://wiki.koumbit.net/Drupal/CommentFossiliser) .

_wget -q --mirror -p --html-extension -e robots=off --base=./ -k -P ./ http://www.elsitioafosilizar.info_


Sin embargo aunque este metodo me resulta practico para los sitios que efectivamente ya nunca tendrán nuevas entradas, no me sirve para los sitios que si tendrán actualizaciones de información, aunque espaciadas y escasas.

Despues leí sobre [jekyll](http://jekyllrb.com/) y [prose](http://prose.io/), en el sitio de development seeds. Una manera de publicar blogs en HTML simulando un entorno dinamico.

En la pagina de jekyll vienen algunos recursos y ligas. Desde alli me dirigí al mini manual de Barry Clark "[Build A Blog With Jekyll And GitHub Pages](http://www.smashingmagazine.com/2014/08/01/build-blog-jekyll-github-pages/)"

Este es mi primera entrada en jekyll, usando prose para editar, git para agregar archivos en en mi maquina con [debian](http://www.debian.org), y [github](https://github.com/) para hospedar gratis.
