# Python Request 

Bazı Anahtar Kelimelerin Türkçe Karşılığı

Request = Talep

Response = Yanıt

Client = Kullanıcı-İstemci 

Server = Sunucu 


## TALEP <-> REQUEST

Talep 3'e ayrılır;
1 - Metot --- HTTP metotları : GET,POST,PUT,DELETE
2 - Adres --- https:// ...
3 - Girdi(ler)---PASSWORDS AND PARAMS

GET
Hali hazır sunucuda belli bilgi varsa almaya yönelik 
POST 
Kullanıcı olarak sunucuya veri Gönderme
PUT 
Veri Gönderme ama kullanım yolları değişik 
DELETE
Belli bir record veya kayıt varsa onu silmeye yönelik bir komut
etc . = https://www.w3schools.com/tags/ref_httpmethods.asp

ADRES: link internet adresi

GİRDİ : şifreler entegre edilmelidir bunlar aslında spesifik bir alana ulaşmak için talep için de bir şekilde tanıtabiliriz
Parametreler : Bir machine learning için veri seti için özel kırılımlara spesifik alt kırılımlara ulaşma sağlanır..

## YANIT <-> RESPONSE

STATUS KODU:
Aslında bir yanıt kodu çok karşılaşırız mesela 404 ,502 
Bunlardan hangisi geliyorsa onun bir karşılığı var kodların 

Status Başlayan ve devam eden kodların Anlamı
1.....(Bilgi veren) İşlemi aldı ama hala işlem devam ediyor demek bir nevi 
2.....(Başarılı)
3.....(Aksiyon Gerekli)[ikincil şifreleme]
4.....(Kullanıcı Hatası)404
5......(Sunucu Hatası)502 vb.
https://en.wikipedia.org/wiki/List_of_HTTP_status_codes

İÇERİK :
Cevap (Text)
Bilgi 
Genel anlamda internet sayfası olabilir , çeşitli dosyalar, çeşitli programlara erişme olabilir.

 https://postman.com : içeriklerin arayüz olarak arka planda neler yaptığını gösteriyor aslında 

LİNK İÇİNDE SORU İŞARETİ VEYA EŞİTTİR VARSA  BU PARAMETRE ALABİLEN BİR 
https://data.police.uk/api/crimes-no-location?category=all-crime&force=leicestershire&date=2017-03 LİNKTİR


Neyin argüman olarak gönderildiğini görebiliriz diyelim ki bir arama yaptık soru işaretinden sonra belli parametrelerin otomatik olarak oluşturulduğu için nerde yapılacağını bilmek çok önemlidir.





