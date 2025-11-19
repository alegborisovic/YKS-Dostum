# Yks Dostum Web Sitesi

Bu web sitesi, App Store Connect için Support URL ve Marketing URL olarak kullanılabilir.

## 📁 Dosya Yapısı

```
website/
├── index.html    # Ana web sitesi dosyası
└── README.md     # Bu dosya
```

## 🚀 Yayınlama Seçenekleri

### Seçenek 1: GitHub Pages (Ücretsiz ve Kolay) ⭐ ÖNERİLEN

1. **GitHub'da yeni bir repository oluşturun:**
   - Repository adı: `yks-dostum-website` (veya istediğiniz bir isim)
   - Public olarak oluşturun

2. **Dosyaları yükleyin:**
   ```bash
   git init
   git add index.html
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/KULLANICI_ADINIZ/yks-dostum-website.git
   git push -u origin main
   ```

3. **GitHub Pages'i etkinleştirin:**
   - Repository → Settings → Pages
   - Source: "Deploy from a branch" seçin
   - Branch: `main` seçin
   - Folder: `/ (root)` seçin
   - Save

4. **URL'iniz hazır:**
   - URL: `https://KULLANICI_ADINIZ.github.io/yks-dostum-website/`
   - Bu URL'i App Store Connect'te kullanabilirsiniz

### Seçenek 2: Netlify (Ücretsiz)

1. **Netlify hesabı oluşturun:** https://www.netlify.com
2. **"Add new site" → "Deploy manually"**
3. **`index.html` dosyasını sürükleyip bırakın**
4. **URL'iniz hazır:** `https://RANDOM-NAME.netlify.app`
5. **Custom domain ekleyebilirsiniz** (opsiyonel)

### Seçenek 3: Vercel (Ücretsiz)

1. **Vercel hesabı oluşturun:** https://vercel.com
2. **"Add New Project"**
3. **GitHub repository'yi bağlayın veya dosyayı yükleyin**
4. **URL'iniz hazır:** `https://RANDOM-NAME.vercel.app`

### Seçenek 4: Kendi Domain'iniz Varsa

1. **Herhangi bir hosting sağlayıcısı kullanın** (örnek: Namecheap, GoDaddy)
2. **`index.html` dosyasını FTP ile yükleyin**
3. **Domain'inizi kullanın:** `https://www.yksdostum.com`

## 📝 App Store Connect'te Kullanım

1. **App Store Connect'e giriş yapın**
2. **"Yks Dostum" uygulamanızı seçin**
3. **"App Information" sekmesine gidin**
4. **Support URL:** Web sitenizin URL'ini girin
5. **Marketing URL:** Aynı URL'yi girin (veya boş bırakabilirsiniz)

**Örnek:**
- Support URL: `https://KULLANICI_ADINIZ.github.io/yks-dostum-website/`
- Marketing URL: `https://KULLANICI_ADINIZ.github.io/yks-dostum-website/`

## ✏️ Özelleştirme

`index.html` dosyasını düzenleyerek:
- İletişim bilgilerini güncelleyebilirsiniz
- Renkleri değiştirebilirsiniz
- Yeni bölümler ekleyebilirsiniz
- FAQ sorularını güncelleyebilirsiniz

## 📧 İletişim Bilgisi

Web sitesinde şu an kullanılan e-posta:
- `emreaydemir480@icloud.com`

Bu e-postayı değiştirmek için `index.html` dosyasındaki ilgili satırı düzenleyin.

## ✅ Kontrol Listesi

- [ ] Web sitesini yayınladınız
- [ ] URL'i test ettiniz (tarayıcıda açıldığını kontrol edin)
- [ ] Mobil cihazlarda görünümü kontrol ettiniz
- [ ] App Store Connect'te Support URL'i eklediniz
- [ ] App Store Connect'te Marketing URL'i eklediniz (opsiyonel)

## 🎨 Özellikler

- ✅ Responsive tasarım (mobil, tablet, desktop)
- ✅ Modern ve profesyonel görünüm
- ✅ Support ve Marketing bölümleri bir arada
- ✅ İletişim bilgileri
- ✅ FAQ bölümü
- ✅ Kolay özelleştirme

