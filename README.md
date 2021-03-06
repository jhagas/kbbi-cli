<h1 align=center>Kamus Besar Bahasa Indonesia (KBBI) <i>CLI-Script</i></h1>

Cari makna kata dari KBBI? Cari aja disini. Cukup dengan mengetikkan kata yang ingin anda cari, ENTER dan langsung keluar hasilnya. Namun perlu diperhatikan bahwa **KONEKSI INTERNET DIBUTUHKAN**!!

<div align=center>
<br><i>Seperti inilah contoh penggunaan script ini..</i>
<img src=demo.gif style=width:80%>
</div>

----
<h1 align=center>Pemasangan</h1>

## _Dependency_, Persyaratan
_Script_ ini menggunakan `w3m` dan `ncurses-utils` agar bisa berjalan dengan baik. Pastikan `w3m` dan`ncurses-utils` telah terinstall di sistem **linux** anda

### Linux
Install dependensi yang diperlukan (berbeda-beda tergantung distro yang anda pakai). Lalu, salin perintah ini di **terminal linux** anda dan tekan ENTER
```bash
sudo curl -sL https://github.com/jhagas/kbbi-cli/raw/main/kbbi -o /usr/local/bin/kbbi
sudo chmod +x /usr/local/bin/kbbi
```

### Android
Saya sangat sarankan untuk menggunakan [Termux](https://play.google.com/store/apps/details?id=com.termux&hl=en&gl=US) saat menjalankan script ini.
```bash
pkg install w3m ncurses-utils -y
curl -sL https://github.com/jhagas/kbbi-cli/raw/main/kbbi -o /data/data/com.termux/files/usr/bin/kbbi
chmod +x /data/data/com.termux/files/usr/bin/kbbi
```


### Windows
Script ini tidak berjalan di Windows secara _native_, namun anda bisa menggunakan fitur [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10) (Windows Subsystem for Linux) pada Windows 10. Lalu jalankan proses pemasangan seperti halnya untuk Linux.

----
<h2 align=center>CARA PENGGUNAAN</h1>
Buka **terminal linux** anda dan ketikkan..
`kbbi [opsi] [kata yang ingin dicari]`

**Opsi yang tersedia**
|OPSI|Kegunaan
|---|---|
|-h or --help|Untuk Menampilkan tulisan bantuan|

---
<h1 align=center><i>DISCLAIMER</i></h1>

Semua hasil pencarian script ini diambil dari situs https://kbbi.kemdikbud.go.id.
>Batas pencarian harian ditentukan oleh situs tersebut, Bukan kehendak saya untuk membatasi anda.
Silahkan gunakan proxy atau VPN..

© 2016 Badan Pengembangan dan Pembinaan Bahasa, Kementerian Pendidikan dan Kebudayaan Republik Indonesia.
Versi daring: 3.5.1.1-20201226171802
