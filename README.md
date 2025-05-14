# -Food-Menu-Management-System-

Bu proje, C# dili kullanılarak bir yemek menüsü sistemi oluşturmayı hedefler. Proje, nesneye dayalı programlama (OOP) prensipleri temel alınarak tasarlanmıştır ve Windows Forms aracılığıyla grafik kullanıcı arayüzü sunar. İşlevsellik şu şekilde açıklanabilir:
Projenin Amacı:
Kullanıcıya yemek türlerini seçme, detaylarını girme ve listeleme işlemleri için bir platform sunmak. Ayrıca, girilen yemeklerin fiyatları ve kalori değerlerini kontrol etme ve bu değerler belirli aralıkta olduğu sürece kabul edilen bir menü oluşturma.
Proje Özellikleri:
- Yemek Sınıfı (Yiyecek):- Temel bir sınıf olarak tasarlanmıştır.
- adi, cins, fiyat, ve kdvOrani adlı dört alan içerir.
- Varsayılan ve parametreli olmak üzere iki kurucu metot ile oluşturulabilir.
- yazdir metodu, sınıfın özelliklerini string formatında döndürür ve diğer sınıflarda özelleştirilebilir (virtual olarak tanımlanmıştır).

- Türetilmiş Sınıflar:- Meyve, Salata, Tatlı, ve İçecek sınıfları, yemek sınıfından türetilmiş olup kalori alanını içerir.
- Her sınıfın yazdir metodu, kendi özelliklerine uygun şekilde özelleştirilmiştir.

- Menu Sınıfı:- Yemek öğelerini yönetmek için List<yiyecek> kullanır.
- ekle, sil, ve menuYazdir gibi metotlarla listeye yeni yemek ekleme, yemek silme ve listeyi yazdırma işlemlerini sağlar.

- Grafik Arayüz (Windows Forms):- Kullanıcı, yemek türünü ComboBox ile seçebilir.
- Detayları (adi, cins, fiyat, kdvOrani, ve kalori) TextBox üzerinden girebilir.
- Button ile listeye öğe ekleme ve listeyi yazdırma işlemleri yapılabilir.
- ListBox üzerinden yemek listesi görüntülenir ve toplam tutar (KDV dahil) hesaplanır.
- Ayrıca seçilen öğeler silinebilir.

- Şart Kontrolleri:- Girilen fiyat ve kalori değerleri belirlenen aralıklar dışında ise öğe reddedilir ve kullanıcı bilgilendirilir.
- Kabul edilen öğeler toplam tutar hesabına dahil edilir.


Projenin Çalışma Mantığı:
- Kullanıcı yemek türünü seçer ve gerekli bilgileri girer.
- Program, girilen detayları alır, gerekli kontrolleri yapar ve uygun öğeleri listeye ekler.
- Listeyi yazdırırken tüm yemeklerin fiyatını ve KDV tutarını hesaplar.
- Kullanıcı isterse seçilen öğeleri listeden silebilir.

Bu proje, öğrencilerin nesneye dayalı programlama konseptlerini anlamaları ve Windows Forms ile grafik arayüz oluşturma yeteneklerini geliştirmeleri için tasarlanmıştır
