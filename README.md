Bu projede oncelikli kuyruk (priority queue)
veri yapısı kullanarak hava uc¸us¸ kontrol sistemi
yapmamız amac¸lanmıstır.
Kuyruk veri yapisi adındanda anlas¸ılacagı˘ uzere ¨
ard arda elemanların eklenerek ve ilk eklenen
elemanların kuyruktan ilk ayrılması ile sonuclanan
(FIFO - Firs in First Out prensibi) bir veri yapısı
algoritmasıdır. Bu yapı dizi veya baglı liste yapısı
kullanılarak olus¸turulabilir. Biz bu projede projenin
kapsamı dolayısıyla baglı liste kullanarak projeyi ˘
gerc¸ekles¸tirdik.
Queue leri anlamak icin kısaca s¸u adımları
sayabiliriz::
• Kuyrugun ilk kısmına (bas¸ına) ”FRONT” son
kısmına ”REAR” denir
• Kuyruk yapısında iki uctanda is¸lemler yapılabilir
• Enqueue ile kuyruga eleman eklenir (kuyruk
sonuna ya da oncelige gore) ¨
• Dequeue ile kuyruktan eleman cikarilir. Front
kısımdaki eleman ilk olarak is¸lem yapacagı icin ilk
olarak o cıkarılır.
Kuyruk yapısında belli bas¸lı fonksiyonlar vardır ,
bunlardan bazıları :
•peek() : Sıradaki elemani getirir
•add() : Kuyruga eleman ekler
•remove() : Belirli elemani siler
•poll () : Son elemani getirir ve siler
•clear() : Tum elemanlari siler
