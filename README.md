<p align="center">
  <b style="font-size:2.1em">SyntaxOrigin</b><br /><br />
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=26&pause=1000&color=38E8FF&center=true&width=620&lines=Rust+ile+yaz%C4%B1lan+23+terminal+arac%C4%B1%3B%C4%B0kinci+eksen%3A+aray%C3%BCz+ve+motion" alt="Rust ile yazılan 23 Rust aracı" /><br /><br />
  <b>Sözdizimi doğru, anlam yerinde.</b><br />
  <sub>SyntaxOrigin &mdash; İstanbul, Türkiye &middot; UTC+3</sub><br /><br />
  <img src="https://komarev.com/ghpvc/?username=SyntaxOrigin&label=Ziyaret%C3%A7i&color=0e75b6&style=flat" alt="Ziyaretçi sayacı" /><br /><br />
  <img src="https://img.shields.io/badge/Rust-90.6%25-38E8FF?style=for-the-badge&logo=rust&logoColor=black" alt="Rust %90.6" />
  <img src="https://img.shields.io/badge/23_Rust_arac%C4%B1-7C5CFF?style=for-the-badge&logo=rust&logoColor=white" alt="23 Rust aracı" />
  <img src="https://img.shields.io/badge/26_a%C3%A7%C4%B1k_repo-38E8FF?style=for-the-badge&logo=github&logoColor=black" alt="26 açık repo" />
  <img src="https://img.shields.io/badge/238_commit_son_12_ay-7C5CFF?style=for-the-badge&logo=git&logoColor=white" alt="Son 12 ayda 238 commit" />
</p>

---

## Hakkımda

**Syntax** kodun dilbilgisidir, **Origin** ise doğduğu an. İkisini birleştirince ortaya tek bir iş kuralı çıkıyor: arayüzü bir cümle gibi okuyorum — sözdizimi doğru olmalı, anlam yerinde olmalı. Bir ekran ya da bir komut çıktısı bu ikisinden birini tutmuyorsa, ne kadar süslü görünürse görünsün işe yaramaz.

```
$ so whoami
syntax  : doğru
origin  : anlam yerinde
method  : ölç, sonra karar ver
measure : tahmin değil, ölçüm
scope   : ölçülmeyen iyileştirme kapsama girmez
```

## Odak

<div align="center">
<table>
<tr>
<td>
<b>Eksen 01 &mdash; Rust</b><br />
23 açık kaynaklı Rust projesi, tümü MIT lisanslı. Ölçek sorunu olan dosya ve akış işlerinde streaming, sabit bellek ve açık ölçüt önce gelir.
</td>
<td>
<b>Eksen 02 &mdash; Arayüz</b><br />
Aynı disiplinin ön yüz tarafı: tasarım sistemi, tema yönetimi, komut paleti, çizim ve geçiş animasyonları. Ölçüt kare bütçesi ve etkileşim gecikmesidir.
</td>
</tr>
</table>
</div>

- **Ortak ölçüt.** Hangisi olursa olsun ölçülebilir olmayan bir özellik listeye girmiyor. Araçlarda çalışma zamanı ve bellek tavanı, arayüzde kare bütçesi ve etkileşim gecikmesi ölçülür.

## Araçlar

23 Rust aracı, altı tema altında. Tamamı çevrimdışı çalışır: hesap açmaz, telemetri göndermez, bulut servisi kullanmaz. `peersync` ve `mockforge` yerel ağ yüzeyi açar — biri alt ağa UDP yayın yapar, diğeri yerel bir HTTP sunucusu açar. Salt okunur olanlar `gitatlas`, `procsight`, `duphunter` ve `clipforge`; kalanı kendi çıktısını diske yazar.

### Veri ve Dosya

| Araç | Ne yapar |
| --- | --- |
| [datalens](https://github.com/SyntaxOrigin/datalens) | Büyük CSV/TSV/JSONL dosyalarını belleğe almadan profilleyen, filtreleyen ve dışa aktaran terminal görüntüleyicisi. |
| [plotpocket](https://github.com/SyntaxOrigin/plotpocket) | Büyük CSV/TSV/JSONL dosyasından tek komutla terminal grafiği ya da bağımsız SVG üretir. |
| [disktree](https://github.com/SyntaxOrigin/disktree) | Sabit bellekli disk analizörü: squarified treemap, ısı haritası ve boyut zaman çizelgesi. |
| [duphunter](https://github.com/SyntaxOrigin/duphunter) | Akış tabanlı karmalarla birebir kopya avcısı yapar; iki aşamalı aday üretimiyle gereksiz okumayı önler. |
| [timefold](https://github.com/SyntaxOrigin/timefold) | Dizin ağacını periyodik tarayıp “disk dolmadan önceki altı ay” tahminini farklarla hesaplayan yerel analiz aracı. |
| [gitatlas](https://github.com/SyntaxOrigin/gitatlas) | `git` kurulu olmayan bir makinede yalnızca `.git` dizinini okuyup depo hikâyesini çıkaran salt okunur terminal aracı. |
| [sqlstage](https://github.com/SyntaxOrigin/sqlstage) | Gömülü SQLite dosyalarını kendi okuyucusuyla açan, mevcut dosyayı değiştirmeyen şema görüntüleyici ve SQL konsolu; `rusqlite` ya da herhangi bir SQLite C kütüphanesi kullanılmaz. (create/insert/sample ile yeni dosya üretir, açtığı dosyaya yazmaz.) |

### Metin ve Altyazı

| Araç | Ne yapar |
| --- | --- |
| [nodemind](https://github.com/SyntaxOrigin/nodemind) | Düz Markdown dosyaları üzerinde blok referansları, tam metin araması ve bilgi grafiğiyle çalışan kişisel bilgi yönetimi. |
| [subforge](https://github.com/SyntaxOrigin/subforge) | SRT, ASS ve WebVTT altyazılarını okuyan, alt güvenilirlik kuralıyla denetleyen, toplu zaman kaydıran ve biçim düzelten metin aracı. |
| [waveclip](https://github.com/SyntaxOrigin/waveclip) | Podcast WAV kayıtlarından kural tabanlı hook (ilginç an) adayı bulur ve SRT/WebVTT üretir. |
| [typefast](https://github.com/SyntaxOrigin/typefast) | Genel metin genişletici. ⚠️ `sablonlar.json`, `pano.json` ve `istatistik.json` **düz metin** olarak diske açık yazılır; `mask` komutu yalnızca ekrandaki metni maskeler, `--gizli` şifreleme değildir. |
| [sniphub](https://github.com/SyntaxOrigin/sniphub) | Kod parçası kütüphanesi ve kesim yöneticisi. ⚠️ `parcalar.json` **düz metin** saklanır, şifreleme yoktur; bu bilinçli bir sapmadır. |

### Görsel ve Video

| Araç | Ne yapar |
| --- | --- |
| [pixelmill](https://github.com/SyntaxOrigin/pixelmill) | Toplu PNG düzenleyici, yeniden boyutlandırıcı ve hedef bayta sıkıştırıcı; grafik arayüz yok, tamamen çevrimdışı. |
| [burstjudge](https://github.com/SyntaxOrigin/burstjudge) | Burst ve çoklu çekim karelerini TIFF/EXIF IFD ayrıştırması, gömülü JPEG önizleme çıkarma ve DCT tabanlı algısal hash ile gruplar. |
| [clipforge](https://github.com/SyntaxOrigin/clipforge) | Platform profillerine göre MP4/MKV kapsal ayrıştırma ve kırp planı üreten saf Rust komut satırı aracı. |

### Güvenlik ve Kasa

| Araç | Ne yapar |
| --- | --- |
| [sealedbox](https://github.com/SyntaxOrigin/sealedbox) | Akış halinde AES-256-GCM ile büyük dosya ve klasörleri şifreler; sabit boyutlu tamponla akar, terminalden çalışır. |
| [vaulta](https://github.com/SyntaxOrigin/vaulta) | Argon2id ve XChaCha20-Poly1305 ile şifreli, tamamen çevrimdışı, tek dosya parola kasası; hesap açmaz, telemetri göndermez, ağ bağlantısı kurmaz. ⚠️ Bağımsız güvenlik incelemesi yapılmadı; Argon2id bellek maliyeti önerilenin altında ve kurtarma anahtarı yok. |

### Sunucu ve Ağ

| Araç | Ne yapar |
| --- | --- |
| [peersync](https://github.com/SyntaxOrigin/peersync) | Sunucusuz P2P dosya senkronizasyonu: UDP yayın es keşfi, içerik tanımlayıcılı parçalama ve şifreli delta aktarımı. |
| [mockforge](https://github.com/SyntaxOrigin/mockforge) | OpenAPI 3.x şemasından deterministik sahte HTTP API sunucusu üretir; aynı istek her zaman aynı yanıtı verir, gecikme ve hata enjeksiyonu JSON ile tanımlanır. |
| [procsight](https://github.com/SyntaxOrigin/procsight) | Bu bilgisayarda şu anda ne çalıştığını, nereye bağlandığını ve kim başlangıçta kendiliğinden açılıyor sorularını periyodik yoklama ile toplar. |

### Bilgi ve Sunum

| Araç | Ne yapar |
| --- | --- |
| [slidestage](https://github.com/SyntaxOrigin/slidestage) | Tek bir Markdown dosyasını slaytlara böler, terminalde oynatır ve tek dosya HTML ya da vektör SVG olarak dışa aktarır. |
| [siteturk](https://github.com/SyntaxOrigin/siteturk) | Klasör dolusu Markdown dosyalarını kurulum gerektirmeyen statik siteye dönüştüren tek dosyalık üretici; Rust standart kütüphanesi, `serde` ve `clap` ile. |
| [focuscompass](https://github.com/SyntaxOrigin/focuscompass) | Pomodoro oturumu, görev bağımlılıkları, günlük kapasite hesabı ve kesinti günlüğüyle birlikte “bugün neyi yapamayacağın” diyen çevrimdışı odak planlayıcı. |

### Diğer Repolar

Rust dışındaki üç açık repo:

| Repo | Ne yapar |
| --- | --- |
| [SyntaxOrigin-Multi-Tools](https://github.com/SyntaxOrigin/SyntaxOrigin-Multi-Tools) | Tarayıcı üzerinde çalışan çok amaçlı HTML araç koleksiyonu. |
| [OpenCode-Desktop-Crash-Recovery-Tool](https://github.com/SyntaxOrigin/OpenCode-Desktop-Crash-Recovery-Tool) | OpenCode Desktop renderer çökmelerinden kurtulmak için ilgili süreçleri sonlandıran ve uygulama verisi dizinlerini temizleyen Python betiği. |
| [Ultimate-Warfare---FPS-Multiplayer-Template-Analysis](https://github.com/SyntaxOrigin/Ultimate-Warfare---FPS-Multiplayer-Template-Analysis) | Unity Asset Store'daki "Ultimate Warfare - FPS Multiplayer Template" varlığının çözümlemesi. |

## Yığın

<p align="center">
  <img src="https://skillicons.dev/icons?i=rust,html,js,go,css,python,ps&theme=dark" alt="Rust, HTML, JavaScript, Go, CSS, Python, PowerShell" />
</p>

Dil dağılımı, tüm açık repoların bayt bazında ölçümü:

| Dil | Bayt payı |
| --- | --- |
| Rust | %90.6 |
| HTML | %6.0 |
| JavaScript | %2.0 |
| Go | %0.8 |
| CSS | %0.3 |
| PowerShell | %0.3 |
| Python | %0.03 |

Kullanım eğilimi: Rust birincil dil ve açık repoların neredey tamamı bu. Arayüz ve tasarım sistemi tarafındaki çalışmalarımın büyük kısmı kamuya açık depoda değil; bu yüzden yukarıdaki tablo tek başına ikinci ekseni yansıtmaz. HTML, JavaScript, Go, CSS, PowerShell ve Python yardımcı veya tek seferlik işlerde kullanıldığı için payları küçük.

## İstatistik

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=SyntaxOrigin&show_icons=true&locale=tr&theme=radical&hide_border=true" alt="GitHub istatistik kartı" height="165" /><br /><br />
  <img src="https://github-readme-stats.vercel.app/api/top-langs?username=SyntaxOrigin&locale=tr&layout=compact&theme=radical&hide_border=true" alt="En çok kullanılan diller" height="120" /><br /><br />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=SyntaxOrigin&theme=dark&hide_border=true&locale=tr" alt="GitHub streak istatistiği" /><br /><br />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=SyntaxOrigin&theme=dark" alt="Profil özet kartı" /><br /><br />
  <img src="https://img.shields.io/github/followers/SyntaxOrigin?color=38E8FF&style=flat" alt="Takipçi sayısı" />
  <img src="https://img.shields.io/github/stars/SyntaxOrigin?color=7C5CFF&style=flat" alt="Yıldız sayısı" />
  <img src="https://img.shields.io/github/last-commit/SyntaxOrigin/peersync?color=38E8FF&style=flat" alt="peersync son commit" />
  <br /><br />
  <sub>Son 12 ayda 238 commit. Takipçi ve yıldız sayısı şu an 0 — istatistikler üretim hacmini gösterir, sosyal kanıtı değil.</sub>
</p>

## Aktivite

<p align="center">
  <img src="https://activity-graph.vercel.app/graph?username=SyntaxOrigin&theme=github&hide_border=true&area=true&custom_title=Aktivite" alt="Katkı aktivite grafiği" /><br />
</p>

## İletişim

- **Konum** — İstanbul, Türkiye · UTC+3. Uzaktan, dünya çapında çalışıyorum.
- **Çalışma biçimi** — Yeni projeye aç. Ölçülebilir bir ölçüt varsa konuşmaya değer.
- **Yanıt süresi** — Bir iş günü içinde. Yavaş bir cevap, ölçülmemiş bir cevaptır.
- **Tercih edilen kanal** — GitHub üzerinden issue veya tartışma; kodu, ölçütü ve kapsamı birlikte yazın.

[![GitHub profilini incele](https://img.shields.io/badge/GitHub-1_i%C5%9Fte_Yeni_Projeye_A%C3%A7%C4%B1k-38E8FF?style=for-the-badge&logo=github&logoColor=black)](https://github.com/SyntaxOrigin)

---

<small>SyntaxOrigin &middot; arayüz ve sistem tasarımı</small>
