# M.Hakeem Alqardhawi 09011282328072 SK3C
Menginstal dan konfigurasi SSH

1.Instal SSH

untuk menginstal SSH gunakan command sudo apt install openssh-server
![image](https://github.com/user-attachments/assets/ecf257bb-0d9e-4665-8e0e-5b4420ff537c)

2.mengaktifkan SSH

untuk mengaktifkan SSH gunakan command sudo systemctl enable --now ssh
--now digunakan agar SSH diaktifkan ketika proses booting

![image](https://github.com/user-attachments/assets/e45af64c-83c5-4ae1-acad-a4110d4641bc)

gunakan command sudo systemctl status ssh untuk memeriksa status SSH

![image](https://github.com/user-attachments/assets/1c6aba51-e5d2-4328-bdfa-103cfc483fd4)

gunakan command sudo systemctl disable ssh untuk menonaktifkan SSH

![image](https://github.com/user-attachments/assets/60c16f98-2c4c-496b-a205-1078ee3ca611)

3.konfigurasi firewall

gunakan command sudo ufw status untuk memeriksa jika ufw telah terinstal

![image](https://github.com/user-attachments/assets/7f085521-9dc2-464a-9457-572554242e02)

jika terdapat daftar pada output, maka koneksi SSH diizinkan jika tidak, maka perlu diberi izin dengan command 
![image](https://github.com/user-attachments/assets/39740f85-89c8-4c07-a834-915ad4b77182)

4.menyambung ke server
ssh username@alamat ip atau ssh username@domain
![image](https://github.com/user-attachments/assets/a4504a38-f262-4768-9255-292f1587df97)

untuk memeriksa alamat ip
![image](https://github.com/user-attachments/assets/115e1948-1598-4dab-882a-508d7044db70)
