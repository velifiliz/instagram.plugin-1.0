<snippet>
  <content><![CDATA[
# ${1:Project Name}

.NET ile Yazdığınız Projelerinizde Instagram İşlemlerinizi Yapmak İçin Kullanabileceğiniz Instagram Api'si.

## Kurulum

İndirdiğiniz Instagram Dll Dosyasını Projenize Dahil Ediniz.

## Kullanım
 
            plugin.Instagram i = new plugin.Instagram();
            i.username = "xxxxxx"; // instagram kullanıcı adınız
            i.password = "xxxxxx"; // instagram şifreniz
            i.imagepath = "C:\\1.jpg"; // resim yolunuz
            i.text = "merhaba - @username - #hashtag"; // kişi etiketi,hashtag veya metin hepsini paylaşabilirsiniz
            i.Send(i); 
            
## NOTLAR
