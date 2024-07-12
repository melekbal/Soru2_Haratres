## Haratres Soru 2

Bu Java programı, dinamik bir e-ticaret platformu için tasarlanmıştır. Kullanıcı, program aracılığıyla ürünlerin eklenmesi, sıralanması ve sepete eklenmesi işlemlerini gerçekleştirebilir.

Ürün Ekleme: Kullanıcıya kaç adet ürün gireceği sorulur ve her bir ürün için ad, fiyat, stok miktarı ve değerlendirme puanı (5 üzerinden) bilgileri alınır. Fiyat bilgisi 1 ile 100 arasında olmalı, stok miktarı en az 1 olmalı ve ürün adı en fazla 20 karakter uzunluğunda olmalıdır. Eğer bu kurallara uyulmazsa, kullanıcıya uygun giriş yapması için uyarı verilir.

Ürünleri Sıralama: Kullanıcıya hangi kritere göre (ad, fiyat, stok miktarı veya değerlendirme puanı) sıralama yapmak istediği sorulur. Ardından sıralama türü (artan veya azalan) belirlenir ve bu kriterlere göre ürünler sıralanır.

Sepete Ürün Ekleme: Sıralama yapıldıktan sonra kullanıcıya sepete ürün ekleyip eklemek istemediği sorulur. Eğer eklemek istiyorsa, en az iki ürün olacak şekilde ürün adı ve eklemek istediği adet bilgisi alınır. Girilen ürün adı kontrol edilir ve stok miktarı yeterli ise ürün sepete eklenir. Yeterli stok miktarı yoksa kullanıcıya uygun adet girmesi için uyarı verilir.

Sepet Tutarı Hesaplama: Kullanıcı ürün eklediğinde, sepetin toplam tutarı şu şekilde hesaplanır: Sepete eklenme sırasına göre ilk ürün fiyatı ikinci üründen fazlaysa, ilk üründen ikinci ürünün birim maliyeti kadar indirim yapılır. Bu indirim mantığı tüm sepet ürünleri için uygulanır.

Bu program Java dilinde geliştirilmiş olup, geliştirme sürecinde Visual Studio Code kullanılmıştır. Projenin tamamı açık kaynak olarak mevcuttur.

## Getting Started

Welcome to the VS Code Java world. Here is a guideline to help you get started to write Java code in Visual Studio Code.

## Folder Structure

The workspace contains two folders by default, where:

- `src`: the folder to maintain sources
- `lib`: the folder to maintain dependencies

Meanwhile, the compiled output files will be generated in the `bin` folder by default.

> If you want to customize the folder structure, open `.vscode/settings.json` and update the related settings there.

## Dependency Management

The `JAVA PROJECTS` view allows you to manage your dependencies. More details can be found [here](https://github.com/microsoft/vscode-java-dependency#manage-dependencies).
