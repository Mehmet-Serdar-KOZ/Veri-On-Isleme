VERİ ÖN İŞLEME NEDİR?
Veri ön işleme, ham verilerin makine öğrenmesi modelleri veya veri analizi süreçleri için daha uygun ve anlamlı hale getirilmesi amacıyla uygulanan bir dizi teknik ve adımdan oluşan kritik bir süreçtir.Gerçek dünya verileri genellikle eksik, gürültülü (hatalı), tutarsız ve düzensiz bir yapıya sahiptir. Bu durum, veri analizi ve modelleme süreçlerinin performansını doğrudan olumsuz etkiler. Veri ön işleme, bu sorunları ortadan kaldırarak daha güvenilir ve doğru sonuçlar elde etmeyi hedefler.

Veri Ön İşlemenin Temel Adımları:
1- Veri Temizleme:Veri setindeki hataları, eksiklikleri ve tutarsızlıkları giderme aşamasıdır.
2- Veri Bütünleştirme:Farklı kaynaklardan gelen verilerin birleştirilmesi işlemidir.
3- Veri Dönüştürme:Verilerin analiz ve modelleme için daha uygun bir formata getirilmesi adımıdır.
4- Veri İndirgeme:Analiz sonucunu etkilemeden veri setinin boyutunu küçültme işlemidir.



1- Veri Temizlemede Hangi Yöntemler Kullanılır?
Eksik Veri
Satır/Sütun Silme:Eksik verinin olduğu satırı veya sütunu tamamen veri setinden çıkarmak.
Değer Atama (Ortalama/Medyan): Eksik hücreyi, bulunduğu sütunun ortalaması veya medyanı ile doldurmak.

Aykırı/Gürültülü Veri
İstatistiksel Tespit (Z-Skoru, IQR): Değerin genel dağılımın ne kadar dışında kaldığını matematiksel olarak hesaplayıp bulmak.

Baskılama (Capping):Aşırı uçtaki aykırı değeri silmek yerine, belirlenen bir eşik (sınır) değeriyle değiştirmek.



2- Veri Bütünleştirme
Şema Eşleştirme:Farklı kaynaklardaki musteri_no ve cust_id gibi aynı anlama gelen sütunları eşlemek.
Veri Tekilleştirme:Birleştirme sonrası aynı olan kayıtların (örneğin aynı müşteri) tespit edilip teke indirilmesi.


3- Veri Dönüştürme
Normalizasyon / Standardizasyon:Yaş ve gelir gibi farklı aralıklardaki sayısal verileri aynı ölçeğe (örn: 0-1 arası) getirmek.
Ayrıklaştırma (Discretization):Sürekli bir sayısal veriyi (örn: yaş) daha anlaşılır kategorilere ("Genç", "Orta Yaşlı") ayırmak.
Logaritmik Dönüşüm:Veri dağılımını normal dağılıma yaklaştırmak için logaritmasını almak.


4- Veri İndirgeme
Boyut İndirgeme (PCA):Birbiriyle ilişkili birçok sütunu birleştirip, bilgiyi en az kayıpla taşıyan daha az sayıda yeni sütun oluşturmak.
Örnekleme (Sampling):Milyonlarca satırlık veri setinin tamamı yerine, onu iyi temsil eden daha küçük bir alt kümesini seçmek.









