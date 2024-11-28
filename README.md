Öğrenci ve Ders Yönetim Sistemi
Bu proje, Nesne Yönelimli Programlama (OOP) prensipleri kullanılarak geliştirilmiş bir Öğrenci ve Ders Yönetim Sistemidir. Proje, öğrencilerin derslere kayıt olmasını, derslerin öğretim görevlileri tarafından yönetilmesini ve bu bilgilerin bir konsol uygulaması aracılığıyla görüntülenmesini sağlar.

Projenin Amacı
Bu sistem, öğrenciler ve öğretim görevlilerinin derslerle ilişkisini düzenlemek için tasarlanmıştır. Kullanıcı, yeni dersler oluşturabilir, öğretim görevlilerini ve öğrencileri tanımlayabilir. Ayrıca, derslerin detayları (adı, kredisi, öğretim görevlisi) ve kayıtlı öğrenciler listelenebilir.

Projenin Temel Yapısı
1. Sınıflar
Projede, öğrenci, öğretim görevlisi ve ders gibi temel kavramları temsil eden sınıflar oluşturulmuştur. Bu sınıflar, OOP prensiplerini kullanarak organize edilmiştir:

BaseEntity: Öğrenci ve öğretim görevlisi için ortak özellikler içeren temel sınıf.
Ogrenci: Sisteme kayıtlı öğrencilerin bilgilerini tutan sınıf.
OgretimGorevlisi: Derslerin sorumlusu olan öğretim görevlilerini temsil eden sınıf.
Ders: Derslerin detaylarını ve derslere kayıtlı öğrencileri tutan sınıf.
2. Polimorfizm (Çok Biçimlilik)
BaseEntity sınıfında bulunan BilgiGoster metodu, Ogrenci ve OgretimGorevlisi sınıflarında farklı özelliklere göre özelleştirilmiştir.

3. Interface Kullanımı
Bir arayüz (interface) kullanılarak, öğretim görevlileri ve öğrencilerin sisteme giriş yapmasını sağlayacak bir yapı oluşturulmuştur.
