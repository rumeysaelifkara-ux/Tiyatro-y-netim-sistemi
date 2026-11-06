# Tiyatro Etkinlik Yönetim Sistemi

## Proje Amacı

Tiyatro oyunlarının, oyuncuların, gösterimlerin ve bilet işlemlerinin düzenli bir şekilde yönetilmesini sağlayan ilişkisel bir veri tabanı sistemidir. Proje, tiyatro etkinliklerine ait bilgilerin saklanmasını, tablolar arasında bağlantı kurulmasını ve bilet-ödeme süreçlerinin takip edilmesini amaçlamaktadır.

## Veri Tabanı Tabloları

Proje 8 tablodan oluşmaktadır:

1. **oyunlar:** Tiyatro oyunlarının adı, türü, süresi ve yaş sınırı bilgilerini tutar.
2. **oyuncular:** Tiyatro oyuncularına ait temel bilgileri saklar.
3. **oyunoyuncular:** Oyuncuların hangi tiyatro oyunlarında görev aldığını gösterir.
4. **salonlar:** Gösterimlerin yapıldığı salonların adını ve kapasitesini tutar.
5. **gosterimler:** Oyunların sahneleneceği tarih, saat ve salon bilgilerini saklar.
6. **seyirciler:** Bilet işlemi gerçekleştiren seyircilere ait bilgileri tutar.
7. **biletler:** Seyircilere ait biletlerin gösterim ve fiyat bilgilerini tutar.
8. **odemeler:** Bilet işlemlerine ilişkin ödeme tutarı, türü ve tarih bilgilerini saklar.

## ER Diyagramı

<p align="center">
  <img 
    src="https://github.com/user-attachments/assets/3aee9d7b-749e-4569-84da-c92bccf29adb"
    alt="Tiyatro Etkinlik Yönetim Sistemi ER Diyagramı"
    width="800"
  />
</p>

