# TUGAS 1
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
```
kilometer = int(input("Masukkan Nilai Dalam Kilometers : "))
faktor_konversasi = 0.62137
mil = kilometer * faktor_konversasi
print(kilometer, "Kilometers sama dengan", mil, "miles")
```
