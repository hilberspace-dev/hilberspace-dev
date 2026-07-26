# atilgandev — backend systems where money and records have to stay correct

**Mutabakat · ödeme ve banka entegrasyonları · KVKK uyumlu veri işleme · devralınan sistemlerin
toparlanması**

*Reconciliation · payment and bank integrations · privacy-compliant data handling · rescuing
inherited systems*

Ödemenin, faturanın ve kaydın tutması gereken yerlerde backend geliştiriyorum. Çalıştığım işlerin
ortak paydası şu: bir yerde para veya kayıt kayboluyor, kimse tam olarak nerede olduğunu
gösteremiyor ve elle kapatılan her ay hem maliyet hem risk üretiyor.

> ### Sabit kapsamlı iş alıyorum · Available for fixed-scope work
>
> Problemi, mevcut sistemi ve beklediğiniz sonucu yazın; kapsamı, süreyi ve teslim edilecekleri
> yazılı olarak geri göndereyim. İlk görüşme ve ön değerlendirme ücretsizdir.
>
> **[E-posta / Email →](mailto:hilberspace@gmail.com)** ·
> **[WhatsApp →](https://wa.me/905431064025)** · **[+90 543 106 40 25](tel:+905431064025)**

📍 Türkiye · [**🇹🇷 Türkçe portföy**](https://github.com/hilberspace-dev/portfolio/blob/main/README.tr.md) ·
[English portfolio](https://github.com/hilberspace-dev/portfolio)

---

## Taklit edilmesi zor üç şey

- **Bir ürünün tamamını tek başıma taşıdım.** Ödeme alan, kişisel veri işleyen ve GPU/ML workload'u
  çalıştıran canlı, multi-tenant ticari bir SaaS'ın tek teknik sahibiydim: mimari, API, web, release
  süreci, KVKK dokümantasyonu ve handover paketi.
- **Başkalarının zaten incelediği para kodunda hata bulurum.** Yoğun biçimde denetlenmiş bir işlem
  doğrulama bileşeninde deterministik bir doğruluk kusurunu iki bağımsız ortamda tekrar ürettim.
- **Kanıt "dur" diyorsa dururum.** Yaklaşık 16,7 milyon dolarlık bir inceleme, kendi kanıtım en güçlü hipotezimi
  çürüttüğü için yazılı bir NO-GO ile bitti. Sayılar umduğunuz sonucu desteklemiyorsa, bunu ilk
  benden duyarsınız.

## Riski küçük tutarak başlıyoruz

Bir referans listesi okuyup bana güvenmenizi beklemiyorum; ilk adımı ucuz ve geri dönülebilir
yapıyorum.

- **Ücretli ön analiz** — birkaç günlük, sabit ücretli, kendi başına duran bir iş. Çıktısı yazılı
  bir teşhis raporudur; devam etmeseniz de sizde kalır.
- **Milestone bazlı ödeme** — peşin toplu ödeme yok.
- **İlk milestone'da yazılı kabul kriteri** — karşılamazsam o milestone'u faturalamam.
- **Ücretsiz teşhis** — anonimleştirilmiş bir mutabakat ekstresi gönderin; sessiz kayıpların nerede
  olduğunu yazılı olarak geri göndereyim. Karşılığında taahhüt beklemiyorum.

## Nasıl çalıştığım — yazılı olarak

İki metodoloji belgesi herkese açık. Pazarlama sayfası değil; fiilen kendime uyguladığım
standartlar ve doğru kişi olup olmadığıma karar vermenin en hızlı yoludur.

- [**Teslim ve Quality Gate Metodolojisi**](https://github.com/hilberspace-dev/portfolio/blob/main/DELIVERY-METHODOLOGY.tr.md)
  — bir değişikliğin production'a nasıl çıktığı
  ([English](https://github.com/hilberspace-dev/portfolio/blob/main/DELIVERY-METHODOLOGY.md))
- [**Güvenlik İncelemesi ve PoC Metodolojisi**](https://github.com/hilberspace-dev/portfolio/blob/main/METHODOLOGY.tr.md)
  — bir defect'in nasıl kanıtlandığı
  ([English](https://github.com/hilberspace-dev/portfolio/blob/main/METHODOLOGY.md))

İkisinin de dayandığı ilke aynı: **iddiadan önce kanıt.**

## Referans işler

**[Aura](https://github.com/hilberspace-dev/portfolio/tree/main/projects/04-aura-photoreal-3d-clinic-platform)**
*(özel, ticari — kendi ürünüm)* — Multi-tenant klinik platformunu tek başıma yazdım: ödeme akışı,
KVKK kontrolleri, GPU/ML workload'u, release süreci ve handover paketi. Fikrî mülkiyet devre
hazırlandığı için kaynak kod kapalı.

**[ReconPilot](https://github.com/hilberspace-dev/reconpilot)** — Go/PostgreSQL deterministik ödeme
mutabakat motoru. Açık, seed'li benchmark; PSP, banka ve pazaryeri kayıtları arasında ~50 bin işlemi
kontrol ediyor: **enjekte edilen 7 uyuşmazlık tipinin tamamı tespit edildi; 0 yanlış eşleşme, 0 kaçırılmış
eşleşme.** Sayıları kendiniz çalıştırabilirsiniz.

[![ReconPilot CI](https://github.com/hilberspace-dev/reconpilot/actions/workflows/ci.yml/badge.svg)](https://github.com/hilberspace-dev/reconpilot/actions/workflows/ci.yml)

**[Bağımsız güvenlik incelemeleri](https://github.com/hilberspace-dev/portfolio#3-independent-security-reviews)**
— Para taşıyan kodda, sistemin kendi kurallarına göre yapılmış iki bağımsız inceleme. Kanıtlanamayan bulgu
raporlanmaz.

## Teknik kapsam

Go · PostgreSQL · Node.js / TypeScript · backend mimarisi · ödeme ve işlem sistemleri · mutabakat ·
API entegrasyonları · otomatik test ve CI · Docker · observability

## İletişim

**Telefon / WhatsApp:** [+90 543 106 40 25](tel:+905431064025) ·
**E-posta:** [hilberspace@gmail.com](mailto:hilberspace@gmail.com)

Sabit kapsamlı bir iş için şunları paylaşın: problem ve bugün nasıl idare edildiği, mevcut sistem,
beklenen teslimat, hedef zaman planı ve erişim kısıtları.

Projeler Türkçe yürütülür. Şartname, dokümantasyon ve kod incelemesi Türkçe veya İngilizce olarak,
ekibinizin tercihine göre hazırlanır.
