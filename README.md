# Tugas Pertemuan 14

Nama  : Ferdyana Eka Prsetya

Nim   : 312210121

Kelas  : T1.22.A1

## Python String

 String adalah jenis yang paling populer di Python.\
 
 Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
 
 Python memperlakukan tanda kutip tunggal (' ') sama dengan tanda kutip ganda (" ").
 
 Membuat string semudah memberi nilai pada sebuah variabel.

### Latihan 1

![image](https://user-images.githubusercontent.com/115714443/209815397-ab404926-c601-4a61-8d0a-0c1db5b2aed0.png)

#### Penjelasan 

- Untuk menghitung jumlah karakter, gunakan fungsi len().

```
# Menghitung jumlah karakternya
print(len(txt))
```

- Cara mengambil satu karakter pada string yaitu menggunakan kurung siku [ ] dan deklarasi nomor di dalam kurung siku dengan urutan ARRAY lalu menggunakan titik dua kemudian masukan nomor ARRAY selanjutnya. Untuk mengambil karakter terakhir, gunakan *index [-1]. Sedangkan untuk mengambil karakter *index ke-2 sampai ke-4, gunakan index [2:5].

```
# Mengambil karakter terakhir
print(txt[-1])
# Mengambil karakter index ke-2 sampai index ke-4 (llo)
print(txt[2:5])
```

- Jika ingin menghilangkan spasi pada string, gunakan method replace(). Method replace() mengganti semua kemunculan string lama dengan yang baru atau paling banyak kemunculan.

- Dalam method replace, kita dapat menggunakan 2 cara, yang pertama bisa menggunakan (txt.replace(" ", "")) dan kedua dengan cara (txt.replace(txt[5], "")).

```
# Menghilangkan spasi pada text tersebut (HelloWorld)
print(txt.replace(" ", ""))
```

- Untuk mengubah huruf menjadi besar, gunakan method upper(). Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan method lower().

```
# Mengubah text menjadi huruf besar
print(txt.upper())
# Mengubah text menjadi huruf kecil
print(txt.lower())
```

- Untuk mengganti karakter 'H' dengan karakter 'J', gunakan method replace().

```
# Mengganti karakter H dengan karakter J
print(txt.replace("H", "J"))
print()
```

#### Hasil Run

![Screenshot (95)](https://user-images.githubusercontent.com/115714443/209818691-e3983288-d144-4fe0-848d-d686ec393645.png)

### Latihan 2

![image](https://user-images.githubusercontent.com/115714443/209820061-3d56b924-7885-45e4-ad2d-2df9a96861d0.png)

#### Penjelasan

- Untuk memasukkan variable ke dalam string, tambahkan kurung kurawal {} untuk menempatkan variable sebelumnya.

```
  umur = 24
  txt = "\nHello, nama saya john, dan umur saya adalah {0} tahun\n"

  print(txt.format(umur))
 ```
 #### Hasil Run
![Screenshot (96)](https://user-images.githubusercontent.com/115714443/209818698-4dc39a4e-1ae0-4541-a97b-fd843991e9ed.png)

# TERIMAKASII
