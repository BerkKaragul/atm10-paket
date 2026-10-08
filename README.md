# ATM10 Sunucu — oyuncu paketi

All the Mods 10 + sunucudaki ek modlar (Create Aeronautics, sable, Create Deep Seas, Create Jetpack, Create Stuff 'N
Additions, Create Ore Excavation + Better Finder, Terralith). Prism Launcher her oyun açılışında bu listeyle modları
eşitler; sunucu güncellenince oyun da kendiliğinden güncellenir.

## Kurulum (Prism Launcher)

1. Prism → **Add Instance** → **Import** → şu adresi yapıştır → OK:
   `https://github.com/BerkKaragul/atm10-paket/releases/latest/download/ATM10-Sunucu.zip`
2. **Launch**. İlk açılışta ~490 mod iner (birkaç dakika), sonra oyun açılır.
3. Multiplayer'da **ATM10 Sunucu** hazır.

Bellek 10 GB ayarlı; bilgisayarında az RAM varsa Edit → Settings → Java'dan düşür (en az 8 GB önerilir).

NeoForge sürümü değişen bir güncellemede açılışta "güncelle" penceresi çıkar → onayla, sonra bir kez daha Launch.

Kendi eklediğin modlara (harita, shader vb.) dokunulmaz.

## Eski ATM10 kurulumun varsa

Eskisini dönüştürme, yukarıdaki gibi yeni kur (dünya sunucuda, kaybolan bir şey yok). İstersen eski ayarlarını taşı —
**yeni kurulumu bir kez açıp kapattıktan sonra**, Prism'de eski kuruluma sağ tık → **Folder**, yenisine sağ tık →
**Folder**, şunları eskiden yeniye kopyala (sor derse "üzerine yaz"):

| Ne | Neyi taşır |
|---|---|
| `options.txt` | tuş atamaları, ses, grafik ayarları |
| `journeymap` klasörü | harita + waypoint'ler |
| `shaderpacks` klasörü ve `config\iris.properties` | shader'lar ve seçili shader |
| `schematics` klasörü | Create şemaları |

Sonra eski kurulumu silebilirsin.
