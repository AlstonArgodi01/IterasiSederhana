# IterasiSederhana
Program Perhitungan Iterasi Sederhana dengan masukan persamaan
Oleh kelompok 2

1.Anwar Sanusi(19081010068)

2.I Wayan Alston Argodi(19081010163)

3.Wariyanti Nugroho Putri (19081010020)

4.Fatimatuz Zahroh (19081010021)

5.Avia Arista (19081010077)

6.Imalia Rosyida (19081010113)

# Import math
from math import * kode ini berfungsi untuk mengimpor/mengambil fungsi math dari phyton sendiri kemudian mengambil operator arimatika pangkat *

# Fungsi
dalam fungsi menggunakan def untuk menyatakan fungsi dalam phyton kemudian variabel x sebagai parameter dan eval berfungsi untuk memparsing (menguraikan) string ekspresi yang dilewatkan ke dalamnya, dan menjalankannya sebagai ekspresi Python murni.
inputgx  dan inputfx adalah persamaan yang dimasukkan user

# Input

1.inputfx=str(input('masukkan f(x): ')) berfungsi untuk memasukan persamaan f(x) dalam bentuk string

2.inputgx=str(input('masukkan g(x): ')) berfungsi untuk memasukan persamaan g(x) dalam bentuk string

3.x0 = float(input('masukkan nilai awal: ')) untuk memasukan nilai awal yang ditentukan oleh pengguna

4.E = float(input('toleransi error : '))untuk memasukan toleransi error

4.N = float(input('maksimum iterasi :')) untuk memasukan batas berapa kali iterasi ingin dilakukan

# Kondisi
didalam potongan kode tersebut terdapat pernyataan kondisi dalam perhitugan step merupakan langkah yang diulang sesuai dengan inputan N ( Batas Iterasi ) yang dimasukan oleh pengguna, kemudian flag jika sama dengan 1 maka hasil akhir perhitungan tersbut memerlukan root sesuai dengan hasil akhir jika tidak maka akan keluar tidak konvergen.condition = True jika kondisi benar maka lanjut ke dalam perhitungan.
Mengecek jika step(perulangan) yang diperlukan lebih besar dari N(batas iterasi) maka program akan berhenti dan akan keluar Not Convergent, selanjutnya jika flag sama dengan 1 maka program akan mengecek apakah nilai f(x1) lebih besar dari e (toleransi eror). Jika lebih besar, maka condition akan bernilai true dan program akan terus melakukan looping sampai nilai f(x1) lebih kecil dari e.
