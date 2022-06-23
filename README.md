# card_game_football


Bu projenin amacı; nesnye yönelik programlama yapısını ortaya koyabilmek ve çözüm üretebilmek amacı ile 16 karttan oluşan basit bir kart oyunu tasarlamaktır. 
Oyuncunun bilgisayara karşı oynayacağı oyun, 2 farklı kategoride (futbol-basketbol) yürütülecektir. Her oyuncunun 8 kartı (4-futbolcu,4-basketbolcu) vardır, her 
kategorinin kendine ait 3 farklı karşılaşma alanı vardır(futbol için serbest atis,penalaltı vb) tur sırası gelen kategoride rasgele seçilen karşılaşma alanına göre 
seçilen oyuncuların özellik puanları karşılaştırılacak, buna göre skor tablosu değişecek elde kart bitince oyun sonlanacaktır.


JAVA dili, netbeans IDE ‘si ve Java Swing arayüz kütüphanesi yardımı ile yazılmış programımızda her sporcuya ait bir resim, resimin üzerinde özellik puanları yazmaktadır,
oyunun akışı ve skor tablosu bu arayüz aracılığı ile takip edilebilmekte ve oyuncunun kart tercihleri yine arayüz ile sağlanmaktadır. Bilgisayarın rasgele seçtiği kart 
ve karsılasma alanı ile oyuncunun seçtiği kart karşılaştırılmaktadır. Kullanılan kartlar tekrar kullanılamamakta fakat eşit karşılaşma puanına sahip olunması durumunda 
seçilen kartlar tekrar kullanılabilmesi için iade edilmektedir. Biglisayarın kartlarını oyuncu göremez. Fakat beraberlik durumunda kalıp bilgisayara geri verilmiş bir 
kart artık görülebilir olmaktadır.

### YÖNTEM

Sporcu ana sınıfından futbolcu ve basketbolcu sınırları kalıtım almıstır. Oyuncu anasınıfından kullanıcı ve bilgisayar sınıfları kalıtım almıştır.Ortak özellikler ana sınflarda tanımlanmış böylece kod sade tutulmuştur. Text sınıfı ise sporcuların özellik ve isimlerinin belirlendiği, oyun akışının gerçekleştiği main metodunu içinde barındıran sınıftır. Oyun akısı text clası içinde kontrol edilmekte ve yönetilmektedir. Oyuncu skorları private tanımlanmış olup get ve set metotları ile erişilebilir olmuştur. (encapsulation)

<img width="901" alt="Screenshot_2" src="https://user-images.githubusercontent.com/43906043/175384139-28f13603-3a1c-4b65-8694-71fff914e117.png">


<img width="899" alt="Screenshot_3" src="https://user-images.githubusercontent.com/43906043/175384146-2ded51ff-38df-4826-953b-b8fe40e5deca.png">


<img width="780" alt="Screenshot_4" src="https://user-images.githubusercontent.com/43906043/175384157-1d613e8c-4741-4047-818a-ff873fd43b76.png">


<img width="1236" alt="Screenshot_5" src="https://user-images.githubusercontent.com/43906043/175384163-cd96a2a6-633d-4c80-be46-e713a766be9d.png">


<img width="1208" alt="Screenshot_6" src="https://user-images.githubusercontent.com/43906043/175384175-7fe50222-ab09-4b1d-9d3f-9303822ca087.png">

### SONUÇ:
Program başarıyla sonlandırılmıştır. Ekran her açıldığında desteden farklı kartlar karılarak dağıtılmış olur. Bilgisayar, rastgele karılan kartlardan yine rastgele olacak şekilde seçim yapar. Kullanıcı ise önce futbolcu ardından basketbolcu seçimi yapmak “zorundadır”. Belirtildiği gibi, art arda işlem yapılamaz. Kullanıcının ve bilgisayarın rastgele “karşılaşma ” seçeneği sonucu kart puanları eşit olursa geri gönderilir. Daha sonra yeniden oynanabilir. Bütün kartlar bittikten sonra kazanana ya da beraberliğe göre ekrana yeni bir pencerede çıktı verilir. 
