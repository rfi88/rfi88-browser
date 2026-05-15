# 🦌 Rfi88 Browser v1.0 - Kijang R88 Edition

Lightweight Fedora Browser with YouTube AdBlocker, Eco Mode 144p, & Download Manager

![Rfi88 Browser](https://raw.githubusercontent.com/rfi88/rfi88-browser/main/screenshot.png)

### ✨ Fitur v1.0
- ✅ **YouTube AdBlocker** Built-in - Nonton tanpa iklan
- ✅ **Eco Mode 144p** - Hemat RAM & Kuota sampe 80%
- ✅ **aria2 Integration** - Download manager kenceng otomatis
- ✅ **Homepage Lock** - Default: rfi88.github.io
- ✅ **Kijang R88 Icon** - Logo custom rusa R88

### 📦 Install Fedora 40/41/42/43
```bash
# Download dari Releases
wget https://github.com/rfi88/rfi88-browser/releases/download/v1.0/Rfi88Browser-1.0-1.fc43.x86_64.rpm

   [![Copr build status](https://copr.fedorainfracloud.org/coprs/rofii159/Rfi88Browser/package/Rfi88Browser/status_image/last_build.png)](https://copr.fedorainfracloud.org/coprs/rofii159/Rfi88Browser/)
   
   # Install
   sudo dnf copr enable rofii159/Rfi88Browser
   sudo dnf install Rfi88Browser

# Install + auto install aria2
sudo dnf install ./Rfi88Browser-1.0-1.fc43.x86_64.rpm

🛠️ Build from Source

# Dependencies
sudo dnf install qt6-qtbase-devel qt6-qtwebengine-devel gcc-c++

# Build
tar -xzvf Rfi88Browser-1.0.tar.gz
cd Rfi88Browser-1.0
qmake6 && make -j$(nproc)
sudo make install

📜 License
GPLv3 © 2026 Rfi88

