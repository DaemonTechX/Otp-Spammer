<h1 align="center"><code>OTP-SPAMMER</code></h1> <p align="center"> <img src="https://github.com/DaemonTechX/Otp-Spammer/blob/main/Screenshot_20251028-204245.png" width="800"><br><br>

_Sebuah alat yang berfungsi untuk mengirimkan banyak kode OTP secara beruntun dengan tujuan menyepam ataupun membanjiri kolom pesan target_

_untuk menggunakan alat ini kalian cukup menjalankan perintah ini di termux_
```bash
pkg update && pkg upgrade

plg install python

pkg install python-pip

pkg install bash

pkg install git

git clone https://github.com/DaemonTechX/Otp-Spammer

cd Otp-Spammer

ls

pip install requests

bash start.sh
```

_jika sudah menjalankan seluruh perintah nya di atas lalu Ingin menjalankan alat nya lagi maka cukup jalankan perintah ini_
```bash
cd $HOME # Berfungsi Untuk Kembali Ke Directory Utama Di Termux

cd Otp-Spammer # Berfungsi Untuk Berpindah Directory Dari Directory Utama Termux Pindah Ke Directory Otp-Spammer

bash start.sh # Menjalankan Program Utama Untuk Menggunakan Alat Otp Spammer
```
