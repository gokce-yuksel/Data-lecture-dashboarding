# Lecture Livecode Example

`dash-project` folder’ını açarak dashboarding live lecture’ın final sonuçlarını inceleyebilirsiniz.

`emissions.csv` file’ını indirmek için:

1. Çalıştırmak istediğiniz page’in bulunduğu folder’a gidin.
2. Terminal’de aşağıdaki command’i çalıştırın:

    ```bash
    curl -s https://raw.githubusercontent.com/owid/co2-data/refs/heads/master/owid-co2-data.csv > emissions.csv
    ```

Başka bir page’i çalıştırmak isterseniz, `emissions.csv` file’ını ilgili folder’a kopyalayın veya taşıyın.


📊 Dashboard Hazırlama – CO₂ Emisyonları Analizi
🎯 Proje Amacı

Bu projede amaç, küresel CO₂ emisyon verilerini kullanarak karar vericilere (özellikle CEO seviyesinde) hızlı ve anlaşılır içgörüler sunabilen bir dashboard çalışmasını incelemek ve çalıştırmaktır.

Gerçek hayatta üst düzey yöneticiler:

Kodun nasıl yazıldığından çok

Ne sonuç çıktığıyla ilgilenir.

Bu proje de tam olarak bu bakış açısıyla ele alınmıştır.

🧠 İş Bağlamı (Business Context)

Bu dashboard aşağıdaki sorulara yanıt vermeyi hedefler:

Ülkelerin CO₂ emisyonları zaman içinde nasıl değişiyor?

Hangi ülkeler en büyük emisyon payına sahip?

Emisyon trendleri artış mı düşüş mü gösteriyor?

Sürdürülebilirlik ve çevresel riskler açısından hangi bölgeler kritik?

Bu tür analizler:

Sürdürülebilirlik stratejileri

Yatırım kararları

Uzun vadeli risk yönetimi

gibi konularda CEO ve üst yönetim için doğrudan girdiler üretir.

📂 Kullanılan Veri Seti

Kaynak: Our World in Data (OWID)

Dosya: emissions.csv

İçerik:

Ülke bazlı CO₂ emisyonları

Yıllara göre emisyon değişimleri

Kişi başı ve toplam emisyon metrikleri

Veri, dashboard çalıştırılmadan önce ilgili klasöre manuel olarak indirilmiştir.

🖥️ Dashboard Çalışma Mantığı

Dashboard, Dash (Plotly) kullanılarak geliştirilmiştir.

Emisyon verisi doğrudan emissions.csv dosyasından okunur.

Grafikler ve metrikler gerçek zamanlı olarak bu veri setinden beslenir.

Farklı dashboard sayfaları aynı veri setini kullanacak şekilde tasarlanmıştır.

Bu projede en az bir dashboard page başarıyla çalıştırılmış ve doğrulanmıştır.

📈 Sunulan İçgörüler

Dashboard üzerinden elde edilebilecek temel içgörüler:

Küresel CO₂ emisyonlarının zaman içindeki artış eğilimi

Ülkeler arası emisyon farkları

Yüksek emisyonlu ülkelerin küresel payı

Uzun vadeli çevresel risk göstergeleri

Bu içgörüler, teknik olmayan bir izleyiciye bile tek bakışta aktarılabilecek şekilde görselleştirilmiştir.

👤 Hedef Kitle

Bu çalışma özellikle şu profillere yöneliktir:

CEO

Yönetim Kurulu Üyeleri

Yatırımcılar

Sürdürülebilirlik & Strateji ekipleri

Amaç, karar destekleyici görseller üretmektir.

✅ Proje Kapsamı ve Tamamlanma Durumu

Bu proje kapsamında:

 Dashboard yapısı incelendi

 Gerekli veri seti doğru klasöre indirildi

 Dashboard başarıyla çalıştırıldı

 Grafiklerin veri setinden beslendiği doğrulandı

 İş bağlamına uygun yorumlama yapıldı

📌 Bu proje, dashboard geliştirme sürecini anlamaya ve sonuç odaklı analiz sunmaya yöneliktir.
