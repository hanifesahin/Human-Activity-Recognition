# Human Activity Recognition
Çalışmada kullanılan veri UCI veri deposundan alınmıştır (https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones). Verinin elde edilebilmesi için deneylerde 19-48 yaş aralığındaki 30 gönüllü kişinin beline bir akıllı telefon takarak(Samsung Galaxy S II) 6 aktivite(Yürüme, merdiven çıkma, merdiven inme, oturma, ayakta durma, uzanma) gerçekleştirmeleri sağlanmıştır. Akıllı telefonda bulunan ivmeölçer ve jiroskop algılayıcıları ile 3 eksenli doğrusal ivme ve 3 eksenli açısal hız sinyalleri elde edilmiştir. Daha sonra bu sinyallere gürültü filtreleri uygulanarak ön işleme yapılmıştır ve ardından 2.56 saniyelik sabit genişlikli pencerelerde ve %50 örtüşme ile örneklenmiştir. Her pencereden zaman(ortalama, standart sapma, varyans, minimum, maksimum, entropi gibi) ve frekans(ortalama ve medyan gibi.) alanından değişkenler hesaplanarak 561 öznitelik elde edilmiştir. Bu öznitelikler [-1,1] aralığında normalleştirilmiştir. Deney sonucunda elde edilen 10299 veri %70 eğitim ve %30 test verisi olmak üzere ikiye ayrılmıştır.
Uygulama veri bilimi platformu olan Anaconda aracılığı ile Orange 3 kullanılarak gerçekleştirilmiştir.
6 insan aktivitesini(yürüme, merdiven çıkma, merdiven inme, oturma, ayakta durma, uzanma) sınıflandırmak için makine öğrenimi algoritmaları olan karar ağaçları, naive bayes, rastgele orman, destek vektör makinesi, lojistik regresyon ve yapay sinir ağları kullanılmıştır.
