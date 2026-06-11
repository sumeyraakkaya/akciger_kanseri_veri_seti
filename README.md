#MAKİNE ÖĞRENMESİ TABANLI AKACİĞER KANSERİ VERİ TAHMİNİ SİSTEMİ 
Akciğer Kanseri Risk Tahminleme ProjesiBu proje, makine öğrenmesi yöntemlerini kullanarak yaşam tarzı ve klinik istatistiklere dayanarak akciğer kanseri risklerini artırmaktadır. Proje kapsamında veri analizi, görselleştirme ve lojistik regresyon kapsamı sağlanır. 

#Proje Özeti
Bu çalışma, veri biliminin sağlık alanında uygulamalarına bir örnektir. Veri setindeki çeşitli etkiler (yaş, sigara kullanımı, anksiyete vb.) analiz edilerek bir tahmin modeli dağılımı sağlanır. Proje, özellikle sosyal sorumluluk projelerinde (örneğin Teknofest gibi) temel bir analiz aracı olarak kullanılabilir niteliktedir. 

#Kullanılan Teknolojiler ve KütüphanelerProgramlama Dili
Python Veri Analizi: Pandas, NumPy Görselleştirme: Matplotlib, Seaborn Makine Öğrenmesi: Scikit-Learn (Logistic Regression, LabelEncoder, StandardScaler) 

#Veri Seti İçeriğiVeri seti, aşağıdakileri içerir
Demografik Bilgiler: Cinsiyet ve Yaş. Yaşam Tarzı ve Değişiklikler: Sigara içme durumu, alkol kullanımı, nefes darlığı, yorgunluk, hırıltılı solunum vb. Hedef Değişken: Akciğer Kanseri (EVET/HAYIR) 

#Proje AdımlarıVeri Ön İşleme
Eksik kişisel verilerin kontrolü ve kategorik kayıtların LabelEncoder ile dijitalleştirilmesi. Eğitim ve Test Ayırımı: Verinin %80 eğitim, %20 test ise mevcut olacaktır. Özel Ölçeklendirme: Modelin arttırılması için StandardScaler kullanımı. Model Eğitimi: Lojistik Regresyon çalıştırıcısı ile ortaya çıkıyor. Değerlendirme: Karmaşıklık Matrisi (Confusion Matrix) ve Doğruluk Skoru ile analiz. 
