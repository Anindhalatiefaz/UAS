# UAS
# Nama  : Anindha Latiefa Zahra 
# NIM   : 312210323
# Kelas : TI.22.A.3 
# Package & Module 

<img width="481" alt="soal uas" src="https://user-images.githubusercontent.com/115516800/211361198-73b4c3d8-da55-4b85-a4da-43aefea55a5a.png">

Package seperti gambar diatas 

![Screenshot (275)](https://user-images.githubusercontent.com/115516800/211364409-b390234f-0437-4280-96d7-89c96f03ff1d.png)

```daftar_nilai.py``` berisi modul :
1. tambah_data
2. ubah_data
3. hapus_data
4. cari_data

```view_nilai.py``` berisi modul :
1. cetak_daftar_nilai
2. cetak_hasil_pencarian

```input_nilai.py``` berisi modul :
1. input_data, yang meminta pengguna untuk memasukkan data.

```main.py``` berisi program utama 


from model.daftar_nilai import *

from view.view_nilai import *

#Mulai
print("===============================================================")
print("|                           Program                           |")
print("===============================================================")

while True:
    print("\n")
    menu = input("(L) Lihat, (T) Tambah, (H) Hapus, (U) Ubah, (C) Cari, (K) Keluar\nPilih menu: ")
    print("\n")

    # menu
    if menu.lower() == 't':
        tambah_data()

    elif menu.lower() == 'c':
        cari_data()

    elif menu.lower() == 'l':
        lihat_data()

    elif menu.lower() == 'u':
        ubah_data()

    elif menu.lower() == 'h':
        hapus_data()

    # Keluar
    elif menu.lower() == 'k':
        break

    else:
        print("Upss ada yang salah, silahkan cek kembali.") 
    
# output tambah data

![Screenshot (276)](https://user-images.githubusercontent.com/115516800/211364666-f084ef82-82fa-4243-9321-d71d7d2e1225.png)

# output lihat data 

![Screenshot (277)](https://user-images.githubusercontent.com/115516800/211364898-180761c3-3874-4e81-b5e8-b45a783e4375.png)

# output ubah data 

![Screenshot (278)](https://user-images.githubusercontent.com/115516800/211365251-33f5e652-87d0-4323-a6a0-d574cb361583.png)

# output hapus data 

![Screenshot (279)](https://user-images.githubusercontent.com/115516800/211365422-aec57af4-b355-4364-92a0-ce47b1df5969.png)

# keluar 

![Screenshot (280)](https://user-images.githubusercontent.com/115516800/211365519-e3b8bf76-0231-42f1-b079-a206151a41f7.png)
