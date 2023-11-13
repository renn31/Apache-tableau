# Apache-tableau
Percobaan ini akan menginstal Apache pada server Ubuntu dan menampilkannya di peramban web. Selanjutnya, percobaan berikutnya akan melakukan koneksi remote SSH ke Putty, ke CMD pada Windows, dan pada terminal di desktop Ubuntu.

## Menginstall apache2 pada ubuntu server

Masuk ke ubuntu server menggunakan login user

masuk sebagai user root
```bash
sudo su
```

lakukan penginstalan Apache2 menggunakan perintah berikut
```bash
apt install apache2
```
## Uji Apache2

Untuk menguju apakah Apache berjalan dengan baik, dapat ditampilkan pada browser web dengan mengakses IP address.

Lakukan perintah berikut untuk melihat IP address
```bash
hostname -I
```
Kemudian buka web browser, masukkan IP tersebut ke dalam pencarian. Jika yang muncul adalah tampilan default Apache2 maka dapat disimpulkan Apache2 telah berhasil diinstall dan berjalan.

## Melakukan remote ssh dengan PuTTY

Buka aplikasi PuTTY, pastikan server ubuntu dalam keadaan online. Masukkan IP Address pada kolom yang disediakan, pilih connection type SSH.

Klik open untuk memulai koneksi, kemudiankan
masukkan username dan password yang akan digunakan sebagai login user.

## Melakukan romote dengan ubuntu desktop

Untuk melakukan remote ke ubuntu desktop digunakan protokol SSH(Secure Shell) untuk mengakses shell jarak jauh, dengan menggunakan perintah:
```bash
ssh username@IPaddress-ubuntuserver
```
Gantilah username dengan nama pengguna Anda dan IPaddress-ubuntuserver dengan IP addres server ubuntu.

## Melakukan remote CMD Windows

Melakukan remote dengan CMD di windows dengan menggunaan SSH dapat dilakukan dengan mengetikkan perintah 
```bash
ssh usename@IPaddress-ubuntuserver
```
Gantilah username dengan nama pengguna Anda dan IPaddress-ubuntuserver dengan IP addres server ubuntu.




