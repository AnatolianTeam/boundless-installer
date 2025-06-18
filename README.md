# Boundless Node Installer

Bu installer, Boundless Dev ve Prover rolü için otomatik kurulum ve kolay kullanım sağlar.

## Gereksinimler

- Ubuntu 20.04 veya üzeri
- Base ağında en az 1-10 USDC ve en az 1$ değerinde ETH
- İnternet bağlantısı

## Hızlı Kurulum

### boundless_installer klasörünü oluşturun
mkdir -p ~/boundless_installer && cd ~/boundless_installer

### Installer'ı indirin
```bash
wget https://github.com/KULLANICI_ADINIZ/boundless-installer/raw/main/boundless_installer
```
### Hash dosyasını indirin
```bash
wget https://github.com/KULLANICI_ADINIZ/boundless-installer/raw/main/boundless_installer.sha256
```
### Hash doğrulaması yapın (önerilen)
```bash
sha256sum -c boundless_installer.sha256
```
### Çalıştırma izni verin
```bash
chmod +x boundless_installer
```
### Installer'ı çalıştırın
```bash
./boundless_installer
```


## Menü Seçenekleri

1. Boundless Kurulumu Yap
2. .env.base Dosyasını Oluştur/Güncelle
3. Prover Rolü Komutunu Çalıştır (1-10 USDC)
4. Dev Rolü Komutunu Çalıştır (0.000001 ETH)
5. Boundless Klasörünü ve Kurulumu Kaldır
6. Çıkış

## Önemli Notlar

- Prover rolü için cüzdanınızda en az 1-10 USDC ve en az 1$ değerinde ETH olmalıdır
- Dev rolü için cüzdanınızda en az 1$ değerinde ETH olmalıdır
- Base Mainnet RPC URL almak için https://dashboard.alchemy.com/ adresini kullanın
- İşlemler tamamlandıktan sonra:
  1. https://guild.xyz/boundless-xyz adresine gidin
  2. Cüzdanınızı bağlayın
  3. Guild'e katılın
  4. Discord sunucusuna katılın: https://discord.gg/K6MEUmFfAC
  5. #🌊｜claim-dev-prover-roles kanalından rollerinizi alın

## Güvenlik

Her kurulumdan önce hash doğrulaması yapmanızı öneririz:
```bash
sha256sum -c boundless_installer.sha256
```

## Sorun Giderme

Herhangi bir sorunla karşılaşırsanız:
1. Cüzdan bakiyelerinizi kontrol edin
2. RPC URL'nizin doğru olduğundan emin olun
3. Discord sunucumuzdan destek alın

## Lisans

Tüm hakları saklıdır. Bu installer'ın kaynak kodu kapalıdır ve yeniden dağıtımı yasaktır.
