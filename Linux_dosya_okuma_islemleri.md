**Linux Dosya Okuma İşlemleri**

![cat_komutu](https://github.com/user-attachments/assets/c679bb45-d169-4adb-94ef-f13b5db4316b)

cat komutu: standart cıktı ekranında dosyalar oluşturmamıza, birleştirmemize veya bastırmamıza izin veren en kullanışlı Linuxda öğrenebileceğimiz bir komuttur.
apache-1691435735822.log dosyasını okumak için Linux da  cat komutu ile herhangi bir seçenek belirtmeden bu dosyanın içeriklerini okuyarak  konsolda göstermiştir. 

![cut_komutu_f _1](https://github.com/user-attachments/assets/540d7c26-92f0-4215-a4bc-dd96a74f4b89)

Okunan dosyada  istediğin parametreyi  almak için (IP adreslerini alabilmek adına)  cut komutu ile sutünun numarası (-f istediğin sutün nosu olan 1)  alındı.

![cut_komutu_2 parametre](https://github.com/user-attachments/assets/7330f987-24cb-4312-b35a-35086abdfadc)

Okunan dosyada ilgili tarih ve saatleri almak için(2.sutunda yer adldığından) 2.sutünü alıp 1.olan sutunu yok etmek için yukarıdaki resimde yer alan cut komutu kullanıldı.

![cut_komutu_sort](https://github.com/user-attachments/assets/f4842602-ac41-4463-acc2-c740e9d8874c)

IP adreslerinin sıralamasını küçükten büyüğe doğru sıralamk için sort komutu kullanılmıştır.  

![cut_komutu_uniq](https://github.com/user-attachments/assets/3048cfcd-ef7f-4061-bbca-bea99595b6ff)

uniq komutu, bir dosyadaki (orn. IP adresinin) yinelenen satırları silmektedir. Sıralama ise küçükten büyüğe doğru gerçekleşti.

![cut_komutu_M](https://github.com/user-attachments/assets/4a1481db-07b8-4651-b994-b6029984b7e4)

M ile (birinciden M'inci (dahil) bayta, karaktere veya alana kadar) tarihe ve saate  göre sort komutuyla küçükten büyüğe doğru sıralama yaptı.

![cut_komutu_sort_M__r_uniq_c](https://github.com/user-attachments/assets/519ee756-6d11-4526-9744-20d93adadd6b)

sort_M_r| uniq -c karakter listesini büyükten küçüğe doğru sıralama gerçekleştirildi.

![sed_komutu](https://github.com/user-attachments/assets/e240b14a-db6d-4842-a4e9-d1145dc46e5b)
s ile basla g ile bitirmek için yukarıda yer alan komut işlemi gerçekleşmiştir. İlgili kaçış için \ kullanarak yazım işlemi gerçekleşti.
![awk_komut_port__araştırma](https://github.com/user-attachments/assets/3ea2bb6e-24fb-4e61-8eb7-d16c08a720c2)

awk ve sed komutları karmaşık metin işleme amacıyla kullanılmaktadır.
awk belli sutünların işlenmesinde kullanılırken sed komutu metin düzenleme ve filtreleme yapmaktadır.
awk komutunun örüntü araması grep komutundan daha genel ve kullanıcının giriş metni satırlarında birden çok işlem gerçekleştirmesini sağlar. 
awk komut programlama dili derleme gerektirmez ve kullanıcının değişkenleri, sayısal işlevleri, dizgi işlevlerini ve mantıksal işleçleri kullanmasını sağlar.
awk '$9 = 200' apache-1691435735822.log komutu ile ilgili portu (200 portu) araştırmak için kullanılmıştır.

![cat_komutu_sed_birlikte_IP_ve_tarih](https://github.com/user-attachments/assets/b4c65105-3643-48f5-bd70-e1b1ce047ab6)

![cat_komutu_tarih_saat_sıralama](https://github.com/user-attachments/assets/cb50113b-fe50-4500-afaf-6c7698858844)

Ayrıca cat komutu ile İstediğin hangi sutundaki değişkense ona bağlı olarak ilgili dosyada okuma işlemi  gerçekleştirilir. 
İlgili IP adresine bağlı tarih(31 July) bazlı olursa yazılacak olan komut uygulaması yukarıdaki gibidir.
Saat dikkate alınıp sıralanırsa yukarıda yer alan ikinci görüntü gibi olur.

![cat_komutu_sort_7 sutun_icerikler](https://github.com/user-attachments/assets/3ee8dbfc-a9e8-42d9-9e09-254059af6cda)

İlgili değişken parametresini alarak sıralamak için apache dosyasında 7.sutunu oluşturan değişken alınarak sıralama yapılmıştır.

![cat_komutu_7 degiskenin_login_php_icerigi](https://github.com/user-attachments/assets/c6e79f44-b972-4914-9321-d2a85e934b17)

7.sutunu oluşturan değişkende bulunan login.php içeriğini göstermek için yukarıdaki Linux komutu kullanılmıştır.
