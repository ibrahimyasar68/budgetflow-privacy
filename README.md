# BudgetFlow — Gizlilik Politikası

BudgetFlow Android uygulamasının (`com.ibrahimyasar.budgetflow`) gizlilik politikası sayfası.
GitHub Pages ile yayınlanır ve Google Play Console → Uygulama içeriği → Gizlilik Politikası
alanında kullanılır.

- Yayın adresi: `https://<kullanici-adi>.github.io/budgetflow-privacy/`
- Kaynak sayfa: [`index.html`](index.html) (tek dosya, harici bağımlılık yok, TR + EN)

## Güncelleme

Politikayı değiştirdiğinde `index.html` içindeki **"Son güncelleme"** / **"Last updated"**
tarihlerini de güncelle, sonra commit + push. GitHub Pages birkaç dakika içinde yayına alır.

Bu sayfanın bir kopyası uygulama deposunda `docs/privacy/index.html` yolunda durur;
ikisini birlikte güncel tut.

## ⚠️ Bu repoya uygulama kaynak kodu ekleme

Bu repo herkese açıktır ve **yalnızca statik sayfalar** içindir. BudgetFlow Flutter projesi
imza anahtarını (`android/app/upload-keystore.jks`) ve parolaları (`android/key.properties`)
barındırır; bu dosyaların herkese açık bir repoya girmesi yükleme anahtarını sızdırır.
