# PySpark Housing Data Analysis

Bu repo, Veri Yoğun Uygulamalar dersinde verilen ödevin reposudur. Veri analizi ve regresyon modellemesi için California konut fiyatları veri seti kullanılmıştır.

## Veri Seti

[Veri Seti Linki](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

Veri seti, 1990 California nüfus sayımı verilerine dayanan belirli bir California bölgesindeki evlerle ilgili bilgileri içerir. Veri seti, temizlenmemiş olduğundan bazı ön işleme adımları gerektirebilir. Sütunlar ve açıklamaları şunlardır:

- longitude: Evlerin boylam koordinatı
- latitude: Evlerin enlem koordinatı
- housing_median_age: Konutun ortanca yaşı
- total_rooms: Toplam oda sayısı
- total_bedrooms: Toplam yatak odası sayısı
- population: Bölgedeki nüfus
- households: Ev sahibi ailelerin sayısı
- median_income: Ortanca hane geliri
- median_house_value: Ortanca ev değeri
- ocean_proximity: Okyanus yakınlığı

## Kullanılan Teknolojiler ve İşlemler

Bu repo, Apache Spark ile büyük veri analizi ve işleme için Python kullanarak yapılmıştır. Aşağıdaki işlemler bu repo içerisinde gerçekleştirilmiştir:

- Gerekli kütüphanelerin ve JDK'nın kurulması
- Java ve Spark ortam değişkenlerinin ayarlanması
- Spark oturumunun başlatılması
- Google Drive'ın bağlanması
- Veri okuma ve Spark DataFrame oluşturma
- Null değerlerin bulunması, silinmesi veya ortalama değerlerle doldurulması
- Kategorik değişkenlerin incelenmesi ve dönüştürülmesi
- Lineer regresyon modelinin kurulması
- Veri kümesinin eğitim ve test kümelerine bölünmesi
- R2 skorunun hesaplanması
- Özelliklerin ölçeklendirilmesi ve lineer regresyon modelinin yeniden oluşturulması

Bu adımlar, veri setinin temizlenmesi, işlenmesi ve bir regresyon modelinin eğitilmesi için izlenmiştir.

## Notlar

Bu repo, temel bir veri analizi ve makine öğrenimi örneği sunmaktadır. Kod parçaları, veri setinin özelliklerini incelemek ve bir regresyon modeli oluşturmak için kullanılabilir. Ancak, gerçek dünya uygulamalarında daha fazla ön işleme ve model ayarı gerekebilir.

