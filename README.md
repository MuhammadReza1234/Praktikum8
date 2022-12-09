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

<img width="297" alt="r1" src="https://user-images.githubusercontent.com/115542704/206631985-7ed6f8b8-f580-4989-8749-174e4579e835.png">

ini adalah output apabila memilih ubah (2)

<img width="229" alt="r2" src="https://user-images.githubusercontent.com/115542704/206632264-37df1256-a3ee-4662-85a6-002f5dd6d76f.png">

berikut data yang sudah diubah

<img width="428" alt="r22" src="https://user-images.githubusercontent.com/115542704/206632858-f11bfb84-7e54-4232-86fe-632e51c896fb.png">

ini adalah output apabila memilih untuk tambah lagi

<img width="226" alt="r1 1" src="https://user-images.githubusercontent.com/115542704/206633055-4569f90b-0861-4eac-85e8-411aea622759.png">

ini adalah output apabila memilih lihat (3)

<img width="422" alt="r3" src="https://user-images.githubusercontent.com/115542704/206634080-2e46eb8d-81f9-4799-9c38-eb5d04703c08.png">

ini adalah output apabila memilih hapus (4)

<img width="201" alt="r4" src="https://user-images.githubusercontent.com/115542704/206633372-daefd529-009d-46e8-be7a-b5d06687388a.png">

berikut tampilan data yang telah terhapus

<img width="418" alt="r4 1" src="https://user-images.githubusercontent.com/115542704/206633747-6f3e7e1a-97ec-4768-9418-f9c78b2e64c7.png">

ini adalah output apabila memilih keluar (5)

<img width="233" alt="r5" src="https://user-images.githubusercontent.com/115542704/206634711-7843405a-c2a7-4a80-8428-b9cb22c58324.png">

# SEKIAN TERIMAKASIH
