---
layout: post
title: Este es el primer post
subtitle: Subtitulo del primer post
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [test]
comments: true
---

Esta es una demostración para mostrarle como escribir publicaciones con Markdown. Le recomiendo encarecidamente que [tome 5 minutos para aprender a escribir en Markdown] (https://markdowntutorial.com/) - le enseñará cómo transformar texto normal en negrita/cursiva/títulos/tablas/etc.

**Texto en negrita**

## Aquí hay un título secundario.

Aquí hay una mesa inútil:

| Numero | Siguiente numero | Anterior numero |
| :------ |:--- | :--- |
| Cinco | Seis | Cuatro |
| Diez | Once | Nueve |
| Siete | Ocho | Seis |
| Dos | Tres | Uno |


¿Qué tal un rico crep?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

También puede estar centrado!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}


Aquí hay un fragmento de código:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~


Y aquí está el mismo código con resaltado de sintaxis:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```


Y aquí está el mismo código una vez más pero con números de línea:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Cuadros

Puede agregar cuadros de notificación, advertencia y error como este:

### Notificación

{: .box-note}
**Nota:** Este es un cuadro de notificación.

### Warning

{: .box-warning}
**Advertencia:** Este es un cuadro de advertencia.

### Error

{: .box-error}
**Error:** Este es un cuadro de error.
