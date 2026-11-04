<img src="img/kapak.png" alt="Software built end to end, from idea to production — web · desktop · mobile" width="100%">

### Merhaba, ben Orkun 👋

**.NET yazılım geliştiriciyim** · C# · ASP.NET Core · Blazor · SQL Server · PostgreSQL

2017'den beri geçiş kontrol ve PDKS sektöründeyim: bu yazılımları geliştirdim, test ettim, sahada kurdum ve destekledim.
Bugün aynı tecrübeyle işletmelerin personel, geçiş ve takip süreçlerini otomatikleştiren web, masaüstü ve mobil
yazılımları baştan sona kendim geliştiriyorum. Perplus markasıyla dağıtılan yazılımların geliştiricisiyim.

İşimi farklı kılan şey, yazılımın sahadaki donanımla ve muhasebe sistemleriyle kesintisiz çalışması: turnike ve kart
okuyucu panelleri, ZKTeco cihazları; Logo, Mikro, Zirve, Paraşüt gibi ERP entegrasyonları. Veritabanı tasarımı, arayüz,
cihaz haberleşmesi, kurulum, lisanslama ve sunucu tarafının tamamı bende.

📬 **.NET rollerine ve serbest projelere açığım** (İstanbul veya uzaktan):
[LinkedIn](https://www.linkedin.com/in/orkunbaylan) · orkunbaylan1@gmail.com

---

### 🧭 Deneyim

| Dönem | Rol | Nerede |
| --- | --- | --- |
| Mar 2026 – devam | **Bağımsız Yazılım Geliştirici** | Serbest çalışan |
| Tem 2022 – Mar 2026 | **Firma Müdürü** | A System Geçiş Güvenlik Sistemleri |
| Oca 2020 – Haz 2022 | **Yazılım Geliştirme ve Destek Müdürü** | Önder Zaman Kontrol ve Geçiş Güvenlik Sistemleri |
| Oca 2017 – Ara 2019 | **Yazılım ve Destek Sorumlusu** | Önder Zaman Kontrol ve Geçiş Güvenlik Sistemleri |

**Eğitim:** Bilgisayar Programcılığı (Anadolu Üniversitesi) · **Kurslar:** C# Programlama (yazılım24, 2017), SQL Veritabanı (Enstitü İstanbul İSMEK, 2019)

---

### 🌐 Web / SaaS

#### PerplusWeb: PDKS, puantaj ve bordro platformu (2026) · [perpluspdks.com](https://perpluspdks.com) · [kılavuz](https://perpluspdks.com/docs)
Kart okuyucu ve turnikelerden gelen giriş-çıkışları toplar, vardiya ve mesai kurallarına göre puantajı hesaplar,
bordroya hazır veri üretir.
- **Personel yönetimi:** özlük bilgileri, izin ve hakediş, ek kazanç ve kesintiler, tarihli maaş geçmişi; tanınmayan
  kart okutmalarının bekletildiği veri merkezi
- **Puantaj ve raporlar:** terminal geçiş logları, arka planda çalışan hesaplama motoru, günlük puantaj analizi, aylık
  bordro ve icmal (Excel), maaş pusulası, departman maliyeti, performans ısı haritası
- **Vardiya ve planlama:** çalışma grupları, geç kalma/erken çıkma toleransları, gece aralığı, vardiya şablonları ve molalar
- **Canlı operasyon merkezi:** günün anlık durumu tek ekranda; kullanıcı yetkisine göre ekranlar
- 19 dakikalık [eğitim videosu](https://www.youtube.com/watch?v=qMVOepinf0I)

#### Perplus Öğrenci: okul giriş-çıkış ve veli bildirim sistemi (2026) · [perplusokul.com](https://perplusokul.com) · [kılavuz](https://perplusokul.com/docs)
Öğrenci okula girdiğinde ya da çıktığında veliye anında bildirim gider; okul yönetimi tüm hareketleri panelden izler.
- **Üç panel:** platform yönetimi, okul paneli, veli paneli (PWA) ve veli mobil uygulaması (React Native / Expo)
- **Okul paneli:** genel bakış ("şu an içeride", henüz gelmeyenler), canlı giriş-çıkış, devamsızlık bildirimi, ders
  programı, elle kayıt (raporlu/izinli)
- **Cihaz altyapısı:** WebSocket ile çalışan cihazlar (ZKTeco vb.) ve yerel köprü üzerinden TCP turnike panelleri
- Canlıda: 15 dakikalık [eğitim videosu](https://www.youtube.com/watch?v=JE4zwpKfh94)

#### PerplusAccess: web tabanlı geçiş kontrol platformu (2026) · [perplusaccess.com](https://perplusaccess.com)
Panel merkezli tasarım: geçiş kararını panel verir, internet kesilse de kartla geçiş sürer.
- Kişiler (Excel/CSV ile toplu aktarım), kişi başına birden fazla kart, son kullanma tarihi ve kontör, ziyaretçiler, gruplar
- Kapılar, zaman dilimleri, tatil takvimi ve erişim grupları
- Kart panele yazılır ve geri okunarak doğrulanır; köprü çevrimdışıyken değişiklikler sıraya alınır
- iOS ve Android mobil uygulaması (React Native / Expo, TypeScript)
- Reddedilen geçişler için anlık bildirim, şube ve köprü yönetimi, kişi portalı, raporlar

---

### 🖥️ Masaüstü programları
Windows Forms ile geliştirildi; Inno Setup kurulumu ve lisans anahtarıyla etkinleştirme.

| Program | Başlangıç | Ne yapar |
| --- | --- | --- |
| **PDKS** | 2021 | ZKTeco ve kart okuyuculardan kayıt alır, puantajı hesaplar; Logo, Mikro, Zirve ve Paraşüt'e aktarır |
| **Giriş-Çıkış Takip** | 2022 | Turnike ve kart okuyucu panellerinden geçişleri toplar; kim ne zaman girdi-çıktı anlık izlenir ve raporlanır |
| **Öğrenci Takip** | 2022 | Okul, kurs ve yurtlar için: öğrenci kaydı ve fotoğrafı, canlı giriş-çıkış, anti-passback, Netgsm ile veliye SMS, borç ve ödeme takibi, Excel raporları |
| **Yurt Takip** | 2024 | Öğrenci Takip'in SQL Server tabanlı çok kullanıcılı ağ sürümü; blok, kat ve kapasite yönetimi; sunucu/istemci kurulumu, eksik SQL Server ve .NET'i kurulumda indirir |
| **KafeTakip** | 2023 | Kafeterya ve kantinler için kartlı (ön ödemeli) satış: kart tanımlama, bakiye yükleme, hızlı sipariş ekranı, iade/iptal, ciro raporları |
| **QR-Bilet** | 2024 | Bilet türüne göre satış ve QR kodlu bilet; girişte QR okuyuculu turnike doğrular; yerel ağda panel bulma, röle ve saat ayarları |

### 🔧 Altyapı ve araçlar
- **Panel Köprü Servisi:** bulut platformlarının müşterinin yerel ağındaki panellerle konuşması için Windows servisi.
  UDP ile cihaz bulma, TCP ile kart/okuyucu/ayar komutları; buluta dışa doğru WebSocket bağlantısı sayesinde port açmaya
  gerek yok; anahtarla kimlik doğrulama, otomatik yeniden bağlanma ve bir ayar arayüzü.
- **Lisans altyapısı:** bilgisayara bağlı, süreli ve kriptografik olarak imzalı lisans anahtarları; müşteri ve bayi
  kayıtları, lisans iptali, dosya bütünlüğü ve kurcalama koruması.

---

### 📸 Ekran görüntüleri (demo veri)

| PerplusWeb: canlı operasyon merkezi | PerplusWeb: bordro ve icmal |
| --- | --- |
| <img src="img/perplusweb-canli-operasyon.jpg" width="420"> | <img src="img/perplusweb-bordro-icmal.jpg" width="420"> |

| Perplus Öğrenci: canlı giriş-çıkış | Perplus Öğrenci: veli uygulaması |
| --- | --- |
| <img src="img/ogrenci-canli-giris-cikis.png" width="420"> | <img src="img/ogrenci-veli-uygulamasi.png" width="200"> |

| PerplusAccess: genel bakış | PerplusAccess: canlı geçişler |
| --- | --- |
| <img src="img/perplusaccess-genel-bakis.jpg" width="420"> | <img src="img/perplusaccess-canli-gecisler.jpg" width="420"> |

| PerplusAccess: kişi profili | PerplusAccess: günlük rapor |
| --- | --- |
| <img src="img/perplusaccess-kisi-profili.jpg" width="420"> | <img src="img/perplusaccess-gunluk-rapor.jpg" width="420"> |

| PerplusAccess: paneller ve köprü bağlantısı |
| --- |
| <img src="img/perplusaccess-paneller.jpg" width="420"> |

| PDKS: aylık puantaj | PDKS: giriş-çıkış |
| --- | --- |
| <img src="img/pdks-aylik-puantaj.jpg" width="420"> | <img src="img/pdks-giris-cikis.jpg" width="420"> |

| Giriş-Çıkış Takip: personel | Giriş-Çıkış Takip: rapor |
| --- | --- |
| <img src="img/giris-cikis-personel.jpg" width="420"> | <img src="img/giris-cikis-rapor.jpg" width="420"> |

| Öğrenci Takip: öğrenci listesi | Öğrenci Takip: giriş-çıkış raporu |
| --- | --- |
| <img src="img/ogrenci-takip-liste.jpg" width="420"> | <img src="img/ogrenci-takip-rapor.jpg" width="420"> |

| KafeTakip: sipariş ekranı | QR-Bilet: satış ve bilet listesi |
| --- | --- |
| <img src="img/kafetakip-siparis.jpg" width="420"> | <img src="img/qr-bilet-satis.jpg" width="420"> |

### 🧰 Teknolojiler

**Backend:** C# · .NET · ASP.NET Core · ASP.NET Web API · Blazor Server · EF Core · LINQ · REST API · SignalR · WebSocket · TCP/UDP cihaz protokolleri · JWT · OOP · Dependency Injection · Clean Architecture · xUnit  
**Arayüz:** Windows Forms · HTML · CSS · JavaScript · TypeScript  
**Mobil:** React Native (Expo) · TypeScript · iOS · Android  
**Veritabanı:** SQL Server (T-SQL) · PostgreSQL · SQLite  
**Altyapı:** Nginx · Cloudflare · Inno Setup · Git · Visual Studio

🎬 Eğitim videoları: [YouTube · Geliştirdiğim Yazılımlar](https://www.youtube.com/playlist?list=PLDf1-6sOXCEU)

Kaynak kodları ticari olduğu için depolarım gizli. Masaüstü programlarını GitHub'ı kullanmaya başlamadan önce geliştirdim;
depolar sonradan yüklendiği için depo tarihleri yenidir. Programları denemek ya da lisans almak için
[LinkedIn](https://www.linkedin.com/in/orkunbaylan) veya orkunbaylan1@gmail.com üzerinden yazabilirsiniz.

---

<details>
<summary>🇬🇧 English</summary>

I'm Orkun Baylan, a .NET software developer (C#, ASP.NET Core, Blazor, SQL Server, PostgreSQL). I have been in the access
control and time & attendance industry since 2017, and today I build web, desktop and mobile software that automates personnel, access and
tracking operations for businesses. I'm the developer of the software distributed under the Perplus brand, and I build
each product end to end: database, UI, device communication, installer, licensing and server.

My specialty is making software talk to hardware (turnstiles, card-reader panels, ZKTeco devices) and to accounting/ERP
systems (Logo, Mikro, Zirve, Paraşüt).

**Experience**
- Independent Software Developer, self-employed (Mar 2026 – present)
- General Manager, A System (Jul 2022 – Mar 2026)
- Software Development & Support Manager, Önder Zaman (Jan 2020 – Jun 2022)
- Software & Support Specialist, Önder Zaman (Jan 2017 – Dec 2019)

**Web / SaaS** (.NET, Blazor Server, PostgreSQL)
- **PerplusWeb** ([perpluspdks.com](https://perpluspdks.com)): time & attendance, timesheet and payroll platform:
  personnel records, leave, shifts and tolerances, a background calculation engine, monthly payroll summaries (Excel),
  payslips, department cost and a live operations dashboard.
- **Perplus Öğrenci** ([perplusokul.com](https://perplusokul.com)): school entry-exit system that notifies parents
  instantly; school, platform and parent panels plus a React Native (Expo) parent app.
- **PerplusAccess** ([perplusaccess.com](https://perplusaccess.com)): panel-centric access control
  that keeps working offline; people, cards, visitors, doors, time zones, access groups, branches, real-time alerts
  and an iOS/Android app (React Native / Expo, TypeScript).

**Desktop** (Windows Forms): PDKS with ERP export, Entry-Exit Tracking, Student Tracking (anti-passback, SMS to
parents, payments), Dormitory Tracking (multi-user SQL Server edition), KafeTakip (prepaid card café sales) and
QR-Bilet (QR ticket sales and turnstile validation).

**Tech stack:** C#, .NET, ASP.NET Core, ASP.NET Web API, Blazor, Windows Forms, EF Core, LINQ, SignalR, JWT, OOP,
Dependency Injection, SQL Server (T-SQL), PostgreSQL, SQLite, TypeScript,
JavaScript, React Native (Expo), HTML, CSS, xUnit, Nginx, Cloudflare, Git, Visual Studio.

**Infrastructure:** a Windows bridge service that connects cloud platforms to on-premise panels over UDP/TCP with an
outbound WebSocket (no port forwarding), and a cryptographically signed, machine-bound licensing system.

🎬 Training videos: [YouTube playlist](https://www.youtube.com/playlist?list=PLDf1-6sOXCEU)

My repositories are private because the code is commercial. I built the desktop programs before I started using GitHub,
so repository dates are recent. I'm open to .NET roles and freelance projects (Istanbul or remote). Reach out on
[LinkedIn](https://www.linkedin.com/in/orkunbaylan) to try my programs or get a license.

</details>
