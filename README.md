Titanic Data Analysis & Report Generation
Bu proje, Titanic veri seti üzerinde veri analizi ve görselleştirme işlemleri yaparak, elde edilen grafik ve analizleri bir PDF raporu halinde sunmayı amaçlamaktadır.

🔍 Proje İçeriği
Veri setinin yüklenmesi ve incelenmesi
Eksik veri temizleme ve doldurma
Sayısal sütunların dağılım grafikleri (histogramlar)
Boxplot analizleri
Korelasyon matrisi oluşturma
Scatter plot (dağılım grafikleri) oluşturma
Grafiklerin PDF dosyası olarak raporlanması

📁 Kullanılan Araçlar & Kütüphaneler
Pandas & NumPy (Veri işleme ve analiz)
Seaborn & Matplotlib (Görselleştirme)
FPDF (PDF dosyası oluşturma)

💡 Nasıl Çalıştırılır?
Proje dizinine gerekli kütüphaneleri yükleyin:
pip install -r requirements.txt
titanic_analysis.py dosyasını çalıştırarak raporu oluşturun.

📄 Çıktı
Oluşturulan rapor, titanic_data_report.pdf adıyla proje dizininde yer alacaktır.

📌 Kaynak
Titanic Veri Seti (Kaggle)

✅ Proje Dizini Yapısı:
/Titanic-Data-Analysis-Report
│
├── titanic_analysis.py      # Proje kodlarının bulunduğu Python dosyası
├── requirements.txt         # Gerekli kütüphaneleri içeren dosya (pandas, numpy, matplotlib, seaborn, fpdf)
├── README.md                # Proje açıklaması
├── Grafikler/               # Grafiklerin kaydedildiği klasör
└── titanic_data_report.pdf   # Oluşturulan rapor (çalıştırdıktan sonra oluşacak)
