# 🦌 Rfi88 Browser v1.0 - Kijang R88 Edition

Lightweight Fedora Browser with YouTube AdBlocker, Eco Mode 144p, & Download Manager

[[Copr build status](https://copr.fedorainfracloud.org/coprs/rofii159/Rfi88Browser/package/Rfi88Browser/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/rofii159/Rfi88Browser/)

[Rfi88 Browser](https://raw.githubusercontent.com/rfi88/rfi88-browser/main/screenshot.png)

### ✨ Fitur v1.0
- ✅ **YouTube AdBlocker Built-in** - Nonton tanpa iklan ganggu
- ✅ **Eco Mode 144p** - Hemat RAM & Kuota sampai 80%
- ✅ **aria2 Integration** - Download manager otomatis, lebih kenceng
- ✅ **Kijang R88 Icon** - Logo custom rusa R88
- ✅ **Homepage Lock** - Default: [rfi88.github.io](https://rfi88.github.io)

### 📦 Install Fedora 40/41/42/43/44

#### 
**Cara 1: Via Copr - Recommended 🔥**
Paling gampang, auto update:

sudo dnf copr enable rofii159/Rfi88Browser

sudo dnf install Rfi88Browser


**Cara 2: Download RPM Manual**
Buat yang mau file .rpm nya:

 Download dari Releases
 
wget https://github.com/rfi88/rfi88-browser/releases/download/v1.0/Rfi88Browser-1.0-1.fc43.x86_64.rpm

**Cara 3: Install langsung dari URL - Paling Gampang**

sudo dnf install https://github.com/rfi88/rfi88-browser/releases/download/v1.0/Rfi88Browser-1.0-1.fc43.x86_64.rpm

🛠 Build from Source

Buat yang mau compile sendiri:


### Install dependencies
sudo dnf install qt6-qtbase-devel qt6-qtwebengine-devel gcc-c++

### Build

tar -xzvf Rfi88Browser-1.0.tar.gz

cd Rfi88Browser-1.0

qmake6 && make -j$(nproc)

sudo make install


### 🗑️ Uninstall Rfi88 Browser
Kalo mau hapus total:
1. Hapus Aplikasi

sudo dnf remove Rfi88Browser

3. Hapus Repo Copr - Opsional

Biar gak auto-update lagi:

sudo dnf copr remove rofii159/Rfi88Browser

4. Hapus Config - Opsional

Kalo mau bersih total, hapus folder config:

rm -rf ~/.config/Rfi88Browser

rm -rf ~/.cache/Rfi88Browser



🐛 Lapor Bug / Request Fitur
Buka Issues: https://github.com/rfi88/rfi88-browser/issues

📜 License
GPLv3 © 2026 Rfi88
Ketapang, Kalimantan Barat, Indonesia
