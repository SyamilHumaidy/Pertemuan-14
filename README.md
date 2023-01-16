Nama    :   Ghufron Malik</br>
NIM     :   312210559</br>
Kelas   :   TI.22.B2</br>

# Pertemuan 14 : Python String


### Apa itu Python String?

- String adalah jenis yang paling populer di Python.
- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
- Python memperlakukan tanda kutip tunggal sama dengan tanda kutip ganda.
- Membuat string semudah memberi nilai pada sebuah variabel.


### 1. Latihan 
![img1](image/11.png)

### 2. Latihan
![img2](image/22.png)

### Source Code
![img3](image/1.png)
![img4](image/2.png)


### A. Penjelasan Latihan 1

1.  Untuk menghitung karakter pada string yaitu menggunakan Fungsi `len()`.</br>
Contoh:
```py
print(len(txt))
```
- Fungsi len() pada python di gunakan untuk menghitung karakter pada string.

2. Jika ingin mengambil karakter terakhir, gunakan index `[-1]`.</br>
Contoh:
```py
print(txt[-1])
```

3. Next. Jika ingin menggambil karakter 2 s/d 4 menggunakan kurung siku yang di deklarasi nomor ARRAY.</br>
Contoh:
```py
print(txt[2:5])
```

4. Bila ingin menghilangkan spasi pada string yaitu menggunakan fungsi `replace()`.</br>
Contoh:
```py
print(txt.replace(" ", ""))
```

5. Untuk mengubah huruf menjadi besar, gunakan fungsi `upper()`.</br>
Contoh:
```py
print(txt.upper())
```

6. Sedangkan jika ingin mengubah huruf menjadi kecil, gunakan fungsi `lower()`.</br>
Contoh:
```py
print(txt.lower())
```

7. Untuk mengganti karakter 'H' dengan karakter 'J', gunakan fungsi `replace()`.</br>
Contoh:
```py
print(txt.replace("H", "J"))
```


### B. Penjelasan Latihan 2

- Untuk memasukkan variable ke dalam string, tambahkan kurung kurung awal dan kurung akhir `{}` untuk menempatkan variable sebelumnya.</br>
Contoh:
```py
    umur = 24
    txt = "Hello, nama saya john, dan umur saya adalah {0} tahun"
    print(txt.format(umur))
```

### C. Hasil Output
- Latihan 1</br>
![img5](image/3.png)


- Latihan 2</br>
![img6](image/4.png)


# *SEKIAN, TERIMA KASIH :)*
