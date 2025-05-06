<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <title>Akdeniz İklimi</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            margin: 0; padding: 0;
            background-color: #fafafa;
            color: #333;
        }
        header {
            background-color: #ff9f00;
            color: white;
            padding: 25px;
            text-align: center;
            font-size: 2rem;
            border-bottom: 5px solid #ff6f00;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #ff9f00;
            padding: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        nav div {
            padding: 12px 25px;
            cursor: pointer;
            color: white;
            border-radius: 20px;
            transition: background-color 0.3s ease;
            font-size: 1.1rem;
        }
        nav div:hover, .active-tab {
            background-color: #ff6f00;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
        }
        .content {
            display: none;
            padding: 30px;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            margin: 20px auto;
            max-width: 1100px;
        }
        .active-content {
            display: block;
        }
        h2 {
            color: #ff9f00;
            font-size: 1.6rem;
            margin-bottom: 15px;
        }
        p {
            line-height: 1.6;
            font-size: 1.1rem;
            color: #555;
        }
        .image-container {
            display: flex;
            flex-wrap: wrap;
            gap: 15px;
            margin-top: 20px;
        }
        .image-container img {
            width: 280px;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease;
        }
        .image-container img:hover {
            transform: scale(1.05);
        }
        .tab {
            font-size: 1.1rem;
        }
    </style>
</head>
<body>

    <header>
        <h1>Akdeniz İklimi</h1>
    </header>

    <nav>
        <div class="tab active-tab" onclick="showTab('main')">Ana Sayfa</div>
        <div class="tab" onclick="showTab('images')">Görseller</div>
        <div class="tab" onclick="showTab('plants')">Bitki Türleri</div>
        <div class="tab" onclick="showTab('animals')">Hayvan Türleri</div>
        <div class="tab" onclick="showTab('climate')">İklim ve Etkiler</div>
    </nav>

    <div id="main" class="content active-content">
        <h2>Genel Bakış</h2>
        <p>Akdeniz iklimi, sıcak ve kurak yazlarla ılık ve yağışlı kışların görüldüğü, ılıman bir iklim tipidir. Türkiye'de en çok Akdeniz kıyılarında, Ege'nin güneyinde ve Marmara'nın batısında görülür. Tarım, turizm ve biyolojik çeşitlilik açısından oldukça zengindir.</p>
        <div class="image-container">
            <img src="akdeniz_manzara.jpg" alt="Akdeniz manzarası">
        </div>
    </div>

    <div id="images" class="content">
        <h2>Tüm Görseller</h2>
        <div class="image-container">
            <img src="akdeniz_manzara.jpg" alt="Manzara">
            <img src="akdeniz_bitki1.jpg" alt="Bitki 1">
            <img src="akdeniz_bitki2.jpg" alt="Bitki 2">
            <img src="akdeniz_hayvan1.jpg" alt="Hayvan 1">
            <img src="akdeniz_hayvan2.jpg" alt="Hayvan 2">
            <img src="akdeniz_iklim_etki.jpg" alt="İklim etkisi">
        </div>
    </div>

    <div id="plants" class="content">
        <h2>Akdeniz Bitki Türleri</h2>
        <p>Akdeniz iklimi, kurak yazlara uyum sağlamış bitki örtüsüyle tanınır. En yaygın bitki formasyonu **maki**dir. Makiler; bodur, her dem yeşil çalılardan oluşur. Defne, zeytin, keçiboynuzu, kocayemiş, zakkum ve lavanta bu bölgenin simgesel bitkilerindendir.</p>
        <p>Akdeniz iklimi ayrıca zeytinlikler ve turunçgil bahçeleri ile dikkat çeker. Ormanlık alanlarda kızılçam ve karaçam türleri görülür. Yaz kuraklığına dayanıklı aromatik bitkiler de oldukça yaygındır.</p>
        <div class="image-container">
            <img src="akdeniz_bitki1.jpg" alt="Akdeniz maki bitkileri">
            <img src="akdeniz_bitki2.jpg" alt="Zeytin ağacı veya lavanta tarlası">
        </div>
    </div>

    <div id="animals" class="content">
        <h2>Akdeniz Hayvan Türleri</h2>
        <p>Akdeniz iklimi, çeşitli canlı türlerine ev sahipliği yapar. Özellikle **endemik türler** açısından zengindir. Türkiye kıyılarında nadir görülen **Akdeniz fokları (Monachus monachus)** bu iklimin simgesel türlerinden biridir. </p>
        <p>Ayrıca kızıl geyik, yaban keçisi, kirpi, sincap, porsuk gibi kara hayvanları da yaygındır. Kuş türleri açısından da zengindir; ötücü kuşlar, atmaca ve yırtıcı kuşlar burada yaşam sürer. Bu biyoçeşitlilik Akdeniz havzasını dünya çapında özel kılar.</p>
        <div class="image-container">
            <img src="akdeniz_hayvan1.jpg" alt="Akdeniz fok balığı">
            <img src="akdeniz_hayvan2.jpg" alt="Kızıl geyik veya kirpi">
        </div>
    </div>

    <div id="climate" class="content">
        <h2>İklim ve Etkiler</h2>
        <p>Akdeniz iklimi, tarım ve turizm sektörünü destekleyen önemli bir faktördür. Zeytin, portakal, üzüm ve lavanta gibi ürünler ekonomik değeri yüksek tarım ürünleridir. Ayrıca yaz aylarında sıcak ve kuru hava sayesinde Akdeniz kıyıları milyonlarca turisti ağırlar.</p>
        <p>Ancak uzun süren kuraklıklar su kaynaklarını zorlayabilir ve orman yangını riskini artırır. Bu nedenle sürdürülebilir kaynak yönetimi büyük önem taşır.</p>
        <div class="image-container">
            <img src="akdeniz_iklim_etki.jpg" alt="Turistik Akdeniz yerleşimi">
        </div>
    </div>

    <script>
        function showTab(id) {
            const tabs = document.querySelectorAll(".tab");
            const contents = document.querySelectorAll(".content");
            tabs.forEach(t => t.classList.remove("active-tab"));
            contents.forEach(c => c.classList.remove("active-content"));

            event.target.classList.add("active-tab");
            document.getElementById(id).classList.add("active-content");
        }
    </script>

</body>
</html>
