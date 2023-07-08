# InterviewCase2
Kurt Problemi

-Bu projede istenilenleri bana ayrılmış kısmı yapmaya çalıştım.
-Sizlerin bana hazır olarak verdiğiniz kodlarda biraz eklemeler yaptım sebebi her çalıştırdığımda o kod bloğunda hata veriyordu.
-Yazdığım kod parçasında turMap adında bir HashMap oluşturdum.Bu her bir kurtID nin tekrar sayısını tutmak için kullandım.
-Burada yazdığım maxTur en yüksek tekrar sayısını tutuyor,minID ise en çok tekrar eden kurtID nin minimum değerini tutuyor.
-for döngüsünde yapmak istediğim kurtIDsinin listesini dolaşmak arr.get(i) ile listrddeki i indeksine karşılık gelen kurtIDsini aldım ve değişkene atadım.
-turMap.getOrDefault(kurtID ,0)+1 ifadesindede turMap ve kurtID ye karşılık gelen tekrar sayılarını aldım eğer kurtIDS turMap içinde bulunmazsa değer 0 olarak kullanılır ardından 1 artırılır.
-Daha sonrasında her bir giriş için for döngüsünü açtım.
-Döngüdeki kurt türünün IDsini aldım bir alt satırında da kurt türünün tekrar sayısını aldım.
-Devamında ise tur değeri ile maxTur değeri karşılaştırılır eğer maxTur dan büyükse maxTur güncellenir ve minID kurtIDsine atanır.
-Eğer tur değeri maxTur ile eşit ve kurtID değeri minID değerinden küçük ise minID güncellenir.
-Son olarak en çok tekrar eden kurtIDsi olan minId uniqueWolfs metodu tarafından döndürülür
