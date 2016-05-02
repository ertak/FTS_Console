--Web Service nedir? 

*Request al�r kendi i�inde de�erlendirir ve geriye cevap d�ner genel yap�s� ve i�leyi�i budur.
*HTTP �zerinden xml veya json ile data al��veri�i sa�lar.
*Go'da web servis kullan�m� i�in net/http paketi kullan�l�r.
*Ba��ms�z platformlarda �al��abilir.
*Son zamanlarda daha �ok kullan�lan yap�lar REST mimarisi ve SOAP protokol�d�r.

--REST?(Representational State Transfer)

*HTTP tabanl�d�r.
*B�t�n REST requestleri birer HTTP requesttir asl�nda ve serverlar bu istekleri farkl� metodlarla handle etmektedir.
*HTTP g�nderilir cevap olarak XML,Json hatta text al�n�r.
*Kullan�m�d daha rahat flexible'd�r.

--SOAP?(Simple Object Access Protocol)

*�apraz network bilgi al��veri�i i�in kullan�l�r.
*XML g�nderilir response olarak XML al�n�r.
*Yap�s� karma��kt�r bu eksi bir �zelliktir.
*Go dilinde program yazarken REST kullan�lmal�d�r bunda temel sebep basit ve kullan��l� olmas� Go kendi
yap�s� itibariyle simple bir yap�ya sahiptir bu y�zden SOAP protokol�n� kullanmak do�ru bir karar de�ildir.
*Microsoft taraf�ndan geli�tirilmi�tir.
*Daha kurall� bir yap�ya sahiptir.

--Socket: Serverlar HTTP nin d���k performans�n�n �stesinden gelebilmek i�in soketleri kullanmaktad�rlar. 

--Gorilla: Bir web toolkitidir ve net/http paketinden extend edilmi�tir ve performans a��s�ndan iyidir.Gorilla gibi daha
bir�ok yap� bulunmaktad�r bunlardan biri tercih edilebilinir hepsinin �e�itli �zellikleri ve eklemeleri bulunmaktad�r.
