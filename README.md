# -nstagramTakip-ste-iGeri-ekme
İnstagram üzerinden gönderilen takip isteklerini otomatik olarak geri çeken otomasyon bot 

Kullanım için öncelikle python kurmanız gerekmekte 
Python kurulumu:
Python resmi sitesine gidin.
https://www.python.org/downloads/windows/?utm_source=chatgpt.com
Python u bilgisayarınıza indirin ardından kuruluma geçin,kurulum esnasında "Add Python 3.x to PATH" kutucuğunu işaretleyin.

Python kurulumunu kontrol etme;
python --version

Ardından pip kurulu mu kontrol edin;
pip --version

Her şey yolundaysa sonraki adıma geçin.

🔹 1. Chrome sürümünü öğren

Chrome’u aç

Sağ üstte ... → Yardım → Google Chrome Hakkında tıkla

Burada Chrome sürümü gözükecek (ör. 139.0.0.0)

🔹 2. ChromeDriver indir

Şu adrese git:
👉 https://googlechromelabs.github.io/chrome-for-testing/#stable

Buradan Chrome sürümüne uygun ChromeDriver’ı indir (Windows → chromedriver-win64.zip)

🔹 3. Dosyayı çıkar

İndirilen .zip dosyasını çıkar

İçinden chromedriver.exe çıkacak


Bu exe dosyasının konumunu koda girmen gerekiyor

Sonraki adımda Selenium indir

pip install selenium


Artık kodun çalışmaya hazır fakat tek bir eksik var o da hangi kullanıcılardan isteği çekeceğimiz.
Bunun için instagram hesabına gir,
Profiline gir,
3 çizgiye bas ve hesaplar merkezine gir,
Bilgilerin ve izinlerin kısmına gir,
Bilgilerini dışa aktar seçeneğine bas,
Dışa aktarım oluştur seçeneğine bas,
İnstagram hesabını seç
Cihaza aktar seçeneğine bas,
Bilgileri özelleştir seçeneğine tıkla,
Sadece takipçiler ve takip edilenler seçeneği aktifken kaydete tıkla,
Sonrasında istediğin tarih aralığını gir,
Html olarak işaretleme yap,
Dışa aktarımı başlat,


Dosyan hazır olduğunda şu adımları takip et;
İnstagrama gir,
Profiline gir,
3 çizgiye bas ve hesaplar merkezine gir,
Bilgilerin ve izinlerin kısmına gir,
Bilgilerini dışa aktar seçeneğine bas,
Mevcut hareketlerden dosyanı indir,
İndirdiğin dosyanı aç,
connections klasörüne gir,
followers_and_following klasörüne gir,
pending_fallow_requests.html dosyasını ChatGPT ye gönderip ondan bu html dosyasındaki kullanıcı isimlerini bir txt dosyasına yazmasını iste

Hazırlanan txt dosyasını bigisayarına indir sonrasında txt dosyasının konumunu kopyala


Kodunu çalıştır,kod çalıştığında senden kullanıcıların hangi txt dosyasında olduğu sorulacak, txt dosyanın tam konumunu bu kısma yapıştır.

Şimdi chrome açılacak ve instagram sayfasına girecek
İnstagrama giriş yap(2 faktörlü kimlik doğrulamasının açık olmasında bir sorun yok bot senin giriş yapmanı bekleyecek)
Giriş yaptıktan sonra kendi profiline tılaman yeterli olacak sonrasında arkana yaslan ve işi bota bırak.


Eğer bir sorunla karşılaşırsanız Yaganmetin1 instagram adresinden benimle iletişime geçebilirsiniz.
