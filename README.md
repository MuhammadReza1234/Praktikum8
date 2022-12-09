# Nama: Muhammad Reza Maulana
# NIM: 312210303
# Kelas: TI.22.A3

## PERTEMUAN 12
## SOAL

![soal](https://user-images.githubusercontent.com/115542704/206460646-4c089e2d-9d9c-427b-a326-d43c633e78d6.png)

## Diagram class

![diagramClass](https://user-images.githubusercontent.com/115542704/206462308-ab57022f-da40-422a-9e52-1c59252d2123.png)

## Flowchart

![flowchart (3)](https://user-images.githubusercontent.com/115542704/206462353-41fd2d95-2329-4f92-9403-e679c5bc1784.png)

## Program

pertama saya membuat dictionary terlebih dahulu untuk menampung data
```python
mahasiswa = {}
```

kemudian membuat sebuah class 
```python
class daftarNilai()
```

Lalu saya melanjutkan dengan membuat method-method fungsinya sebagai berikut
```
def tambah(self)
def ubah(self)
def lihat(self)
def hapus(self)
def keluar(self)
```

lalu saya mengisi setiap method dengan elemen-elemen nya
```python
nama= input("masukan nama: ")
nim= input("masukan nim :")                                         
nilaiTugas= int(input("Masukkan Nilai Tugas: "))
nilaiUts= int(input("Masukkan Nilai UTS\t: "))            
nilaiUas= int(input("Masukkan Nilai UAS\t: "))             
nilaiAkhir= (30/100 * nilaiTugas) + (35/100 * nilaiUts) + (35/100 * nilaiUas)
mahasiswa[nama]=nim,nilaiTugas,nilaiUts,nilaiUas,nilaiAkhir
```

lalu saya membuat sebuah looping
```python
while True:
    data = daftarNilai()
    print('\ntambah\t(1)\nubah\t(2)\nlihat\t(3)\nhapus\t(4)\nkeluar\t(5)')
    c = input("\nsilahkan masukan pilihan : ")
    print()
```

Dan terakhir membuat fungsi if else untuk menjalankan method
```python
if (c == "1"):
    data.tambah()
elif (c == "2"):
    data.ubah()
elif (c == "3"):
    data.lihat()
elif (c == "4"):
    data.hapus()
elif (c == "5"):
    data.keluar()
    break    
```

Dan saya juga menggunakan else di akhir program yang digunakan apabila salah memasukkan pilihan inputan
```python
else:
    print()
    print("Kode yang anda masukkan salah!")
```

# output program

ini adalah output apabila memilih tambah (1)

<img width="280" alt="j1" src="https://user-images.githubusercontent.com/115516607/206637149-da0fc9cf-eb11-4815-9dc2-d118a8138236.png">

ini adalah output apabila memilih ubah (2)

<img width="242" alt="j2" src="https://user-images.githubusercontent.com/115516607/206637919-76f0ac74-cfdd-4e77-bad6-079dd0958076.png">

berikut tampilan data yang sudah diubah

<img width="425" alt="j2 1" src="https://user-images.githubusercontent.com/115516607/206638050-f9d9bf4f-011c-40f4-9b6f-231e4c03620c.png">

ini adalah output apabila memilih untuk tambah lagi

<img width="236" alt="j1 1" src="https://user-images.githubusercontent.com/115516607/206638190-258bf7c3-98af-467e-a0c2-092729c1f6f5.png">

ini adalah output apabila memilih lihat (3)

<img width="425" alt="j2 1" src="https://user-images.githubusercontent.com/115516607/206638302-ebd2cfb1-452c-4477-b4b7-bd9c5ee475ff.png">

ini adalah output apabila memilih hapus (4)

<img width="211" alt="j4" src="https://user-images.githubusercontent.com/115516607/206638445-ad4d0726-7edb-48af-92ac-0fcdd8b25b5c.png">

berikut tampilan data yang telah terhapus

<img width="424" alt="j4 2" src="https://user-images.githubusercontent.com/115516607/206638582-6f50f512-8f4c-4f4b-9a28-5de3cac7ccab.png">

ini adalah output apabila memilih keluar (5)


# SEKIAN TERIMAKASIH
