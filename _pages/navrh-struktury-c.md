---
permalink: /navrh-struktury-c/
title: "Návrh struktury C"
layout: splash
author_profile: false
sitemap: false
robots: noindex
header:
  overlay_image: /assets/images/background-home.jpg
  overlay_filter: 0.5
---

<section class="redesign redesign--c">
  <article class="redesign__card redesign__card--hero">
    <h2>Malé knihkupectví v malém městě, ale něco se do něj vejde.</h2>
    <p>Máme hodně knih pro děti, nějakou tu beletrii i trochu toho odborného, také deskové hry a audioknihy.</p>
    <div class="redesign__actions">
      <a class="btn btn--primary" href="/kontakty/">Zavolat a naplánovat návštěvu</a>
      <a class="btn" href="/about/">Podívat se na prodejnu</a>
    </div>
  </article>

  <div class="redesign__grid redesign__grid--quickinfo">
    <article class="redesign__card">
      <h3>Rychlý kontakt</h3>
      <ul class="redesign__list">
        <li><strong>Telefon:</strong> <a href="tel:+420607928760">607 928 760</a></li>
        <li><strong>Email:</strong> <a href="mailto:knihkupka@knihkupka.cz">knihkupka@knihkupka.cz</a></li>
        <li><strong>Adresa:</strong> Komenského nám. 105, Nové Strašecí</li>
      </ul>
    </article>

    <article class="redesign__card">
      <h3>Otevírací doba</h3>
      <table>
        <tbody>
          <tr><td>Po - Pá</td><td>8:30 - 17:00</td></tr>
          <tr><td>So</td><td>9:00 - 11:00</td></tr>
          <tr><td>Ne</td><td>Zavřeno</td></tr>
        </tbody>
      </table>
    </article>

    <article class="redesign__card">
      <h3>Co u nás najdete</h3>
      <ul class="redesign__list">
        <li>Knihy pro děti</li>
        <li>Beletrie i odborné tituly</li>
        <li>Deskové hry a audioknihy</li>
        <li>Dárkové poukázky</li>
      </ul>
    </article>
  </div>

  <div class="redesign__timeline">
    <article class="redesign__card">
      <h3>1. Vyberte</h3>
      <p>Knihy, deskovky nebo audioknihy podle věku i nálady.</p>
    </article>
    <article class="redesign__card">
      <h3>2. Zeptáte se</h3>
      <p>Když titul nemáme, pokusíme se ho objednat na přání.</p>
    </article>
    <article class="redesign__card">
      <h3>3. Odnesete</h3>
      <p>Zabalíme dárkově a poradíme i s výběrem poukázky.</p>
    </article>
  </div>

  <div class="redesign__grid redesign__grid--contact-map">
    <article class="redesign__card redesign__card--map">
      <iframe title="Mapa Knihkupky" style="border:none" src="https://frame.mapy.cz/s/fosavuluzu" width="700" height="466" frameborder="0"></iframe>
    </article>

    <article class="redesign__card redesign__card--feed">
      <h3>Aktuálně z Facebooku</h3>
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
    </article>
  </div>
</section>

<script>
  var _fbC = document.querySelector('.redesign--c .facebook-embed-wrapper iframe[data-src]');
  if (_fbC) {
    var _wC = Math.min(500, Math.max(180, document.documentElement.clientWidth));
    _fbC.src = _fbC.dataset.src.replace(/width=\d+/, 'width=' + _wC);
    _fbC.style.width = _wC + 'px';
  }
</script>
