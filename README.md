# fallout2-turkce-font-cozumu
Fallout 2 Türkçe font sorunu çözümü

Çeviri yapacaklar için adımlar:

1 : notepad++ indirin ve kurun
2 : "Fallout DAT Explorer II": "https://www.nma-fallout.com/resources/fallout-dat-explorer-ii.140/"
   İndirin ve programı başlatın "open" sekmesinden "master.dat" dosyasını açın ve attığım font dosyalarını buraya atın. bu kadar fontlar değişti. eğer diyalog dosyalarını da almak istiyorsanız aşşağıdaki "text" yerinden diyalog dosyalarını çıkartabilirsiniz.
   Resim8


3:
 ".msg" dosyalarında türkçe karakterler yerine kullanılan ifadeler:
  "@" = "ç" harfine karşılık geliyor
  "<" = "ğ" harfine karşılık geliyor
  ">" = "ş" harfine karşılık geliyor
  "^" = "ö" harfine karşılık geliyor
  "/" = "ü" harfine karşılık geliyor
  bu karakterler sadece küçük harf dikkat edin büyük harf değiller. Yani oyun içinde "Ü"-"ü" olacak
  "İ" leri "I" harfine çevirin çünkü onun fontunu ayarlamadım.
  "ı" ları ise "i" yapın aksi taktirde hiçbir şey okunmaz
  
    Resim12
Bir metin dosyasını çevirdiniz ve bu şekilde görünüyor diyelim
  Resim10
Şimdi yukarıda saydığım karakterleri değiştirmemiz gerekecek "ctrl+h" yapın çıkan ekranda aranan kısıma hangi harfi değiştirmek istiyorsanız onu yazın. daha sonra değiştir yerine o harfe karşılık gelen işareti girin ve tümünü değiştire basın.
 Resim11
Bu şekilde olması gerekecek. aynı işlemleri diğer karakterler için de yapın ve dosyanızı kaydedin. Artık bu dosya için "çeviriniz" bitti oyun içinde düzgün bir biçimde görünecektir.



 

UYARI! Font dosyalarında düzenleme yapmak istiyorsanız kesinlikle sanal makinede çalışın. ".aaf editor" gibi programlar ne kadar güvenilir belli değil çünkü.

Bu kısım font dosyalarını kurcalamak isteyenler için:

Fallout 1 ve 2'de diyaloglar ASCII ile yazıldığı için diyaloglarda türkçe bir karakter olunca oyun içinde malum gözükmüyor veya saçma bir şekilde gözüküyor.
Bu font sorununu düzeltmek için font dosyalarını düzenlemek gerekecek.

1. Adım "Fallout DAT Explorer II": "https://www.nma-fallout.com/resources/fallout-dat-explorer-ii.140/"
   Bu program oyun dosyaları içerisinde diyalog,script gibi dosyalara erişmemizi sağlayacak. Programı çalıştırın ve oyun klasöründeki "master.dat" i açın direkt karşınıza orijinal .fon uzantılı dosyalar gelecek.    Dışarıya aktarmak istediğiniz dosyaları seçin ve sağ tıklayın. "Extract selected file(s)" diyerek herhangi bir konuma dosyaları çıkartın.
   (Eğer metin dosyalarına oluşmak istiyorsanız text>english yerinde olan ".msg" uzantılı dosyalar oyun içindeki diyaloglara ait çeviri yapmak isterseniz buradaki dosyaları düzenleyeceksiniz.)

2. Adım ".aaf editor":
   Program bildiğim kadarıyla rusça ama yine de işinizi görür. "https://fodev.net/files/fo2/tools.html" Bu linkten "AAF Editor" indirin ve başlatın
   
   Sol üstte "????" olan yere tıklayın (dediğim gibi program rusça hiçbir yazı yazmaması ???? olması sizde de olabilir.)
   Resim
   Kırmızıyla işaretlediğim yere tıklayın
   Resim acma
   Daha sonra "font.aaf" uzantılı dosyaları nereye çıkardıysanız oradan dosyayı bulup açın
   Resim
   Şimdi düzenleme kısmına gelelim sağ tarafta gördüğünüz yerden tek tek pikselleri boyamanız gerekiyor. Maviyle işaretlediğim yerde de karakterler arasında geçiş yapabiliyorsunuz.
   Burada kullanılmayan bir ASCII karakterini herhangi bir türkçe karakter yapalım örneğin ">" işaretini "ç,ş,ö" yapıcaz. Bu sadece bir örnek ">" işaretini "ç" ye çevirmek istediniz diyelim. ">" işaretini bulun ardından sağ panelden o fontu boyayın ve "ç" çizin.
   Bu adımları font0.aaf,FONT1.AAF ... nereye kadar o karakter gidiyorsa tek tek çizmeniz gerekecek.
   Tüm bu işlemleri yaptıktan sonra artık bir fontu oyun içinde değiştirdiniz. Örneğin: "<" işaretini "ş" yaptınız. diyalog dosyalarında bu işaret oyun içinde "ş" olarak görünecek.
   
   
   
