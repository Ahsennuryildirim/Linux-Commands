# LİNUX KOMUTLARI

---

## Linux İşletim Sistemi
Linux, açık kaynaklı, Unix benzeri bir işletim sistemidir. 1991 yılında Linus Torvalds tarafından geliştirilmeye başlanmış ve dünya genelindeki geliştiricilerin katkılarıyla büyümüştür. Güvenilirliği, esnekliği ve çoklu platform desteği ile bilinir. Günümüzde sunuculardan masaüstü bilgisayarlara, mobil cihazlardan gömülü sistemlere kadar birçok alanda kullanılmaktadır.

---

## Linux Komutları
### **1.** **pwd**  Komutu
---

* **pwd**, Linux ve Unix tabanlı sistemlerde kullanılan bir komuttur. Bu komut, çalıştığınız terminal oturumunda mevcut dizinin yolunu ekrana yazdırır.

![görsel](/Komutlar%20L/pwd%20Komutu%20L.JPG)

### **2.** **alias** Komutu

---

* **alias** komutu, Linux ve diğer Unix tabanlı sistemlerde kullanılan, mevcut komutları daha kısa ve öz bir şekilde çalıştırmak için takma adlar oluşturmanıza yarayan bir komuttur. Komutları kişiselleştirmenizi sağlar ve sık kullanılan uzun komutların yazımını kolaylaştırır.

 ![görsel](/Komutlar%20L/alias%20Komutu%20L.JPG)

### **3.** **apropos(killall)** Komutu

---

* Linux'ta **apropos** komutu belirli bir anahtar kelimeyle ilişkili komutları veya konuları bulmak için kullanılır. apropos, komut ve işlev açıklamalarını içeren "man" sayfalarında arama yapar. Yani, bir komutun ne işe yaradığını bilmiyorsanız veya belirli bir konuyla ilgili komutları görmek istiyorsanız apropos size yardımcı olur.

* **killall** ise Linux'ta belirli bir adı taşıyan tüm işlemleri sonlandırmak için kullanılan bir komuttur.

![görsel](/Komutlar%20L/apropos%20Komutu%20L.JPG)

### **4.** **arch** Komutu

---

* Linux'ta **arch** komutu, mevcut sistemin donanım mimarisini (architecture) gösterir. Bu komut, özellikle sistemin 32-bit mi yoksa 64-bit mi olduğunu hızlıca öğrenmek için kullanılır. 
* Komut çalıştırıldığında, sistemin işlemci mimarisine bağlı olarak bir çıktı verir.
* arch komutu genellikle **uname -m** komutuyla benzer işlev görür.
* arch komutu genellikle çok temel bilgi verdiği için bazı sistemlerde bulunmayabilir; böyle bir durumda uname -m alternatifi kullanılabilir.

![görsel](/Komutlar%20L/arch%20Komutu%20L.JPG)

### **5.** **df** Komutu

---

* Linux'ta **df (disk free)** komutu, disk bölümleri hakkında bilgi almak ve her bir bölümdeki kullanılabilir disk alanını göstermek için kullanılır. Bu komut, dosya sistemlerindeki kullanılabilir ve kullanılan disk alanını tablo halinde sunar.
* Bu komut, tüm bağlı dosya sistemlerini ve bunların toplam, kullanılan, boş alanlarını kilobyte cinsinden listeler.

![görsel](/Komutlar%20L/df%20Komutu%20L.JPG)

### **6.** **du** Komutu

---

* Linux'ta **du (disk usage)** komutu, belirli bir dosya veya dizinin disk üzerinde ne kadar alan kapladığını, görmek için kullanılır. du, dosya boyutlarını ve dizinlerin toplam boyutlarını listeleyerek, özellikle disk alanını yönetmek ve analiz etmek için faydalı bilgiler sağlar.
   
![görsel](/Komutlar%20L/du%20Komutu%20L.JPG)

 ### **7.** **free** Komutu

  ---

* Linux'ta **free** komutu, sistemdeki bellek ve takas alanı kullanımıyla ilgili bilgi almak için kullanılır. Bu komut, toplam, kullanılan, boş ve mevcut bellek miktarını hızlıca görmenizi sağlar. 

![görsel](/Komutlar%20L/free%20Komutu%20L.JPG)

### **8.** **groups** Komutu

---
* Linux'ta **groups** komutu, bir kullanıcının hangi gruplara üye olduğunu listelemek için kullanılır. Linux sistemlerinde kullanıcılar birincil bir gruba ve isteğe bağlı olarak birden fazla ek gruba atanabilir. Bu komut, özellikle izinler ve dosya erişim kontrolüyle ilgili durumları analiz etmek için kullanışlıdır. 

![görsel](/Komutlar%20L/groups%20Komutu%20L.JPG)

### **9.** **id** Komutu

---

* Linux'ta **id** komutu, kullanıcı ve grup bilgilerini görüntülemek için kullanılır. Bu komut, çalıştırıldığı kullanıcının UID, GID ve kullanıcının bağlı olduğu grupların bilgilerini gösterir. 
* id komutunun çıktısı genellikle şu bilgileri içerir:
    
      UID: Kullanıcının benzersiz kimliği.
      GID: Kullanıcının ana grubunun kimliği.
      Gruplar: Kullanıcının ait olduğu tüm gruplar.

![görsel](/Komutlar%20L/id%20Komutu%20L.JPG)

### **10.** **logname** Komutu

---

* Linux'ta **logname** komutu, şu anda oturum açmış olan kullanıcının oturum adı bilgilerini gösterir. Bu, kullanıcının sistemdeki giriş kimliğidir. 
* Eğer birden fazla kullanıcıyla oturum açılmışsa, logname komutu yalnızca ilk oturum açan kullanıcının adını verir. 

![görsel](/Komutlar%20L/logname%20Komutu%20L.JPG)

### **11.** **man** Komutu
---
* Linux'taki bir komut hakkında bilgi almak için kullanılır. Komutun ne işe yaradığını, seçeneklerini ve örnek kullanımlarını içerir.
* Her komutun kapsamlı dökümantasyonunu sağlar. 

![görsel](/Komutlar%20L/man%20Komutu%20L1.JPG)
![görsel](/Komutlar%20L/man%20Komutu%20L%202.JPG)

### **12.** **info** Komutu
---
* Komutlar hakkında daha geniş ve yapılandırılmış bilgi sağlar. man komutunu alternatif olarak kullanılır.
* Komutlar hakkında bağlantılarla dolaşmayı destekler.

![görsel](/Komutlar%20L/info%20Komutu%20L1.JPG)
![görsel](/Komutlar%20L/info%20Komutu%20L2.JPG)

### **13.** **ls** Komutu
---
* Linux'ta **ls** komutu, geçerli dizindeki dosya ve klasörleri listeler.
* Çıktısı, varsayılan olarak alfabetik sıraya göre düzenlenir.

![görsel](/Komutlar%20L/ls%20Komutu%20L.JPG)

### **14.** **ls -a** Komutu
---
* Linux'ta **ls -a** komutu, gizli dosyalar da dahil olmak üzere dizindeki tüm dosyaları listeler.
* Gizli dosyalar **.** ile başlar ve varsayılan **ls** komutuyla görünmez.

![görsel](/Komutlar%20L/ls%20-a%20Komutu%20L.JPG)

### **15.** **ls -l** Komutu
---
* Linux'taki **ls -l** komutu, dosyaları ayrıntılı bir şekilde listeler.
  
      Çıktıda Şunları İçerir :
    
      Dosya türü (dizin, dosya, bağlantı vb.)
      İzinler
      Sahibi
      Grubu
      Boyutu
      Değiştirilme tarihi

![görsel](/Komutlar%20L/ls%20-l%20Komutu%20L.JPG)

### **16.** **ls -t** Komutu
---
* Linux'ta **ls -t** komutu dosyaları son değiştirilme tarihine göre sıralar.
* Varsayılan olarak yeni dosyalar üstte olur.

![görsel](/Komutlar%20L/ls%20-t%20Komutu%20L.JPG)

### **17.** **ls -as** Komutu
---
* Linux'taki **ls -as** komutu, her dosyanın blok boyutunu gösterir ve gizli dosyaları listeler.
* Bu komut, sistem depolama analizi için kullanışlıdır.

![görsel](/Komutlar%20L/ls%20-as%20Komutu%20L.JPG)

### **18.** **ls -l [A-Z]*** Komutu
---
* Linux'ta **ls -l [A-Z]*** komutu, büyük harfle başlayan dosyaları ayrıntılı şekilde listeler.
* Bu komut, düzenli ifadeleri destekler.

![görsel](/Komutlar%20L/Komut%20L..JPG)

### **19.** **ls -lh** Komutu
---
* Linux'ta **ls -lh** komutu, insan tarafından okunabilir bir biçimde dosya boyutlarını gösterir.
* Bu komut, dosya boyutlarını daha anlaşılır hale getirir.

![görsel](/Komutlar%20L/ls%20-lh%20Komutu%20L.JPG)

### **20.** **ls -R** Komutu
---
* Linux'ta **ls -R** komutu, alt dizinler dahil olmak üzere dizindeki tüm dosyaları listeler. 
* Bu komut, rekürsif listeleme yapar.

![görsel](/Komutlar%20L/ls%20-R%20Komutu%20L.JPG)

### **21.** **ls -alh** Komutu
---
* Linux'ta **ls -alh** komutu, gizli dosyalar dahil olmak üzere, insan tarafından okunabilir formatta tüm dosyaları ayrıntılı bir şekilde listeler.
* Bu komut, -a, -l ve -h seçeneklerini birleştirir.

![görsel](/Komutlar%20L/ls%20-alh%20Komutu%20L.JPG) 

### **22.** **ls -LH** Komutu
---
* Linux'ta **ls -LH** komutu, simge bağlantılar için hedef dosyanın boyutunu gösterir.
* Bu komut, normal **ls -l** komutundan farklı olarak bağlantının işaret ettiği dosyanın detaylarını verir. 

![görsel](/Komutlar%20L/ls%20-LH%20Komutu%20L5.JPG)


### **23.** **ls -ltr** Komutu
---
* Linux'ta **ls -ltr** komutu, dosyaları ayrıntılı ve tarih sırasına göre listeler.
* Bu komut, ters sıralama yapar.

![görsel](/Komutlar%20L/ls%20-ltr%20Komutu%20L.JPG)


### **24.** **ls -r** Komutu
---
* Linux'ta **ls -r** komutu, ters sırayla dosyaları listeler.
* Varsayılan sıralamayı tersine çevirir.

![görsel](/Komutlar%20L/ls%20-r%20Komutu%20L%205.JPG)

### **25.** **ls -s** Komutu
---
* Linux'ta **ls -s** komutu, dosyaları boyutlarına göre sıralar.

![görsel](/Komutlar%20L/ls%20-s%20Komutu%20L.JPG)

### **26.** **cd ..** Komutu
---
* Linux'ta **cd ..** komutu, bir üst dizine geçiş yapar.

![görsel](/Komutlar%20L/cd%20..%20Komutu%20L.JPG)


### **27.** **cd -** Komutu
---
* Linux'ta **cd -** komutu, bir önceki kullanılan dizine geri döner.
* Bu komut, hızlı geçiş için faydalıdır.

![görsel](/Komutlar%20L/cd%20-%20Komutu%20L.JPG)

### **28.** **head** Komutu
---
* Linux'ta **head** komutu, bir dosyanın ilk birkaç satırını görüntüler.
* Varsayılan olarak ilk 10 satırı gösterir; -n seçeneğiyle bu sayı değiştirilebilir.

![görsel](/Komutlar%20L/head%202.JPG)
![görsel](/Komutlar%20L/head%20Komutu%20L.JPG)


### **29** **cat** Komutu
---
* Linux'ta **cat** komutu, dosya içeriklerini okur ve birleştirir. 
* Bu komut, hızlı dosya içeriği kontrolü veya birden fazla dosyanın birleştirilmesi için kullanılır.

![görsel](/Komutlar%20L/cat%20Komutu%20L.JPG)

### **30.** **ps** Komutu
---
* Linux'ta **ps** komutu, çalışan süreçlerin durumunu listeler.
* Varsayılan olarak yalnızca terminalde çalışan süreçleri gösterir.
* ps -aux gibi seçeneklerle sistem genelindeki tüm süreçleri görüntüleyebilir. 

![görsel](/Komutlar%20L/ps%20Komutu%20L.JPG)

