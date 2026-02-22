---
permalink: /navrh-struktury-a/
title: "Návrh struktury A"
layout: splash
author_profile: false
sitemap: false
robots: noindex
header:
  overlay_image: /assets/images/background-home.jpg
  overlay_filter: 0.5
---

<section class="redesign redesign--a">
  <div class="redesign__grid redesign__grid--intro">
    <article class="redesign__card">
      <h2>Co u nás najdete</h2>
      <p>Máme hodně knih pro děti, nějakou tu beletrii i trochu toho odborného, také deskové hry a audioknihy.</p>
      <p>Pokud to půjde, objednáme na přání. <a href="mailto:knihkupka@knihkupka.cz">Napište nám</a>, o co máte zájem.</p>
      <p>Zabalíme dárkově. Máte co číst?</p>
    </article>

    <article class="redesign__card">
      <h2>Rychlý kontakt</h2>
      <ul class="redesign__list">
        <li><strong>Telefon:</strong> <a href="tel:+420607928760">607 928 760</a></li>
        <li><strong>Email:</strong> <a href="mailto:knihkupka@knihkupka.cz">knihkupka@knihkupka.cz</a></li>
        <li><strong>Adresa:</strong> Komenského nám. 105, Nové Strašecí</li>
      </ul>
      <a class="btn btn--primary" href="/kontakty/">Detail kontaktů</a>
    </article>
  </div>

  <div class="redesign__grid redesign__grid--hours">
    <article class="redesign__card">
      <h2>Otevírací doba</h2>
      <table>
        <tbody>
          <tr><td>Po - Pá</td><td>8:30 - 17:00</td></tr>
          <tr><td>So</td><td>9:00 - 11:00</td></tr>
          <tr><td>Ne</td><td>Zavřeno</td></tr>
        </tbody>
      </table>
    </article>

    <article class="redesign__card">
      <h2>Sortiment</h2>
      <ul class="redesign__list">
        <li>Knihy pro děti</li>
        <li>Beletrie i odborné tituly</li>
        <li>Deskové hry</li>
        <li>Audioknihy</li>
        <li>Dárkové poukázky</li>
      </ul>
      <a class="btn" href="/about/">Fotogalerie prodejny</a>
    </article>
  </div>

  <section class="homepage-section homepage-section--facebook">
    <div class="facebook-embed-wrapper">
      <iframe
        title="Facebook stránka Knihkupka"
        data-src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fknihkupka&tabs=timeline&width=500&height=720&small_header=true&adapt_container_width=true&hide_cover=true&show_facepile=false&appId"
        style="border:none;overflow:hidden"
        scrolling="no"
        frameborder="0"
        allowfullscreen="true"
        allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
      </iframe>
    </div>
  </section>
</section>

<script>
  var _fbA = document.querySelector('.redesign--a .facebook-embed-wrapper iframe[data-src]');
  if (_fbA) {
    var _wA = Math.min(500, Math.max(180, document.documentElement.clientWidth));
    _fbA.src = _fbA.dataset.src.replace(/width=\d+/, 'width=' + _wA);
    _fbA.style.width = _wA + 'px';
  }
</script>
