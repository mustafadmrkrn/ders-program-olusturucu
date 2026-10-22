# 📅 Dinamik Ders Programı Oluşturucu

Öğrencilerin haftalık ders programını kolayca oluşturup PDF olarak indirebildiği sürükle-bırak tabanlı bir web uygulaması.

![HTML](https://img.shields.io/badge/HTML-5-orange?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/Tailwind-CSS-38bdf8?logo=tailwindcss&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow?logo=javascript&logoColor=black)
![License](https://img.shields.io/badge/Lisans-MIT-green)

## ✨ Özellikler

- 🖱️ **Sürükle & Bırak** — Dersleri palet üzerinden tabloya sürükleyin
- 📅 **Ayarlanabilir Saat Aralığı** — Başlangıç ve bitiş saatini kendiniz belirleyin
- 💾 **Otomatik Kayıt** — Program ve öğrenci bilgileri `localStorage` ile tarayıcıda saklanır, sayfa kapatılsa bile kaybolmaz
- 🎨 **Özel Dersler** — İstediğiniz ad ve renkte yeni ders ekleyin; sonradan paletten silebilirsiniz
- 📄 **PDF İndirme** — Programı A4 yatay PDF olarak kaydedin (silme butonları PDF'e yansımaz)
- ♿ **Erişilebilirlik** — ARIA etiketleri, klavye navigasyonu ve ekran okuyucu desteği
- 🔤 **Türkçe Karakter Desteği** — PDF dosya adında `İ`, `Ş`, `Ğ` vb. karakterler doğru dönüştürülür

## 🚀 Kullanım

Projeyi klonlayın ve `index.html` dosyasını tarayıcınızda açın. Herhangi bir kurulum ya da bağımlılık gerekmez.

```bash
git clone https://github.com/mustafadmrkrn/ders-program-olusturucu.git
cd ders-program-olusturucu
# index.html dosyasını çift tıklayarak veya aşağıdaki komutla açın:
open index.html        # macOS
xdg-open index.html   # Linux
start index.html       # Windows
```

> **Not:** Uygulama CDN üzerinden Tailwind CSS, Google Fonts ve html2pdf.js yükler. İlk açılışta internet bağlantısı gerekir.

## 🎯 Nasıl Kullanılır?

1. Sol panelden **öğrenci adını** ve **sınıf/şubeyi** girin
2. İstenirse **saat aralığını** değiştirip "Saatleri Uygula" butonuna tıklayın
3. Ders paletinden bir dersi **tablodaki hücreye sürükleyin**
4. "Ders Oluşturucu" ile **yeni ders ekleyin** (renk seçebilirsiniz)
5. Bitince **PDF Olarak İndir** butonuyla programı kaydedin

## 🛠️ Kullanılan Teknolojiler

| Araç | Sürüm | Açıklama |
|------|-------|----------|
| [Tailwind CSS](https://tailwindcss.com) | v3 (CDN) | Stil |
| [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) | 0.10.1 | PDF dışa aktarma |
| [Google Fonts – Inter](https://fonts.google.com/specimen/Inter) | — | Tipografi |

## 🤝 Katkıda Bulunma

Pull request'ler memnuniyetle karşılanır.

1. Repoyu forklayın
2. Özellik dalı oluşturun (`git checkout -b ozellik/yeni-ozellik`)
3. Değişikliklerinizi commit edin (`git commit -m 'feat: yeni özellik'`)
4. Dalı gönderin (`git push origin ozellik/yeni-ozellik`)
5. Pull Request açın

## 📄 Lisans

Bu proje MIT Lisansı ile lisanslanmıştır.
