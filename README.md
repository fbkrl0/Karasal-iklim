<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Karasal İklim</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #f0f0f0; }
    header { background: #4b6584; padding: 20px; text-align: center; color: white; }
    nav { background: #2f3640; display: flex; justify-content: center; }
    nav a { color: white; padding: 15px 20px; text-decoration: none; }
    nav a:hover { background: #718093; }
    section { padding: 20px; display: none; }
    section.active { display: block; background: white; margin: 20px; border-radius: 10px; }
    img { width: 300px; margin: 10px; border-radius: 8px; }
  </style>
</head>
<body>

<header>
  <h1>Karasal İklim</h1>
</header>

<nav>
  <a href="#" onclick="showSection('iklim')">İklim Özellikleri</a>
  <a href="#" onclick="showSection('bitki')">Bitki Türleri</a>
  <a href="#" onclick="showSection('hayvan')">Hayvan Türleri</a>
  <a href="#" onclick="showSection('foto')">Fotoğraflar</a>
</nav>

<section id="iklim" class="active">
  <h2>Karasal İklim Özellikleri</h2>
  <p>Karasal iklim, deniz etkisinden uzak iç bölgelerde görülür. Yazları sıcak ve kurak, kışları ise soğuk ve kar yağışlıdır. Sıcaklık farkları çok fazladır. Yıllık yağış miktarı azdır. Özellikle gece ve gündüz sıcaklıkları arasında büyük farklar vardır. Bitki örtüsü genellikle bozkırdır.</p>
  <img src="karasal1.jpg" alt="Karasal İklim 1">
  <img src="karasal2.jpg" alt="Karasal İklim 2">
</section>

<section id="bitki">
  <h2>Karasal İklimde Bitki Türleri</h2>
  <p>Karasal iklimin hakim olduğu bölgelerde doğal bitki örtüsü bozkırdır. Bozkırlar, yazın kuruyan, ilkbaharda yeşeren ot topluluklarıdır. Kuraklığa dayanıklı çalılar, kısa boylu otlar ve yer yer çam ormanları görülür. Ayrıca stepler ve yüksek yerlerde orman kalıntıları mevcuttur.</p>
  <img src="karasal_bitki1.jpg" alt="Bozkır Bitki">
  <img src="karasal_bitki2.jpg" alt="Kurak Bitki Örtüsü">
</section>

<section id="hayvan">
  <h2>Karasal İklimde Hayvan Türleri</h2>
  <p>Bu iklimde yaşayan hayvanlar genellikle soğuk ve kurak koşullara dayanıklıdır. Yaban tavşanı, tilki, kurt, geyik, vaşak gibi memeliler; doğan, kartal gibi yırtıcı kuşlar yaygındır. Ayrıca step alanlarda yaşayan küçük kemirgen türleri de oldukça fazladır. Bu hayvanlar, uzun kışlara karşı kalın postları ya da uykuya yatma gibi adaptasyonlar geliştirirler.</p>
  <img src="karasal_hayvan1.jpg" alt="Karasal İklim Hayvanı 1">
  <img src="karasal_hayvan2.jpg" alt="Karasal İklim Hayvanı 2">
</section>

<section id="foto">
  <h2>Tüm Fotoğraflar</h2>
  <img src="karasal1.jpg" alt="Karasal İklim">
  <img src="karasal2.jpg" alt="Karasal İklim 2">
  <img src="karasal_bitki1.jpg" alt="Bitki 1">
  <img src="karasal_bitki2.jpg" alt="Bitki 2">
  <img src="karasal_hayvan1.jpg" alt="Hayvan 1">
  <img src="karasal_hayvan2.jpg" alt="Hayvan 2">
</section>

<script>
  function showSection(id) {
    document.querySelectorAll('section').forEach(section => {
      section.classList.remove('active');
    });
    document.getElementById(id).classList.add('active');
  }
</script>

</body>
</html>
