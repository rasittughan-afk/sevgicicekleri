# 🌸 Sevgi Çiçekleri Anaokulu — Web Sitesi Projesi

## Projeye Genel Bakış

Bu proje, **Kdz. Ereğli / Zonguldak'ta faaliyet gösteren Özel Sevgi Çiçekleri Anaokulu**'nun landing page web sitesidir.

**Ana hedef:** Biri Google'da "kdz ereğli anaokulu", "ereğli kreş", "3-4 yaş anaokulu ereğli" gibi kelimeler yazdığında bu web sitesi ve Google Business profili **en üstte** çıkacak.

---

## 🏫 Okul Bilgileri (Gerçek Veriler)

```
Ad:           Özel Sevgi Çiçekleri Anaokulu
Yaş grubu:    3-6 yaş (3-4 yaş / 4-5 yaş / 5-6 yaş)
Adres:        Kavaklık, Halkapınar Sk. No:12, 67300 Ereğli/Zonguldak
Telefon 1:    0545 376 77 18
Telefon 2:    0545 376 77 19
E-posta:      sevgiciceklerianaokulu6767@gmail.com
Instagram:    https://www.instagram.com/sevgicicekleri_anaokulu/
WhatsApp:     https://wa.me/905453767718  (tıklandığında direkt sohbet açar)
Mezun sayısı: 1500+
Sosyal etkinlik: 50+
```

### Grup İsimleri
- **3-4 Yaş** → Çalışkan Arılar
- **4-5 Yaş** → Minik Kelebekler
- **5-6 Yaş** → Sevimli Çiçekler

### Ders İçerikleri
- Manevi Değerler Eğitimi (Kuran-ı Kerim dahil)
- Robotik Kodlama
- İngilizce
- Akıl ve Zeka Oyunları
- Yaratıcılık Atölyeleri
- Takım Çalışması ve Sosyal Etkinlikler
- Akademik Gelişim Etkinlikleri

### Hakkımızda Metni (Orijinal)
"Geleceğin temelleri küçük yaşta atılır. Anaokulumuzda çocuklarımız, alanında uzman ve deneyimli eğitim kadromuz eşliğinde hem akademik hem de sosyal anlamda donanımlı çocuklar olarak yetişirler. Programımızda; çocuklarımızın milli ve manevi değerlerle yoğrulması, İngilizce dil gelişimi, akıl ve zeka oyunlarıyla problem çözme becerilerinin artırılması, matematiksel düşünme yeteneklerinin desteklenmesi temel hedeflerimizdendir. Sevgi dolu, güvenli ve destekleyici bir ortamda; her çocuğun potansiyelini en iyi şekilde ortaya koymasına yardımcı oluyor, onları güçlü bir geleceğe hazırlıyoruz."

---

## 🎨 Tasarım Direktifi

### Renk Paleti (Mevcut Markayla Uyumlu)
```
Ana mavi-yeşil (teal):  #00897B  (header, butonlar, vurgular)
Sarı/Altın:             #FFC107  (accent, highlight)
Turuncu:                #FF7043  (ikincil accent)
Krem/Beyaz arka plan:   #FAFAFA
Koyu metin:             #1A1A2E
```

### Tasarım Tonu
- Çocuklara özgü **neşeli ama profesyonel** bir dil
- **Sıradışı layout** — sıradan bootstrap grid değil, organik şekiller, eğik section geçişleri, blob formlar
- Renk geçişleri (gradient) ve SVG dekoratif elementler kullanılabilir
- Marka renklerini koru ama tasarımı özgün hissettir
- **Gerçek fotoğraf KULLANILMAYACAK** — illustrasyon, SVG veya placeholder görseller kullan
- Mobil öncelikli (mobile-first) tasarım zorunlu

### Sayfa Yapısı (Sırasıyla)
1. **Hero** — Büyük başlık, kısa slogan, WhatsApp + İletişim CTA butonu
2. **Hakkımızda** — Sol metin, sağda istatistikler (1500+ mezun, 50+ etkinlik)
3. **Gruplar** — 3 kart: Çalışkan Arılar / Minik Kelebekler / Sevimli Çiçekler
4. **Ders İçerikleri** — İkonlu grid layout
5. **Neden Biz / Avantajlar** — Öne çıkan 4-5 madde, görsel destekli
6. **Veli Yorumları** — Otomatik dönen slider, 6-7 yorum, isim belirtilmez
7. **İletişim / Bize Ulaşın** — Telefon, mail, adres, Google Maps embed
8. **Footer** — Logo, sosyal medya ikonları (Instagram + WhatsApp), kısa bilgi

### Zorunlu Elementler
- **WhatsApp floating butonu** — sağ alt köşe, her zaman görünür, tıklayınca `https://wa.me/905453767718` açılır
- **Instagram ikonu** — footer ve hero'da, linki `https://www.instagram.com/sevgicicekleri_anaokulu/`
- **Sticky header** — scroll'da küçülen, transparan başlayıp beyaz/teal olan

---

## 🔍 SEO Stratejisi — EN KRİTİK HEDEF

### Hedef Anahtar Kelimeler (Öncelik Sırасıyla)

**Birincil (en yüksek öncelik):**
- kdz ereğli anaokulu
- ereğli anaokulu
- zonguldak ereğli anaokulu
- özel anaokulu kdz ereğli

**İkincil:**
- kdz ereğli kreş
- ereğli kreş
- 3-4 yaş anaokulu kdz ereğli
- 4-5 yaş anaokulu ereğli
- okul öncesi eğitim ereğli
- özel okul öncesi ereğli zonguldak

**Uzun kuyruk (long-tail):**
- kdz ereğlide iyi anaokulu
- ereğli çocuk yuvası
- zonguldak ereğli okul öncesi
- halkapınar anaokulu
- kavaklık anaokulu ereğli

### Teknik SEO Gereksinimleri (ZORUNLU)

#### HTML Yapısı
```html
<!-- Title Tag - Maksimum 60 karakter -->
<title>Özel Sevgi Çiçekleri Anaokulu | Kdz. Ereğli'nin En İyi Anaokulu</title>

<!-- Meta Description - 150-160 karakter -->
<meta name="description" content="Kdz. Ereğli'de 3-6 yaş anaokulu. 1500+ mezun, uzman eğitim kadrosu. Robotik kodlama, İngilizce, manevi değerler eğitimi. Hemen kaydolun!">

<!-- Meta Keywords -->
<meta name="keywords" content="kdz ereğli anaokulu, ereğli kreş, zonguldak anaokulu, 3-6 yaş anaokulu, özel anaokulu ereğli, okul öncesi eğitim">

<!-- Open Graph (sosyal medya paylaşımları için) -->
<meta property="og:title" content="Özel Sevgi Çiçekleri Anaokulu - Kdz. Ereğli">
<meta property="og:description" content="Sevgi dolu ortamda, uzman eğitimcilerle 3-6 yaş anaokulu. Kdz. Ereğli'nin güvenilir anaokulu.">
<meta property="og:type" content="website">
<meta property="og:locale" content="tr_TR">

<!-- Canonical URL -->
<link rel="canonical" href="https://sevgiciceklerianaokulu.com/">
```

#### Schema.org Yapısal Veri (JSON-LD) — KESİNLİKLE EKLE
```json
{
  "@context": "https://schema.org",
  "@type": "ChildCare",
  "name": "Özel Sevgi Çiçekleri Anaokulu",
  "alternateName": "Sevgi Çiçekleri Anaokulu",
  "description": "Kdz. Ereğli'de 3-6 yaş arası çocuklara hizmet veren özel anaokulu. Robotik kodlama, İngilizce, manevi değerler eğitimi.",
  "url": "https://sevgiciceklerianaokulu.com",
  "telephone": "+905453767718",
  "email": "sevgiciceklerianaokulu6767@gmail.com",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Kavaklık, Halkapınar Sk. No:12",
    "addressLocality": "Kdz. Ereğli",
    "addressRegion": "Zonguldak",
    "postalCode": "67300",
    "addressCountry": "TR"
  },
  "geo": {
    "@type": "GeoCoordinates",
    "latitude": "41.2760",
    "longitude": "31.4207"
  },
  "openingHoursSpecification": {
    "@type": "OpeningHoursSpecification",
    "dayOfWeek": ["Monday","Tuesday","Wednesday","Thursday","Friday"],
    "opens": "08:00",
    "closes": "17:00"
  },
  "sameAs": [
    "https://www.instagram.com/sevgicicekleri_anaokulu/"
  ],
  "priceRange": "₺₺",
  "areaServed": {
    "@type": "City",
    "name": "Kdz. Ereğli"
  }
}
```

#### İçerik SEO Kuralları
- Her section `<section>` tag'i ile sarılı olacak, `id` attribute alacak
- **H1:** Sayfada sadece 1 tane olacak, ana keyword içerecek
- **H2'ler:** Her bölüm başlığı, anahtar kelime içerecek
- Görsellerin hepsinde `alt` attribute ZORUNLU, içinde keyword geçecek
- İç linkler: section'lar arası smooth scroll anchor linkler
- Sayfa yükleme hızı: tüm CSS inline veya minified, JS async/defer

#### Örnek Heading Hiyerarşisi
```
H1: Kdz. Ereğli'nin En Güvenilir Özel Anaokulu — Sevgi Çiçekleri
H2: Hakkımızda — Ereğli'de 15 Yıllık Eğitim Deneyimi
H2: Yaş Gruplarımız — Kdz. Ereğli Anaokulu Programları
H2: Ders İçerikleri — Özel Anaokulu Ereğli Müfredatı
H2: Neden Sevgi Çiçekleri Anaokulu?
H2: Velilerimiz Ne Diyor?
H2: Bize Ulaşın — Kdz. Ereğli Anaokulu İletişim
```

#### Robots & Sitemap
```html
<meta name="robots" content="index, follow">
```
- `sitemap.xml` dosyası oluştur
- `robots.txt` dosyası oluştur

---

## 💬 Veli Yorumları (Hazır İçerik)

Slider/carousel şeklinde dönecek, isim belirtilmeyecek sadece "Veli" yazacak.

**Google'dan alınan gerçek yorumlar (özetlenerek):**

1. *"Sınıflar tertemiz ve güvenlik önlemleri eksiksiz. Çocuğumuz burada hem özgüven kazandı hem de yeni arkadaşlıklar edindi. Kesinlikle tavsiye ediyorum, Öznur öğretmenin ilgisi için de çok teşekkür ederim."* — Bir Veli ⭐⭐⭐⭐⭐

2. *"Sınıflar çok temiz ve düzenli. Öğretmenler de bir o kadar iyi ve ilgili. Verilen eğitimden ve eğitim anlayışından çok memnunuz."* — Bir Veli ⭐⭐⭐⭐⭐

**Web sitesi için ek yorumlar (özgün yazılmış):**

3. *"Robotik kodlama ve İngilizce dersleri sayesinde oğlum ilkokula gerçekten donanımlı başladı. Öğretmenler gerçekten ilgili ve şefkatli."* — Bir Veli ⭐⭐⭐⭐⭐

4. *"Manevi değerler eğitimi konusunda başka yerde bu kadar özenli bir yaklaşım görmedim. Hem modern hem de milli değerlere sahip bir eğitim anlayışı."* — Bir Veli ⭐⭐⭐⭐⭐

5. *"İkinci çocuğumu da Sevgi Çiçekleri'ne verdim. Ailenin bir parçası gibi hissettiriyorlar, iletişimleri mükemmel."* — Bir Veli ⭐⭐⭐⭐⭐

6. *"Akıl oyunları derslerinin çocuğuma katkısını okul sürecinde çok net gördüm. Problem çözme becerisi inanılmaz gelişti."* — Bir Veli ⭐⭐⭐⭐⭐

7. *"Küçük kızım her sabah okula gitmek için benden önce hazır oluyor. Bu bile başlı başına büyük bir başarı!"* — Bir Veli ⭐⭐⭐⭐⭐

---

## 📁 Proje Dosya Yapısı

```
C:/sevgicicekleri/
├── CLAUDE.md              ← Bu dosya (proje hafızası)
├── index.html             ← Ana sayfa (tek sayfa landing page)
├── sitemap.xml            ← SEO için
├── robots.txt             ← SEO için
├── css/
│   └── style.css          ← Varsa ayrı CSS
├── js/
│   └── main.js            ← Varsa ayrı JS
└── assets/
    └── icons/             ← WhatsApp, Instagram SVG ikonları
```

> **NOT:** Web sitesi tek bir `index.html` dosyasında da tamamlanabilir (inline CSS+JS). Tercih edilir çünkü daha hızlı yüklenir.

---

## 🚀 Teknik Gereksinimler

- **Tek sayfa (landing page)** — birden fazla HTML dosyası olmayacak
- **Mobile-first responsive** — 375px, 768px, 1280px breakpoint'leri
- **Vanilla HTML/CSS/JS** — framework gerekmez (jQuery bile yok)
- **Google Fonts** — online embed ile (Inter + Nunito önerisi ama Claude özgür)
- **Font Awesome veya SVG ikonlar** — WhatsApp ve Instagram için
- **Smooth scroll** — tüm iç linkler için
- **Lighthouse skoru hedefi:** Performance 90+, SEO 100, Accessibility 85+
- **WhatsApp butonu:** Sağ altta fixed position, mobilde de görünür
- **Instagram linki:** Footer'da ve hero'da

---

## 🗺️ Google Business Profile — Mevcut Durum & Yapılacaklar

**Profil VAR ve aktif.** Google Business Profile kurulu, şu an görünen veriler:
- Ad: ÖZEL SEVGİ ÇİÇEKLERİ ANAOKULU
- Puan: ⭐ 5.0 (14 yorum) — mükemmel
- Adres: Kavaklık, Halkapınar Sk. No:12, 67300 Ereğli/Zonguldak
- Telefon: 0545 376 77 18
- Çalışma saatleri: Açık · Kapanış saati 18:00
- Kategori: "Ereğli'de bir anaokulu"

**⚠️ KRİTİK EKSİK — Hemen yapılmalı:**
1. **"Web sitesi ekle"** → Web sitesi bittikten sonra URL'i buraya ekle (business.google.com)
   Bu tek adım Google harita sıralamasını doğrudan etkiler.
2. **Kategori genişlet** → Şu an sadece "anaokulu" var, "Okul Öncesi Eğitim Kurumu" da ekle
3. **Açıklama ekle** → SEO keyword'leri içeren Türkçe açıklama yaz (750 karakter max):
   *"Kdz. Ereğli'nin en köklü özel anaokulu. 3-6 yaş grubu çocuklara robotik kodlama, İngilizce, Kuran-ı Kerim ve manevi değerler eğitimi veriyoruz. 1500+ mezun öğrenci, uzman kadro. Kavaklık Mahallesi, Ereğli/Zonguldak."*
4. **Posts paylaş** → Her hafta 1 etkinlik postu at (sıralamayı yukarı taşır)
5. **Fotoğraf ekle** → Mümkünse 10+ fotoğraf (okul içi, etkinlikler, bahçe)
6. **14 yorumu korumak için** → Yeni velilerden Google yorumu iste, QR kod bastır ve kapıya as

**Instagram profili de Google'da görünüyor:** @sevgicicekleri_anaokulu — 1.2B+ takipçi gösteriyor (büyük ihtimal algoritma hatası, gerçek rakam daha düşük ama bu iyi bir sinyal)

---

## 🎨 Referans Siteler & Sektör Dili

### Türkiye'deki Referans Anaokulu Siteleri

Claude bu sitelerin **genel tasarım anlayışını ve içerik dilini** referans alacak.
Hiçbir özellik birebir kopyalanmayacak — sadece Türkiye pazarındaki ton ve yaklaşım için referans.

- **ceceli.com.tr** (Kdz. Ereğli) → Doğrudan rakip, aynı şehir. Onların olmadığı/zayıf olduğu alanlarda öne geç.
- **kolibrikids.com.tr** (İstanbul) → Modern Türk anaokulu tasarımı, oyun tabanlı eğitim dili
- **adaokullari.com** (İstanbul) → Kurumsal ama sıcak ton, veli iletişimi güçlü
- **tobbkultur.com.tr** → Etkinlik odaklı içerik yapısı
- **terakki.org.tr** (İstanbul) → Köklü kurum, güven vurgulu dil

### ⚠️ Önemli Kural
Yukarıdaki sitelerde **olmayan** hiçbir özellik, hizmet veya program web sitesine eklenmeyecek.
Sadece Sevgi Çiçekleri'nde gerçekten olan şeyler yazılacak:
✅ Robotik Kodlama, İngilizce, Kuran-ı Kerim, Akıl ve Zeka Oyunları, Manevi Değerler Eğitimi
❌ Reggio Emilia, Montessori, Waldorf — bunlar programda YOK, yazılmayacak

### Sektör Terminolojisi (SEO + İçerik için)
Bu kelimeler doğal biçimde içeriğe serpiştirilecek:
- "erken çocukluk eğitimi"
- "okul öncesi eğitim"
- "bütünsel gelişim"
- "çocuk merkezli eğitim"
- "oyun tabanlı öğrenme"
- "sosyal-duygusal gelişim"
- "akademik hazırlık"
- "güvenli öğrenme ortamı"
- "uzman eğitim kadrosu"
- "bireysel ilgi"

---

## ⚡ Geliştirme Öncelikleri (Sırayla)

1. `index.html` — tam sayfa, SEO-optimized, responsive
2. `sitemap.xml`
3. `robots.txt`
4. WhatsApp butonu çalışır durumda
5. Instagram linki çalışır durumda
6. Veli yorumları slider'ı otomatik dönüyor
7. İletişim bölümü tam dolu

---

## 🛠️ Kullanılacak Skills

> **Neden bu kadar skill?** "Claude ile yaptığım tüm siteler birbirine benziyor" sorununu çözmek için. Her skill Claude'un farklı bir "kör noktasını" kapatıyor. Hepsini birlikte kullanmak birbirini tamamlayan bir sistem oluşturuyor.

---

### KURULUM

ECC skill koleksiyonunu klonla (bir kez yeterli):
```bash
git clone https://github.com/affaan-m/ECC.git C:/skills/ECC
```

Her skill aşağıda belirtilen yoldan okunacak.

---

### 1. `frontend-design` — Anthropic Resmi Skill
**Dosya:** `/mnt/skills/public/frontend-design/SKILL.md`
**Ne için:** Tasarımın "neden sıradan görünüyor" sorusunu yanıtlar. Başlamadan önce renk/tipografi/layout planını zorunlu kılar, şablona kaçmayı engeller. **Her geliştirme oturumunda ilk okunacak skill.**

---

### 2. `frontend-design-direction` — ECC Skill (Benzer site sorununu çözen asıl silah)
**Dosya:** `C:/skills/ECC/skills/frontend-design-direction/SKILL.md`
**Ne için:** "Claude ile yaptığım tüm siteler birbirine benziyor" probleminin doğrudan çözümü. Bu skill Claude'a şunu söyler:
- Purple gradient, decorative blob, oversized card, vague hero copy YASAK
- Kodlamadan önce: Purpose → Audience → Tone → Memorable detail seç
- Domain'e özgü tasarım yap (anaokulu ≠ SaaS ≠ portfolio)

---

### 3. `make-interfaces-feel-better` — ECC Skill (Polished hissi)
**Dosya:** `C:/skills/ECC/skills/make-interfaces-feel-better/SKILL.md`
**Ne için:** Sitenin "hazır template" değil "el yapımı" hissettirmesini sağlayan küçük detaylar: concentric radius, optical alignment, tabular numbers, hit areas, transition scope. Bunlar olmadan site fonksiyonel ama kaba kalır.

---

### 4. `seo` — ECC Skill (Bu projenin 1 numalı hedefi)
**Dosya:** `C:/skills/ECC/skills/seo/SKILL.md`
**Ne için:** Teknik SEO checklist'i, schema markup, Core Web Vitals (LCP < 2.5s, CLS < 0.1), keyword mapping. Bu CLAUDE.md'deki SEO direktifleriyle birlikte kullanılacak. İkisi birbirini güçlendirir.

---

### 5. `accessibility` — ECC Skill (SEO'yu da etkiler)
**Dosya:** `C:/skills/ECC/skills/accessibility/SKILL.md`
**Ne için:** Google, erişilebilir siteleri sıralamada yukarı taşır. WCAG 2.2 AA standartları, semantic HTML, ARIA attributes, keyboard navigation. Veliler farklı cihazlar kullanıyor — mobilde düzgün çalışması şart.

---

### 6. `motion-foundations` — ECC Skill (Animasyon temeli)
**Dosya:** `C:/skills/ECC/skills/motion-foundations/SKILL.md`
**Ne için:** Veli yorumları slider'ı, hero animasyonları, scroll reveal. Ama önemlisi: `prefers-reduced-motion` desteği ve performans kuralları. Kötü animasyon = yüksek CLS = düşük SEO puanı.

---

### 7. `motion-patterns` — ECC Skill (Hazır animasyon blokları)
**Dosya:** `C:/skills/ECC/skills/motion-patterns/SKILL.md`
**Ne için:** Slider/carousel, scroll-reveal, stagger entrance gibi pattern'ler için referans. Sıfırdan yazmak yerine kanıtlanmış pattern'leri kullan.

---

### Skills Yükleme Sırası (Claude Code'da her oturumda)

```
1. frontend-design          → Tasarım kararlarını ver
2. frontend-design-direction → Generic'e düşme, domain'e özel tasarla
3. make-interfaces-feel-better → Polish detaylarını uygula
4. seo                      → Her HTML elementini SEO lens'iyle yaz
5. accessibility            → Semantic HTML + ARIA
6. motion-foundations       → Animasyon varsa önce bunu oku
7. motion-patterns          → Slider/scroll animasyonları için
```

> **NOT:** `liquid-glass-design` ve `motion-advanced` bu projeye gerekmez — iOS SwiftUI ve karmaşık gesture animasyonları için. `frontend-patterns` de gerekmez — React/Next.js projesi değil, vanilla HTML.

---

## ✅ Tamamlandı Sayılma Kriterleri

- [ ] index.html açılıyor, mobile'da güzel görünüyor
- [ ] WhatsApp butonu çalışıyor (wa.me linki)
- [ ] Instagram linki çalışıyor
- [ ] Veli yorumları otomatik dönüyor
- [ ] Lighthouse SEO skoru 95+
- [ ] Schema.org JSON-LD sayfada var (validator ile kontrol: schema.org/SchemaValidator)
- [ ] Title + description meta tag'leri doğru
- [ ] sitemap.xml var
- [ ] robots.txt var
- [ ] H1'de "kdz ereğli anaokulu" geçiyor (veya eşdeğeri)
- [ ] Tüm görsellerde alt text var
