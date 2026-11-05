# XOX & SOS — FOZ Yapım

## [▶ TARAYICIDA OYNA](https://fozdemiroglu.github.io/tas-kagit-makas/xox-sos/)

**FOZ Yapım sunar · Fatih Özdemiroğlu**

İki strateji oyunu, tek ekranda. Ücretsiz; indirme, kurulum veya GitHub hesabı gerekmez. Telefon, tablet ve bilgisayarda oynanır.

- Bilgisayara karşı veya aynı cihazda iki kişi.
- **Minik stratejist:** rastgele hamle yapan kolay bilgisayar.
- **Klasik:** XOX'ta minimax ile yenilmez bilgisayar; SOS'ta puan ve güvenli hamle arayan bilgisayar (SOS'ta yenilmezlik iddiası yoktur).
- Neon skor tabelası, son altı tur, kazanınca konfeti ve başlangıçta kapalı ses.
- FOZ Yapım / Fatih Özdemiroğlu imzası ve diğer oyunlara bağlantılar.
- Erişilebilir hücre adları, Tab / Enter ile kullanım, azaltılmış hareket tercihine destek.
- Harici kütüphane, font veya CDN gerektirmez. `index.html` doğrudan açılabilir.

## XOX

Maç başlamadan önce sen / 1. oyuncu **X veya O seçer**. Diğer oyuncu / bilgisayar diğer sembolü kullanır. Seçim yapılana kadar tahta kapalıdır. Semboller maç boyunca sabit kalır; yeni maçta yeniden seçilir. Yatay, dikey veya çapraz üçlü turu kazanır. İlk **3 tur galibiyetine** ulaşan maçı kazanır. Beraberlikler puan getirmez. Her tur başlangıç oyuncusu değişir.

## SOS

4 × 4, 5 × 5 veya 6 × 6 tahta seçilir. Her iki oyuncu da **S veya O** koyabilir. Yatay, dikey ve iki çapraz yönde oluşan her yeni SOS **1 puan** getirir. Bir hamlede birden fazla SOS puanı alınabilir. **Puan alan yeniden oynar.** Tahta dolunca daha çok puanı olan kazanır. Yeni maçta tahta puanları sıfırlanır.

S / O tuşlarıyla harf seçilebilir. Yerleştirme için bir hücreye dokunulur veya Tab ve Enter kullanılır. Renkler harfi yerleştiren oyuncuyu; çizgiler SOS'u tamamlayan oyuncuyu gösterir.

## Kayıtlar

Maç kazanımları yalnızca bu tarayıcıda, oyun / rakip / bilgisayar seviyesi / SOS tahta boyutuna göre ayrı saklanır. Aktif tahta yenilemede saklanmaz; son altı tur mevcut maç boyunca gösterilir. Ayar değişikliği ve maçı yeniden başlatma, devam eden turda onay ister. Kayıt silme de onaylıdır.

## Kontrol

`node check.cjs` kural ve durum kontrollerini çalıştırır: XOX bilgisayarına karşı tüm oyuncu dalları, SOS yönleri ve çoklu puanlar, eski bot zamanlayıcısının iptali ve tur puanlarının sıfırlanması.

## Diğer FOZ Yapım oyunları

- [Taş Kağıt Makas](https://fozdemiroglu.github.io/tas-kagit-makas/)
- [Shadow Runner](https://fozdemiroglu.github.io/shadow-runner/)
- [Neon Drift](https://fozdemiroglu.github.io/neon-drift/)
- [Neon Tower](https://fozdemiroglu.github.io/neon-tower/)
