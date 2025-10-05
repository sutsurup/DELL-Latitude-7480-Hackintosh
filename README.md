# DELL Latitude 7480 14" | Intel i7 (7600U)

[![macOS](https://img.shields.io/badge/macOS-13.7.8-orange)](https://www.apple.com/ge/macos/monterey/)
[![OpenCore](https://img.shields.io/badge/OpenCore-1.0.5-9cf)](https://github.com/acidanthera/OpenCorePkg)
[![release](https://img.shields.io/badge/indir-son%20sürüm-blue.svg)](https://github.com/sutsurup/DELL-Latitude-7480-Hackintosh/releases)

<img align="right" src="https://amso.eu/hpeciai/c4ca612aebe63bb79001f63b3010f90c/eng_pl_Dell-Latitude-7480-i5-6300U-8GB-480GB-SSD-1920x1080-Class-A-Windows-10-Professional-199887_3.jpg" alt="DELL" height="" width="363">

Türkçe | [English](https://github.com/sutsurup/DELL-Latitude-7480-Hackintosh)

**macOS Versiyonu: 13.7.8**

**OpenCore Versiyonu: 1.0.5**

Yardımcı olabilecek kaynaklar: 

- [OpenCore Yükleme Rehberi](https://dortania.github.io/OpenCore-Install-Guide)


# Detaylar

    Tarih:        Ekim 5, 2025
    Durum:        Stabil
    Destek:       BIOS (1.41.3)
    Yapı:         OpenCore

## Donanım

| **DELL** | Detay                                                  |
| ------------------- | ------------------------------------------- |
| Model Ismi      | DELL Latitude 7480      |
| Anakart           | 	DELL 0F48ND     |
| CPU              | Intel(R) Core(TM) i7-7600U CPU @ 2.80GHz              |
| RAM           | 2400 MHz 16GB + 2400 MHz 16GB SODIMM DDR4 (Total: 32GB)   |
| Dahili Grafik Kartı | Intel UHD Graphics 620                   |
| Wi-Fi | 		Intel(R) Dual Band Wireless-AC 8260 (OpenIntelWireless Support)               |
| BIOS Versiyonu      | 1.41.3                   |

## macOS Sürüm ve Uyumluluk Bilgileri
Bu yapılandırma (config), şu anda macOS Ventura 13.7.8 sürümünde çalışmaktadır ve Sequoia 15.2 sürümüne kadar sorunsuz bir şekilde güncellenebilir.

Aşağıdaki macOS sürümlerinin son versiyonlarında testler yapılmış ve başarılı olunmuştur:

Big Sur, Monterey, Ventura, Sonoma, Sequoia (üst sürümleri dahil)
Belirtilen tüm bu sürümler, hazırlanan bu config dosyası ile başarıyla çalışmaktadır.

Şu anda Ventura kullanmamın iki ana sebebi var: OpenIntelWireless ile ilgili bazı sorunlar yaşadım. Bu rehberi hazırlarken Sequoia için henüz itlwm (Intel Wi-Fi) desteği mevcut değildi.

EFI Kurulum Talimatları
Kurulum için gerekli EFI klasörünün sıkıştırılmış (zip) dosyasını Releases bölümünde bulabilirsiniz.

Kurulum adımları:

macOS kurulum belleğinizdeki EFI için ayrılan disk bölümüne gidin.

Bu disk bölümünde EFI adında yeni bir klasör oluşturun.

İndirdiğiniz zip dosyasının içerisindeki BOOT ve OC klasörlerini, yeni oluşturduğunuz EFI klasörünün içine kopyalayın.
### Çalışıyor

- [x] Uyku
- [x] Wi-Fi + Bluetooth (openIntelWireless, HeliPort'suz)
- [x] Ses ve Mikrofon
- [x] Batarya yüzde göstergesi
- [x] TouchPad ve macOS fonksiyonları (Full)
- [x] Fonksiyon tuşları (fn Keys)
- [x] Ekran parlaklığı
- [x] HDMI
- [x] Apple Servisleri

### Çalışmıyor
- [ ] SIM Kart (Cellular - Sierra Wireless AirPrime)
- [ ] Ethernet

## Ekran Görüntüleri
![](https://github.com/sutsurup/DELL-Latitude-5491-Hackintosh/blob/main/Screenshots/ventura-for-7480.png)

## Kurulum sonrası yararlanabileğiniz rehber bağlantıları
* önerilir: iCloud'a giriş yapacaksanız veya iMessage, FaceTime kullanmak istiyorsanız, bu rehberi harfiyen uygulayın: [OpenCore ile iMessage ve Apple Servislerini Aktif Etmek](https://osxinfo.net/konu/opencore-ile-imessage-ve-apple-servislerini-aktif-etmek.16297/)
* [ProperTree](https://osxinfo.net/konu/propertree-opencore-bootloader-icin-config-duzenleyici.12919/) (config.plist düzenlemek için)
* Hackintool ([Forum thread](https://www.insanelymac.com/forum/topic/335018-hackintool-v286/) | [Direkt indirme linki](http://headsoft.com.au/download/mac/Hackintool.zip)) (Detaylı sistem bilgileri öğrenme ve düzenlemeleri için)

## İletişime geçin
Herhangi bir adımda sorun yaşıyorsanız, öncelikli olarak [issue](https://github.com/sutsurup/DELL-Latitude-7480/issues) bölümüne destek talebi açın!
Diğer sorularınız için, Website: https://sutsurup.tr // Mail: [veysel@sutsurup.tr](mailto:veysel@sutsurup.tr)

</details>

## Destek olun.
Projeyi faydalı bulduysanız, kaynak bulma konusunda bana yardımcı olmak için bağış yapabilirsiniz:
```
₿ 1Q8CEMHTuecxPUJpEdpRiG6Bg2GVtzw4bN
``` 
<a href='https://github.com/sutsurup/sutsurup/blob/main/Donate.md'><img alt='Bağış' src='https://github.com/sutsurup/MSI-Hackintosh-Build/blob/main/Images/donate.png?raw=true' height='360px' width='375px'/></a>
```
QR koda tıklayarak alternatif seçeneklere ulaşabilirsiniz
``` 
