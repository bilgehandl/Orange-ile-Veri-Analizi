### Orange (.ows) Kullanarak Fiziksel Özelliklere (Saç uzunluğu, Yüz en ve boyu, burun ve dudak özellikleri vb.) Göre Cinsiyet Analizi

## Giriş:
Bu projenin amacı, insanların çehrelerinin özelliklerine göre cinsiyetlerinin bilinip bilinemeyeceğinin testinin yapılmasıdır. Ayrıca bu testler yapılırken farklı algoritmalar arasından en tutarlı sonuç veren algoritmanın tespiti yapılacaktır.

# Aşamalar:
1.	Veri setinin seçilmesi,
2.	Veri setinin Orange uygulamasına yüklenmesi,
3.	Farklı algoritmalar kullanılarak yapılan test süreci,
4.	Confusion Matrix ile sonuçların karşılaştırılması,
5.	Sonuç.
### 1.	Veri Setinin Seçilmesi
Veri seti seçilirken farklı kaynaklar taranır ve veri seti kaynağı olarak Kaggle belirlenir. Kaggle üzerinde bir gözden geçirme sonucunda “gender classification” veri seti seçilir. Bu veri setinin amacı, insanların yüz hatlarına bakılarak cinsiyetlerinin belirlenip belirlenemeyeceğidir. Eğer sonuç olumlu olur ise bir kamera ile bir insanın cinsiyeti anlık olarak bilinebilecektir.
### 2.	Veri Setinin Orange Uygulamasına Yüklenmesi
Veri seti Orange uygulamasına yüklenmeden önce, “Test and Score” aşamasının olabildiğince kısa sürede olabildiğince tutarlı sonuçları vermesi için, ne kadar verinin yeterli olacağının testi yapılır. Yaklaşık 5000 veriye sahip olan veri setinden, ayıklamalar yapılarak 500 küsür verinin yeterli olacağı anlaşılmıştır. Bu sebeple belirlenen sayı kadar veri Orange uygulamasına yüklenmiştir.
### 3.	Farklı Algoritmalar İle Yapılan Test Süreci
SVM, Tree, ve kNN gibi algoritmalar kullanılarak tahminlerin (predictions), gerçek sonuçlarla (actuals) olan karşılaştırması yapılmıştır. Algoritmaların verdiği sonuçlar aşağıdaki gibidir: 
### 4.	Confusion Matrix ile Sonuçların Karşılaştırılması
3. başlıkta da görüldüğü gibi 3 algoritma arasından en tutarlı sonuç vereni kNN’dir. (Tablo 1). Ardından SVM ve Tree gelmektedir.       
### 5. Sonuç
Bu çalışma sonucunda insanların yüz hatlarının verileriyle cinsiyetlerinin yüksek doğruluk oranlarıyla tespit edilebileceği görülmüştür. Yalnızca 500 veri ile olan bu yüksek doğruluk oranları, daha fazla veri ile daha yüksek doğruluk oranları olmasını sağlayacaktır. Kullanılan veri seti ve .ows uzantılı dosya aşağıda verilmiştir.


