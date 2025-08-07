# Trendyol Scraper

A Python script to scrape seller information from Trendyol and export detailed results to a styled Excel file.

## Features

- Uses Selenium for browser automation
- Reads seller names from Excel
- Scrapes seller ratings, review counts, and more
- Exports results to Excel with colorful styles and filters

## Setup

1. **Install dependencies:**

# 🚀 Trendyol Seller Data Scraper

![Python](https://img.shields.io/badge/Python-3.8%2B-blue?logo=python)
![Selenium](https://img.shields.io/badge/Selenium-Automation-green?logo=selenium)
![Excel](https://img.shields.io/badge/Excel-Export-217346?logo=microsoft-excel)

---

## 🎯 Özellikler

- 🔍 Trendyol mağaza verilerini otomatik olarak toplar
- 📊 Sonuçları renkli ve filtreli Excel dosyasına aktarır
- 🛡️ Kurumsal ve modüler Python mimarisi
- 🖌️ Excel dosyasında başlık ve hücre stilleri, otomatik sütun genişliği

---

## ⚡ Kurulum

1. Gerekli paketleri yükleyin:
   ```powershell
   pip install -r requirements.txt
   ```
2. Edge WebDriver'ın sisteminizde kurulu olduğundan emin olun.
3. `Trendyol Satıcı Bilgileri.xlsx` dosyasını oluşturun ve mağaza adlarını girin.

---

## 📝 Kullanım

1. Excel dosya yolunu kodda belirtin:
   ```python
   excel_path = r"C:\Users\YASIN\Desktop\Trendyol Satıcı Bilgileri.xlsx"
   ```
2. Scripti çalıştırın:
   ```powershell
   python SellerDataScraper.py
   ```
3. Sonuçlar `Trendyol Satıcı Bilgileri (Detaylı).xlsx` dosyasına kaydedilir.

---

## 📦 Çıktı

- Renkli başlık satırı
- Otomatik sütun genişliği
- Filtreli tablo
- Sayısal sütunlar için özel format

---

## 🖼️ Ekran Görüntüsü

![Excel Styles Example](https://img.icons8.com/color/96/000000/ms-excel.png)

---

## 💡 İpuçları

- Mağaza adlarını Excel dosyasına ekleyin.
- Kodunuzu kurumsal projelerde kolayca entegre edebilirsiniz.

---

## 📚 Lisans

MIT
