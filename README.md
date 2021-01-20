## MongoDB Nedir ?

![enter image description here](https://nakedsecurity.sophos.com/wp-content/uploads/sites/2/2017/01/mongodb.png?w=775)

Merhaba MongoDB öğrenirken bu şekilde bir repo açıp notlarımı buraya almak istedim. Bu sayede hem şahsım hem MongoDB öğrenmek isteyen arkadaşlarımıza yol göstermeyi amaçladım. Sözü fazla uzatmadan notlarımıza geçelim.

## NoSQL Nedir ?
MongoDB kavramından önce NoSQL kavramından bahsetmekte yarar var. Teknolojinin ilerlemesi ve verilerin büyük boyutlara ulaşması sebebiyle halihazırda kullanılan ilişkisel veritabanları yerine daha yenilikçi bir çözüm olarak NoSQL veritabanı sistemleri getirilmiştir. SQl veritabanlarının yapısı, tablolar, satırlar ve sütünlardan oluşurken NoSQL veritabanlarının yapısı Json tipindedir.
![enter image description here](https://omerdemirarslan.com/wp-content/uploads/2020/03/MONGODBSQLFARK.jpg)

NoSQL veritabanlarının avantajlarından bir tanesi performansdır. İlişkisel veritabanına kıyasla NoSQL veritabalarında okuma ve yazma işlemleri daha hızlıdır. NoSQL veritabanı yatay olarak ölçeklendirilebilir ve bu sayede birden çok sunucu kullanılarak hacimsel olarak büyük veriler üzerinde işlemler yapılabilir.

NoSQL veritabanı sistemlerinde verilere erişmek ve yönetmek için veri modelleri kullanılır. NoSQL veritabanları düşük tepkime süreleri, büyük veri hacmi ve esnek veri modelleri gerektiren uygulamalarda kullanılır.

Peki NoSQL adının anlamı nedir ? bunu benim bir zamanlar merak ettiğim gibi sizinde merak ettiğinizi düşünüyorum. Kısaca **NoSQL, veri modelinin ilişkisel olduğu ve sorgu dilininin SQL olmadığında kullanılan bir terimdir.** oldukça manidar değil mi ?

**NoSQL** veritabanı sistemleri yapılarına göre gruplara ayrılır.
![enter image description here](https://dist.neo4j.com/wp-content/uploads/20181127035440/nosql-database-technologies-quadrant.png)

**Döküman tabanlı** : Bu yapıda veriler döküman olarak saklanır. Bkz. MongoDB, CouchDB

**Anahtar / Değer tabanlı** : Bu yapıda veriler anahtar değer ikisi olarak saklanırlar. Bkz. Redis, Memcached

**Grafik Tabanlı** : Bu yapıda veriler çizgi (graf) düğüm şeklinde birbirlerine bağlı şekilde saklanırlar. Bkz. ArongoDB.

**Sütun Tabanlı** : Bu yapıda veriler satırlar yerine sütunlarda saklanır. Bkz. Cassandra,Hbase.


## MongoDB Tarihi

**MongoDB** 2009 yılında **MongoDB** Inc. tarafından yayımlanan bir **NoSQL** veritabanı çözümüdür. **MongoDB** C++ programlama dili ile geliştirilmiştir.  **MongoDB** veritabanında veriler Json tipinde saklanmaktadır. **MongoDB**, veri hacmi yüksek ve **RDMS** (ilişkisel veritabanı) sistemlerinin hantal kaldığı ve yetemediği sistemlerde kullanılmaktadır. **MongoDB**, GNU Affero Genel Kamu Lisansı ile yayınlanan ücretsiz ve açık kaynak bir **NoSQL** veritabanı sistemidir.
