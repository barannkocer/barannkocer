# Baran Koçer

Ankara Yıldırım Beyazıt Üniversitesi **Büyük Veri Analistliği** (ön lisans) öğrencisiyim. Zonguldak Bülent Ecevit Üniversitesi’nden **3.67/4.00 GNO** ile yatay geçiş yaptım.

*Associate-degree student in Big Data Analytics at Ankara Yıldırım Beyazıt University.*

Python, SQL/PostgreSQL ve veri hazırlama üzerine çalışıyor; LLM araçlarını ve model API’lerini projelerimde kullanıyorum. Uygulamalı yapay zekâ, özellikle LLM tabanlı uygulamalar, model çıktılarının değerlendirilmesi ve veri hazırlama alanlarında staj fırsatlarına açığım.

## Odak alanları

- LLM tabanlı uygulamalar ve model çıktılarının değerlendirilmesi
- Veri toplama, temizleme, ön işleme ve görselleştirme
- SQL ve PostgreSQL

## Teknik yığın

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![xarray](https://img.shields.io/badge/xarray-1d4e89?style=flat-square)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=flat-square)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4B8BBE?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu%20%2F%20WSL2-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square)

Yapay zekâ araçları: Claude (Code, Work), ChatGPT (Codex), Grok Bot, Gemini ve Ollama (yerel model). Model API bağlantıları kuruyor, yerel LLM ile SQL sorguları oluşturup çalıştırıyorum.

## Deneyim

**Stajyer – Veritabanı Yönetimi**  
Profelis Bilişim ve Danışmanlık Tic. ve San. Ltd. Şti. · Ankara · 29.06.2026 – 27.07.2026 (20 iş günü)

- Ubuntu/WSL2 ortamında PostgreSQL kurulumu ve yapılandırmasını gerçekleştirdim; aynı sunucuda birden fazla PostgreSQL sürümünü eş zamanlı çalıştırarak sürüm yönetimi üzerine çalıştım.
- Büyük Veri ve PostgreSQL kesişimini (JSONB, Citus, PL/Python, güvenlik) inceleyen teknik bir makale hazırladım.
- Kurulum ve sorun giderme süreçlerini günlük teknik raporlarla dokümante ettim.

**Saha Satış Temsilcisi – Turkcell Superonline Bayisi**  
Sümer Bilgi Teknolojileri Sanayi Ticaret Limited Şirketi · 05.08.2026 – 30.08.2026. Yüz yüze müşteri görüşmeleriyle iletişim, müşteri odaklılık ve ihtiyaç analizi.

## Projeler

**Öğrenci Veri Seti Üzerinde Veri Temizleme ve Ön İşleme**  
Python · Pandas · NumPy · Feature Engineering

- Eksik verileri mean/median/mode ile doldurdum; aykırı değerleri IQR ile tespit edip Capping ile düzenledim.
- Kategorik verileri One-Hot Encoding ile sayısallaştırdım ve StandardScaler ile ölçeklendirdim.

**Türkiye İllerinde Kuraklık Analizi (TÜBİTAK 2209-A Proje Önerisi)**  
Python · xarray · Pandas · SciPy · CHIRPS · CMIP6

- 81 il için CHIRPS yağış verisinden SPI-1/3/6/12 kuraklık indekslerini hesapladım; Mann-Kendall testi ve Benjamini-Hochberg düzeltmesiyle eğilimleri analiz ettim.
- CMIP6 modelleriyle 2021–2040 kuraklık projeksiyonu için proje önerisi hazırladım.

**Python ile Hava Durumu Verilerinin Analizi ve Görselleştirilmesi**  
Python · Pandas · Matplotlib

- 1000 satırlık veri setini temizledim; temel istatistikler (mean, median, std) ve histogram, scatter plot, boxplot, bar chart ile analiz ettim.

**Kişisel Portföy Web Sitesi**  
Python · Web Development · Admin Panel

- Kişisel portföy sitesi ve dinamik içerik yönetimi için veritabanı bağlantılı admin paneli geliştirdim. Canlı site: [barankocer.com.tr](https://barankocer.com.tr)

**[Mulakat RAG – Kaynaklı Ders Asistanı](https://github.com/barannkocer/mulakat-rag)**  
Yerel RAG uygulaması: Ollama, Chroma, FastAPI ve C#/WPF masaüstü istemcisi; değerlendirme (eval) seti.

- PDF parçalama (chunking), Ollama ile gömme (embedding) ve Chroma ile vektör arama
- FastAPI REST servisi; soru ve cevapların JSON şemasıyla iletilmesi
- Üç prompt yaklaşımını 180 gerçek model yanıtıyla karşılaştıran bir eval
- pytest testleri ve C#/WPF masaüstü istemcisi

**[Altyazı Köprüsü – Oyunlar İçin Gerçek Zamanlı Türkçe Altyazı](https://github.com/barannkocer/altyazi-koprusu)**  
Python · OpenCV · RapidOCR · PyQt6 · deep-translator

- Ekranın altyazı bölgesini saniyede 8 kare yakalayıp OpenCV ile temizleyen ve yerel OCR ile okuyan bir pipeline kurdum.
- Konum, kutu ve harf kurallarıyla yalnızca diyalog altyazılarını süzdüm; yarım kareleri iki okuma onayıyla eledim.
- Çeviriyi arka planda önbellekli ve yedekli servislerle (Google, DeepL, MyMemory) yapıp Türkçeyi PyQt6 katmanıyla İngilizcenin üstüne yerleştirdim; pytest testleri.

## Eğitim

- **Ankara Yıldırım Beyazıt Üniversitesi** — Ön Lisans, Büyük Veri Analistliği (Yatay Geçiş 1. Asil) · 2026 – Devam
- **Zonguldak Bülent Ecevit Üniversitesi** — Ön Lisans, Büyük Veri Analistliği · GNO: 3.67 / 4.00 · 2025 – 2026

## Seminerler

AYBÜ Teknik Bilimler MYO – Büyük Veri Analistliği Programı, “Büyük Veri Dünyasında Güncel Konular” seminer dizisi:

- **18.11.2026** — Yapay Zekâ İşe Başladı. Veriyi Kim Hazırlıyor, Sistemi Kim Koruyor? (Eren Hasipek, Türkiye Siber Güvenlik Kümelenmesi)
- **14.10.2026** — Analiz ve Kanıta Dayalı Kamu Politikaları (T.C. Sanayi ve Teknoloji Bakanlığı Stratejik Araştırmalar ve Verimlilik Genel Müdürlüğü)
- **30.09.2026** — Kurumsal Veri Yönetimi: Veri Ambarı Mimarisi, Veri Bütünlüğü ve Sahadan Uygulamalar (Ahmet Fırat Köse, Sentinus Holding IT Direktörü)

**19. Uluslararası Bilgi Güvenliği ve Kriptoloji Konferansı (ISCTurkey 2026)** — Bölüm başkanı Dr. Öğr. Gör. Harun Kınacı ile birlikte · Dinleyici · 20.10.2026

**Bilişim Teknolojilerinde Patent Farkındalığı** — ZBEÜ Bilişim Teknolojileri MYO · Prof. Dr. Şenay Saraç · Katılımcı · 09.12.2025

## Topluluk ve liderlik

**Karaelmas Alemdar Oryantiring Topluluğu Başkanı** · 2025–2026 Güz · Zonguldak Bülent Ecevit Üniversitesi

## İletişim

- E-posta: [barankocer1@gmail.com](mailto:barankocer1@gmail.com)
- Web sitesi: [https://barankocer.com.tr](https://barankocer.com.tr)
- LinkedIn: [linkedin.com/in/baran-kocer](https://www.linkedin.com/in/baran-kocer/)
- Özgeçmiş (PDF): [cv/Baran_Kocer_CV.pdf](cv/Baran_Kocer_CV.pdf)
