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


How about a yummy crepe?

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

It can also be centered!

![Crepe](https://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg){: .mx-auto.d-block :}

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}

## Boxes
You can add notification, warning and error boxes like this:

### Notification

{: .box-note}
**Note:** This is a notification box.

### Warning

{: .box-warning}
**Warning:** This is a warning box.

### Error

{: .box-error}
**Error:** This is an error box.
