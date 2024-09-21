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

![Screenshot 2024-09-19 012100](https://github.com/user-attachments/assets/3ba58c86-5140-4383-a81c-3b7344571dc0)

![Screenshot 2024-09-19 011637](https://github.com/user-attachments/assets/6fd41725-e9f9-4de3-9400-7b9ef1cbdfbc)

Domain : www.its.ac.id

IP Domain :  103.94.189.5

untuk melakukan JARM :

-Install python
-Download jarm.py pada https://github.com/salesforce/jarm/blob/master/jarm.py


JARM Fingerprint : 2ad2ad16d2ad2ad22c2ad2ad2ad2ad74aaecca9f9c4a3303863dfee62b241e

Flag : JarkomIT{Dn5_C0rR34t10n_HzR2WyVLF2AIsEY8T4OOcG91Dr1zZQCGzyNcMah0otP08WTPjZDFQE1T5}


### Gajah Terbang (Server Recon)

![Screenshot 2024-09-19 012531](https://github.com/user-attachments/assets/4bec1a6c-e1fa-41e9-954b-0490c8595cf9)

![Screenshot 2024-09-19 012613](https://github.com/user-attachments/assets/1fa16b6a-79ac-4c11-8017-cded23cbc619)


DBMS : PostgreSQL

Port : 6969

OS : Debian

credentials username DBMS : s1gm4

nama database : sigmaskibidigyatrizzzz

berapa banyak users dalam database : 4

email yang digunakan oleh admin : jojohermawan@gmail.com

password admin : admin1234 dari c93ccd78b2076528346216b3b2f701e6 (MD5)

![Screenshot 2024-09-19 014904](https://github.com/user-attachments/assets/276fd7cb-ed0f-4c6b-a8b8-7fc70fe858da)

Flag : JarkomIT{Gy4tT_M5g_4U_NM7KknbO9OYnH5ZARGyhmIIUR5k1V027ipezzm7Z8iuOeSU4zWvMFBiD1}


### Gajah Terbang (Attacker Recon)

![Screenshot 2024-09-19 012531](https://github.com/user-attachments/assets/4bec1a6c-e1fa-41e9-954b-0490c8595cf9)

![Screenshot 2024-09-19 012613](https://github.com/user-attachments/assets/1fa16b6a-79ac-4c11-8017-cded23cbc619)


Akun apa yang dimiliki oleh penyerang dalam database :  kuntoajiisrillll@gmail.com

password yang digunakan oleh penyerang : kissme dari aa1cbddbb1667f7227bcfdb25772f85c (MD5)

![Screenshot 2024-09-19 014816](https://github.com/user-attachments/assets/58f290e8-9ceb-4e8c-a491-dc9bb5c881bc)

tanggal akun penyerang diban : 2024-06-09

Table apa saja yang dimodifikasi : users dan banned_users

Barang apa saja yang telah dibeli : rokok dan es krim

Berapa total transaksi : 24500

Flag : JarkomIT{G4jaH_K0k_t3RbaNG_GIgtXO5N9fGsYhpTTzBYcPPFeYntdKQoukw8fXXOU617467GQP4yVKt5}


### 22 Nightmare

![Screenshot 2024-09-19 013726](https://github.com/user-attachments/assets/206ca52b-956e-441d-9622-548177eca93f)

![Screenshot 2024-09-19 013932](https://github.com/user-attachments/assets/f6f7bf0d-a02e-40f3-9060-d3415781acd9)


File yang dikirim : Sh1k4.jpg
nama file yang dikirim : NUN

stream keberapa file kedua dikirim setelah file pertama : 141

Siapa asli nama pengirim : Torako Koshi

Flag : JarkomIT{Sh1k4n0ko_N0_k05h1tan_89CzvYufccSOHIP6SQUDGbVhw7Anzrep8F3fgKbKhAC50nYU39eXqUNU}

### Pegawai Negeri Sebelah
- buka package yang telah diberikan
- buka package dengan wireshark
- cari file yang mberkemungkinan terdapat clue
- lalu jawab nc yang telah diberikan dan dapatkan flagnya
  <img width="474" alt="image" src="https://github.com/user-attachments/assets/90a5b0d1-5214-49f5-8f21-3a1b8f9e8294">

### EZ
- buka package yang telah diberikan
- buka package dengan wireshark
- cari file yang mberkemungkinan terdapat clue
- lalu jawab nc yang telah diberikan dan dapatkan flagnya
  <img width="476" alt="image" src="https://github.com/user-attachments/assets/7c4c9917-1a7a-46e3-aa51-a1f0e49ac699">

### FTP Login
- buka package yang telah diberikan
- buka package dengan wireshark
- cari file yang mberkemungkinan terdapat clue
- lalu jawab nc yang telah diberikan dan dapatkan flagnya
  <img width="476" alt="image" src="https://github.com/user-attachments/assets/9d267fbd-29ca-4a7d-a9d3-7293f05caf5a">

### Surprise
- buka package yang telah diberikan
- buka package dengan wireshark
- cari file yang mberkemungkinan terdapat clue
- lalu jawab nc yang telah diberikan dan dapatkan flagnya
<img width="475" alt="image" src="https://github.com/user-attachments/assets/b9d46e4b-a67b-4e3e-b3dd-8586dff0d9be">
<img width="473" alt="image" src="https://github.com/user-attachments/assets/9c23947b-ae70-4659-8f26-fd1bae95fceb">

### Corporate Breach
- buka package yang telah diberikan
- buka package dengan wireshark
- cari file yang mberkemungkinan terdapat clue
- lalu jawab nc yang telah diberikan dan dapatkan flagnya
<img width="473" alt="image" src="https://github.com/user-attachments/assets/a2ef5807-77f6-4c71-be07-f54d295d6b34">






