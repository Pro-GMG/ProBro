# 💻 ProBro - AI Bilgisayar Asistanı

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/ProTechnologies/ProBro)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/platform-Windows%2010%2B-0078d7.svg)](https://github.com/ProTechnologies/ProBro)

> **Yapay Zeka Destekli Bilgisayar Asistanı** | Terminal komutlarını anlar, kod yazar, sistem bilgisi verir.

---

## 🚀 Özellikler

| Özellik | Açıklama |
|---------|----------|
| 🧠 **Yapay Zeka** | Llama 3.2 tabanlı özel model ile çalışır |
| 💻 **Terminal Komutları** | Doğal dili komutlara çevirir |
| 📝 **Kod Yazabilir** | Python, JavaScript, Bash, HTML, CSS |
| 🌐 **HTML/CSS** | Web sayfası oluşturabilir |
| 📊 **Sistem Bilgisi** | CPU, RAM, Disk kullanımı |
| ⚡ **Hızlı & Hafif** | Düşük kaynak tüketimi |
| 🔒 **Tamamen Güvenli** | Tehlikeli komutları engeller |
| 🪟 **Windows 10/11** | Native uygulama |

---

## 📥 İndir

### [⬇️ ProBro v1.0.0 İndir](https://github.com/ProTechnologies/ProBro/releases/latest)

| Sürüm | Platform | Boyut |
|-------|----------|-------|
| v1.0.0 | Windows 10/11 (64-bit) | ~100 MB |

---

## 📋 Sistem Gereksinimleri

| Gereksinim | Minimum | Önerilen |
|------------|---------|----------|
| **İşletim Sistemi** | Windows 10 64-bit | Windows 11 64-bit |
| **RAM** | 4 GB | 8 GB |
| **Disk Alanı** | 3 GB | 5 GB |
| **İnternet** | İlk kurulum için | - |

---

## 🎯 Kullanım

### Temel Komutlar

```bash
ProBro> selam
🤖 Merhaba! 👋 Ne yapmak istersin?

ProBro> bugün oluşan dosyaları bul
▶ find . -type f -mtime -1
[çıktı]

ProBro> sistem durumu
📊 SİSTEM BİLGİSİ
CPU: %15.2
RAM: 4.2 GB / 8.0 GB (%52.5)

ProBro> bana bir Python kodu yaz (fibonacci)
📝 Kod (python):
def fibonacci(n):
    if n <= 1:
        return n
    return fibonacci(n-1) + fibonacci(n-2)
Örnek Kullanımlar
Ne Yapmak İstersin?	Yaz
Bugün oluşan dosyaları bul	bugün oluşan dosyaları bul
Büyük dosyaları göster	büyük dosyaları bul
Sistem durumu	sistem durumu
Disk kullanımı	disk kullanımı
Python kodu yaz	bana bir Python kodu yaz
HTML sayfası yap	bana bir HTML sayfası yap
Komut açıklama	ls -la ne işe yarar?
🔧 Kurulum
1. ProBro'yu İndir
ProBro v1.0.0 İndir

2. Kurulumu Başlat
ProBro Setup 1.0.0.exe dosyasını çalıştır

Kurulum sihirbazını takip et

Masaüstü kısayolu oluştur (önerilir)

3. İlk Çalıştırma
ProBro'yu masaüstünden başlat

AI modeli otomatik indirilir (~2 GB)

İndirme tamamlandığında kullanmaya başla

🏗️ Geliştirici Bilgileri
Teknolojiler
yaml
Frontend: HTML5, CSS3, JavaScript
Backend: Node.js, Electron
AI Model: Llama 3.2 3B (Özel eğitilmiş)
AI Motor: Ollama
Build Tool: electron-builder
Proje Yapısı
text
ProBro/
├── main.js              # Electron ana dosyası
├── renderer.js          # UI mantığı
├── index.html           # Ana arayüz
├── style.css            # Stil dosyası
├── package.json         # Bağımlılıklar
├── Modelfile            # AI model yapılandırması
└── dist/                # Derlenmiş uygulama
🤝 Katkıda Bulun
