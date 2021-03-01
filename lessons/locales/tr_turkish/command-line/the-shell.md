# Kabuk (Shell)

## Ders İçeriği

Dünya senin istiridyen, ya da gerçekten kabuk senin istiridyen. Kabuk nedir? Kabuk temelde komutlarınızı klavyeden alan ve bunları gerçekleştirmek için işletim sistemine gönderen bir programdır. Daha önce bir GKA(GUI) kullandıysanız, muhtemelen "Terminal" veya "Konsol" gibi programlar görmüşsünüzdür, bunlar yalnızca sizin için bir kabuk başlatan programlardır. Tüm bu kurs boyunca kabuğun harikalarını öğreneceğiz.

Bu kursta, bash (Bourne Again shell) kabuk programını kullanacağız, hemen hemen tüm Linux dağıtımları varsayılan olarak bash kabuğunu kullanır. Ksh, zsh, tsch gibi başka kabuklar da mevcuttur, ancak bunların hiçbirine değinmeyeceğiz.

Hemen başlayalım! Dağıtıma bağlı olarak, kabuk isteminiz değişebilir, ancak çoğunlukla aşağıdaki biçime uymalıdır:
<pre> kullaniciadi@ana_bilgisayaradi:geçerli_dizin
pete@icebox:/home/pete $ </pre>

İstemin sonundaki $ 'a dikkat ettiniz mi? Farklı kabukların farklı komut istemleri olacaktır, bizim durumumuzda $ Bash, Bourne veya Korn, kabuğunu kullanan normal bir kullanıcıyı temsil eder, komutu yazarken istem sembolünü eklemiyorsunuz, sadece orada olduğunu bilin.

Basit bir komut ile başlayalım, echo. echo komutu sadece  metin parametresini ekrana yazdırır. 

<pre>$ echo Merhaba Dünya</pre>

## Alıştırma

Diğer Linux komutlarını deneyin ve çıktılarını görün:

<ol>
<li>$ date</li>
<li>$ whoami</li>
</ol>

## Alıştırma sorusu

echo Merhaba Dünya yazdığınızda ekrana ne yazdırmalıdır?


## Cevap

Merhaba Dünya