# Diagram-Alir 1 [Menghitung Luas Persegi]
![Diagram Alir 1](https://github.com/syamsec/Diagram-Alir/assets/121809593/2be6c706-ad6d-45c2-b28e-cf3f13280f71)

    Deskripsi tingkat tinggi:
    1. Baca nilai sisi persegi.
    2. Hitung luas dengan menguadratkan nilai sisinya.
    3. Cetak luas.
    
    Pseudocode:
    Algoritma Menghitung Luas Persegi
    Input: Nilai Panjang Sisi Persegi.
    Output: Luas Persegi tercetak.
    input sisi
    luas← sisi * sisi
    print luas
# Diagram-Alir 2 [Menghitung Luas Permukaan Kubus]
![Diagram Alir 2](https://github.com/syamsec/Diagram-Alir/assets/121809593/2a3ddecd-ad50-46d9-99b3-6227a845f4cf)

    Deskripsi tingkat tinggi:
    1. Baca nilai sisi kubus.
    2. Hitung luas (persegi) dari sisi kubus. Kalikan luas kubus dengan angka 6 (banyaknya jumlah persegi pada kubus) untuk mendapatkan luas permukaan.
    3. Cetak luas_permukaan.
    
    Pseudocode:
    Algoritma Menghitung Luas Permukaan Kubus
    Input: Nilai Panjang Sisi Kubus.
    Output: Luas Permukaan Kubus tercetak.
    input sisi
    luas_permukaan ←luas(sisi) * 6
    print luas_permukaan

# Diagram-Alir 3 [Membagi Bilangan]
![Diagram Alir 3](https://github.com/syamsec/Diagram-Alir/assets/121809593/f21fa725-c06f-4065-b7b5-f7f9f520e8c0)

    Deskripsi tingkat tinggi:
    1. Baca nilai pembilang dan penyebut.
    2. Jika penyebut bernilai 0, cetak tulisan “Penyebut tidak boleh nol”.
    3. Jika penyebut tidak bernilai nol, lakukan pembagian pembilang dengan penyebut dan simpan hasilnya.
    4. Cetak hasil pembagian.

    Pseudocode:
    Algoritma Membagi Bilangan
    Input: Pembilang dan Penyebut.
    Output: Hasil Pembagian tercetak.
    input pembilang, penyebut
    if penyebut = 0 print “Penyebut tidak boleh nol”
    else
     hasil ← pembilang / penyebut
     print hasil

# Diagram-alir 4 [Menghitung Mundur Dari N hingga 1]
![Diagram Alir 4](https://github.com/syamsec/Diagram-Alir/assets/121809593/e8e7911a-15aa-4487-b7d0-0192339182e7)

    Deskripsi tingkat tinggi:
    1. Baca nilai N.
    2. Selama N > 0, ulangi.
    3. Cetak tulisan N.
    4. Kurangi nilai N dengan 1. 

    Pseudocode:
    Algoritma Menghitung Mundur dari N hingga 1
    Input: Nilai N.
    Output: Angka hasil hitung mundur dari nilai N sampai 1 tercetak.
    input N
    while N > 0
     print N
     N ← N - 1
