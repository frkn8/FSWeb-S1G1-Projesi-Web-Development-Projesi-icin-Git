## Araştırma Soruları

Şimdi görevi gerçekleştirmek için hazırsınız. Şimdi biraz daha kullandığımız araçları anlama zamanı. Bu dokümanı güncelleyerek, aşağıdaki soruları cevaplayınız. Git'e biraz daha aşina olmaya başladığınızı göreceksiniz. 

Soruları cevaplamak için [GitHub docs](https://docs.github.com/en)'u kullanabilirsiniz. Docs, (ingilizce documentation'ın kısaltılmış halidir) bir programı veya dilin nasıl kullanılacağını anlatan dokümandır. Yazılım dünyasında sıkça kullanılır. Bir yazılımcı olarak zamanınızın büyük çoğunluğu da bu tarz dokümanları okumakla ve üzerinde çalışmakla geçer.

Eğer aradığınız soruların cevapları GitHub docs'ta yok ise Google'lama becerileriniz size yardımcı olacaktır :)

1. Git nedir?
-Hazırladığımız projeleri ve uygulamaları bilgisayarımızda değilde internet üzerinde tutmamızı ve yönetmemizi sağlayan bir versiyon kontrol sistemidir.
2. Git ile GitHub arasında ne fark var?
-Git, bir versiyon takip yazılımıdır. Lokal olarak bilgisayarda çalışır. Git ile projelreinizin versiyonlamasını yapabilir ve bunu internete bile bağlanmadan kullanabilirsiniz. Herhangi bir kayıt işlemine ihtiyaç duymaz. Github'a kayıt olmanız gereklidir ve ek fayda olarak da başka kişilerin repository'lerine erişebilir ya da kendi repository'lerinize erişmelerini ve katkı sağlamalarını isteyebilirsiniz.
3. Neden bir branch oluşturuyoruz? 
-Projenin farklı versiyonlarına erişmemizi sağlar. Kullanıcı projesine bir yenilik eklemek istediğinde yaptığı değişiklik projeyi olumsuz etkileyebilir. Bu gibi durumlarda projemizi bozmamak için branchı kullanırız.
4. Pull Request'in amacı nedir?
-Pull request talebi, temelde branch'dan sorumlu kişiden kodunuzu eklemesini istemektir. Ayrıca o kişinin kodda tam olarak neyi değiştirdiğinizi görmesine de yardımcı olur.
5. Bir Branchten diğerine geçmek için kullanıdığımız KOMUT nedir? Örneğin ADINIZ-SOYADINIZ branch'inde çalıştığınızı hayal edin ve main branch'ine geçmek istiyorsunuz.
- Checkout 
6. `git fetch`, `git merge` ve `git pull` arasındaki farklıarı açıklayınız. Bu konutlar ne yapar açıklayınız.
-Git fetch, yerel depomu uzaktaki deponun içeriğine güncelle anlamına gelir. Git merge, herhangi bir brach'de yaptığımız değişiklikleri master branch'imiz ile birleştirme veya master branch'e entegre etme işlemidir. Git pull, uzak sunucudaki değişiklikleri çalışma dizininize getirir ve birleştirir.
7. Merge conflict nedir?
- İki kişi aynı dosyayı ve aynı satırı değiştirirse ve git otomatik olarak merge edemezse bu durumda conflict yani çakışma olacaktır. Bu durumda çakışma yaşayan kişi gerekirse ekipteki diğer kişi ile beraber oturup çakışmayı çözdükten sonra merge işlemine devam etmelidir.
8. Merge conflict'i nasıl çözeriz?
-Konfigürasyon ayarı yapmak gerekiyor