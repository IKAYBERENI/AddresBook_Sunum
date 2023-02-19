# AddresBook_Sunum

Merhaba, Address Book projesi İstanbul - Beşiktaş Wissen Akademi'de Eğitim aldığım süreçte 302 sınıfı ile yazdık.Bu projede Trendyol,Getir gibi uygulamalardaki adres ekleme bölümünden esinlendik. Amacımız adres kaydı yapmaktır. 

Bu projenin tüm hakları hocamız Betül Akşan'a, bana ve 302 sabah grubu sınıfının öğrencilerine aittir. Burada projenin ekran resimlerini ve kaynak kodlardan bazı kod parçalarını aşağıda görebilirsiniz.

PROJE HAKKINDA TEKNİK BİLGİLER:

Proje Visual Studio .Net 6 ASP.NET MVC CORE ile yazıldı.
Proje Entity Framework Core Code-First yaklaşımıyla yazılmıştır.
Projede AspnetCore Identity kullanarak üyelik sistemini yazdık.
Projeyi 5 katman (EL,DAL,BLL,UI, AddressBookNeighborhoodsLoad) olarak yazdık. -AddressBookNeighborhoodsLoad katmanı Console uygulaması olup Mahalle datasını eklemektedir. (70bin data bulunuyor)
Projede İlleri ve İlçeleri Excel dosyasını back-endde okuyarak veritabanına proje ilk ayağa kalktığında ekledik.
Projede Adres listesi ve Adres Ekle - Adres Sil ekranları bulunuyor.
Adres Ekle sayfasındaki işlemleri AJAX ile yapmaktayız. Örneğin; ili seçtiğinde ilçeler sayfa yenilenmeden gelir. İlçeyi seçtiğinde mahalleler sayfa yenilenmeden gelir.
Mahalleyi seçince o mahallenin posta kodunu APi'den çektik. https://api.ubilisim.com/postakodu/il/34
Proje gelişmeye açık olup zaman buldukça yeni sayfalar ya da yeni özellikler eklenecektir.
Ekran resimleri ve kaynak kodlardan bir parça aşağıda görebilirsiniz .

<img width="953" alt="AdresSayfası" src="https://user-images.githubusercontent.com/112905722/219973118-70aa141d-0fff-40a0-8119-56fe8fc612d4.png">


<img width="960" alt="AdresSayfası2" src="https://user-images.githubusercontent.com/112905722/219973120-4ba141e1-edaa-4227-b2be-7df6e91620fa.png">


<img width="960" alt="AdresSayfası3" src="https://user-images.githubusercontent.com/112905722/219973129-d02886ed-fa57-4dc3-b000-6a73221b414f.png">


<img width="254" alt="KatmanSayısı" src="https://user-images.githubusercontent.com/112905722/219973154-40855ca0-e02a-451a-a51c-b06e51a06c83.png">


<img width="956" alt="HomeController" src="https://user-images.githubusercontent.com/112905722/219973160-d4cd5d8b-b45a-41d7-bc3d-15a261a3f549.png">


<img width="959" alt="HomeController2" src="https://user-images.githubusercontent.com/112905722/219973168-22bbf1bc-cd11-4bf4-8817-9d996cf4e30b.png">


