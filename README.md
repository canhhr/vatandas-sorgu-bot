# vatandas-sorgu-bot

🌟 🌟 🌟 🌟 🌟 🌟 🌟 🌟 🌟 🌟 🌟🌟 🌟 

➡️ ➡️  VATANDAŞ SORGU DISCORD BOT

KODU DISCORD SUNUCUMUZDA BULABİLİRSİNİZ:

https://discord.gg/deyS7ZNzWE

👉 Kullanım;

👉 Vatandaş Sorgu Discord Bot ile istediğiniz vatandaşın, isim-soyisim bilgisiyle, tckn bilgisiyle, gsm bilgisiyle kişisel bilgilerine ulaşabilirsiniz. Kod, discord bot üzerinden çalışmaktadır, kodu çalıştırmak için öncelikle sunucunuza, bu kod için bir bot eklemeniz gerekmektedir. Eğer bir discord botunuz yoksa, https://discord.com/developers/applications sayfasından botunuzu oluşturup, botunuza gerekli yetkiyi verip(administrator), auth linki oluşturup botu sunucunuza çağırıp, ardından developer sayfasındaki sol taraftaki Bot seçeneğinden botunuzun tokenını kopyalayıp, kodun 397. satırına token bilgisini girip, kodu kaydedip aktif hale getirebilirsiniz. Kodun işleyişi şu şekildedir; sahip olduğunuz sql database'e (eğer database'iniz yoksa onu da talep edebilirsiniz, fiyatı aşağıda belirtilmiştir) localhost bağlantısından bağlanıp, kod ile database arasında bağlantı kurup, discord sunucunuzda sorgu yapma yetkisine sahip kişiler !isimsoyisim, !tcsorgu, !teltcsorgu ve !tctelsorgu komutları ile istediğiniz vatandaşın bilgilerini görüntüleyebilirsiniz. Kodun kurulumu, uygulamayı satın aldığınızda detaylıca anlatılacaktır. Sunucunuzdaki üyeye sorgu yapma yetkisi vermek için ise şu adımları izlemeniz gerekmektedir; istediğiniz isimde bir TXT dosyası oluşturup, kodun 92. satırındaki alana oluşturduğunuz TXT dosyasının konumunu girip(Örnek: C:/...../sorguyetki.txt) kodu kaydedebilirsiniz. TXT dosyasını ise şöyle düzenlemeniz gerekmektedir, (ID):(HAKSAYISI). Örnek: 1111111111:5. Bu örnekte 1111111111 ID'li kişinin 5 sorgu hakkı olucaktır ve kişi her sorgu yaptığında, kod TXT dosyasını güncelleyip, sorgu hakkını azaltmaktadır. Eğer birisine sonsuz sorgu hakkı vermek istiyorsanız sorgu hakkı yerine - girmeniz gerekmektedir.
Örnek: 1111111111:-. Bu şekilde de, 1111111111 ID'li kişiye sonsuz sorgu hakkı vermiş olursunuz. ID, : ve hak sayısı arasında boşluk olmaması gerekmektedir! Bir başka üyeye de sorgu hakkı verebilmek için alt satıra geçip, yine aynı işlemi uygulayabilirsiniz. Bot, kodu her çalıştırdığınızda aktif olucaktır. Eğer botun 7/24 aktif olmasını istiyorsanız bir VDS satın alabilir/kiralayabilir veya SQL Database'inizi kaydedebilecek bir discord bot için free hosting sitesi araştırabilirsiniz.
!isimsorgu komudu çalışma şekli; !isimsorgu (isim) (soyisim) ile o isimdeki vatandaşın/vatandaşların bilgilerini discord bot ile sunucunuzda görüntüleyebilirsiniz. Eğer sorgulama işlemini il'e göre filtrelemek isterseniz komudu şu şekilde yazabilirsiniz, !isimsorgu (isim) (soyisim) il=(büyük harflerle il adı). Bu komudu çalıştırdığınızda, hedef kişinin tckn bilgisini, aile bilgilerini, doğum tarihini, ve nüfus bilgilerini görüntüleyebilirsiniz.
!tcsorgu komudu çalışma şekli; !tcsorgu (tckn) ile o TCKN'ye ait vatandaşın bilgilerini discord bot ile sunucunuzda görüntüleyebilirsiniz. Bu komudu çalıştırdığınızda hedef kişinin isim-soyisim bilgilerini, aile bilgilerini, doğum tarihini, ve nüfus bilgilerini görüntüleyebilirsiniz.
!dur komudu çalışma şekli; !dur komudu ile, çalışmakta olan !isimsorgu komudunun çalışmasını durdurabilirsiniz. !isimsorgu komudu ile sorgulattığınız isimden fazla sayıda varsa ve bot durmadan bilgileri yazdırıyorsa, botun durması için !dur komudunu yazabilirsiniz.
!teltcsorgu komudu çalışma şekli; !teltcsorgu (GSM) ile o telefon numarası hattının kayıtlı olduğu vatandaşın TCKN bilgisini discord bot ile sunucunuzda görüntüleyebilirsiniz. GSM kısmına gireceğiniz numaranın başında 0 olmamalıdır.
!tctelsorgu komudu çalışma şekli; !tctelsorgu (TCKN) ile o TCKN'ye ait vatandaşın GSM bilgisini discord bot ile sunucunuzda görüntüleyebilirsiniz.
!komutlar komudu çalışma şekli; !komutlar komudu ile bota ait kodları görüntüleyebilirsiniz.
Kodlama dili: Python. 7/24 destek hizmetimiz vardır, para iadesi yapılmamaktadır. Kod eğitim amaçlıdır. Kod, localhost ile SQL Database'inize bağlanıp, o bilgilere ait dataları çekip, discord bot ile sunucunuzda görüntülemenize yaramaktadır. Bu kod ile elde ettiğiniz bilgilerin/elde ettiğiniz bilgilerle yapacağınız işlemlerin sorumluluğu size aittir. Örnek görüntü:

![image](https://github.com/canhhr/vatandas-sorgu-bot/assets/82213336/deeeaf19-7b43-4744-ab65-dc33defd54bf)

![image](https://github.com/canhhr/vatandas-sorgu-bot/assets/82213336/47d671f7-c749-4b07-9835-1f04fcb6c940)

![image](https://github.com/canhhr/vatandas-sorgu-bot/assets/82213336/e169c067-1f73-47e5-8a7f-23b4d50750b5)

![image](https://github.com/canhhr/vatandas-sorgu-bot/assets/82213336/8a7c13a4-7f84-44ff-b5b5-a495d5cb0f25)

![image](https://github.com/canhhr/vatandas-sorgu-bot/assets/82213336/5c8e3e37-14b4-4fd4-b153-db3311e7f977)


