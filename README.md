# fallout2-turkce-karakter-cozumu
Fallout 2 Türkçe karakter sorunu çözümü

NOT: Font sorununun daha iyi bir çözüm yöntemi olursa issue isteği atın ve açıklayın. ben ancak bu şekilde çözebildim. ve tavsiyem çeviri yapacaksanız sanal makinede yapmanız yönünde. 
Çeviri yapacaklar için adımlar:
NOT2: Attığım fontlar Fallout 1 için çalışıyor mu kontrol etmedim. Muhtemelen çalışıyordur yine de kontrol edin.

1 : 
notepad++ indirin ve kurun
2 : 
 "Fallout DAT Explorer II": "https://www.nma-fallout.com/resources/fallout-dat-explorer-ii.140/"
   İndirin ve programı başlatın "open" sekmesinden fallout2'nin kurulu olduğu yerdeki "master.dat" dosyasını açın ve attığım font dosyalarını buraya yapıştırın. bu kadar fontlar değişti. eğer diyalog dosyalarını da almak istiyorsanız aşağıdaki "text" yerinden diyalog dosyalarını çıkartabilirsiniz.
![8](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/b1d5789e-7c18-4ec3-89e3-ee7298f418b0)



3: (Burası önemli)
 ".msg" dosyalarında türkçe karakterler yerine kullanılan ifadeler:
  "@" = "ç" harfine karşılık geliyor
  "<" = "ğ" harfine karşılık geliyor
  ">" = "ş" harfine karşılık geliyor
  "^" = "ö" harfine karşılık geliyor
  "/" = "ü" harfine karşılık geliyor
  bu karakterler sadece küçük harf dikkat edin büyük harf değiller. Yani oyun içinde "Ş"-"ş" olacak
  "İ" leri "I" harfine çevirin çünkü onun fontunu ayarlamadım.
  "ı" ları ise "i" yapın aksi taktirde hiçbir şey okunmaz
  
Bir metin dosyasını çevirdiniz ve bu şekilde görünüyor diyelim
![12](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/5036cbb3-46cd-4a5d-9d42-89f63cdd3ca0)


Şimdi yukarıda saydığım karakterleri değiştirmemiz gerekecek. "ctrl+h" yapın çıkan ekranda "aranan" kısmına hangi harfi değiştirmek istiyorsanız onu yazın. daha sonra "değiştir" yerine o harfe karşılık gelen işareti girin ve "tümünü değiştire" basın.
![10](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/2053fec8-66d8-439a-b471-1ca60dcc024a)


Artık tüm kelimelerdeki "ü" harfi yerine "/" geldi. aynı işlemleri diğer karakterler için de yapın ve dosyanızı kaydedin. Artık bu dosya için "çeviriniz" bitti oyun içinde düzgün bir biçimde görünecektir.
![11](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/03abe16e-76ec-4b2e-84bd-b2812973441a)

En son dosyanızdaki karakterler bu şekilde olması gerekecek.
![133](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/3bed4ab8-973c-43dc-a889-3fe69f8ca5f6)

Oyun içinden görseller.
![14](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/60b29bbd-2fde-4d65-a529-7feb0dcbfd2b)

![15](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/004576bd-6818-4d40-ac0f-cb54114212cb)






 

UYARI! Font dosyalarında düzenleme yapmak istiyorsanız kesinlikle sanal makinede çalışın. ".aaf editor" gibi programlar ne kadar güvenilir belli değil çünkü.

Bu kısım font dosyalarını kurcalamak isteyenler için:

Fallout 1 ve 2'de diyaloglar ASCII ile yazıldığı için diyaloglarda türkçe bir karakter olunca oyun içinde malum gözükmüyor veya saçma bir şekilde gözüküyor.
Bu font sorununu düzeltmek için font dosyalarını düzenlemek gerekecek.

1. Adım "Fallout DAT Explorer II": "https://www.nma-fallout.com/resources/fallout-dat-explorer-ii.140/"
   Bu program oyun dosyaları içerisinde diyalog,script gibi dosyalara erişmemizi sağlayacak. Programı çalıştırın ve oyun klasöründeki "master.dat" i açın. direkt karşınıza orijinal .aaf uzantılı dosyalar gelecek.    Dışarıya aktarmak istediğiniz dosyaları seçin ve sağ tıklayın. "Extract selected file(s)" diyerek herhangi bir konuma dosyaları çıkartın.
   (Eğer metin dosyalarına ulaşmak istiyorsanız text>english yerinde olan ".msg" uzantılı dosyalar oyun içindeki diyaloglara ait. çeviri yapmak isterseniz buradaki dosyaları düzenleyeceksiniz.)

2. Adım ".aaf editor":
   Program bildiğim kadarıyla rusça ama yine de işinizi görür. "https://fodev.net/files/fo2/tools.html" Bu linkten "AAF Editor" indirin ve başlatın
   
   Sol üstte "????" olan yere tıklayın (dediğim gibi program rusça hiçbir yazı yazmaması,???? olması sizde de olabilir.)

![1](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/8539eb9e-6e6d-436b-a563-9af34b36f568)
                                            Kırmızıyla işaretlediğim yere tıklayın


![acma](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/c24aceda-8576-4680-8506-071b947c311c)
Daha sonra "font.aaf" uzantılı dosyaları nereye çıkardıysanız oradan dosyayı bulup açın

![4](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/c4476703-013d-4107-9314-8da8ede9b395)
Şimdi düzenleme kısmına gelelim. sağ tarafta gördüğünüz yerden tek tek pikselleri boyamanız gerekiyor. Maviyle işaretlediğim yerde de karakterler arasında geçiş yapabiliyorsunuz.
Burada kullanılmayan bir ASCII karakterini herhangi bir türkçe karakter yapalım örneğin ">" işaretini "ç,ş,ö" yapıcaz. Bu sadece bir örnek ">" işaretini "ç" ye çevirmek istediniz diyelim. ">" işaretini bulun ardından sağ panelden o fontu boyayın ve "ç" çizin.
Bu adımları font0.aaf,FONT1.AAF ... nereye kadar o karakter gidiyorsa tek tek çizmeniz gerekecek.
Tüm bu işlemleri yaptıktan sonra artık bir fontu oyun içinde değiştirdiniz. Örneğin: "<" işaretini "ş" yaptınız. diyalog dosyalarında bu işaret oyun içinde "ş" olarak görünecek.

![7](https://github.com/Dermanblake/fallout2-turkce-font-cozumu/assets/155254976/c019dbe1-15db-4f93-bdfc-95841637addb)
Kaydetmek için kırmızıyla gösterdiğim yere tıklayın ve istediğiniz bir yere kaydedin.
Tüm ".aaf" uzantılı düzenledikten sonra orijinal "font.aaf" dosyalarıyla yer değiştirin. font dosyalarının aynı isimde olmasına dikkat edin ve oyun içinden fontlar çalışıyor mu diye kontrol edin. 

Not: "{" "}" "(" ")" "%" "#" bu karakterleri değiştirmeyin oyun içinde sıkıntı yaratabilir.
   
   
