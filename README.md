# labpy03
## Nama : Althaf Afif Faiz ##
## NIM : 312410404 ##
## Kelas: TI.24.A.3 ##

# Latihan Python #

## Random Number Generator (latiha1.py) 
Sebuah program yang akan menggenerate angka random kurang dari 0,5 berdasrkan input user.

## Code Latihan 1 ##
![code latihan 1](https://github.com/user-attachments/assets/34f3584a-b163-4215-855c-f10d525ce5c5)

## Hasil Latihan 1 ##
![Hasil latihan 1](https://github.com/user-attachments/assets/10715f66-3d24-4f7c-b835-5e89e1020a45)


## Algoritma ##

```
python
1. Import random library
2. Minta input N dari user
3. Loop N times:
   - Generate random number between 0 and 1
   - Bagi dengan 2 untuk memastikan angka < 0.5
   - Tampilkan output
4. Print "Selesai" saat selesai
```
## Example Output

```python
## Example Output

```python
Masukkan nilai N: 5
data ke: 1 => 0.17294922043570056
data ke: 2 => 0.08717360127477924
data ke: 3 => 0.050516076545020832
data ke: 4 => 0.27535124215716744
data ke: 5 => 0.39262323600723776
Selesai
```
## Investment Profit Calculator (latihan2.py)
Program yang menghitung laba bulanan untuk investasi selama 8 bulan dengan tingkat laba yang bervariasi.

## Code Latihan 2 ##

![code latihan 2](https://github.com/user-attachments/assets/b1802b6a-c1c6-4013-a42e-95e456bac4a4)

## Hasil Latihan 2 ##

![Hasil latihan 2](https://github.com/user-attachments/assets/9dd26702-58f7-4fe9-bfa1-9b9d5343e404)

## Algorithm

```python
1. Tetapkan modal awal = 100.000.000
2. Buat list kosong untuk menyimpan laba bulanan
3. Lakukan perulangan selama 8 bulan:
   - Bulan 1-2: laba 0%
   - Bulan 3-4: laba 1%
   - Bulan 5-7: laba 5%
   - Bulan 8: laba 2%
4. Untuk setiap bulan:
   - Hitung laba berdasarkan persentase
   - Tampilkan laba bulanan
   - Simpan laba dalam list
5. Hitung dan tampilkan total laba
```

## Example Output

```python
laba bulan ke- 1 sebesar: 0
laba bulan ke- 2 sebesar: 0
laba bulan ke- 3 sebesar: 10000000.0
laba bulan ke- 4 sebesar: 10000000.0
laba bulan ke- 5 sebesar: 50000000.0
laba bulan ke- 6 sebesar: 50000000.0
laba bulan ke- 7 sebesar: 50000000.0
laba bulan ke- 8 sebesar: 20000000.0
Total laba adalah: 190000000.0
```

## ATM Sederhana (latihan3.py)
Program ini akan mensimulasikan mesin ATM sederhana dengan fitur penarikan uang, pengecekan saldo, keluar.

## Code Latihan 3 ##

![code latihan 3](https://github.com/user-attachments/assets/22af1b80-d08e-4b26-a523-7bd332896931)


# Hasil Latihan 3 #

## Hasil menu 1 ##
![Hasil latihan 3](https://github.com/user-attachments/assets/d3449ec8-dcbb-4eb9-a894-bbeef48a44e4)

## Hasil menu 2 ##
![Hasil latihan 3(2)](https://github.com/user-attachments/assets/eb113e5e-b2f0-4598-bde7-1d0efade8072)

## Hasil menu 3 ##
![Hasil latihan 3(3)](https://github.com/user-attachments/assets/f1bf0a28-5257-467c-b1b8-3a0421f7c4ee)

## Algorithm

```python
1. Inisialisasi:
   - Set saldo awal = Rp 100.000

2. Mulai perulangan utama:
   a. Tampilkan informasi:
      - Saldo saat ini
      - Menu pilihan (1. Tarik Uang, 2. Cek Saldo, 3. Keluar)

   b. Minta input pilihan menu dari pengguna

   c. Jika pilihan = 1 (Tarik Uang):
      - Minta input jumlah penarikan
      - Cek apakah jumlah <= saldo
      - Jika ya: kurangi saldo dan tampilkan pesan sukses
      - Jika tidak: Saldo tidak cukup untuk melakukan penarikan

   d. Jika pilihan = 2 (Cek Saldo)
      - Tampilkan saldo saat ini

   e. Jika pilihan = 3 (Keluar):
      - Tampilkan pesan Terima kasih telah menggunakan Mesin ATM Sederhana. Selamat tinggal Orang Baik!
      - Keluar dari program

   f. Jika pilihan tidak valid:
      - Tampilkan pesan Pilihan tidak valid. Silakan coba lagi
      - Kembali ke awal perulangan

3. Program selesai
```

## Program Details
## latihan1.py
1. Menggunakan modul random Python
2. Menerapkan validasi input
3. Menghasilkan angka dalam rentang [0, 0,5)
4. Memformat output sesuai spesifikasi
## latihan2.py
- Modal awal tetap: Rp 100.000.000
- Menghitung laba selama 8 bulan
- Tingkat laba bervariasi:
1. Bulan 1-2: 0%
2. Bulan 3-4: 1%
3. Bulan 5-7: 5%
4. Bulan 8: 2%
- Memberikan rincian laba bulanan
- Menghitung total laba yang terakumulasi
## latihan3.py
## Komponen Utama(ATM Sederhana)
1. Variabel Saldo
- Menyimpan jumlah saldo yang tersedia
- Diinisialisasi dengan nilai Rp 100.000

2. Loop Utama
- Menggunakan while True untuk menjalankan program terus-menerus
- Berhenti hanya jika user memilih keluar

3. Validasi Input
- Memastikan pilihan menu valid (1 atau 2)
- Memastikan jumlah penarikan tidak melebihi saldo

## Batasan Program (ATM Sederhana)
- Saldo awal tetap: Rp 100.000
- Hanya menyediakan fitur penarikan
- Tidak ada fitur penyimpanan data permanen
