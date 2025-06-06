<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Karasal İklim Ve Biyomları</title>
  <style>
    /* Genel stil */
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: #2c3e50; /* Koyu mavi arka plan */
      color: #fff; /* Beyaz metin */
      line-height: 1.6;
    }

    /* Başlık kısmı */
    header {
      background: #2c3e50; /* Koyu mavi */
      color: #f39c12; /* Altın sarısı */
      text-align: center;
      padding: 30px 0;
      font-size: 2.2rem; /* Başlık boyutu */
      font-weight: bold;
      border-bottom: 4px solid #f39c12; /* Başlık altı için altın sarısı çizgi */
    }

    header h1 {
      margin: 0;
    }

    /* Menü kısmı */
    nav {
      background: #34495e; /* Koyu gri-mavi ton */
      display: flex;
      justify-content: center;
      padding: 12px 0;
    }

    nav a {
      color: #f39c12; /* Altın sarısı yazı */
      padding: 14px 20px;
      text-decoration: none;
      text-transform: uppercase;
      font-weight: bold;
      border-right: 2px solid #f39c12; /* Menü öğeleri arasında ince altın sarısı çizgi */
    }

    nav a:last-child {
      border-right: none;
    }

    nav a:hover {
      background: #f39c12; /* Altın sarısı arka plan */
      color: #fff;
      transition: 0.3s;
    }

    /* Bölümler */
    section {
      padding: 30px;
      margin: 20px;
      background: #34495e; /* Koyu gri-mavi ton */
      border-radius: 8px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
      display: none;
    }

    section.active {
      display: block;
    }

    /* Başlıklar */
    section h2 {
      color: #f39c12; /* Altın sarısı başlık */
      font-size: 2rem;
      text-align: center;
    }

    /* Metin ve resimler */
    section p {
      font-size: 1.1rem;
      text-align: justify;
      line-height: 1.8;
      color: #ecf0f1; /* Açık gri beyaz metin */
    }

    img {
      width: 100%;
      max-width: 350px;
      margin: 10px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    img:hover {
      transform: scale(1.05);
    }

    /* Fotoğraf galerisi */
    #foto {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    #foto img {
      margin: 15px;
    }

  </style>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&display=swap" rel="stylesheet">
</head>
<body>

<header>
  <h1>Karasal İklim Ve Biyomları</h1>
</header>

<nav>
  <a href="#" onclick="showSection('iklim')">İklim Özellikleri</a>
  <a href="#" onclick="showSection('bitki')">Bitki Türleri</a>
  <a href="#" onclick="showSection('hayvan')">Hayvan Türleri</a>
  <a href="#" onclick="showSection('foto')">Fotoğraflar</a>
</nav>

<section id="iklim" class="active">
  <h2>Karasal İklim Özellikleri</h2>
  <p>Karasal iklim, deniz etkisinden uzak iç bölgelerde görülür. Yazları sıcak ve kurak, kışları ise soğuk ve kar yağışlıdır. Sıcaklık farkları çok fazladır. Yıllık yağış miktarı azdır. Özellikle gece ve gündüz sıcaklıkları arasında büyük farklar vardır. Bitki örtüsü genellikle bozkırdır. Bu iklimin en belirgin özelliklerinden biri de ani sıcaklık değişimlerinin ve uzun kışların etkisiyle biyolojik çeşitliliğin sınırlı olmasıdır.</p>
  <img src="karasal1.jpg" alt="Karasal İklim 1">
  <img src="karasal2.jpg" alt="Karasal İklim 2">
</section>

<section id="bitki">
  <h2>Karasal İklimde Bitki Türleri</h2>
  <p>Karasal iklimin hakim olduğu bölgelerde doğal bitki örtüsü bozkırdır. Bozkırlar, yazın kuruyan, ilkbaharda yeşeren ot topluluklarıdır. Bu bölgede yer alan çalı türleri, bitki çeşitliliği açısından oldukça önemlidir. Kuraklığa dayanıklı çalılar, kısa boylu otlar ve yer yer çam ormanları görülür. Çalı biyomu, bu iklimde daha belirgindir, özellikle Doğu Anadolu gibi bölgelerde yoğunlaşan çalı türleri, bölgenin iklim koşullarına uyum sağlamış türlerden oluşur. Karasal iklimin bitki çeşitliliği, daha fazla tür barındırmakla birlikte, ekstrem iklim koşulları nedeniyle bu çeşitliliğin sürdürülebilirliği sınırlıdır. Stepler ve yüksek yerlerde ise orman kalıntıları, biyolojik çeşitliliğin bir göstergesi olarak yer alır.</p>
  <img src="karasal_bitki1.jpg" alt="Bozkır Bitki">
  <img src="karasal_bitki2.jpg" alt="Kurak Bitki Örtüsü">
</section>

<section id="hayvan">
  <h2>Karasal İklimde Hayvan Türleri</h2>
  <p>Karasal iklimde biyolojik çeşitlilik, bitki örtüsündeki kısıtlamalardan dolayı genellikle düşük olsa da, yine de çeşitli hayvan türlerine ev sahipliği yapar. Bu bölgede yaşayan hayvanlar genellikle soğuk ve kurak koşullara dayanıklıdır. Yaban tavşanı, tilki, kurt, geyik, vaşak gibi memeliler; doğan, kartal gibi yırtıcı kuşlar yaygındır. Bu türler, biyolojik çeşitliliğin azalmasına rağmen belirli alanlarda hâlâ sürdürülebilir bir yaşam alanı bulabilmektedir.</p>
  <img src="karasal_hayvan1.jpg" alt="Karasal İklim Hayvanı 1">
  <img src="karasal_hayvan2.jpg" alt="Karasal İklim Hayvanı 2">
</section>

<section id="foto">
  <h2>Tüm Fotoğraflar</h2>
  <div id="foto">
    <img src="karasal1.jpg" alt="Karasal İklim">
    <img src="karasal2.jpg" alt="Karasal İklim 2">
    <img src="karasal_bitki1.jpg" alt="Bitki 1">
    <img src="karasal_bitki2.jpg" alt="Bitki 2">
    <img src="karasal_hayvan1.jpg" alt="Hayvan 1">
    <img src="karasal_hayvan2.jpg" alt="Hayvan 2">
  </div>
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
