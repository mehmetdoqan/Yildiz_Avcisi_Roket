🚀 Yıldız Avcısı

Çocuklar için tasarlanmış, blok tabanlı bir kodlama eğitim oyunu. Roketi yönlendirerek tüm yıldızları topla!

🎮 Oyun Hakkında

Yıldız Avcısı, öğrencilerin komut dizileri oluşturarak bir uzay aracını 5×5'lik bir ızgara üzerinde yönlendirdiği, tarayıcı tabanlı bir eğitim oyunudur. Logo/Turtle tarzı hareket sistemiyle algoritmik düşünme ve temel programlama kavramlarını eğlenceli bir şekilde öğretir.

✨ Özellikler
🗺️ 60 Bölüm — 3 zorluk seviyesi (Kolay / Orta / Zor)
🔄 Logo/Turtle Hareket Sistemi — Roketi döndür, sonra ilerlet
☄️ Meteor Engelleri — Yolları kapatan meteorlar
🌀 Kara Delikler — Roketi içine çeken tehlikeli alanlar
⭐ Çoklu Yıldız — Bazı bölümlerde birden fazla yıldız toplanmalı
🔊 Uzay Ses Efektleri — İtiş, toplama, meteor çarpması, kara delik sesleri
🎉 Animasyonlar — Roket dönüşü, yıldız parlaması, kara deliğe çekilme
🛠️ Harita Editörü — Şifre korumalı öğretmen editörü (sifigu)
📱 Mobil Uyumlu — Telefon çerçeveli, dokunmatik destekli arayüz
🕹️ Nasıl Oynanır?
Harita ekranından zorluk seviyesi ve bölüm seç
Komut butonlarıyla hareket sırası oluştur:
↩️ Sol Dön — Roketi 90° sola döndür
↪️ Sağ Dön — Roketi 90° sağa döndür
🚀 İlerle — Roket baktığı yönde bir adım atar
▶ BAŞLAT butonuna bas
Roket komutları sırayla uygular — tüm yıldızları toplarsan kazanırsın!

Komuta tıklayarak silebilirsin. Maksimum 20 komut eklenebilir.

🌌 Harita Elemanları
Eleman	Açıklama
🚀	Uzay aracı (oyuncu)
⭐	Toplanacak yıldız
☄️	Meteor — çarparsan bölüm biter
🌀	Kara delik — içine girersen çekilirsin
🎯 Zorluk Seviyeleri
Seviye	Bölümler	İçerik
🟢 Kolay	1–20	Sadece yıldızlar
🟠 Orta	21–40	Yıldız + Meteorlar
🔴 Zor	41–60	Yıldız + Meteor + Kara Delik
🗂️ Proje Yapısı
yildiz-avcisi/
└──index.html   # Tüm oyun tek dosyada (HTML + CSS + JS)

🚀 Kurulum

Herhangi bir kurulum gerekmez. Sadece uzay_araci.html dosyasını bir tarayıcıda aç:

# Yerel sunucu ile çalıştır (isteğe bağlı)
npx serve .
# veya
python -m http.server 8080


Ya da dosyayı doğrudan tarayıcıya sürükle-bırak.

🛠️ Harita Editörü (Öğretmenler İçin)

Oyun ekranındaki ⚙️ simgesine tıkla ve şifreyi gir. Editörde:

Araç	İşlev
🚀	Roketin başlangıç konumunu ayarla
⭐	Yıldız ekle
☄️	Meteor ekle
🌀	Kara delik ekle
❌	Nesne sil
🧰 Teknolojiler
Vanilla HTML/CSS/JS — Sıfır bağımlılık
Web Audio API — Uzay temalı ses efektleri
CSS Animations — Roket dönüşü, yıldız parlaması, kara delik animasyonları
SVG — Özel roket grafiği (4 yön desteği)
📄 Lisans

MIT License — Eğitim amaçlı serbestçe kullanılabilir.
