---
layout: default
---

<style>
  /* Sayfanın tam yayılması için basit ayarlar */
  body, html {
    margin: 0;
    padding: 0;
  }

  .hero-container {
    position: relative;
    width: 100%;
    height: 80vh; /* Ekranın %80'ini kaplar */
    background-image: url('assets/images/hero.png'); /* PNG olarak güncelledim */
    background-size: cover;
    background-position: center;
    background-repeat: no-repeat;
    display: flex;
    align-items: center;
    justify-content: center;
    background-color: #333; /* Resim yüklenene kadar koyu bir renk görünür */
  }

  .hero-text {
    color: white;
    font-size: clamp(40px, 8vw, 80px); /* Mobilde küçülür, masaüstünde büyür */
    font-family: "Playfair Display", serif; /* Şık bir font */
    text-align: center;
    text-shadow: 2px 2px 15px rgba(0,0,0,0.6);
    font-weight: bold;
    letter-spacing: 2px;
  }
</style>

<div class="hero-container">
    <div class="hero-text">
      Nagihan Saka
    </div>
</div>
