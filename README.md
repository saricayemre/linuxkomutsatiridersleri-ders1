## Ders 1 | Yardım Alma Komutları

# Giriş

Linux işletim sistemlerinin komut satırında diğer komutların icrası ile ilgili çok güçlü ve çok güzel bir yardım alma sistemi vardır. Komut satırında kullanacağımız bir komutun opsiyonları ve parametreleri ile ilgili veya bir uygulamanın nasıl kullanılacağı hakkında geniş bir yazılı döküman anlatımı vardır. Linux sistemlerde kurulu veya kurulacak olan programlar genellikle yardım dökünamlarıyla birlikte gelir. Komutları kullanırken yardım alabileceğimiz bazı seçenekler mevcuttur. Bunları kullanarak Linux'un kendine ait anlatımıyla takıldığınız komutta veya programda çözüm bulabilirisiniz.

## help

Linux komut satırında bir komut veya bir programın nasıl kullanılacağı hakkında bilgi almak için `help` komutunu kullanabiliriz. Bu komutun kullanım kalıbı; `<komut_adı> --help` şu şekildedir. Örneğin; daha sonra değinilecek olan `ls` komutu hakkında yardım alamak için komut satırına, `ls --help` komutu girildiğinde terminalde aşağıdaki gösrelde görüldüğü gibi bir bilgi ekranı gelecektir. 

![help-img1](https://github.com/saricayemre/linuxkomutsatiridersleri-ders1/blob/main/resim/help-img1.png)

`help` komutu ile bu şekilde yardım alınabilgiği gibi `help <komut_adı>` şeklinde de kullanımı mevcuttur.

 ![help-img2](https://github.com/saricayemre/linuxkomutsatiridersleri-ders1/blob/main/resim/help-img2.png)

Fakat her komut kullanımı için bu uygun olmayabilir. Örneğin `ls --help` şeklinde kullandığımızda işe yaradı fakat tersi şeklinde kullanıldığında işe yaramadığı görülüyor.

 ![help-img3](https://github.com/saricayemre/linuxkomutsatiridersleri-ders1/blob/main/resim/help-img3.png)

## whatis

Terminalde kullanıcıya yardımcı olan diğer komutlardan biride `whatis` komutudur. Bu komutu kullandığımızda bize komutun hangi kılavuz sayfasında olduğunu ve ne işe yaradığını gösterecektir. 

 ![whatis-img1](https://github.com/saricayemre/linuxkomutsatiridersleri-ders1/blob/main/resim/whatis-img1.png)

## apropos

Yardım almak için kullanılan başka bir komut ise `apropos` komutudur. Aslında bu komut arka planda `man -k` komutunu çalıştırır. 

 ![apropos-img1](https://github.com/saricayemre/linuxkomutsatiridersleri-ders1/blob/main/resim/apropos-img1.png)

Komut çıktısını incelediğimizde, `printf` ifadesinin geçtiği uygulamaların listesini de görmüş oluyoruz. 

## Sonuç

Bu komutlar genellikle bir program veya komutu kullanmadan önce hata yapmamak veya nasıl kullanıldığına dair net bilgiye kolayca ulaşabilmek için kullanılır. Her Linux kullanıcısı bu işe başlamadan önce bu komutların tozunu yutmuştur. Bir süre sonra bu komutlar unutulmaya yüz tutuyor ama başımız her sıkıştığında başvurabiliriz. Ayrıca bizi hiç terslemeyecektir. 

[< Önceki Sayfa](https://saricayemre.github.io/linuxkomutsatiridersleri/) | [Sonraki Sayfa >](https://saricayemre.github.io/linuxkomutsatiridersleri-ders2/)
