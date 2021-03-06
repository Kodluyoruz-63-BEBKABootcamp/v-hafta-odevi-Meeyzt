# v-hafta-odevi

# DEVELOPER SUMMIT 2020'deki yazılım konferanslarından ilginizi çekenlerin özetlerini çıkarmaya çalışınız.
 * dev.not un düzenlemiş olduğu DEVELOPER SUMMIT 2020 Etkinliğine dair youtube da sadece 1 tane video bulabildim onu da buraya bırakıyorum. Çok ilgimi çekmediği için de özetini çıkartamadım. [Developper Summit 2020 Erhan Yakut "Bir Saas ürünü hayata geçirmek" (Youtube)](https://www.youtube.com/watch?v=cqULp5aYDiE&list=PLhXBUthqwNDDELRdhF86ylssTSEZ28FUv)

## SQLite ve LocalDB kabramlarını karşılaştırınız.

 * **Sqlite**, bir veritabanı kütüphanesidir. Kullanımı ve kurulumu oldukça kolaydır. Kullanmak için kurulum yapmanızı gerektirmez. Herhangi bir kurulum prosedürü yoktur. Kullanmak için herhangi bir sunucu işlemini başlatmak, durdurmak ya da yapılandırmak gerekmez. Sqlite kullanımı için bir yöneticinin yeni bir veritabanı örneği oluşturmasına veya kullanıcılara erişim izni vermesine gerek yoktur. Bir sistem çökmesi ya da elektrik kesintisinden sonra kurtarmak için herhangi bir eylem gerektirmez. Sadece çalışır. Hayat kolaylaştıran bir uygulamadır.
 * Sqlite disk dosyasını okuyabiliyorsa, veritabanında bulunan herhangi bir şeyi de okuyabilir. Disk dosyası ve dizini yazılabilir durumda ise, bu programı kullanarak veritabanındaki her şeyi değiştirebilirsiniz. Veritabanı dosyalarını bir USB’ye kopyalayabilir ya da e-posta ile paylaşabilirsiniz. Dosyalara erişmek son derece kolaydır. Elbette tüm bu işlemleri kolay ve hızlı bir şekilde yaparken verilerin güvenliğini sağlamak da son derece önemlidir.
 * Sqlite, dosya biçimli bir çapraz platformdur. Bu sayede bir cihazda yazılmış olan bir veritabanı dosyası, farklı bir mimariye sahip olan farklı bir cihaza kopyalanabilir ve bu cihazda kullanılabilir. Diğer veritabanı motorlarının bir platformdan diğerine geçerken, veritabanınızı dökmenizi ve yeniden yüklemenizi gerektirdiği düşünülürse, Sqlite’in işleri ne kadar kolaylaştırdığı daha iyi anlaşılabilir. Ayrıca dosya formatları sabittir ve geriye dönük olarak da uyumludur.
 * Sqlite kaynak kodları okunabilir durumdadır. Standart programlar tarafından erişilebilir ve okunabilir olacak şekilde tasarlanmıştır. Ayrıca Sqlite için kaynak kodları kamu malıdır. Herkes erişebilir ve okuyabilir. Çekirdek kaynak kodunun hiçbir bölümünde telif hakkı talep edilmez. Yazılıma katkıda bulunan tüm kullanıcılar, kaynak kodlarını kullanabilir. Kod geniş bir kitle tarafından özgürce kullanılabilir. Dil uzantıları da bu kodların herkes tarafından rahatlıkla erişilebilmesine ve okunabilmesine imkan tanır. Tüm bunlar, Sqlite’i programcılar tarafından kısa süre içinde oldukça popüler hale getirmiştir. Güvenlik konusu düzgün yönetildiği sürece hayat kolaylaştıran bir yazılımdır.  
 
 * **LocalDB**, Geliştiricilen uğraştıkları uygulamaları daha rahat test edebilmek için kendi bilgisayarlarına kurarak kullandıkları veritabanı tipidir. Genelde geleneksel CRUD işlemleri için kullanılır.Bellekte çok yer kaplamaz.
 
 
 ## Lazy Loading kavramı hakkında temel bir araştırma yapınız.
* Lazy Loading ( eşzamansız yükleme olarak da bilinir ), bilgisayar programlamasında ve çoğunlukla bir nesnenin başlatılmasını ihtiyaç duyulduğu noktaya kadar ertelemek için web tasarımı ve geliştirmede yaygın olarak kullanılan bir tasarım modelidir . Düzgün ve uygun şekilde kullanılırsa, programın işleyişinde verimliliğe katkıda bulunabilir. Bu, ağ içeriğine erişildiği ve web sayfalarında olduğu gibi başlatma sürelerinin minimumda tutulduğu kullanım durumlarında idealdir . Lazy Loading'in tersi, eager loading'dir . Tembel Yükleme, web sayfalarının daha hızlı yüklenmesini sağlamak için yalnızca ihtiyaç duyulduğunda görünmelerini sağlamak için web'deki görsellerde büyük ölçüde kullanılır.

* Lazy Loading kullanılan bir c# örneğinde öncelikle yaratmak istediğimiz nesneyi get methodu dışında ```c# null``` olarak tanımlarız. Get methodu çağırıldığında ```c# null``` kontrolü yaptırıp nesneyi oluştururuz.
 
