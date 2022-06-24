# Grafik Çizici / Graph Plotter

## Libraries that are being used / Kullanılan kütüphaneler
* mathjs
* chartjs
# Grafik Çizici / Graph Plotter

##  Kullanılan kütüphaneler / Libraries that are being used
* mathjs
* chartjs

## Nasıl çalışıyor ? / How does it work ?
### [TR]
1. "Denklemi Gir" yazan yere denkleminizi giriyorsunuz,
2. Uygulamanın hangi aralıklarda grafiği çizeceğini belirlemek için başlangıç ve bitiş değerini giriyosunuz
3. Grafiği güncelleye basıyorsunuz
4. Grafiği güncelleye bastığınız anda index.html'de o butona atanan onclick eventi sayesinde app.js'deki grafikCiz() fonksiyonu tetikleniyor.
5. Tetiklenen fonksiyon denklemi, başlangıç ve bitiş değerlerini çekiyor
6. Başlangıç değerinden bitiş değerine kadar birer birer arttıran bir for döngüsü devreye giriyor
7. Döngü her tekrarlandığında tekrarlanan döngüdeki x değeri için denklem çözülüp baştan tanımlanan yValues isimli diziye ekleniyor ve aynı x değeri bu sefer işleme uğramadan xValues isimli diziye ekleniyor.
8. Chart.js ile grafiğin x ve y değerleri güncelleniyor ardından chart.update() ile değişiklikler ekrana yansıtılıyor.
  
### [EN]
  On the way
