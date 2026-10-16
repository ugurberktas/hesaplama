# 🧮 Hesap Makinesi Pro+

Modern, tarayıcıda çalışan, kurulum gerektirmeyen hesap makinesi. Saf HTML/CSS/JavaScript — tek dosya, sıfır bağımlılık.

## ✨ Özellikler

### Temel
- Dört işlem: **toplama, çıkarma, çarpma, bölme**
- **Yüzde (%)** hesabı, ondalık sayılar
- **Binlik ayraç** (1.250.000) ve virgülle ondalık gösterimi
- Sonucu **panoya kopyalama** (⧉ butonu)

### Bilimsel Mod
- Trigonometri: **sin, cos, tan** — **DEG / RAD** açı modu seçilebilir
- **√** (karekök), **xʸ** (üs), **1/x** (çarpım tersi)
- **ln**, **log**, **n!** (faktöriyel), **π**

### Hafıza (Memory)
- **MS** kaydet · **MR** geri çağır · **M+ / M−** artır/azalt · **MC** temizle
- Bellek doluyken ekranda **M** rozeti yanar

### Geçmiş
- Yapılan tüm işlemler yan panelde listelenir
- Bir geçmişe **tıklayarak sonucu geri çağırabilirsin**
- İstenirse tek tuşla temizlenir

### Arayüz
- **Glassmorphism** (cam efektli) tasarım, yüzen ışık baloncukları
- **Açık / koyu tema** geçişi (◐ butonu)
- Butonlarda **ripple** (dalga) efekti, kartlarda belirme animasyonu
- Hatalarda **sallanma animasyonu** + HATA rozeti
- Tam **mobil uyumlu**

## 🎮 Klavye Kısayolları

| Tuş | İşlev |
|---|---|
| `0-9` | Rakam girişi |
| `+ - * /` | Operatörler |
| `^` | Üs (power) |
| `%` | Yüzde |
| `Enter` / `=` | Hesapla |
| `Backspace` | Son karakteri sil |
| `Escape` | Tümünü temizle (AC) |
| `r` | Karekök |

## 🚀 Kullanım

1. `hesap-makinesi.html` dosyasını tarayıcıda aç — hazır!
2. Üstteki **KLASİK / BİLİMSEL** düğmesiyle bilimsel satırı aç/kapa
3. Sağ alttaki **⌨ Kısayollar** balonu tüm kısayolları gösterir

> 💡 Yerel sunucu ile açmak istersen:
> ```bash
> python3 -m http.server 8000
> # sonra http://localhost:8000/hesap-makinesi.html
> ```

## 🛡️ Güvenlik

Hesaplama `Function()` ile yapılır, fakat ifade **yalnızca sayı, operatör ve `Math.pow` çağrılarına** izin veren sıkı bir regex ile doğrulanır — serbest kod çalıştırılmasına izin verilmez.

## 🗂️ Proje Yapısı

```
hesaplama/
├── README.md            # Bu dosya
└── hesap-makinesi.html  # Uygulamanın tamamı (HTML + CSS + JS)
```

## 📄 Lisans

Serbestçe kullanabilir, değiştirebilir ve dağıtabilirsin.
