# Temel Linux Komutları Quiz Cevapları
(bu cevaplar repoya ekli pdf'in cevaplarıdır)

# 1) 
![resim](https://github.com/user-attachments/assets/84d18de6-f147-48ad-9594-b9a80326ef52)<br>
<b>1.Adım:</b> Masaüstü dizini seçilir <br>
**2.Adım:** guvenlik.txt dosyası oluşturulur<br>
**3.Adım:** dizinler listelenir<br>
**4.Adım:** guvenlix.txt dosyası düzenleme modunda açılır.<br>
**5.adım:** guvenlik.txt dosyası görüntülenir.<br>
**6.Adım:** guvenlik.txt dosyası üzerine ekleme modunda açılır ve düzenlenir.<br>
**7.adım:** guvenlik.txt dosyası görüntülenir.<br>
<br>

# 2)
**"cat –n /etc/passwd” komutunun işlevini açıklayınız?** <br>
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
satırını görüntülemek için kullanılan komutu yazınız?**<br>
**Komut:** head -n 2 Deneme.txt

# 5)
**Sistem yapılandırma dosyaları içerisinde bulunan “passwd” dokümanının ilk ve son 5 satırını
görüntülemek için kullanılan komutu yazınız?**<br>
**Komut:** head -n 5 /etc/passwd
**Komut:** tail -n 5 /etc/passwd

# 6) 
<b>Masaüstünde “okul.txt” adında doküman oluşturunuz. Doküman içerisine adınızı, soyadınızı ve
okuduğunuz bölüm bilgisini komut blokları ile ekleme ve görüntüleme sağlayınız. Son olarak
oluşturduğunuz dokümanda karakter ve kelime sayısını bulan komut bloklarını yazınız?</b> <br>
**Komut:** cd Masaüstü
**Komut:** touch okul.txt
**Komut:** cat > okul.txt
**Komut:** Abdurrahman Ebrar Koçak
**Komut:** cat okul.txt
**Komut:** wc -w okul.txt
**Komut:** wc -m okul.txt
# 7)
<b>Masaüstünde “ben.txt ve program.txt” adında iki adet doküman oluşturunuz.<br>
ben.txt içerisine; ad, soyad ve memleket bilgisi ekleyin ve görüntüleme sağlayınız.<br>
program.txt içerisine; bildiğiniz üç tane programlama dilini ekleyin ve görüntüleme sağlayınız.<br>
Oluşturulan her iki dokümanı aralarına tab boşluğu koyarak “birlestirme.txt” dokümanı
içerisine ekleyiniz.<br>
Son olarak “komut” dizini oluşturup içerisine “birlestirme.txt” dokümanını taşıyan ve
arşivleyen komut bloklarını yazınız?</b><br>

**Komut:** cd Masaüstü
**Komut:** touch ben.txt program.txt
**Komut:** echo "Abdurrahman Ebrar" > ben.txt
**Komut:** echo "Bilgisayar" > program.txt
**Komut:** cat ben.txt
**Komut:** cat program.txt
**Komut:** paste ben.txt program.txt > birlestirme.txt
**Komut:** mkdir komut
**Komut:** mv birlestirme.txt komut
**Komut:** tar -cvf birlestirme.tar komut


# 8) 
<b>Masaüstünde “yetki” adında dizin oluşturunuz. Dizin içerisine “yetkilendirme.txt” dokümanı
oluşturup erişim izinlerini listeleyiniz. Grup ve diğer kullanıcıların erişim izinlerine yazma
yetkisini veren komut bloklarını yazınız?</b><br>
**Komut:** cd /Masaüstü
**Komut:** mkdir /yetki
**Komut:** cd /yetki
**Komut:** touch yetkilendirme.txt
**Komut:** ls -l /yetki
**Komut:** chmod g+w yetkilendirme.txt
**Komut:** chmod o+w yetkilendirme.txt
**Komut:** ls -l /yetki

