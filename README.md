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

untuk melakukan JARM =

-Install python

-Download jarm.py pada https://github.com/salesforce/jarm/blob/master/jarm.py
![Screenshot 2024-09-21 160248](https://github.com/user-attachments/assets/3516a6e5-42d8-4223-b9b9-5e58fd8d938a)


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

untuk mendapatkan nama file =

- export file dari paket

-![Screenshot 2024-09-21 161316](https://github.com/user-attachments/assets/4cf48182-7b3d-4f8a-a711-8f75a02445ba)
  
- buka file Sh1k4.jpg

- ![Sh1k4](https://github.com/user-attachments/assets/459e4eb5-3299-423f-995c-09330afd66d7)161316](https://github.com/user-attachments/assets/55e08879-142f-46a8-a804-1a8cc96ef93e)

nama file yang dikirim : NUN

mencari file ke-2 =

- gunakan filter `tcp contains "STOR"`

![Screenshot 2024-09-21 162013](https://github.com/user-attachments/assets/b685972e-7b6b-44b3-b0d9-c9fa329a64a9)

stream keberapa file kedua dikirim setelah file pertama : 141

untuk mendapatkan nama asli pengirim :

- Buka file noko.py yg telah di export
  
- isi file
```
Import Shika

Class Noko
    input = int
    key = String
    value = String
    
    # input = 001001100011010000100010001000100011101001101110001001110011100001101110000110100011101000111100001011110011111000100001011011100001111000100001001111010011110100100111
    
    key = jpg msg
    
    op xor bit
```


- jalankan filenya

Siapa asli nama pengirim : Torako Koshi

Flag : JarkomIT{Sh1k4n0ko_N0_k05h1tan_89CzvYufccSOHIP6SQUDGbVhw7Anzrep8F3fgKbKhAC50nYU39eXqUNU}


### Pegawai Negeri Sebelah
- Tampilan nc dan mendapatkan Flagnya
  ![image](https://github.com/user-attachments/assets/ef8f1528-8c93-44a2-b012-88e596482d08)

<details>
  <summary>Berikut Tahapannya</summary>
- Buka package Rahasia.pcap
  
  ![image](https://github.com/user-attachments/assets/2bbc316d-f6fa-4e43-8519-d942c74d6c75)
  
  *pada package 47, terdapat semua data yang bisa dijawab pada nc*

⛳ **JarkomIT{Tum8eN_p45SnYa_Ku4t_B1aS4Nya_vcBRw42hH9MQusu1gPINKxmdjL32DSVAkEVPrmOXDFoxadjF2usOM4h}** 
</details>

### EZ
- Tampilan nc dan mendapatkan Flagnya
![image](https://github.com/user-attachments/assets/53497418-688e-4944-aab9-43c9d72db46a)

<details>
  <summary>Berikut Tahapannya</summary>
    - Buka package ez.pcapng
  
   ![image](https://github.com/user-attachments/assets/02d77fe0-2b82-43f8-908d-8339dac8bd1f)
   
  *pada file 1144, terdapat semua data yang bisa dijawab pada nc (string sebelah kanan atau folow tcp dan port sebelah kiri yang “Dsrt Port”*
    
⛳ **JarkomIT{BiAr_aman_Pake_sSh_FcBhHi1CtvVTsl4RU5TEZBDMf3ztj4ewG6eXUlZK8CxmQMbsGtTpEZ}**
</details>


### FTP Login
- Tampilan nc dan berhasil mendapatkan Flagnya
![image](https://github.com/user-attachments/assets/66d08b37-c121-4da9-90b3-859efcae508c)

<details>
<summary>Berikut Tahapannya</summary>
    - Buka package ftplogin.pcapng
    
   ![image](https://github.com/user-attachments/assets/63879f0e-3537-4bce-a675-3351ba4f1f01)
   
  *pada file 222 (warananya beda sendiri) follow TCP dan dapatkan jawaban dari nc lalu dapatkan Flagnya*
    
⛳ **JarkomIT{n0t_s0_s3cur3_ftp_wZlZOhaA92SsDyrMWlUyq29v4L0wFzPnFVNli8t4gstnQP72pOzRG1N}**
 </details>   


### Surpise
- Tampilan nc dan berhasil mendapatkan Flagnya
![image](https://github.com/user-attachments/assets/37b4c11d-99a1-4425-998b-00fe395ff30c)
![image](https://github.com/user-attachments/assets/f4de1488-869d-4b7b-95fd-ddb531a9f7cf)

<details>
  <summary>Berikut Tahapannya</summary>
  - Buka package ftplogin.pcapng
    
   ![image](https://github.com/user-attachments/assets/742685ba-0f25-4927-b4fe-505ea88d94ef)
  
  *pada file 234  follow TCP dan dapatkan jawaban dari nc ( service yang digunakan bagian atas banget)  file yang dikirmkan yaitu g0tcha*
    
  - Buka file 243
      
    ![image](https://github.com/user-attachments/assets/13ad3c5f-f7f0-4b8c-898b-bc2248ef24e6)
      
     *pada file terdapat code cpp.* 
    
 - compile dan dapatkan pesannya untuk menjawab nc
  
    ![image](https://github.com/user-attachments/assets/a61730af-4af2-4e7d-965b-a7e7512b3f1e)
      
⛳ **JarkomIT{l1ttl3_m0us3_1n_th3_h0us3_Z5rnnFeArDKwivWLUu8GpXt6fG0u5g4Q67IfcPaRcB2QFThtmzR1TCHU}**
   </details> 
  





    
  
### Pegawai Negeri Sebelah
- Tampilan nc dan berhasil mendapatkan Flagnya
  
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






