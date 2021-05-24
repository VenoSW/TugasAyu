# TUGAS 1
* Coding
```
print("Program Menyewa Buku\n")
print("Selamat datang dipenyewaan buku KITA, disini kalian bisa menyewa buku bermacam-macam dari komik, novel, biografi dan ilmu pengetahuan, berikut list harga buku\n")
print("1. Buku Komik Harga Sewa Rp. 2000")
print("2. Buku Novel Harga Sewa Rp. 4000")
print("3. Buku Biografi Harga Sewa Rp. 8000")
print("4. Buku Ilmu Pengetahuan Harga Sewa Rp. 5000\n")
print("List Diskon")
print("1. Jika mewnyewa buku Komik di Hari Jum'at - Minggu maka Diskon 20%")
print("2. Jika mewnyewa buku Biografi dan Ilmu Pengetahuan Diskon 30%")
print("1. Jika mewnyewa buku Novel di Hari Senin dan Kamis maka Diskon 15%\n")
print("Silahkan Input Data Sewa Dibawah\n")
judul_buku = input("Masukkan judul buku : ")
jenis_buku = input("Masukkan jenis buku : ")
lama_sewa = int(input("Masukkan Lama sewa (Hari) : "))
harga_sewa = int(input("Harga Sewa Buku : Rp. "))
diskon = int(input("Masukkan Voucher Diskon : "))
print("")
print("Buku yang disewakan : ", judul_buku)
print("Jenis Buku : ", jenis_buku)
print("Harga Sewa Sebelum Diskon : ", harga_sewa)
print("Harga Sewa Sedudah Diskon : ", harga_sewa*diskon/100)
```

# TUGAS 2
* Algoritma
```
1 kilometer = 0.62137
Cara merubah KM ke Mil : Kilometer x 0.62137
```
* Coding
```
kilometer = int(input("Masukkan Nilai Dalam Kilometers : "))
faktor_konversasi = 0.62137
mil = kilometer * faktor_konversasi
print(kilometer, "Kilometers sama dengan", mil, "miles")
```
# PRAKTIKUM PEMROGRAMAN PYTHON
## NO 1
* Coding
```
nama = "Nur Ayu Anjani Wibowo"
kelas = "X "
jurusan = "TKJ A"
sekolah = "SMK N 1 Cikarang Selatan"
hobi = "Renang"
nomor_hp = int("083806755027")
umur = int("15")

print("Hallo, perkenalkan nama saya", nama, "saya sekarang berada dikelas", kelas, jurusan, "saat ini saya bersekolah di", sekolah, "saya memiliki hobi", hobi, "umur saya sekarang", umur, "tahun, bagi teman-teman yang seumuran dan ingin berteman silahkan kontak nomor hp saya di", nomor_hp)
```
## NO 2
* Coding
```
print("Program Volume Balok\n")
panjang = int(input("Panjang Balok : "))
lebar = int(input("Lebar Balok : "))
tinggi = int(input("Tinggi Balok : "))
volume = panjang*lebar*tinggi
print("\nJadi Volume Balok tersebut : ", volume)
```
## NO 3
* Coding
```
print("Program Habitat Hewan\n")
habitat = ['laut', 'hutan', 'sungai', 'rawa', 'gurun']
nama_hewan = ['kodok', 'unta', 'hiu', 'harimau', 'lele']
print("Hewan", nama_hewan[0], "hidup di", habitat[3])
print("Hewan", nama_hewan[1], "hidup di", habitat[4])
print("Hewan", nama_hewan[2], "hidup di", habitat[0])
print("Hewan", nama_hewan[3], "hidup di", habitat[1])
print("Hewan", nama_hewan[4], "hidup di", habitat[2])
```
# PRAKTIKUM PERCABANGAN DALM PYTHON
## NO 1
* Algoritma
```
1. Jika angka tahun itu habis dibagi 400, maka tahun itu sudah pasti tahun kabisat.
2. Jika angka tahun itu tidak habis dibagi 400 tetapi habis dibagi 100, maka tahun itu sudah pasti bukan merupakan tahun kabisat.
3. Jika angka tahun itu tidak habis dibagi 400, tidak habis dibagi 100 akan tetapi habis dibagi 4, maka tahun itu merupakan tahun kabisat.
4. Jika angka tahun tidak habis dibagi 400, tidak habis dibagi 100, dan tidak habis dibagi 4, maka tahun tersebut bukan merupakan tahun kabisat.
```
* Coding
```
print("===== Program Mecari Tahun Kabisat =====")
tahun = int(input("Masukkan tahun untuk diperiksa : "))
if tahun % 400 == 0:
    print("Tahun tersebut adalah tahun kabisat")
elif tahun % 100 == 0:
    print("Tahun tersebut adalah bukan tahun kabisat")
elif tahun % 4 == 0:
    print("Tahun tersebut adalah tahun kabisat")
else:
    print("Tahun tersebut adalah bukan tahun kabisat")
```
## NO 2
* Coding
```
print("======= PROGRAM PREDIKAT NILAI RAPORT =======\n")
nilai = eval(input("Masukkan Nilai Raport : "))
if nilai >= 90:
    print("Predikat A")
elif nilai >= 80:
    print("Predikat B")
else:
    print("Predikat C")
```
## NO 3
* Coding
```
print("===== SELAMAT DATANG DI PROGRAM SELEKSI SNMPTN =====\n")
pilihan = input("Apakah anda ingin melanjutkan kuliah ?\n Y/y untuk Yes | N/n nutuk No\n")
if (pilihan == "y" or pilihan == "Y"):
    usia         = int(input("Masukkan usia Anda sekarang  : "))
    nilai_raport = int(input("Masukkan nilai Raport        : "))
    nilai_un     = int(input("Masukkan nilai UN            : "))
    if (usia >= 17 and usia <=20 and nilai_raport >= 85 and nilai_un >= 75):
        print("Selamat Anda memenuhi persyaratan untuk mengikuti SNMPTN!")
    else:
        print("Mohon maaf Anda tidak bisa mengikuti SNMPTN!")
else:
    print("Terimakasih sudah menggunakan Program Seleksi SNMPTN")
```
