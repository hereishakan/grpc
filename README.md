# gRPC - Bir RPC kitaplığı ve çerçevesi

gRPC, modern, açık kaynaklı, yüksek performanslı bir uzaktan yordam çağrısıdır (RPC)
her yerde çalışabilen bir çerçeve. gRPC, istemci ve sunucu uygulamalarının
şeffaf iletişim kurar ve bağlı sistemlerin oluşturulmasını basitleştirir.

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

[![Sohbete katılın https://gitter.im/grpc/grpc](https://badges.gitter.im/grpc/grpc.svg)](https://gitter.im/grpc/grpc?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

## gRPC kullanmaya başlamak için

Kullanılabilirliği en üst düzeye çıkarmak için gRPC, bağımlılıklar eklemek için standart yöntemi destekler
kullanıcının seçtiği dile (varsa). Çoğu dilde, gRPC
çalışma zamanı, kullanıcının dil paket yöneticisinde bulunan bir paket olarak gelir.

Bir proje için dile özgü gRPC çalışma zamanının nasıl kullanılacağına ilişkin yönergeler için,
lütfen bu belgelere bakın

- [C ++] (src / cpp): `src / cpp' dizini altındaki talimatları izleyin
- [C#/.NET](https://github.com/grpc/grpc-dotnet ): NuGet paketleri `Grpc.Net.Client`, `Grpc.Ağ çekirdeği.Hizmetçi`
- [Dart](https://github.com/grpc/grpc-dart ): pub paketi 'grpc`
- [Git](https://github.com/grpc/grpc-go ): 'git al google.golang.org/grpc `
- [Java](https://github.com/grpc/grpc-java ): Maven Central'dan Kavanozlar kullanın
  Depo
- [Kotlin](https://github.com/grpc/grpc-kotlin ): Maven Central'dan Kavanozlar kullanın
  Depo
- [Düğüm](https://github.com/grpc/grpc-node ): 'npm kurulumu @grpc / grpc-js`
- [Objective-C] (src / objective-c): Podspec'e `gRPC-ProtoRPC` bağımlılığı ekleyin
- [PHP](src/ php): `pecl grpc'yi yükle'
- [Python](src / python / grpcıo): `pip grpcio'yu yükle'
- [Ruby] (src / ruby): `gem kurulum grpc'si'
- [Webj'ler](https://github.com/grpc/grpc-web ): grpc-web talimatlarını izleyin

Dil başına hızlı başlangıç kılavuzları ve öğreticiler şu adreste bulunabilir:
[dokümantasyon bölümü grpc.io web sitesi](https://grpc.io/docs /). Kod
örnekler [örnekler] (örnekler) dizininde mevcuttur.

gRPC 'ana' dalının 'KAFASININ' önceden derlenmiş kanama kenarı paketi yapıları şunlardır
her gün yükleniyor [packages.grpc.io ](https://packages.grpc.io ).

## gRPC geliştirmeye başlamak için

Katkıları bekliyoruz!

Lütfen okuyun [Nasıl katkıda bulunulur](CONTRIBUTING.md ) size yol gösterecek olan
kaynak kodun nasıl oluşturulacağına, testlerin nasıl çalıştırılacağına dair tüm iş akışı ve
gRPC kod tabanındaki değişikliklere nasıl katkıda bulunulur. "Nasıl katkıda bulunulur" belgesi
ayrıca katkı sürecinin nasıl çalıştığı hakkında bilgi içerir ve en iyisini içerir
katkı yaratma uygulamaları.

## Arıza

Bazen işler ters gider. Lütfen kontrol edin
[Sorun giderme kılavuzu] (TROUBLESHOOTING.md ) ile ilgili sorunlar yaşıyorsanız
gRPC.

## Performans

Bakın
[Performans kontrol paneli](https://grafana-dot-grpc-testing.appspot.com /)
günlük ana dal yapılarının performans sayıları için.

## Kavramalar

Bkz. [gRPC Kavramları] (CONCEPTS.md )

## Bu Depo Hakkında

Bu depo, birden çok uygulamada uygulanan gRPC kitaplıkları için kaynak kodu içerir
paylaşılan bir C çekirdek kitaplığının [src / core] (src / core) üzerine yazılmış diller.

Farklı dillerdeki kütüphaneler çeşitli gelişim durumlarında olabilir. Biz
tüm bu kütüphanelere katkı sağlamak:

/ Dil / Kaynak |
| ----------------------- | ---------------------------------- |
/ Paylaşılan C [çekirdek kitaplığı] / [src / çekirdek] (src | çekirdek) /
| C++ | [src/cpp](src/cpp) |
/ Yakut | [src/yakut](src/yakut) |
/ Python / [src/python](src/python) |
| PHP / [src/php](src/php) |
| C # (temel kitaplık tabanlı) | [src/csharp] (src/csharp) |
/ Amaç-C / [src/amaç-c] (src/amaç-c) |

/ Dil / Kaynak repo |
| -------------------- | -------------------------------------------------- |
| Java / [grpc-java](https://github.com/grpc/grpc-java ) |
/ Kotlin | [grpc-kotlin](https://github.com/grpc/grpc-kotlin ) |
| Git / [grpc-git](https://github.com/grpc/grpc-go ) |
| NodeJS / [grpc düğümü](https://github.com/grpc/grpc-node ) |
| WebJS | [grpc-web](https://github.com/grpc/grpc-web ) |
/ Dart / [grpc-dart](https://github.com/grpc/grpc-dart ) |
| .NET (saf C # impl.) / [grpc-dotnet](https://github.com/grpc/grpc-dotnet ) |
| Hızlı | [grpc-hızlı](https://github.com/grpc/grpc-swift ) |
