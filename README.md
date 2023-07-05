## "Water Quality" adlı veri seti projesi hakkında
Bu proje, suyun içilebilir veya içilemez durumunu sınıflandırma amacıyla
gerçekleştirilmiştir. Veri seti, suyun içilebilirliği ve diğer bilgilerini içermektedir. Bu veri seti,
suyun değerlerine göre sonuçları analiz etmek ve içilebilirlik durumlarını sınıflandırmak için
kullanılacaktır. Bu proje önemlidir çünkü sağlıklı su içmek hayatımız için önemlidir ve sağlıklı
su içmek için suyun kalitesinin sürekli olarak izlenmesi gerekir.
Veri setinde yer alan eksik değerler ortalama değerler kullanılarak dolduruldu. Bu
eksik değerlerin doldurulması, modelin daha doğru sonuçlar vermesine yardımcı olacaktır.
Aykırı değerler, veri setinde yer alan değerlerin normal dağılımın dışına çıkan değerlerdir.
Aykırı değerler, veri setinde yer alan diğer değerlerin etkisini arttırabilir veya modelin
performansını düşürebilir. Baskılama yöntemi kullanılarak, aykırı değerler tespit edildi. Bu
işlem, veri setinde yer alan değerlerin birbirine yakın ölçekte olmasını sağladı.
Veri seti kullanılarak eğitilen model, KNN, Logistic Regression, Naive Bayes,
Decision Tree, Random Forest, Support Vector ve yapay sinir ağları kullanılarak eğitildi. Bu
algoritmalar kullanılarak, hangisi daha iyi sonuçlar verdiği ve hangisiyle daha iyi eğitildiği
analiz edildi. Bu işlem, modelin daha iyi performans göstermesi için en uygun algoritmanın
seçilmesine yardımcı olacaktır.
Modelin performansı, doğruluk oranı ile ölçülmüştür. Elde edilen doğruluk oranı %60
olarak bulunmuştur. Bu, veri setinde yer alan örneklerin
%60'sının doğru bir şekilde sınıflandırıldığı anlamına gelmektedir. Bu oran, modelin suyun
içilebilirliği konusunda orta seviyede bir performans gösterdiğini göstermektedir. Ancak,
genellikle daha yüksek bir doğruluk oranı beklenir, özellikle de sınıflandırma problemleri için.
Modelin performansı, beklenen seviyede olmuştur ancak daha yüksek bir performans
elde etmek modelin daha yüksek bir kapasiteye sahip olması veya farklı algoritmaların
deneyimlenmesi önerilmektedir. Ayrıca, modelin overfitting veya underfitting gibi sorunlar
yaratmasına dikkat edilmelidir. Aynı zamanda, veri seti daha fazla veriyle güncellenmeli ve
daha iyi kaliteli veri kullanılmalıdır. Bu veri setinin kullanımı, sağlıklı su içmek için önemli bir
adımdır ve su kalitesinin sürekli olarak izlenmesi gerekir.
Kaynakça:https://www.kaggle.com/datasets/adityakadiwal/water-potability
