# DbisTAKİP Veritabanı ve Tablolar

Bu repository, DbisTAKİP adında bir SQL Server veritabanı ve ilgili tabloları içermektedir. Bu veritabanı, bir iş takip sistemini desteklemek amacıyla tasarlanmıştır.

## Veritabanı Oluşturma ve Konfigürasyon

1. SQL Server Management Studio (SSMS) veya tercih ettiğiniz bir SQL sorgu aracı kullanarak SQL Server'a bağlanın.

2. `script.sql` dosyasını açın.

3. Tüm script'i çalıştırarak "DbisTAKİP" veritabanını oluşturun ve aşağıdaki konfigürasyon ayarlarını uygulayın:

   - Veritabanı ismi: DbisTAKİP
   - Diğer konfigürasyon ayarları (Script içinde detaylı olarak belirtilmiştir)

4. Script içindeki tüm tablolar ve ilişkiler oluşturulduktan sonra, iş takip sisteminizi kullanmaya başlayabilirsiniz.

## Tablolar ve Amaçları

1. **tblCagriDetay:** Çağrı detaylarını içeren tablo.
2. **tblCagrilar:** Çağrıları yöneten ana tablo.
3. **tblDepartmanlar:** Personel departmanlarını içeren tablo.
4. **tblFirmalar:** Firmaları ve ilişkili bilgileri içeren tablo.
5. **tblGorevDetaylar:** Görev detaylarını içeren tablo.
6. **tblGorevler:** Görevleri yöneten ana tablo.
7. **tblMesajlar:** Mesajları içeren tablo.
8. **tblPersonel:** Personel bilgilerini içeren tablo.

## Bağlantı Ayarları ve Kullanım

- Veritabanına bağlanmak için kullanıcı adı, şifre ve diğer bağlantı ayarlarınızı güncelleyin.
- İlk kez kullanıyorsanız, `tblFirmalar` tablosuna firmalarınızı ekleyerek iş takip sistemine başlayabilirsiniz.

## Dikkat Edilmesi Gereken Noktalar

- Script içindeki kullanıcı adları, şifreler veya diğer hassas bilgileri paylaşmamaya özen gösterin.
- Proje hakkında daha fazla bilgi almak için [LICENSE](LICENSE) dosyasını inceleyin.

Bu repository, DbisTAKİP veritabanının şemasını oluşturmak ve kullanmak isteyen geliştiricilere yönelik bir başlangıç ​​noktasıdır. Daha fazla bilgi için [CONTRIBUTING.md](CONTRIBUTING.md) dosyasını da inceleyebilirsiniz.

