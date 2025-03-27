# BlogReadme
Kurumsal Websitesi
Backend Geliştirme: .NET 9, Entity Framework Core ve MediatR PostgreSQL veritabanı kullanılarak tenant izolasyonu ve veri yönetimi optimize edildi.
Frontend Geliştirme: Angular ve Ionic kullanılarak duyarlı (responsive), mobil uyumlu bir arayüz geliştirildi ve Progressive Web App (PWA) desteği sağlandı.
![chrome_NJvdQDSOfe](https://github.com/user-attachments/assets/de07bb82-9ee9-4192-b6ba-e0a33382a6e8)

Önbellekleme: Redis entegrasyonu ile tenant'lar arasında veri erişimi hızlandırılarak performans iyileştirmeleri yapıldı.

Arka Plan İşlemleri ve Loglama: Hangfire ile arka plan görevlerinin planlanması ve yönetimi sağlandı. Serilog kullanılarak yapılandırılmış ve merkezi loglama sistemi oluşturuldu.
Temel Özellikler: Birden fazla tenant'ı destekleyen, izole veri yapısına sahip, ölçeklenebilir ve sürdürülebilir bir mimari tasarlandı. Bu yapı, kurumsal danışmanlık hizmetleri için uygun şekilde geliştirildi.
Slider Yönetimi: Slider ekleme, silme ve güncelleme işlemleri.
Blog Yönetimi: Blog yazıları ekleme, silme ve güncelleme.
Kategori Yönetimi: Kategori ağacına yeni kategoriler ekleme, mevcut kategorileri silme ve güncelleme.
İletişim Formu Yönetimi: Kullanıcıların iletişim formu aracılığıyla gönderdiği mesajları görüntüleme ve e-posta ile yanıt verebilme.
Web Site Bilgi Güncelleme: Site genel bilgilerini düzenleme ve güncelleme.
Takım Yönetimi: Ekibimizde yer alan kişileri güncelleme.
Yetkilendirme ve Kullanıcı Yönetimi: Yönetici kullanıcı ekleme ve yetkilendirme işlemleri.
Dil Yönetimi: Çevirileri ekleme, düzenleme, silme ve güncelleme.
![cpJPLJiAzH](https://github.com/user-attachments/assets/49a31ae6-db5a-4978-9228-d96b4347485f)
Çoklu Dil Desteği: Web sitesinin birden fazla dilde kullanılabilmesi için çoklu dil desteği sağlanmaktadır.
Multitenant yapısı Veritabanı bazlı olup Hangfire Dbleri ve Veritabanları Tenant bazlı olarak ayrıldı
![tenant](https://github.com/user-attachments/assets/e553b58d-6000-4b0e-83e6-3a609e037985)

Aktif proje çalışırken Tenant eklenebilmesi sağlandı
Herşey pagination'a uygun şekilde listelendi
Her sayfada yanlızca 1 adet istek gidecek şekilde proje ayarlandı Backendde bunun için optimizasyon sağlandı
![da](https://github.com/user-attachments/assets/18cb15b0-c6ef-4754-8bff-6cb80afd1228)

