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
        <h2>DVORCE - Nový domov pro činorodé Tábořany</h2>
      </div>

      <div class="row fw my-2">
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/norma_tabor_panel_01.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/norma_tabor_panel_02.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/norma_tabor_panel_03.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/norma_tabor_panel_04.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/norma/norma_tabor_panel_05.jpg" />
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
        <h2>Nové Dvorce: lokalita mnoha tváří</h2>
      </div>

      <div class="row fw my-2">
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/UNIT_graficka%20cast1024_1.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/UNIT_graficka%20cast1024_2.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/UNIT_graficka%20cast1024_3.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/UNIT_graficka%20cast1024_4.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/unit/UNIT_graficka%20cast1024_5.jpg" />
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
        <h2>třiarchitekti - Michal Fišer a David Mareš</h2>
      </div>

      <div class="row fw my-2">
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/0001.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/0002.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/0003.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/0004.jpg" />
        </div>
        <div class="col-lg-2 col-md-4">
          <img src="http://data.vxk.cz/JPEGYDvorce/3a/0005.jpg" />
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
