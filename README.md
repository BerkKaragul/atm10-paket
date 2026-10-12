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

## Paketteki bir modu istemiyorsan

Prism → kuruluma sağ tık → **Edit** → **Mods** → modun tikini kaldır (disable). Kapalı kalır, güncellemelerde de kapalı
gelir. Geri açmak için tiki yeniden koy. Modun jar dosyasını sildiysen bir sonraki açılışta mod geri iner ama **kapalı**
gelir. Sunucuda da olan bir modu kapatırsan sunucuya giremeyebilirsin; o zaman yeniden aç.

## Haritam (JourneyMap) boş görünüyor

JourneyMap haritayı ve waypoint'leri sunucu listesindeki **ada** göre saklar. Eski kurulumda sunucunun adı başka olduğu
için harita eski adın altında kalmıştı. Açılışta eski adla duran harita ve waypoint'ler bir kez "ATM10 Sunucu"ya
kopyalanır; büyük haritalarda bu ilk açılış biraz uzun sürer.

## Bu sayfadan önce kurduysan (bir kerelik)

Başlatıcı yenilendi. Kurulumun `minecraft` klasöründeki (Prism → sağ tık → **Folder**) `atm10-baslat.jar`'ı
[buradaki](https://github.com/BerkKaragul/atm10-paket/releases/download/kurulum/atm10-baslat.jar) dosyayla değiştir.
Sonrasında hiçbir şey yapman gerekmez.

## Eski ATM10 kurulumun varsa

Hiçbir şey yapma. Yeni kurulum ilk açılışta Prism'deki eski ATM10 kurulumunu kendisi bulur ve şunları kopyalar:
kendi eklediğin modlar (paketteki modların başka sürümleri hariç), `options.txt` (tuşlar, ayarlar), JourneyMap haritası ve
waypoint'ler, shader'lar ve seçili shader, resource pack'ler, Create şemaları. Ne taşındığı yeni kurulumun klasöründe
`atm10-tasima.txt`'de yazar. Eski kurulum olduğu gibi kalır; her şey yerindeyse silebilirsin.

Windows, Linux ve Mac'te aynı çalışır (Prism'in Java'sıyla).
