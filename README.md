# Erhun Etiket: Sürümler

Bu depo yalnızca **Erhun Etiket** programının kurulum ve güncelleme dosyalarını içerir. Kaynak kod ayrı ve gizlidir.

## Kurulum

Kurulum dosyası (sabit adres, giriş gerekmez):
**https://github.com/bedirfurkan/erhun-etiket-surumler/releases/latest/download/Erhun-Etiket-Kurulum.exe**

Windows'un mavi **"Windows bilgisayarınızı korudu"** uyarısını görmemek için dosyayı tarayıcıyla değil, şu iki yoldan biriyle alın
(uyarı yalnızca tarayıcıyla indirilen dosyalarda çıkar):

- **USB ile:** dosyayı başka bir bilgisayarda (ör. Mac) indirip USB belleğe kopyalayın, PC'de çift tıklayın.
- **Komutla:** Başlat menüsüne **PowerShell** yazıp açın ve şu iki satırı yapıştırın:

  ```
  curl.exe -L -o "$env:USERPROFILE\Downloads\Erhun-Etiket-Kurulum.exe" https://github.com/bedirfurkan/erhun-etiket-surumler/releases/latest/download/Erhun-Etiket-Kurulum.exe
  & "$env:USERPROFILE\Downloads\Erhun-Etiket-Kurulum.exe"
  ```

Tarayıcıyla indirdiyseniz ve uyarı çıkarsa: **Daha fazla bilgi → Yine de çalıştır**.

Program ilk açılışta **30 gün deneme** olarak çalışır; lisans anahtarı sağ üstteki **anahtar simgesinden** girilir.
Kurulumdan sonra program yeni sürümleri kendiliğinden bulur ve "Şimdi güncelle" ile günceller (güncellemelerde uyarı çıkmaz).
Ürün listesi ve resimler güncellemede korunur.

## Dosyalar

| Dosya | Ne için |
| --- | --- |
| `Erhun-Etiket-Kurulum.exe` | Yeni bilgisayara kurulum (yönetici izni gerekmez) |
| `Erhun-Etiket-v…-Tasinabilir.zip` | Kurulumsuz, klasörden çalışan sürüm |
| `Guncelleme-Paketi-v….zip` | Eski sürümleri elle güncellemek için |
| `app.asar`, `manifest.json` | Programın otomatik güncelleme dosyaları (elle kullanılmaz) |
