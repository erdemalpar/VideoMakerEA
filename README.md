# 🎬 Video Maker EA

**Fotoğraflarınızı saniyeler içinde profesyonel videolara dönüştürün.**  
Donma yok, kare atlama yok. Garantili kare işleme teknolojisi ile tarayıcınızda stüdyo kalitesinde sonuçlar alın.

---

<div align="center">
  
  ### ✨ Hemen Deneyin ✨
  
  <a href="https://videomakerea-c41031.gitlab.io/" target="_blank">
    <img src="https://img.shields.io/badge/GitLab_Pages-🚀_CANLI_DEMO-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white&labelColor=111827" height="55" alt="GitLab Demo" />
  </a>
  &nbsp;&nbsp;
  <a href="https://erdemalpar.github.io/VideoMakerEA/" target="_blank">
    <img src="https://img.shields.io/badge/GitHub_Pages-🚀_CANLI_DEMO-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=111827" height="55" alt="GitHub Demo" />
  </a>

  <br><br>
  
  [![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white)](https://gitlab.com/erdemalpar/videomakerea)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/erdemalpar/VideoMakerEA)
  
  <br>
  
  ![Version](https://img.shields.io/badge/Sürüm-v3.31-green?style=flat-square)
  ![Status](https://img.shields.io/badge/Durum-Kararlı-green?style=flat-square)
  ![Tech](https://img.shields.io/badge/Teknoloji-FFmpeg.wasm-blue?style=flat-square)
  ![License](https://img.shields.io/badge/Lisans-Açık_Kaynak-blue?style=flat-square)

</div>

---

## 🌟 Özellikler

*   **🛡️ Garantili Kare Kaydı (v3.15+):** Bilgisayarınız yavaşlasa bile video asla donmaz. Kare-kare işleme teknolojisi ile %100 akıcı sonuç.
*   **👻 Hayalet Buton Teknolojisi:** Sorunsuz dosya yükleme deneyimi.
*   **🎨 Modern Arayüz:** Sürükle-bırak desteği, canlı önizleme ve görsel zaman çizelgesi.
*   **🎵 Müzik Desteği:** MP3 dosyalarınızı yükleyin ve videoya senkronize edin.
*   **⚡ İstemci Tabanlı:** Sunucu yok! Tüm işlemler tarayıcınızda (Client-side) gerçekleşir. Gizliliğiniz %100 güvende.
*   **🌐 Çapraz Platform:** Hem GitLab hem GitHub'da barındırılıyor.

## 🚀 Hızlı Başlangıç

### Canlı Demo
Uygulamayı hemen denemek için:
- **GitLab Pages:** [https://videomakerea-c41031.gitlab.io/](https://videomakerea-c41031.gitlab.io/)
- **GitHub Pages:** [https://erdemalpar.github.io/VideoMakerEA/](https://erdemalpar.github.io/VideoMakerEA/)

### Yerel Kurulum

#### GitLab'dan klonlama:
```bash
git clone https://gitlab.com/erdemalpar/videomakerea.git
cd videomakerea
python3 server.py
```

#### GitHub'dan klonlama:
```bash
git clone https://github.com/erdemalpar/VideoMakerEA.git
cd VideoMakerEA
python3 server.py
```

Ardından tarayıcınızda `http://localhost:8000` adresine gidin.

### Alternatif Sunucu Başlatma Yöntemleri

```bash
# Python HTTP sunucusu
python3 -m http.server 8000

# Node.js ile (http-server kurulu ise)
npx http-server -p 8000

# PHP ile
php -S localhost:8000

# VS Code "Live Server" eklentisi ile
# Sağ tık > "Open with Live Server"
```

## 🛠️ Teknik Detaylar

### Gereksinimler
- Modern web tarayıcısı (Chrome, Firefox, Safari, Edge)
- COOP/COEP başlıkları için HTTP sunucusu (FFmpeg.wasm kullanımı için)

### Kullanılan Teknolojiler
- **FFmpeg.wasm:** Video işleme
- **HTML5 Canvas:** Görsel manipülasyon
- **Web Audio API:** Ses senkronizasyonu
- **Vanilla JavaScript:** Saf JavaScript implementasyonu

## 📦 Proje Yapısı

```
VideoMakerEA/
├── index.html          # Ana uygulama
├── server.py           # COOP/COEP başlıklı Python sunucusu
├── sounds/             # Ses dosyaları klasörü
├── README.md           # Bu dosya
└── .gitlab-ci.yml      # GitLab CI/CD yapılandırması
```

## 🤝 Katkıda Bulunma

Katkılarınızı bekliyoruz! Her iki platformda da pull request/merge request gönderebilirsiniz:
- **GitLab:** https://gitlab.com/erdemalpar/videomakerea
- **GitHub:** https://github.com/erdemalpar/VideoMakerEA

## 📝 Sürüm Geçmişi

- **v3.31** - Mevcut kararlı sürüm
- **v3.15** - Garantili kare kaydı eklendi
- Daha fazla bilgi için commit geçmişine bakın

## 📜 Lisans

Bu proje açık kaynaklıdır. Özgürce kullanabilir, değiştirebilir ve paylaşabilirsiniz.

## 📧 İletişim

**Geliştirici:** Erdem Alpar  
**GitLab:** [@erdemalpar](https://gitlab.com/erdemalpar)  
**GitHub:** [@erdemalpar](https://github.com/erdemalpar)

---

<div align="center">
  <sub>⭐ Projeyi beğendiyseniz yıldız vermeyi unutmayın!</sub>
</div>
