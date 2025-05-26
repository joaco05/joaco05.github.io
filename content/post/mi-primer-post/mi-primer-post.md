---
title: "Sitio web gratis?"
description: El primer post de mi sitio web
date: 2025-05-26T18:17:35-03:00
image: "https://images.pexels.com/photos/261662/pexels-photo-261662.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1"
hidden: false
comments: true
draft: false
tags: [
    "markdown",
    "css",
    "html",
    "hugo",
]
categories: [
    "informática",
]
---

# Bienvenido a mi primer post!

Aquí voy a empezar a publicar mis locuras, delirios, proyectos e investigaciones tecnológicas.

## Cómo fue creado este sitio web?

Este sitio web fue creado utilizando un dominio de segundo nivel .dev.ar, estos dominios pueden ser obtenidos de forma gratuita en [home.dev.ar](https://home.dev.ar) utilizando un mail.

Para el hosting del sitio utilice [Github Pages](https://github.com), de hecho si te fijas en mi cuenta de github vas a encontrar que este sitio unicamente es un registro CNAME (o alias) del sitio [joaco05.github.io](https://joaco05.github.io).


## Hugo

![Hugo Logo](https://gohugo.io/images/hugo-logo-wide.svg)

[Hugo](https://gohugo.io) es un generador de sitios web estáticos escrito en go que me permite editar posts en formato Markdown.

## Diseño del sitio

Si bien el contenido del sitio es mio en realidad el diseño del sitio es un [tema de github para Hugo](https://github.com/CaiJimmy/hugo-theme-stack).

Esto también me facilita mucho al momento de realizar cambios ya que utiliza un template de Github Actions para que yo al pushear los cambios al repo, se actualicen automáticamente en la web.

## Comentarios

Para los comentarios utilice [Giscus](https://giscus.app/) que me permite vincular los comentarios de mis posts utilizando el apartado discusiones en mi repo de Github.