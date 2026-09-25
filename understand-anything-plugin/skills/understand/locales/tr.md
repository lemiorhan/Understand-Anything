# Türkçe Çıktı Rehberi (Turkish)

Bu dosya, bilgi grafı içeriğini Türkçe üretirken uyulacak dil kurallarını içerir.

## Etiket Kuralları

Türkçe etiketler ya da yerleşmiş İngilizce teknik terimler kullan:

| Kalıp | Önerilen etiketler |
|-------|--------------------|
| Giriş noktası | `giriş-noktası`, `barrel`, `exports` veya `entry-point` |
| Yardımcı fonksiyonlar | `yardımcılar`, `helpers`, `common` veya `utility` |
| API handler'ları | `api-handler`, `controller`, `endpoint` |
| Veri modelleri | `veri-modeli`, `entity`, `schema` veya `data-model` |
| Test dosyaları | `testler`, `unit-test`, `test` |
| Konfigürasyon dosyaları | `konfigürasyon`, `build-system`, `settings` veya `configuration` |
| Altyapı | `altyapı`, `deployment`, `container` veya `infrastructure` |
| Dokümantasyon | `dokümantasyon`, `rehber`, `documentation` |

**Karma strateji:** Türk geliştiricinin günlük konuşmada İngilizce kullandığı terimler İngilizce kalır (örneğin `middleware`, `api-handler`, `controller`). Tanımlayıcı etiketler Türkçe yazılabilir.

## Özet Stili

Özetleri Türkçe, 1–2 cümle olarak yaz:
- Dosyanın **amacını** ve **rolünü** anlat
- Etken çatı ve geniş zaman kullan ("sağlar…", "işler…", "yönetir…")
- Dosya adını tekrar etme
- İngilizce terimlere Türkçe ek kesme işaretiyle eklenir: "middleware'i", "endpoint'ler", "cache'ten"

**Örnekler:**
- İyi: "Tarih biçimlendirme ve string temizleme için yardımcı fonksiyonlar sağlar; API katmanında yaygın olarak kullanılır."
- Kötü: "utils dosyası yardımcı fonksiyonlar içerir."

## Teknik Terimler

Aşağıdaki terimler İngilizce kalır (yerleşmiş Türkçe karşılıkları yok ya da geliştiriciler kullanmıyor):
- `middleware`, `hook`, `barrel`, `entry-point`
- `ORM`, `REST API`, `CI/CD`, `CRUD`
- `singleton`, `factory`, `observer`
- `interceptor`, `guard`
- `endpoint`, `handler`, `controller`, `repository`, `cache`, `deploy`

## Katman Adları

Türkçe katman adları kullan:
- `API katmanı`, `servis katmanı`, `veri katmanı`, `UI katmanı`
- `altyapı`, `konfigürasyon`, `dokümantasyon`
- `yardımcı katman`, `middleware katmanı`, `test katmanı`

Ya da İngilizce bırak (ekibin tercihine göre):
- `API Layer`, `Service Layer`, `Data Layer`
