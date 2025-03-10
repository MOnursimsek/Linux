# **GNU Linux **

## Kavramlar

### Donanım (Hardware)
Donanım, bilgisayarın fiziksel bileşenlerinden oluşur. İşletim sistemi ve yazılımlar, donanımı kullanarak işlemleri gerçekleştirir. İşlemci (CPU)
Bellek (RAM)
Sabit disk, SSD
Klavye, fare, ekran kartı, yazıcı donanıma örnek verilebilir.

###  Kernel (Çekirdek)
Kernel, işletim sisteminin çekirdeğidir ve donanımla doğrudan iletişim kuran en temel bileşendir. Bilgisayarın bellek yönetimi, işlem yönetimi, dosya sistemi ve donanım sürücülerini kontrol eder.

### Shell (Kabuk)
Shell, kullanıcı ile işletim sistemi arasındaki ara yüzdür. Kullanıcının komutlarını alır, Kernel’e ileterek gerekli işlemleri başlatır.
Shell, Kernel’i doğrudan yönetmeyi kolaylaştıran bir katmandır.

### Uygulamalar
Uygulama yazılımları, kullanıcıların belirli görevleri gerçekleştirmesine olanak tanıyan programlardır. Bu yazılımlar Shell ve Kernel üzerinden çalışarak donanımı kullanır.

### İşletim Sistemi Nedir?
- Donanımlarının denetimi ve yönetiminden sorumlu yazılımdır.
- Temel sistem işlemlerinden ve programlarının çalıştırılmasından sorumludur.
- Yazılımların, donanım katmanlarına ve sisteme erişebilmesi için arayüz sunar.
- İşlem (Process) yönetiminden ve işlenme sıralarından sorumludur.
- Giriş-Çıkış (Input-Output I/O), Ağ (Network) ve Bellek (RAM) yönetimlerinden sorumludur.
- İşletim sistemleri, ‘Operating System’in kısaltması olan ‘OS’ ile gösterilir.


<br>
<img src="resimler/linux.png" alt="alt text" width="500"/>

<br><br>

## **GNU**
GNU; çekirdeği, sistem araçlarını, açıcılarını, kütüphanelerini ve son kullanıcı yazılımlarını içeren, GNU Tasarısı kapsamında geliştirilen bir işletim sistemidir. İsminin açılımı "GNU's Not Unix" (GNU Unix değildir) dir. Bu ismi almasındaki sebep de tasarımının Unix'e benzerken kendisinin özgür yazılım olması ve herhangi bir UNIX kodunu içermemesidir.

GNU işletim sistemi planı 1983 Eylül'ünde Richard Stallman tarafından duyurulmuş, 1984 Ocak ayında işleyişe başlamıştır. 2025 itibarıyla GNU hâlâ etkin olarak gelişmektedir.[[1](https://tr.wikipedia.org/wiki/GNU)]

## **Linux** 

Linux, 1991 yılında Linus Torvalds adlı bir Fin üniversite öğrencisi tarafından, daha eski işletim sistemlerinden birisi olan UNIX'in mimarisine ve POSIX standartlarına uygun şekilde sıfırdan yazılmaya başlanmıştır. Geliştirilmesinde Unix mimarisinden esinlenilmiş olmakla birlikte Linux içinde Unix'ten alınmış herhangi bir kod bulunmamaktadır. Geliştirilen bu yazılım, kullanıcı araçları olmayan sadece bir çekirdek yazılımıdır. 
[[2](https://tr.wikipedia.org/wiki/Linux)]


## **GNU-Linux**
Linux’un, henüz kararlı bir işletim sistemi yoktu. Linus Torvalds bu konuda endişeliydi. İyi bir ‘çekirdek’ bulamama konusunda da benzer endişeyi o dönem, GNU işletim sisteminin kurucusu Richard Stallman yaşıyordu. Çünkü GNU’nun Hurd isimli, işlevsiz bir çekirdeği vardı. Linux’un iyi bir işletim sistemine; GNU’nun ise iyi bir çekirdeğe ihtiyacı
vardı. Richard Stallman’ın işletim sistemi olan GNU ve Linus Torvalds’ın çekirdeği Linux birleşti ve GNU/Linux ortaya çıktı. İsmi için yaygın kullanım ‘Linux’ olsa da, doğrusu GNU/Linux’tur.

## **Linux Dağıtımları (Linux Distributions)**
Linux dağıtımı Linux çekirdeği, GNU araçları ve bir masaüstü ortamının bir araya gelmesiyle, bu birlikteliği sürdürülebilir şekilde yönetecek bir yapılandırma araçları seti, yazılım güncelleme araçları vb. ile oluşturularak tam teşekküllü bir işletim sistemi haline gelen uygulamalar bütününü ifade eder.
Dağıtım kavramı, özgür yazılım felsefesinin çok alternatifli dünyasının bir sonucu olarak ortaya çıkmış, Linux'a özgü bir terimdir. 

Yaygınlıkları ve GNU/Linux dünyasına katkılarıyla öne çıkan bazı dağıtımlar vardır: Debian, Ubuntu, Red Hat, Fedora, Linux Mint, openSUSE ve Arch Linux bunlardan birkaçıdır.[[3](https://tr.wikipedia.org/wiki/Linux_da%C4%9F%C4%B1t%C4%B1m%C4%B1)]

Dağıtımlar, hedeflenen kullanım amacına göre ufak farklılıklar
gösterirler. Dosya-dizin yapıları, yükleme paketleri,
uygulamalar, belgeler vs gibi. Ücretli ve ücretsiz de olabilirler.




## **Linux dağıtımlarının kronolojisi**

![alt text](resimler\Linux_Distribution_Timeline.svg)
[[3](https://tr.wikipedia.org/wiki/Linux_da%C4%9F%C4%B1t%C4%B1m%C4%B1)]


## **Masaüstü Ortamları (Desktop Environments)**
 - DE’lar, kullanıcı ile işletim sistemi arasında grafiksel olarak etkileşimi sağlayan tabanlar, yorumlayıcılardır.

 - İşletim sisteminin, amacınıza veya konforunuza uygun halde kullanımını sağlarlar.

 - DE’ların olmadığı distrolarda, işletim sistemi terminalden, komutlarla kullanılmalıdır.

 - Bir tema değildir. Temaları da kapsayan bir grafik arayüz deneyimidir.

 - Distrolar kadar bağımsızdırlar. Herhangibir distro, herhangibir DE kullanabilir.

 - Kurulum sırasında veya sonrasında değiştirilebilir. Açılışta çoktan seçmeli olarak da kullanılabilirler.

 ### Örnek Masaüstü Ortamları

**KDA plasma**

![alt text](resimler\fullscreen_with_apps.png)

**Gnome**

![alt text](resimler\GNOME-44-Desktop.webp)

**Mate**

![alt text](resimler\mate-2.png)