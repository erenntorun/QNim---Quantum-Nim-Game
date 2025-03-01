# QNim - Quantum Nim Game

QNim, klasik Nim oyununun kuantum mekaniğiyle entegre edilmiş bir versiyonudur. Oyunda, sıradan bir oyuncu ile kuantum bilgisayarı arasında bir rekabet gerçekleşir.

## 📌 Oyun Kuralları

- Oyunda 4 sıra taş bulunmaktadır ve her sıradaki taş sayısı farklıdır (varsayılan olarak 1,3,5,7 olarak ayarlanmıştır).
- Oyuncular sırayla taş almaktadır.
- Bir sıradan en az 1, en fazla o sıradaki taşların tümünü alabilirsiniz.
- Son taşı alan oyuncu oyunu kaybeder.
- Kuantum bilgisayarı, hamlelerini kuantum hesaplama kullanarak yapmaktadır.

## 🎮 Nasıl Oynanır?

1. Oyunu başlatın.
2. Oyuncu olarak bir sıradan taş seçin ve "Tamam" butonuna basın.
3. Kuantum bilgisayarı hamlesini yapacaktır.
4. Oyun, bir oyuncu son taşı almak zorunda kalana kadar devam eder.

## 🚀 Kurulum

Projeyi çalıştırmak için aşağıdaki adımları takip edebilirsiniz:

### 1️⃣ Gerekli Bağımlılıkları Kurun

Python ve Pygame'in yüklü olduğundan emin olun. Eğer yüklü değilse aşağıdaki komutları çalıştırabilirsiniz:

```bash
pip install pygame
```

### 2️⃣ Depoyu Klonlayın

```bash
git clone https://github.com/kullanici/qnim.git
cd qnim
```

### 3️⃣ Oyunu Başlatın

```bash
python main.py
```

## 🛠 Proje Yapısı

```
qnim/
│-- src/
│   │-- board.py        # Oyun tahtasını yönetir
│   │-- constants.py    # Sabit değerler (renkler, boyutlar vb.)
│   │-- button.py       # Buton mekanikleri
│   │-- home.py         # Ana menü ekranı
│   │-- config.py       # Oyun ayarları
│   │-- qnim.py         # Kuantum hesaplamalar
│-- main.py             # Oyunun ana çalışma dosyası
│-- README.md           # Bu dosya
```
