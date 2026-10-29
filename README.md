# CAD Viewer

Windows 10 / 11 (64-bit) için kurulum gerektirmeyen CAD görüntüleme ve ölçüm aracı.
A portable CAD viewing and measurement tool for Windows 10 / 11 (64-bit).

## İndir / Download

[Releases](../../releases/latest) sayfasından `CAD-Viewer-Portable-<sürüm>-win-x64.zip` dosyasını indirin.

1. Zip'i açmadan önce: sağ tık → **Özellikler** → **Engellemeyi kaldır** (uygulama imzasızdır; SmartScreen uyarısı çıkarsa **Ek bilgi → Yine de çalıştır**).
2. Zip'i istediğiniz klasöre açın.
3. `app\CadViewer.exe` (veya `CAD Viewer.cmd`) dosyasını çalıştırın. Bir CAD dosyasını exe'nin üzerine sürükleyerek ya da **Birlikte aç** ile de açabilirsiniz.

.NET veya Visual C++ kurulu olması gerekmez; çalışma zamanları paketin içindedir. Klasör USB bellekten de çalışır.

## Özellikler / Features

- **Okunan formatlar:** STEP, IGES, BREP, STL, OBJ, SKP, CATIA V5 CATPart / CATProduct, `.catdesign`
- **CATProduct montajları:** ürün yapısı ve bileşen yerleşimleri dosyadan okunur, bileşenler montaj konumunda gösterilir
- **CATPart PMI:** datum, GD&T ve tolerans değerleri doğrudan CATPart dosyasından okunup yüzeylere bağlanır
- **Ölçüm:** mesafe, açı, yarıçap, kenar uzunluğu, alan, hacim/kütle, delik tablosu, et kalınlığı, kesit
- **Dışa aktarma:** STEP, IGES, BREP, STL, OBJ, SKP; HTML ölçüm raporu
- **Komut satırı:** `cadviewer.cmd info parca.step`, `cadviewer.cmd measure parca.step --all --html --out rapor.html`

## Sistem gereksinimleri / Requirements

- Windows 10 (1607 veya üzeri) ya da Windows 11, 64-bit (x64)
- OpenGL destekli ekran sürücüsü önerilir
- Yaklaşık 450 MB disk alanı

## Lisanslar / Licenses

Pakette yer alan üçüncü taraf bileşenler ve lisansları için [THIRD-PARTY-NOTICES.txt](THIRD-PARTY-NOTICES.txt) ve [licenses](licenses) klasörüne bakın.
