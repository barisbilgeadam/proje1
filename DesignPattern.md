## Design Pattern
* Tasarım Desenleri, Tasarım Kalıpları, Tasarım Örüntüleri
* GoF Pattern 
* Gang of Four
* 23 Tane Design Pattern.
* Ezbere bilmenize gerek yok. 
* Kullanacağımız frameworkler arka planda sıklıkla design patternlar kullanılarak yazılmışlardır. Spring, Hibernate...
* Bu konu Java konusu değil. Herhangi bir dil ile ilgili değil.

### Singleton
* Bir sınıftan bir tane nesne üretilmesini garanti altına almak.
* Neden tek nesne üretilmesini isteyelim?
  1. Bellek Verimliliğini sağlamak için
  2. Performans sorunlarını azaltmak için
  3. Maliyeti azaltmak için
// Urun u1=new Urun(101,"Kalem",20.25);
// db.save(u1);
// u1=new Urun(101,"Silgi",20.25);
// db.save(u1);
// u1=new Urun(101,"Kitap",20.25);
// db.save(u1);

### Factory
* Fabrika
* Nesne üretme fabrikası
* Genişletilebilirliği sağlar.
* Bağımlılıklardan kaçınmayı sağlar.
* Nesnenin nasıl oluşturulduğu kısmı gizlenir.

#### Adımlar:
* Enum yazılabilir.
* Interface / Abstract Class yazılabilir.
* Alt sınıflar yazılmalı.
* Factory Sınıfı yazılacak. Genellikle içinde bir switch case yapısı olacak.
* Runnerda factory sınıftan nesne isteyeceğiz.
