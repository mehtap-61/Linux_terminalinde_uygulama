**Linux dosya işlemleri**

![linux_calistigin_dizin](https://github.com/user-attachments/assets/78bbf7a5-6b03-4493-83c6-8ea7d4588ca8)
Linuxda terminal kullanımında çalıştığın dizini görmek için pwd kullanılır.
Unix ve Unix benzeri işletim sistemlerinde mevcut dizinin yolunu pwd ile görebiliriz.
Terminalde hiçbir değişiklik yapmadığımızda ilk dizin home/kali olduğu görülmektedir.


![dizini_bin_olarak_degisti](https://github.com/user-attachments/assets/8fa0c50f-4884-4349-8a23-5248b3609840)
cd komutu dizini değiştirmek için kullanılmaktadır.
Dizini ** cd /bin ** olarak değiştirildi.
**/bin** : Yürütülebilir dosyaların bulunduğu yerdir.
Yani dizini  cd /bin olarak yürütülebilir dosyalara ulaşmaya çalıştık.
Tüm yaptığımız değişikliklerden sonra *hangi dizinde  olduğumuzu görmek* için **pwd** yazıldı.

![calisma_history](https://github.com/user-attachments/assets/48b058fe-e0a1-4199-8e16-f99c77121135)

**uptime **: Sunucunun ne zamandır açık olduğunu (daha doğrusu işletim sisteminin) ne zamandır hizmet verdiğini öğrenilir.
**history**: Terminal üzerinde, daha önce girdiğimiz komutların çıktısını verir.

![rm--help](https://github.com/user-attachments/assets/17f73441-98c5-436b-96c5-216a53d83b41)

rm --help komutu ile ne yapacagımıza göre bize alternatifler vermektedir.
Kullanımını öğrenebilmek için rm--help yazılır.
Bu komut  dosya parametresine ilişkin girişleri bir dizinden kaldırır.
Bir girdi bir dosyaya son bağlantıysa, dosya silinir. 

![echo_komut](https://github.com/user-attachments/assets/94258678-e850-4431-9772-15a110dd97e8)

Linux **echo** komutu ile terminal ekranına istediğimiz yazıyı çıktı olarak alabileceğimiz gibi, yeni dosya oluşturmak için de kullanabiliriz. 
Ekrana bir şeyler yazdırmak için echo komutundan sonra çift tırnak içerisinde yazımızı yazabiliriz.

![kayıtli_kullanici_izleme](https://github.com/user-attachments/assets/4de2d38d-aee9-44e7-9a60-215935a9ea6b)
cat komutu, Linux'ta en yaygın kullanılan komutlardan biridir.
cat komutunun adı, dosyaları birleştirme işlevinden gelir.
Geleneksel olarak cat /etc/passwd dosyası, bir sisteme erişimi olan her kayıtlı kullanıcıyı izlemek için kullanılır.

![grep_komutu](https://github.com/user-attachments/assets/63003e43-30d6-4c31-b599-056b800c020b)

**grep**: Dosya parametresinde birden çok ad belirlerseniz, eşleşen satırı içeren dosyanın adını görüntüler.

![nano.bashrc](https://github.com/user-attachments/assets/f7fc612a-e465-4c04-a07f-cef3807df2b3)

Dosyanın içeriğini açmak ve düzenlemek için nano.bashrc komutu kullanılmıştır.

![kayit_tutma](https://github.com/user-attachments/assets/7a6013cb-fae2-4b0f-a690-8b9e39f6f86a)

Hello Word deyip Ctrl O enter Ctrl x deyip pencereden çıktık.

![hello_word](https://github.com/user-attachments/assets/e476af56-f562-4451-bb6b-3ff3f85fea1f)

Daha sonra yeni terminal açınca terminalin üstünde Hello Word yazısını göreceğiz.

![lastlog_komutu](https://github.com/user-attachments/assets/50ba13fb-4038-4be4-9dbb-127318331a90)

**lastlog**: Genellikle çok seyrek bir dosya olan son oturum açma günlük dosyasının içeriğini (oturum açma adı, bağlantı noktası ve son oturum açma tarihi ve saati) biçimlendirir ve yazdırır. 
Hangi kullanıcının en son ne zaman giriş yaptığını görüntülemek için 'lastlog' komutunu kullanabilir.

![last](https://github.com/user-attachments/assets/2ee34f0c-52f7-40e1-a4fc-19ccd8bfdced)

**last**: Tüm kullanıcıların veya belirli bir kullanıcının en son girişini listeler.
Son giriş yapan kullanıcıların giriş yaptığı ip bilgilerini ve çıkış bilgilerini de gösterir.

![dosya ovpn](https://github.com/user-attachments/assets/842fa7f3-1aa0-4c28-b4cd-260249da3b67)

track hack.me de Intro Logda indirdiğimiz *vpn dosyasının adını* dosya.ovpn olarak değiştirdik.
Sanal bilgisayara atıp terminali cd Desktop yapıp masaüstünden ilgili dosya okumasını gerçekleştirildi.

![less_komutu](https://github.com/user-attachments/assets/050a69d6-febe-477d-94a8-3559e7b49336)

**less**: Dosyaları okumak için veya dosyanın içinde bir şey aramak istenirse ilgili  dosyayı sayfa sayfa görüntülenir. Boşluk tuşuna basıldığında bir sonraki sayfa görüntülenir.

![wc_komutu](https://github.com/user-attachments/assets/fae1077c-8f9f-4e86-a10b-87185d5b6b71)

Linux'ta wc (word count) komutu dosyada bulunan satır sayısını, kelime sayısını ve karakter sayısını çıktı olarak verir.

![cut_komutu](https://github.com/user-attachments/assets/ca927bdd-e0bb-4966-bb95-117de0c6ca5c)

**cut** komutu ile istediğin alanı sütununu(1 olarak) belirtip IP adresleri görüldü.

![cut_komutu_sort_siralama](https://github.com/user-attachments/assets/7f21324c-e202-49fa-935c-4199767617ae)

cut komutuna |sort -n  eklenip IP adresleri sıralanır.
