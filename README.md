# DHCP dan Wireless
**LAPORAN KONFIGURASI DHCP & WIRELESS**

Nama	: Cisa Livia Virnandyka

NIM	: 09010182327016

Kelas	: MI3A

MK	: Praktikum Jaringan Komputer

## A. PERCOBAAN DHCP
1.	Buat Topologi.
2.	Pasang Kabel Copper Straight dari PC ke Switch terhubung.
   
     ![image](https://github.com/user-attachments/assets/7af05a48-50cf-43c1-959f-cd9316659399)
  	
3.	Setelah itu, kita menyalakan switch daya dan tunggu beberapa menit, router akan menyala.
4.	Setelah looding router selesai, kita lanjutkan konfigurasinya.
     ![image](https://github.com/user-attachments/assets/095a6916-44fa-4be9-9911-a4f125c6e893)
5.	Setelah itu lakukan konfigurasi DHCP client pada PC.
     ![image](https://github.com/user-attachments/assets/40ed6f51-78ab-4e62-b384-4d5ed6f78315)
     ![image](https://github.com/user-attachments/assets/3efd0f74-9e29-4c66-81d6-79c4f6f23cc5)
     ![image](https://github.com/user-attachments/assets/780e5957-c853-4028-9bf5-a67f249039ed)

6.	Setelah itu Melihat daftar IP dari Client
    ![image](https://github.com/user-attachments/assets/77b851cc-65fc-4e94-94a0-960c89d3d646)
    ![image](https://github.com/user-attachments/assets/5de31578-68bf-4dbc-a142-830c37f97def)

7.	Setelah itu lakukan pengalamatan ip pada Client/PC
    ![image](https://github.com/user-attachments/assets/1f93b23b-cf74-47b7-b27a-368e8d31630f)

8.	Lakukan pengujian PING pada setiap PC
    ![image](https://github.com/user-attachments/assets/84cf8df0-9543-49e0-950b-d86ff9b4a6e3)
    ![image](https://github.com/user-attachments/assets/6ebf1cb0-9d6b-4144-a822-11028dfa9ef9)
    ![image](https://github.com/user-attachments/assets/5134fcf4-02e8-4ba8-a228-b3398df7292c)
    ![image](https://github.com/user-attachments/assets/714155ca-559d-4b0b-bce5-025d8f2e1639)


## B. PERCOBAAN WIRELESS
1.	Buat Topologi Seperti Gambar diatas (note*: Gantilah device tablet menjadi laptop pada topologi diatas dan harus terhubung secara wireless

    ![image](https://github.com/user-attachments/assets/c89754ac-8541-4dc4-aabc-529fa3675d9b)

2.	Konfigurasi Access Point
- Klik Wireless Router pada topologi.
- Buka tab GUI.
- Masukkan IP Address: 192.168.0.1 dan Subnet Mask: 255.255.255.0.
- Aktifkan DHCP Server dengan mengaturnya ke Enabled.
- Setel Start IP Address ke 192.168.0.100.
- Tentukan jumlah maksimum pengguna IP DHCP sesuai kebutuhan.
- Simpan pengaturan dengan mengklik Save Settings.
 ![image](https://github.com/user-attachments/assets/28745441-4948-4ed3-bc08-73b9e28ce548)

- Buka tab Wireless -> Basic Wireless Settings.
- Setel SSID ke LabJarkom.
- Klik Save Settings untuk menyimpan.
 ![image](https://github.com/user-attachments/assets/70ab12dd-8234-4518-8c22-b567d6de100d)

- Buka tab Wireless -> Wireless Security.
- Setel Security Mode ke WPA2 Personal.
- Pilih Encryption: AES.
- Masukkan Passphrase: 12345678.
- Simpan pengaturan dengan mengklik Save Settings.
 ![image](https://github.com/user-attachments/assets/dc67f610-5f81-4429-8a6e-8a2a8b3cad72)

3. Konfigurasi Client

  Konfigurasi Laptop0
  1.	Buka tab Config pada Laptop0.
  2.	Setel SSID ke LabJarkom.
  3.	Pilih Authentication: WPA2-PSK.
  4.	Masukkan Pass Phrase: 12345678.
  5.	Pilih IP Configuration: DHCP (IP akan otomatis diberikan jika DHCP server aktif).
   ![image](https://github.com/user-attachments/assets/40a7e49e-2bb0-401b-a33f-15a018c6f73e)

  Konfigurasi Laptop1
  1.	Buka tab Config pada Laptop1.
  2.	Setel SSID ke LabJarkom.
  3.	Pilih Authentication: WPA2-PSK.
  4.	Masukkan Pass Phrase: 12345678.
  5.	Pilih IP Configuration: DHCP (IP akan otomatis diberikan jika DHCP server aktif).
  ![image](https://github.com/user-attachments/assets/73f2689a-582b-4735-91b8-b3093ddb3679)

 
4. Pengujian PING
+	Di PC Tablet, pilih tab/menu Desktop -> Command Prompt
+	Jalankan perintah Ping ke IP Access Point 192.168.0.1
+	Ping IP  Laptop0 ke Laptop1

![image](https://github.com/user-attachments/assets/8e19984f-3394-43bf-a20e-4b6d6924750f)
+ Ping Laptop1 ke Laptop0

 ![image](https://github.com/user-attachments/assets/feb2aacb-c61c-4c84-a606-2a0c20567e4b)
