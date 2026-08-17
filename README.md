# Y-Z-TABANLI-YOKLAMA-UYGULAMASI
# Yüz Tanıma Tabanlı Güvenlik ve Otomasyon Sistemi

Bu proje, Fırat Üniversitesi Bilgisayar Mühendisliği bölümü bitirme tezi kapsamında geliştirilmiştir. Sistem, gerçek zamanlı yüz tanıma ve veritabanı yönetimi kullanarak yetkilendirme ve güvenlik süreçlerini otomatize etmeyi amaçlar.

## Proje Hakkında
Sistem, Python tabanlı bir görüntü işleme mimarisi üzerine kurulmuştur. OpenCV ve DeepFace kütüphaneleri kullanılarak yüz özniteliklerinin çıkarılması ve SQLite veritabanı üzerinden kişi eşleştirme süreçleri yürütülür. Proje, ölçeklenebilir ve çoklu iş parçacığı (multi-threading) destekli bir altyapı ile tasarlanmıştır.

## Kullanılan Teknolojiler
- **Programlama Dili:** Python
- **Görüntü İşleme:** OpenCV, DeepFace
- **Veritabanı:** SQLite
- **Mimari:** Multi-threading (Eş zamanlı işlem yönetimi)

## Sistem Mimarisi
Proje, yüksek performanslı bir görüntü işleme akışına sahiptir:
1. **Veri Toplama:** Kamera akışından anlık görüntülerin yakalanması.
2. **Öznitelik Çıkarımı:** DeepFace algoritmaları ile yüz vektörlerinin oluşturulması.
3. **Doğrulama:** SQLite veritabanındaki kayıtlı profillerle eşleştirme yapılması.
4. **Sonuç:** Başarılı/Başarısız yetkilendirme loglarının tutulması.

## Özellikler
- ✅ Gerçek zamanlı yüz tespiti ve kimlik doğrulama.
- ✅ Hafif ve hızlı SQLite entegrasyonu ile yerel veritabanı yönetimi.
- ✅ Çoklu iş parçacığı sayesinde kamera akışında donma yaşanmadan işlem yapabilme.
- ✅ Modüler kod yapısı sayesinde farklı donanımlara kolay entegrasyon.

---
