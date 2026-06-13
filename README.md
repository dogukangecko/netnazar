<div align="center">

<img src="https://dogukangecko.github.io/netnazar/assets/screens/dashboard.png" width="240" alt="NetNazar" />

# 🧿 NetNazar

### Ağını gözetleyen göz.

**Yerel ağ tarayıcı + izleyici — bulut yok, veri cihazında kalır.**

[**🌐 netnazar sitesi**](https://dogukangecko.github.io/netnazar/) · [**⬇️ macOS indir**](https://github.com/dogukangecko/netnazar/releases/latest) · [**🔒 Gizlilik**](https://dogukangecko.github.io/netnazar/privacy.html)

iPhone · iPad · Mac · Android &nbsp;|&nbsp; 11 dil &nbsp;|&nbsp; ücretsiz

</div>

---

## NetNazar nedir?

NetNazar; evindeki ya da iş yerindeki yerel ağda **kim var, bağlantın nasıl, güvenliğin yerinde mi** sorularını tek uygulamada yanıtlayan bir ağ tarayıcı ve izleyicidir. Fing, Nmap ve ev-ağı izleyicilerinin yaptığı işi yapar — ama **hiçbir veriyi buluta göndermez**, hesap istemez, seni izlemez. Her şey cihazında işlenir.

> İsteğe bağlı uzaktan izleme bile **senin kurduğun kendi sunucunda** çalışır. Aradaki üçüncü taraf yoktur.

## ✨ Özellikler

| | |
|---|---|
| 🔎 **Cihaz keşfi** | ARP · ICMP · mDNS ile saniyeler içinde tüm cihazlar; üretici, hostname, IP & MAC, açık portlar |
| 📡 **Sürekli izleme** | Kim bağlandı/ayrıldı, çevrimiçi süresi, yeni-cihaz uyarısı, cihaz bazlı çevrimdışı alarmı |
| 📈 **Bağlantı metrikleri** | Gateway & internet RTT/jitter/kayıp, canlı grafik, hız testi, DNS, traceroute, kesinti geçmişi |
| 🛡️ **Güvenlik denetimi** | Açık port + servis/sürüm tespiti, router zafiyet denetimi (Telnet, TR-069…), SNMP |
| 🎥 **Gizli kamera tarama** | Otel/Airbnb modu — ağdaki gözetim cihazlarını imza tabanlı puanlayıp ortaya çıkarır |
| 🗺️ **Ağ haritası** | Router merkezli yıldız topoloji görselleştirmesi |
| ☁️ **Uzaktan izleme (self-host)** | Kendi Docker sunucunla evdeki ağı dışarıdan izle, cihaz arayüzlerine eriş |
| 🏠 **Ana ekran widget'ları** | iOS & Android ana ekranda ağ durumu |
| 🌍 **11 dil** | Animasyonlu çok dilli karşılama, otomatik sistem dili |
| 🔐 **Gizlilik-öncelikli** | 0 veri toplama, 0 satıcı bulutu, 0 izleyici |

## ⬇️ İndir

- **macOS** (11 Big Sur+, Apple Silicon & Intel): [**en güncel .dmg**](https://github.com/dogukangecko/netnazar/releases/latest) — imzalı ve Apple tarafından notarize edilmiş.
- **iPhone & iPad**: App Store incelemesinde — yakında.
- **Android**: yakında.

macOS kurulumu: `.dmg`'yi indir → aç → **NetNazar**'ı **Applications**'a sürükle → çift tıkla. Gatekeeper sorunsuz açar (notarize edilmiş).

## 📸 Ekran görüntüleri

<div align="center">
<img src="https://dogukangecko.github.io/netnazar/assets/screens/dashboard.png" width="200" alt="Pano" />
<img src="https://dogukangecko.github.io/netnazar/assets/screens/metrics.png" width="200" alt="Bağlantı metrikleri" />
<img src="https://dogukangecko.github.io/netnazar/assets/screens/map.png" width="200" alt="Ağ haritası" />
<img src="https://dogukangecko.github.io/netnazar/assets/screens/welcome.png" width="200" alt="11 dil" />
</div>

## 🔒 Gizlilik

NetNazar veri toplamaz. Tarama sonuçları (IP/MAC, cihaz adları) yalnızca cihazında saklanır. Konum izni **sadece** bağlı Wi-Fi adını (SSID) göstermek için ve **yalnızca uygulama açıkken** istenir; arka planda konum kullanılmaz. Tam metin → [Gizlilik Politikası](https://dogukangecko.github.io/netnazar/privacy.html).

## 🛠️ Teknoloji

Çapraz platform: **Rust çekirdek** (tarama/keşif/güvenlik motoru) + **Flutter** arayüz. iOS, iPad, macOS ve Android tek kod tabanından. Uzaktan izleme için isteğe bağlı **self-host relay** (Docker) — kaynağı **açık**: [netnazar-relay](https://github.com/dogukangecko/netnazar-relay) (AGPL-3.0). Kendi sunucunda çalışan parçayı satır satır denetleyebilirsin.

## 💬 Destek

Soru, hata bildirimi, öneri: [geckodogukan@gmail.com](mailto:geckodogukan@gmail.com)

---

<div align="center">

Bu depo NetNazar'ın **tanıtım sitesini, sürümlerini ve destek/gizlilik sayfalarını** barındırır. Uygulama ve tarama çekirdeği kaynağı özeldir; self-host **relay + protokol açık kaynaktır** → [netnazar-relay](https://github.com/dogukangecko/netnazar-relay) (AGPL-3.0).

© 2026 NetNazar 🧿

</div>
