# HydroTick Privacy Policy / Gizlilik Politikası

Baqir Develop tarafından sunulan HydroTick (`com.hydrotick.app`) için Türkçe ve İngilizce statik gizlilik politikası.

- Geliştirici / Developer: **Baqir Develop**
- İletişim / Contact: **baqirdevelop@gmail.com**
- Depo / Repository: https://github.com/KamilErtap/hydrotick-privacy
- Yayın adresi / Publication URL: https://kamilertap.github.io/hydrotick-privacy/
- Politika güncellemesi / Policy revision: **2026-11-09**

## GitHub'a gönderilecek dosyalar

Yalnızca bu klasördeki üç dosyayı `hydrotick-privacy` deposunun köküne koyun:

1. `index.html`
2. `style.css`
3. `README.md` (mevcut kısa README'nin yerine)

Android projesini, `keystore.properties`, `.jks` dosyalarını veya derleme çıktılarını bu herkese açık depoya göndermeyin. Bu klasör bağımsız bir yayın paketidir; Android projesinin kök README'si değildir. Dosyalar hazırlanmıştır; otomatik commit, push veya yayın yapılmamıştır.

## GitHub Pages yayını

Onayınızın ardından üç dosyayı deponun `main` dalının köküne gönderin. GitHub'da **Settings → Pages → Build and deployment → Source: Deploy from a branch → main → /(root) → Save** seçin. Yayın tamamlandığında yukarıdaki HTTPS adresini açarak Türkçe/İngilizce, mobil görünüm ve bağlantıları kontrol edin. Varsa **Enforce HTTPS** seçeneğini etkin tutun.

Dosyaların depo içinde bulunması tek başına Pages'in yayınlandığı anlamına gelmez. Adresin çalıştığını doğrulamadan Play Console'a hazır kabul etmeyin. Google Play Console gizlilik politikası alanına web adresini girin; PDF veya README dosyasının adresini kullanmayın. Android uygulamasındaki bağlantı da aynı adresi açar.

## Teknik özellikler ve yerel kontrol

- Derleme, npm paketi, CDN, harici JavaScript, harici yazı tipi veya sunucu kodu gerektirmez.
- Her iki politika HTML içinde bulunur; JavaScript kapalı olsa da okunabilir.
- `#tr` / `#en` bağlantıları dili seçer; bağlantıda dil yoksa tarayıcı dili Türkçeyse Türkçe, diğer durumlarda İngilizce gösterilir.
- Tema varsayılan olarak sistem tercihidir. Açık/koyu seçimi yalnızca açık sayfanın belleğinde tutulur. Çerez, localStorage veya sessionStorage kullanılmaz.
- GitHub Pages güvenlik amaçlı ziyaretçi IP kaydı tutabilir. Bu durum politika metninde uygulamadaki yerel su kayıtlarından ayrı açıklanır.
- Stil dosyası göreli `./style.css` yoluyla yüklenir; GitHub proje alt diziniyle uyumludur.

Yerel önizleme için bu klasörde `python -m http.server 8080 --bind 127.0.0.1` çalıştırın ve `http://127.0.0.1:8080/` adresini açın. HTML dosyasını doğrudan tarayıcıda açmak da mümkündür.

## İçerik kapsamı

Politika Room/DataStore saklamasını, 30 günlük gösterim ile gerçek saklama süresi arasındaki farkı, yerel bildirimleri, veri silmeyi, yedekleme ve şifreleme sınırlarını, destek e-postalarını ve web barındırmasını açıklar. Bağımsız güvenlik sertifikası veya mutlak gizlilik garantisi vermez. Uygulama davranışı değişirse iki dili ve tarihi birlikte güncelleyin.

## English publishing notes

Publish only `index.html`, `style.css`, and this `README.md` at the repository root. Enable GitHub Pages for the `main` branch and root folder after approving the upload. No deployment is performed by these files. Do not upload Android signing credentials or the Android project. Check the public HTTPS page before using its URL in Play Console.

Both translations are embedded in the HTML. Language selection uses URL fragments and browser language; themes follow the system unless changed for the current page. No cookies, persistent browser storage, analytics, external scripts, or remote fonts are included. GitHub's hosting-related IP logging and voluntary email correspondence are disclosed separately from the app's local data.

Reference requirements: [Google Play User Data policy](https://support.google.com/googleplay/android-developer/answer/10144311), [GitHub Pages hosting and data collection](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages).
