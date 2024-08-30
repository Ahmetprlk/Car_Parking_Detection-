Otopark Alanı Tespiti 

Bu proje, bir video akışındaki boş ve dolu otopark alanlarını tespit eden ve sayan bir web uygulamasıdır. Uygulama, bir otopark alanının araç tarafından işgal edilip edilmediğini sınıflandırmak için önceden eğitilmiş bir Evrişimli Sinir Ağı (CNN) modelini kullanır. Flask, OpenCV ve TensorFlow/Keras kullanılarak oluşturulmuştur.

Özellikler
Gerçek Zamanlı Video İşleme: Video akışından gerçek zamanlı olarak araçları tespit eder.
Otopark Alanı Tespiti: Önceden tanımlanmış her bir otopark alanını "araç" veya "araç yok" olarak sınıflandırır.
Canlı Video Akışı: Video akışını, otopark alanı bilgisiyle birlikte görüntüler.
Alan Sayısı için API: Boş ve dolu alanların mevcut sayısını almak için bir API uç noktası sağlar.
Kullanılan Teknolojiler
Flask: Python için bir mikro web çatısı.
OpenCV: Gerçek zamanlı bilgisayarla görme için bir kütüphane.
TensorFlow/Keras: CNN modelini eğitmek ve çalıştırmak için kullanılan bir derin öğrenme çerçevesi.
NumPy: Python'da sayısal hesaplamalar için bir kütüphane.
Pickle: Kaydedilmiş otopark alanı konumlarını yüklemek için kullanılır.
