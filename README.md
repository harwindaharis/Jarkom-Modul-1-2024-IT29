# KELOMPOK IT 29

## Anggota Team:
1. **Harwinda** - 5027231079
2. **Muhammad Syahmi Ash Shidqi** - 5027231085

## Write Up

### Advance Sanity Check
- membuka file dan mencari jawaban dari nc yaitu username dari pengirim, lalu follow TCP STREAM
  <img width="960" alt="image" src="https://github.com/user-attachments/assets/31e99695-2681-47f2-acf0-393a0e748ba4">
- menemukan jawaban dari nc yaitu username dari pengirim
  <img width="642" alt="image" src="https://github.com/user-attachments/assets/018177f1-b30e-4fb5-aa4f-9050226a0a2a">
- membuka file dan follow TCP STREAM
  <img width="960" alt="image" src="https://github.com/user-attachments/assets/c8b6708e-ebf2-43a5-95df-b57c99cc46cc"> 
- menemukan nama file yang dikirim beserta clue untuk mendapatkan pesan rahasia
  <img width="642" alt="image" src="https://github.com/user-attachments/assets/acc0c244-01a3-463f-b61a-d2278b5bbc7b">
-membuka ppt "soal shift" dan menemukan pesan rahasia
<img width="930" alt="image" src="https://github.com/user-attachments/assets/0b829994-1108-4950-86a9-912d749decb6">
- lalu decode menggunkan CyberChef from base64 dan dapatkan pesan rahasianya
  <img width="959" alt="image" src="https://github.com/user-attachments/assets/5a9b556d-bc5a-4e10-86c7-38ef10939e29">
- kemudian masukkan pada nc dan dapatkan Flagnya
<img width="473" alt="image" src="https://github.com/user-attachments/assets/d53a21e9-045e-4e55-939f-e29802960711">

### Ilegal Breakthrough

sumber

![Screenshot 2024-09-19 011914](https://github.com/user-attachments/assets/c8c8cd35-6c12-45ad-8cb7-e86066a8db16)

![Screenshot 2024-09-19 011449](https://github.com/user-attachments/assets/355f7972-71b7-4ce1-a821-cd584e68ec09)

IP : 172.21.88.207

Port : 1917

Endpoint : /ww1.php

Tools : ffuf-v2.1.0-dev

username : password = Redbaron:fly1ng4c3

Flag : JarkomIT{d34th_fr0m_th3_sky_lKy1BboESFfnn3zjhhUIFiP2gH1ANR6wqOfenMZ52VRyl9MpkDVoWW1}


### Rizzset 

![Screenshot 2024-09-19 011637](https://github.com/user-attachments/assets/6fd41725-e9f9-4de3-9400-7b9ef1cbdfbc)

Domain : www.its.ac.id

IP Domain :  103.94.189.5

JARM Fingerpront : 2ad2ad16d2ad2ad22c2ad2ad2ad2ad74aaecca9f9c4a3303863dfee62b241e

Flag : JarkomIT{Dn5_C0rR34t10n_HzR2WyVLF2AIsEY8T4OOcG91Dr1zZQCGzyNcMah0otP08WTPjZDFQE1T5}


### Gajah Terbang (Server Recon)

DBMS : PostgreSQL

Port : 6969

OS : Debian

credentials username DBMS : s1gm4

nama database : sigmaskibidigyatrizzzz

berapa banyak users dalam database : 4

email yang digunakan oleh admin : jojohermawan@gmail.com

password admin : admin1234

Flag : JarkomIT{Gy4tT_M5g_4U_NM7KknbO9OYnH5ZARGyhmIIUR5k1V027ipezzm7Z8iuOeSU4zWvMFBiD1}


### Gajah Terbang (Attacker Recon)

Akun apa yang dimiliki oleh penyerang dalam database :  kuntoajiisrillll@gmail.com

password yang digunakan oleh penyerang : kissme

tanggal akun penyerang diban : 2024-06-09

Table apa saja yang dimodifikasi : users dan banned_users

Barang apa saja yang telah dibeli : rokok dan es krim

Berapa total transaksi : 24500

Flag : JarkomIT{G4jaH_K0k_t3RbaNG_GIgtXO5N9fGsYhpTTzBYcPPFeYntdKQoukw8fXXOU617467GQP4yVKt5}


### 22 Nightmare

File yang dikirim : Sh1k4.jpg

nama file yang dikirim : NUN

stream keberapa file kedua dikirim setelah file pertama : 141

Siapa asli nama pengirim : Torako Koshi

Flag : JarkomIT{Sh1k4n0ko_N0_k05h1tan_89CzvYufccSOHIP6SQUDGbVhw7Anzrep8F3fgKbKhAC50nYU39eXqUNU}

