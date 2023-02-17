#  gRPC - Bir RPC kitaplığı ve çerçevesi
 
gRPC, modern, açık kaynaklı, yüksek aktarım bir uzak yordam iletimdir (RPC)
her yerde çalışabilen bir çerçeve. gRPC, gözetim ve sunucu uygulamalarının
şeffaf iletişim kurar ve bağlı sistemlerin kütüphanesini basitleştirir.
 
<Tablo>
<tr>
<td><b>Ana Sayfa:</b></td>
<td><a href="https://grpc.io /">grpc.io </a></td>
</tr>
<tr>
<td><b>Posta Listesi:</b></td>
<td><a href="https://groups.google.com/forum /#!forum/grpc-ıo">grpc-io@googlegroups.com </a></td>
</tr>
</Tablo>
 
[![ Sohbete katıl https://gitter.im/grpc/grpc ](https://badges.gitter.im/grpc/grpc.svg)](https://gitter.im/grpc/grpc?utm_source= badge&utm_medium=rozet&utm_campaign=pr-rozeti&utm_content=rozet)
 
##  gRPC kullanmaya başlamak için
 
Kullanılabilirliği en üst düzeye çıkarmak için gRPC, kötüye kullanımlardan yararlanmak için standart yönteme geçildi
kullanıcı bilgisayarı dile (varsa). Çoğu dilde, gRPC
Çalışma zamanı, kullanıcıların dil paket yöneticisinde bulunan bir paket olarak gelir.
 
Bir proje için dile sahip gRPC çalışma zamanının nasıl yönlendiricilere bağlı olarak yönlendiriciler için,
lütfen bu belgelere bakın
 
- [C ++] (src / cpp): `src / cpp' dizini verilerini talimatları izleyin
- [C#/.NET](https://github.com/grpc/grpc-dotnet ): NuGet konteynerleri ` Grpc.Net.Client `, ` Grpc.Ağ kiti.Hizmetçi`
- [ Dart ](https://github.com/grpc/grpc-dart ): pub paketi 'grpc'
- [ Git ](https://github.com/grpc/grpc-go ): 'git al google.golang.org/grpc `
- [ Java ](https://github.com/grpc/grpc-java ): Maven Central'dan Kavanozlar kullanın
depo
- [ Kotlin ](https://github.com/grpc/grpc-kotlin ): Maven Central'dan Kavanozlar kullanın
depo
- [ Düğüm ](https://github.com/grpc/grpc-node ): 'npm kurulum @ grpc / grpc-js`
- [Objective-C] (src / Objective-c): Podspec'e `gRPC-ProtoRPC` ekleme ekleyin
- [ PHP ](src/ php): `pecl grpc'yi yükle'
- [Python](src / python / grpcıo): ` pip grpcio'yu yükle'
- [Ruby] (src / ruby): `gem kurulum grpc'si'
- [Webj'ler](https://github.com/grpc/grpc-web ): grpc-web yönergelerini izleyin
Dil başına hızlı başlangıç ​​kılavuzları ve eğiticiler şu adreste bulunabilir:
[dokümantasyon bölümü grpc.io web sitesi](https://grpc.io/docs /). Kod
Tablolar [örnekler] (örnekler) dizininde mevcuttur.
gRPC 'ana' dalının 'KAFASININ' ölçeğinde derlenmiş damar kenarı paketi yapı organları
her gün yükleniyor [packages.grpc.io ](https://packages.grpc.io ).
## gRPC yolcularına başlamak için
Katkıları karşılandı!
Lütfen okuyun [Nasıl bir katkıda bulunulur](CONTRIBUTING.md ) size yol gösteren olan
kaynak kodunun nasıl oluşturulacağına, testlerin nasıl çalıştırılacağına dair tüm iş paketlerini ve
gRPC kod tabanındaki değişikliklere nasıl yayılıyor. "Nasıl davet edilmeur" belgesi
Ayrıca katkıları nasıl yaptığı hakkında bilgi içerir ve en içindekileri içerir
yaratma yaratma uygulamaları.
## Arıza
Bazen işler ters gider. Lütfen kontrol edin
[Sorun giderme kılavuzu] (TROUBLESHOOTING.md ) ile ilgili sorunları evine
gRPC.
## performans
Bakın
[Performans kontrol paneli](https://grafana-dot-grpc-testing.appspot.com /)
Günlük ana dal yapılarının performansı için.
## Kavramalar
Bkz. [gRPC Kavramları] (CONCEPTS.md )
## Bu Depo Hakkında
Bu depo, birden çok veritabanında uygulanan gRPC kitaplıkları için kaynak kodunu içerir
Kullanıcı bir C özelliği kitaplığının [src / core] (src / core) üzerine yazılan diller.
Farklı dillerdeki kütüphaneler çeşitli gelişim durumlarında olabilir. Biz
tüm bu kütüphanelere katkı sağlamak:
/ Dil / Kaynak |
| ----------------------- | ---------------------------------- |
/ Paylaşılan C [çekirdek kitaplığı] / [src / fayda] (src | fayda) /
| C++ | [kaynak/cpp](kaynak/cpp) |
/ Yakut | [src/yakut](src/yakut) |
/ Python / [src/python](src/python) |
| PHP / [kaynak/php](kaynak/php) |
| C# (temel kitaplık tabanlı) | [kaynak/csharp] (kaynak/csharp) |
/ Amaç-C / [kaynak/amaç-c] (kaynak/amaç-c) |
/ Dil / Kaynak deposu |
| -------------------- | -------------------------------------------------- |
| Java / [grpc-java](https://github.com/grpc/grpc-java ) |
/ Kotlin | [grpc-kotlin](https://github.com/grpc/grpc-kotlin ) |
| Git / [grpc-git](https://github.com/grpc/grpc-go ) |
| NodeJS / [grpc düğümü](https://github.com/grpc/grpc-node ) |
| WebJS | [grpc-web](https://github.com/grpc/grpc-web ) |
/ Dart / [grpc-dart](https://github.com/grpc/grpc-dart ) |
| .NET (saf C# impl.) / [grpc-dotnet](https://github.com/grpc/grpc-dotnet ) |
| Hızlı | [grpc-hızlı](https://github.com/grpc/grpc-swift ) |
