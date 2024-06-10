---
layout: homePage
title: Psichoterapija
subtitle: 
sitemap:
  priority: 0.9
description : Profesionalios psichoterapijos paslaugos Jūsų emocinei gerovei. Individualios, konfidencialios konsultacijos Kaune.
---

<div id="index-container">
	<div id="describe-text">
		<!-- <img src="{{ '/assets/img/index.jpg' | prepend: site.baseurl }}" class="page-img" style="width: auto;" alt="{{ page.imageAlt }}"> -->
<!-- The Gallery as inline carousel, can be positioned anywhere on the page -->
<div
  id="blueimp-gallery-carousel"
  class="blueimp-gallery blueimp-gallery-carousel"
  aria-label="image carousel"
  style="border-radius: 20px;"
>
  <div class="slides" aria-live="off"></div>
  <h3 class="title"></h3>
  <a
    class="prev"
    aria-controls="blueimp-gallery-carousel"
    aria-label="previous slide"
  ></a>
  <a
    class="next"
    aria-controls="blueimp-gallery-carousel"
    aria-label="next slide"
  ></a>
  <a
    class="play-pause"
    aria-controls="blueimp-gallery-carousel"
    aria-label="play slideshow"
    aria-pressed="true"
    role="button"
  ></a>
  <ol class="indicator"></ol>
</div>		
		<br>
		<div class="about">
			<div class="about__divider">*****</div>
		</div>
		<p>Sveiki atvykę į psichoterapijos kelionę po vidinį pasaulį, kuriame glūdi kiekvieno iš mūsų vidinis vaikas.
Vidinis vaikas auga mumyse nuo pirmųjų dienų po atsiradimo šiame pasaulyje, kaupia emocinę patirtį ir keliauja kartu visą tolimesnį gyvenimą. Tai tik dar kartą įrodo, kiek vaikystės patyrimai yra svarbūs mūsų dabarčiai. Ir, deja, vien tik laikas mūsų negydo ir vidinio vaiko neaugina. Psichoterapija tai ta vieta, kurioje vidinis vaikas gali pasirodyti, atsiskleisti ir augti. Čia tam galime ir susitikti.</p>
	</div>
</div>

<div id="links">
  <a href="/assets/img/index_old.jpg" title="Lonely tree" />
  <a href="/assets/img/index.jpg" title="Talk to me" />
</div>

<script src="/assets/vendor/gallery-master/js/blueimp-gallery.min.js"></script>

<script>
  document.getElementById('links').onclick = function (event) {
    event = event || window.event
    var target = event.target || event.srcElement
    var link = target.src ? target.parentNode : target
    var options = { index: link, event: event }
    var links = this.getElementsByTagName('a')
    blueimp.Gallery(links, options)
  }
</script>

<script>
  blueimp.Gallery(document.getElementById('links').getElementsByTagName('a'), {
    container: '#blueimp-gallery-carousel',
    carousel: true
  })
</script>