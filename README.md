# Lecture Livecode Example

`dash-project` folder’ını açarak dashboarding live lecture’ın final sonuçlarını inceleyebilirsiniz.

`emissions.csv` file’ını indirmek için:

1. Çalıştırmak istediğiniz page’in bulunduğu folder’a gidin.
2. Terminal’de aşağıdaki command’i çalıştırın:

    ```bash
    curl -s https://raw.githubusercontent.com/owid/co2-data/refs/heads/master/owid-co2-data.csv > emissions.csv
    ```

Başka bir page’i çalıştırmak isterseniz, `emissions.csv` file’ını ilgili folder’a kopyalayın veya taşıyın.

------------------------------------------------------------------------------------------------------------------------

📊 CO₂ Emissions Dashboard — Executive Summary
🎯 Amaç (Why this dashboard exists)

Bu dashboard, ülke bazında CO₂ emisyonlarının zaman içindeki değişimini ve enerji kaynağı kırılımlarını görselleştirerek, üst yönetimin:

Uzun vadeli çevresel trendleri anlamasını

Enerji dönüşümüyle ilgili stratejik kararlar almasını

Risk ve fırsat alanlarını hızlıca tespit etmesini

amaçlar.

Odak karar destek içgörüleridir.

👥 Hedef Kitle

Bu dashboard özellikle aşağıdaki roller için tasarlanmıştır:

CEO → Stratejik yön ve uzun vadeli trendler

CFO → Regülasyon, karbon maliyeti ve finansal riskler

Pazarlama / Kurumsal İletişim → Sürdürülebilirlik anlatısı ve itibar

📈 Dashboard Ne Gösteriyor?
1️⃣ Zaman İçinde Toplam CO₂ Emisyonu

1950’den günümüze kadar ülke bazlı toplam CO₂ trendi

Uzun vadeli artış / azalış dönemleri net şekilde görülebiliyor

👉 Yönetici için anlamı:

“Emisyonlarımız yapısal olarak mı düşüyor, yoksa geçici bir dalgalanma mı?”

2️⃣ Enerji Kaynağına Göre Emisyon Kırılımı

Oil / Gas / Coal kaynaklı CO₂ emisyonları ayrı ayrı izlenebiliyor

Enerji karmasının zaman içinde nasıl değiştiği açıkça görülüyor

👉 Yönetici için anlamı:

“Hangi enerji türü gerçek risk? Hangisi stratejik dönüşüm fırsatı?”

3️⃣ Ülke Seçimi ile Dinamik Analiz

Dropdown ile ülke değiştirildiğinde tüm grafikler senkron güncelleniyor

Aynı dashboard farklı ülkeler için tekrar tekrar kullanılabiliyor

👉 Yönetici için anlamı:

“Tek bir araçla farklı pazarları karşılaştırabilirim.”

🧠 Executive Insights (Karar Aldıran Çıkarımlar)
🔹 İçgörü 1 — Emisyonlar her ülkede aynı hızda düşmüyor

Bazı ülkelerde toplam CO₂ emisyonu düşerken, bazı ülkelerde enerji türü değişmesine rağmen toplam emisyon yüksek kalıyor.

📌 CEO için karar:

Tek tip sürdürülebilirlik stratejisi yerine ülke bazlı farklı yol haritaları gerek.

🔹 İçgörü 2 — Coal düşerken Oil/Gas baskısı devam edebiliyor

Kömür kullanımı azalsa bile, petrol ve gaz kaynaklı emisyonlar bazı ülkelerde yapısal olarak yüksek kalıyor.

📌 CFO için karar:

Karbon vergisi ve regülasyon riski yalnızca “kömür” odaklı düşünülmemeli.

🔹 İçgörü 3 — Enerji dönüşümü ≠ Emisyonun otomatik düşmesi

Enerji kaynağı değişimi tek başına yeterli değil; toplam tüketim artışı, kazanımı gölgeleyebiliyor.

📌 CEO & Strateji için karar:

Verimlilik ve talep yönetimi, enerji dönüşümünün ayrılmaz parçası olmalı.

🔹 İçgörü 4 — Bu dashboard bir “takip aracı” olarak konumlanmalı

Bu çalışma tek seferlik bir analiz değil, periyodik olarak izlenmesi gereken bir KPI ekranıdır.

📌 Yönetim için karar:

CO₂ trendleri, finansal KPI’lar gibi düzenli izlenmeli.

🛠️ Teknik Not:
Dashboard Dash (Plotly) ile geliştirilmiştir

Veri kaynağı: Our World in Data – CO₂ Dataset

Amaç: kod sergilemek değil, içgörü üretmek

🚀 Sonuç

Bu dashboard, teknik bir demo değil;
stratejik karar aldırmayı hedefleyen bir yönetici aracıdı
