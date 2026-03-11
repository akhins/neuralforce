# VibeAI

Modern, karanlık (dark) tema ile tasarlanmış tam duyarlı (responsive) bir AI (Yapay Zeka) Agent odaklı açılış sayfası (landing page) projesi. 

## Özellikler

- **Modern & Cyberpunk Tasarım**: Özel renk paleti ve parlayan elementler ile dikkat çekici tasarım.
- **Tam Duyarlı (Responsive)**: Masaüstü, tablet ve mobil cihazlar için optimize edilmiştir.
- **Etkileşimli Animasyonlar**: Saf CSS ve SVG ile oluşturulmuş, yormayan, dinamik robot ve scroll animasyonları.
- **Fonksiyonel UI Öğeleri**: 
  - Mobil uyumlu Hamburger Menü.
  - Sıkça Sorulan Sorular (SSS) bölümü için Accordion listesi.
  - Sayfa kaydırmalarında aktifleşen "Yukarı Çık" ve "Yüzen CTA (Demo)" butonları.
  - İletişim Formlu Demo Talep Modalı.

## Kurulum ve Dağıtım (Deployment)

Bu proje statik bir HTML/CSS/JS projesidir. Node.js, Webpack, ya da herhangi bir derleme aracına ihtiyaç duymaz.

### Yerel Ortamda Çalıştırma

Sadece `index.html` dosyasını tercih ettiğiniz web tarayıcısında (Chrome, Safari, Firefox, vb.) açmanız yeterlidir. Veya bir yerel sunucu kullanabilirsiniz:

```bash
# Python (Mac/Linux/Windows)
python -m http.server 8000
```
Sonrasında [http://localhost:8000](http://localhost:8000) adresine gidebilirsiniz.

### Netlify'a Yükleme (Deployment)

Projenizi Github'a yükledikten sonra Netlify üzerinden otomatik olarak canlıya alabilirsiniz:
1. Netlify hesabınıza giriş yapın.
2. **"Add new site" -> "Import an existing project"** seçeneğine tıklayın.
3. Github'ı seçin ve projenizin reposunu bulun.
4. "Build settings" kısmında herhangi bir ayar yapmanıza gerek yoktur (Build command boş kalabilir, Publish directory kök dizin `/` olacaktır).
5. **"Deploy site"** butonuna tıklayın.

### Github Pages ile Yayınlama
Bu repo Github'da barındırılıyorsa, **Settings -> Pages** sekmesine giderek "Source" kısmını "main" branch olarak seçebilir ve dakikalar içinde sitenizi Github Pages üzerinden yayınlayabilirsiniz.

## Teknolojiler
- HTML5
- CSS3 (Vanilla)
- Vanilla JavaScript
- Google Fonts (Inter, DM Mono)
- Satıriçi (Inline) İsteğe Uyarlanmış SVG'ler
