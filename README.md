# Zphisher

<p align="center">
  <img src="https://raw.githubusercontent.com/wanzxploit/zphisher/refs/heads/master/logo.png" alt="Logo">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Version-2.3.5-green?style=for-the-badge">
  <img src="https://img.shields.io/github/license/wanzxploit/zphisher?style=for-the-badge">
  <img src="https://img.shields.io/github/stars/wanzxploit/zphisher?style=for-the-badge">
  <img src="https://img.shields.io/github/issues/wanzxploit/zphisher?color=red&style=for-the-badge">
  <img src="https://img.shields.io/github/forks/wanzxploit/zphisher?color=teal&style=for-the-badge">
</p>

<p align="center">
  <b>Zphisher adalah tool phishing otomatis dengan lebih dari 30+ template login, dirancang ramah untuk pemula.</b>
</p>

---

## Disclaimer

<i>Penggunaan Zphisher sepenuhnya merupakan tanggung jawab Anda. Penyalahgunaan toolkit ini dapat mengakibatkan <b>tuntutan pidana</b> terhadap individu yang bersangkutan. Kami tidak bertanggung jawab atas tindakan ilegal yang dilakukan menggunakan toolkit ini.

<b>Toolkit ini dibuat untuk tujuan edukasi saja</b>. Harap jangan gunakan untuk melanggar hukum. Jika tujuan Anda adalah menggunakan ini secara ilegal, <b>silakan tinggalkan repositori ini</b>. Toolkit ini bertujuan untuk menunjukkan "bagaimana phishing bekerja" tanpa melanggar privasi siapa pun.</i>

---

## Fitur

- Halaman login terbaru dan diperbarui.
- Mudah digunakan untuk pemula.
- Pilihan tunneling yang beragam:
  - Localhost
  - Cloudflared
  - LocalXpose
- Dukungan Mask URL.
- Dukungan Docker.

---

## Cara Instalasi

### Clone Repository
```bash
git clone --depth=1 https://github.com/wanzxploit/zphisher.git
```

Masuk ke direktori dan jalankan script utama:
```bash
cd zphisher
bash zphisher.sh
```

Pada peluncuran pertama, semua dependensi akan diinstal secara otomatis.

### Instalasi di Termux
```bash
pkg install tur-repo
pkg install zphisher
zphisher
```

**Catatan**: Termux melarang diskusi tentang hacking di grup diskusinya. Pastikan Anda mematuhi kebijakan mereka. Informasi lebih lanjut tersedia di [Termux Wiki](https://wiki.termux.com/wiki/Hacking).

### Instalasi via File .deb

1. Unduh file `.deb` dari [**Rilis Terbaru**](https://github.com/wanzxploit/zphisher/releases/latest).
2. Instal file `.deb`:
```bash
apt install ./path/to/your.deb
```

Atau:
```bash
dpkg -i ./path/to/your.deb
apt install -f
```

---

## Menjalankan di Docker

- **DockerHub**:
```bash
docker pull wanzxploit/zphisher
```

- Jalankan kontainer sementara:
```bash
docker run --rm -ti wanzxploit/zphisher
```
Pastikan Anda mount direktori `auth` untuk menyimpan data.

---

## Dependensi

Zphisher membutuhkan program berikut:
- `git`
- `curl`
- `php`

Dependensi akan otomatis diinstal saat Zphisher pertama kali dijalankan.

---

## Sistem yang Diuji

- **Ubuntu**
- **Debian**
- **Arch Linux**
- **Manjaro**
- **Fedora**
- **Termux**

---

## Kontribusi

Proyek ini adalah hasil forked dari repositori [Zphisher](https://github.com/htr-tech/zphisher). Terima kasih kepada semua kontributor sebelumnya atas fondasi yang telah dibuat.

---

## Preview Alur Kerja

<p align="center">
  <img src="https://raw.githubusercontent.com/wanzxploit/zphisher/refs/heads/master/workflow.gif" alt="Workflow">
</p>

---

**Catatan Penting**: Tool ini dirancang untuk tujuan edukasi dan pengujian keamanan saja. Jangan gunakan untuk tindakan ilegal. Selalu pahami hukum setempat sebelum menggunakan alat ini.
