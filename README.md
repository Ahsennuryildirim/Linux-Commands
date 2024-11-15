# LİNUX KOMUTLARI

---

## Linux İşletim Sistemi
Linux, açık kaynaklı, Unix benzeri bir işletim sistemidir. 1991 yılında Linus Torvalds tarafından geliştirilmeye başlanmış ve dünya genelindeki geliştiricilerin katkılarıyla büyümüştür. Güvenilirliği, esnekliği ve çoklu platform desteği ile bilinir. Günümüzde sunuculardan masaüstü bilgisayarlara, mobil cihazlardan gömülü sistemlere kadar birçok alanda kullanılmaktadır.

---

## Linux Komutları
### **1.** **pwd**  Komutu
---

* **pwd**, Linux ve Unix tabanlı sistemlerde kullanılan bir komuttur. Bu komut, çalıştığınız terminal oturumunda mevcut dizinin yolunu ekrana yazdırır.

### **2.** **alias** Komutu

---

* **alias** komutu, Linux ve diğer Unix tabanlı sistemlerde kullanılan, mevcut komutları daha kısa ve öz bir şekilde çalıştırmak için takma adlar oluşturmanıza yarayan bir komuttur. Komutları kişiselleştirmenizi sağlar ve sık kullanılan uzun komutların yazımını kolaylaştırır.

### **3.** **apropos(killall)** Komutu

---

* Linux'ta **apropos** komutu belirli bir anahtar kelimeyle ilişkili komutları veya konuları bulmak için kullanılır. apropos, komut ve işlev açıklamalarını içeren "man" sayfalarında arama yapar. Yani, bir komutun ne işe yaradığını bilmiyorsanız veya belirli bir konuyla ilgili komutları görmek istiyorsanız apropos size yardımcı olur.

* **killall** ise Linux'ta belirli bir adı taşıyan tüm işlemleri sonlandırmak için kullanılan bir komuttur.

### **4.** **arch** Komutu

---

* Linux'ta **arch** komutu, mevcut sistemin donanım mimarisini (architecture) gösterir. Bu komut, özellikle sistemin 32-bit mi yoksa 64-bit mi olduğunu hızlıca öğrenmek için kullanılır. 
* Komut çalıştırıldığında, sistemin işlemci mimarisine bağlı olarak bir çıktı verir.
* arch komutu genellikle **uname -m** komutuyla benzer işlev görür.
* arch komutu genellikle çok temel bilgi verdiği için bazı sistemlerde bulunmayabilir; böyle bir durumda uname -m alternatifi kullanılabilir.

### **5.** **df** Komutu

---

* Linux'ta **df (disk free)** komutu, disk bölümleri hakkında bilgi almak ve her bir bölümdeki kullanılabilir disk alanını göstermek için kullanılır. Bu komut, dosya sistemlerindeki kullanılabilir ve kullanılan disk alanını tablo halinde sunar.
* Bu komut, tüm bağlı dosya sistemlerini ve bunların toplam, kullanılan, boş alanlarını kilobyte cinsinden listeler.

### **6.** **du** Komutu

---

* Linux'ta **du (disk usage)** komutu, belirli bir dosya veya dizinin disk üzerinde ne kadar alan kapladığını, görmek için kullanılır. du, dosya boyutlarını ve dizinlerin toplam boyutlarını listeleyerek, özellikle disk alanını yönetmek ve analiz etmek için faydalı bilgiler sağlar.
  
 ### **7.** **free** Komutu

  ---

* Linux'ta **free** komutu, sistemdeki bellek ve takas alanı kullanımıyla ilgili bilgi almak için kullanılır. Bu komut, toplam, kullanılan, boş ve mevcut bellek miktarını hızlıca görmenizi sağlar. 

### **8.** **groups** Komutu

---
* Linux'ta **groups** komutu, bir kullanıcının hangi gruplara üye olduğunu listelemek için kullanılır. Linux sistemlerinde kullanıcılar birincil bir gruba ve isteğe bağlı olarak birden fazla ek gruba atanabilir. Bu komut, özellikle izinler ve dosya erişim kontrolüyle ilgili durumları analiz etmek için kullanışlıdır. 

### **9.** **id** Komutu

---

* Linux'ta **id** komutu, kullanıcı ve grup bilgilerini görüntülemek için kullanılır. Bu komut, çalıştırıldığı kullanıcının UID, GID ve kullanıcının bağlı olduğu grupların bilgilerini gösterir. 
* id komutunun çıktısı genellikle şu bilgileri içerir:
    
      UID: Kullanıcının benzersiz kimliği.
      GID: Kullanıcının ana grubunun kimliği.
      Gruplar: Kullanıcının ait olduğu tüm gruplar.

### **10.** **logname** Komutu

---

* Linux'ta **logname** komutu, şu anda oturum açmış olan kullanıcının oturum adı bilgilerini gösterir. Bu, kullanıcının sistemdeki giriş kimliğidir. 
* Eğer birden fazla kullanıcıyla oturum açılmışsa, logname komutu yalnızca ilk oturum açan kullanıcının adını verir. 

