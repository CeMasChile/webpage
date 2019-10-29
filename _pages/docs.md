---
layout: page
title: Documentación
permalink: /docs
comments: false
AmarMago: false
---

<div class="row justify-content-between">
<div class="col-md-8 pr-5">

<p>Explicación de la documentación</p>

<h4>Código</h4>

<p>Podemos mostrar aquí el código usado en python, por ejemplo:</p>
{% highlight python linenos %}
def hola(name):
  print("¡Te estamos saludando, %s" % name)
{% endhighlight %}

<h4>Herramienta para gráficos</h4>

<p><a href="https://plot.ly">Plot.ly</a></p>

</div>
{%if page.AmarMago == true %}
<h1> MAGO CHUPA EL PEDAZO DE PICO </h1>
{% endif %}

<div class="col-md-4">

<div class="sticky-top sticky-top-80">
<h5>Donativos</h5>

<p>Gracias por tu aporte! Tus donaciones nos ayudan a costear este proyecto <a target="_blank" href="https://github.com/wowthemesnet/mediumish-theme-jekyll">Mediumish <i class="fab fa-github"></i></a>.</p>

<a target="_blank" href="https://www.wowthemes.net/donate/">Donar</a> <a href="{{ site.baseurl}}/">Dashboard</a>

</div>
</div>
</div>
