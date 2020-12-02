---
layout: default
section: blog
description: Stránka táborské pirátské buňky s nejnovějšími články a základním rozcestníkem.
keywords: organizace,transparence,politika
---


{% include sections/hero.html %}

<main id="main">

<section id="cta" class="cta">
  <div class="container" data-aos="zoom-in">
    {% capture my_include %}{% include sections/call2action.md %}{% endcapture %}
    {{ my_include | markdownify }}
  </div>
</section>

  {% include sections/about.html %}

  {% include sections/about-video.html %}

  {% include sections/galerie.html %}

  {% include sections/team.html %}

  {% include sections/odbornici.html %}

  {% include sections/proArchitekty.html %}

  {% include sections/faq.html %}

  {% include sections/contact.html %}

</main><!-- End #main -->
