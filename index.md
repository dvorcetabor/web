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

  <section id="1cena" class="team section-bg">
    <div class="container" data-aos="fade-up">
      <div class="section-title">
        <h2>1. cena: DVORCE - Nový domov pro činorodé Tábořany</h2>
      </div>

      <div class="row fw my-2">
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/sm.1.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/sm.2.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/sm.3.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/sm.4.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/sm.5.jpg" class="zoomphoto" />
        </div>
      </div>

      <div class="row">
      {% capture my_include %}{% include sections/navrhy/1.md %}{% endcapture %}
      {{ my_include | markdownify }}
      </div>
    </div>
  </section>

  <section id="2cena" class="team">
    <div class="container" data-aos="fade-up">

      <div class="section-title">
        <h2>2. cena: Nové Dvorce: lokalita mnoha tváří</h2>
      </div>

      <div class="row fw my-2">
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/sm.1.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/sm.2.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/sm.3.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/sm.4.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/sm.5.jpg" class="zoomphoto" />
        </div>
      </div>

      <div class="row">
      {% capture my_include %}{% include sections/navrhy/2.md %}{% endcapture %}
      {{ my_include | markdownify }}
      </div>
    </div>
  </section>

  <section id="3cena" class="team section-bg">
    <div class="container" data-aos="fade-up">

      <div class="section-title">
        <h2>3. cena: Třiarchitekti - Michal Fišer a David Mareš</h2>
      </div>

      <div class="row fw my-2">
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/sm.1.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/sm.2.jpg" class="zoomphoto"/>
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/sm.3.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/sm.4.jpg" class="zoomphoto" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/sm.5.jpg" class="zoomphoto" />
        </div>
      </div>

      <div class="row">
      {% capture my_include %}{% include sections/navrhy/3.md %}{% endcapture %}
      {{ my_include | markdownify }}
      </div>
    </div>
  </section>

  {% include sections/contact.html %}

</main><!-- End #main -->
