# Temel Linux Komutları Quiz Cevapları
(bu cevaplar repoya ekli pdf'in cevaplarıdır)

# 1) 
![resim](https://github.com/user-attachments/assets/84d18de6-f147-48ad-9594-b9a80326ef52)<br>
<b>1.Adım:</b> Masaüstü dizini seçilir <br><br>
**2.Adım:** guvenlik.txt dosyası oluşturulur<br>
**3.Adım:** dizinler listelenir<br>
**4.Adım:** guvenlix.txt dosyası düzenleme modunda açılır.<br>
**5.adım:** guvenlik.txt dosyası görüntülenir.<br>
**6.Adım:** guvenlik.txt dosyası üzerine ekleme modunda açılır ve düzenlenir.<br>
**7.adım:** guvenlik.txt dosyası görüntülenir.<br>
<br>

# 2)
**"cat –n /etc/passwd” komutunun işlevini açıklayınız?** <br><br>
**Açıklama:** /etc/passwd dosyasını satır numaraları ile birlikte ekrana yazdırır. 

# 3)
<b>
$ echo Açık Kaynak > ders1.txt <br>
$ echo İşletim Sistemi > ders2.txt<br>
$ cat ders1.txt ders2.txt<br>
Yukarıdaki komut bloğu çalıştırıldığında ekran çıktısı ne olur?<br>
</b>
<b>Çıktı:</b> Açık Kaynak <br> İşletim Sistemi

# 4)
**“Deneme.txt” dokümanı içerisinde 100 satırlık paragraf bulunmaktadır. Paragrafın sadece 2
satırını görüntülemek için kullanılan komutu yazınız?**<br><br>
**Komut:** head -n 2 Deneme.txt

# 5)
**Sistem yapılandırma dosyaları içerisinde bulunan “passwd” dokümanının ilk ve son 5 satırını
görüntülemek için kullanılan komutu yazınız?**<br><br>
**Komut:** head -n 5 /etc/passwd
**Komut:** tail -n 5 /etc/passwd

# 6) 
<b>Masaüstünde “okul.txt” adında doküman oluşturunuz. Doküman içerisine adınızı, soyadınızı ve
okuduğunuz bölüm bilgisini komut blokları ile ekleme ve görüntüleme sağlayınız. Son olarak
oluşturduğunuz dokümanda karakter ve kelime sayısını bulan komut bloklarını yazınız?</b> <br><br>
**Komut:** cd Masaüstü <br>
**Komut:** touch okul.txt<br>
**Komut:** cat > okul.txt<br>
**Komut:** Abdurrahman Ebrar Koçak<br>
**Komut:** cat okul.txt<br>
**Komut:** wc -w okul.txt<br>
**Komut:** wc -m okul.txt<br>
# 7)
<b>Masaüstünde “ben.txt ve program.txt” adında iki adet doküman oluşturunuz.<br>
ben.txt içerisine; ad, soyad ve memleket bilgisi ekleyin ve görüntüleme sağlayınız.<br>
program.txt içerisine; bildiğiniz üç tane programlama dilini ekleyin ve görüntüleme sağlayınız.<br>
Oluşturulan her iki dokümanı aralarına tab boşluğu koyarak “birlestirme.txt” dokümanı
içerisine ekleyiniz.<br>
Son olarak “komut” dizini oluşturup içerisine “birlestirme.txt” dokümanını taşıyan ve
arşivleyen komut bloklarını yazınız?</b><br>
<br>
**Komut:** cd Masaüstü<br>
**Komut:** touch ben.txt program.txt<br>
**Komut:** echo "Abdurrahman Ebrar" > ben.txt<br>
**Komut:** echo "Bilgisayar" > program.txt<br>
**Komut:** cat ben.txt<br>
**Komut:** cat program.txt<br>
**Komut:** paste ben.txt program.txt > birlestirme.txt<br>
**Komut:** mkdir komut<br>
**Komut:** mv birlestirme.txt komut<br>
**Komut:** tar -cvf birlestirme.tar komut<br>


# 8) 
<b>Masaüstünde “yetki” adında dizin oluşturunuz. Dizin içerisine “yetkilendirme.txt” dokümanı
oluşturup erişim izinlerini listeleyiniz. Grup ve diğer kullanıcıların erişim izinlerine yazma
yetkisini veren komut bloklarını yazınız?</b><br><br>
**Komut:** cd /Masaüstü<br>
**Komut:** mkdir /yetki<br>
**Komut:** cd /yetki<br>
**Komut:** touch yetkilendirme.txt<br>
**Komut:** ls -l /yetki<br>
**Komut:** chmod g+w yetkilendirme.txt<br>
**Komut:** chmod o+w yetkilendirme.txt<br>
**Komut:** ls -l /yetki<br>

