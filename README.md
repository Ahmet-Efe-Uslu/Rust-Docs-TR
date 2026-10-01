# Rust-Docs-TR

[![Lisans: MIT](https://img.shields.io/badge/Lisans-MIT-blue.svg)](LICENSE)
[![Rust Sürümü](https://img.shields.io/badge/Rust-1.96.0-orange.svg)](https://www.rust-lang.org/)
[![Dil](https://img.shields.io/badge/Dil-Türkçe-red.svg)](#)
[![Formatlar](https://img.shields.io/badge/Format-md%20%7C%20html%20%7C%20epub%20%7C%20docx%20%7C%20tex-green.svg)](#-dosya-formatları)

Rust programlama dili için kapsamlı, tamamen Türkçe ve çok formatlı dokümantasyon.

---

## 📖 İçindekiler

- [Hakkında](#-hakkında)
- [Özellikler](#-özellikler)
- [Dokümantasyon Yapısı](#-dokümantasyon-yapısı)
- [Dosya Formatları](#-dosya-formatları)
- [Nasıl Kullanılır?](#-nasıl-kullanılır)
- [Katkıda Bulunma](#-katkıda-bulunma)
- [Lisans](#-lisans)
- [İletişim](#-iletişim)
- [Teşekkür](#-teşekkür)
- [Sorumluluk Reddi](#-sorumluluk-reddi)

---

## 📘 Hakkında

**Rust-Docs-TR**, Rust programlama dilini Türkçe öğrenmek, öğretmek ve başvuru kaynağı olarak kullanmak isteyenler için hazırlanmış detaylı bir dokümantasyon deposudur.

İçerik, **Claude Sonnet 5 Medium + Web Search** kullanılarak derlenmiş ve **Rust 1.96.0** sürümü baz alınarak güncellenmiştir. Dokümantasyon; temel kavramlardan ileri seviye konulara kadar geniş bir yelpazeyi kapsar ve her konu, öğrenmeyi kolaylaştıran iki katmanlı bir yapıda sunulur.

Bu depo, Rust topluluğuna açık kaynak bir katkı sunmayı ve Türkçe kaynak eksikliğini gidermeyi amaçlar.

---

## ✨ Özellikler

- **Tamamen Türkçe:** Tüm içerik anlaşılır ve akıcı bir Türkçe ile yazılmıştır.
- **Çoklu format desteği:** Aynı içerik; Markdown, HTML, EPUB, DOCX ve LaTeX olarak sunulur.
- **Modüler konu yapısı:** Her konu bağımsız olarak okunabilir, sıralı takip zorunlu değildir.
- **İki katmanlı öğrenme:** Her konu önce "İlk Okuma" ile anlatılır, ardından "Recall Kartları" ile pekiştirilir.
- **Güncel sürüm:** Rust 1.96.0'a özgü değişiklikler ve notlar içerir.
- **Açık kaynak:** MIT lisansı ile özgürce kullanılabilir, dağıtılabilir ve değiştirilebilir.
- **Yapay zeka destekli:** İçerik, geniş kapsamlı bir web araştırması ve dil modeli desteğiyle derlenmiştir.

---

## 🧠 Dokümantasyon Yapısı

Dokümantasyon, konu bazlı ilerler. Her konu şu şablonu takip eder:

```text
KONU [numara]: [Konu Başlığı]
Kategori: [Kategori Adı]
Sürüm: Rust 1.96.0

KATMAN 1 — İLK OKUMA
  - Konunun temel anlatımı
  - Kod örnekleri
  - Sık kullanılan komutlar ve yapılar
  - Sürüme özel notlar

KATMAN 2 — RECALL KARTLARI
  - Konuyu pekiştiren soru-cevap kartları
  - Kritik noktaların vurgulanması
  - Hızlı tekrar imkanı
```

Örnek Konu

```text
KONU 1: Cargo ve Proje Yapısı
Kategori: Araçlar
Sürüm: Rust 1.96.0

KATMAN 1 — İLK OKUMA
  - cargo new
  - cargo run
  - cargo check
  - Cargo.toml yapısı
  - cargo add
  - Rust 1.96.0'da LLD linker değişikliği

KATMAN 2 — RECALL KARTLARI
  - Cargo.toml ne işe yarar?
  - cargo check ile cargo build arasındaki fark nedir?
  - Rust 1.96.0'da linker değişikliği neydi?
```

Bu yapı, öğrenilen bilginin kalıcı hale gelmesini hedefler.

---

📂 Dosya Formatları

Depoda aynı içeriğin farklı kullanım senaryolarına uygun beş farklı formatta sunulduğu dosyalar bulunur:

Dosya Açıklama Kullanım Alanı
Rust.md Markdown formatında ana dokümantasyon GitHub'da okuma, metin düzenleyici, statik site üreticileri
Rust.html Tarayıcıda okunabilir web sürümü Çevrimdışı tarayıcı, hızlı başvuru
Rust.epub E-kitap formatı Telefon, tablet, e-kitap okuyucu
Rust.docx Word belgesi Düzenleme, yazdırma, kurumsal kullanım
Rust.tex LaTeX kaynak dosyası Akademik çalışma, özelleştirilmiş PDF üretimi
LICENSE MIT lisans metni Yasal bilgilendirme
README.md Bu dosya Depo tanıtımı ve kullanım kılavuzu

---

🚀 Nasıl Kullanılır?

1. Doğrudan GitHub'da Okuma

· Rust.md dosyasına tıklayarak GitHub arayüzünde okuyabilirsiniz.
· Markdown formatı sayesinde başlıklar, kod blokları ve tablolar düzgün görüntülenir.

2. Tarayıcıda Açma

· Rust.html dosyasını indirin ve herhangi bir web tarayıcısında açın.
· İnternet bağlantısı gerektirmez.

3. E-kitap Okuyucuda Okuma

· Rust.epub dosyasını indirin.
· Telefonunuzdaki veya tabletinizdeki e-kitap uygulamasına (ör. Apple Books, Google Play Books, Calibre) ekleyin.

4. Word ile Düzenleme

· Rust.docx dosyasını indirin.
· Microsoft Word, LibreOffice Writer veya Google Docs ile açıp düzenleyebilirsiniz.

5. LaTeX ile Derleme

· Rust.tex dosyasını indirin.
· Herhangi bir LaTeX dağıtımı (TeX Live, MiKTeX) ile PDF'ye dönüştürebilirsiniz.

6. Repoyu Klonlama

Tüm dosyalara yerel olarak erişmek için:

```bash
git clone https://github.com/Ahmet-Efe-Uslu/Rust-Docs-TR.git
cd Rust-Docs-TR
```

---

🤝 Katkıda Bulunma

Katkılarınız bu projeyi daha da güçlendirecektir. Aşağıdaki yollarla katkı sağlayabilirsiniz:

· Hata bildirimi: İçerikte yanlış veya eksik gördüğünüz yerler için Issue açın.
· Düzeltme: Yazım hataları, dil bilgisi veya teknik yanlışlar için Pull Request gönderin.
· Yeni konu: Dokümantasyona eklenmesini istediğiniz konular için öneri sunun.
· Çeviri iyileştirmesi: Türkçe ifadelerin daha anlaşılır hale gelmesine yardımcı olun.
· Format desteği: Yeni bir dosya formatı (ör. PDF) eklenmesi için fikir verin.

Katkı sağlamadan önce lütfen mevcut yapıyı ve üslubu korumaya özen gösterin. Büyük değişiklikler için önce bir Issue açarak tartışma başlatmanız önerilir.

---

📜 Lisans

Bu proje MIT License ile lisanslanmıştır.

Copyright (c) 2026 PixelPhantom

Ayrıntılar için LICENSE dosyasına bakabilirsiniz.

---

📬 İletişim

· GitHub: Ahmet-Efe-Uslu
· Repo: Rust-Docs-TR
· E-posta: javacoder3131@gmail.com
· Sorular ve Öneriler: Lütfen GitHub Issues üzerinden veya doğrudan e-posta yoluyla iletişime geçin.

---

🙏 Teşekkür

· Bu dokümantasyonun derlenmesinde kullanılan Claude Sonnet 5 Medium + Web Search teknolojisine,
· Rust topluluğuna ve resmi dokümantasyona,
· Geri bildirimleriyle katkı sağlayan tüm kullanıcılara teşekkür ederiz.

---

⚠️ Sorumluluk Reddi

Bu dokümantasyon, yapay zeka destekli olarak derlenmiştir. İçerikte hata, eksiklik veya güncel olmayan bilgiler bulunabilir. Rust programlama dili hakkında en doğru ve güncel bilgi için her zaman resmi Rust dokümantasyonunu referans almanız önerilir.

Bu depodaki bilgilerin kullanımından doğabilecek sonuçlardan depo sahibi ve katkıda bulunanlar sorumlu tutulamaz.

---

Rust-Docs-TR — Türkçe Rust öğrenimine açık kaynak bir katkı.
