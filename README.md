# Praktikum10
#### Nama : Veronika Natalia Kala
#### NIM : 312210690
#### Kelas : TI.22.A.2
# Praktikum 10 
## Pertemuan 14 : Python String , Operasi String 
### Apa Itu Python String 
- String adalah jenis yang paling populer di Python.
- Untuk membuatnya hanya dengan melampirkan karakter dalam tanda kutip.
- Python memperlakukan tanda kutip tunggal sama dengan tanda kutip ganda.
- Membuat string semudah memberi nilai pada sebuah variabel.
#### Contoh String 
```
var1 = 'Hello World!'                 # penggunaan petik tunggal
var2 = "Python Programming"           # penggunaan petik ganda
```
### Mengakses Nilai String 
- Python tidak mendukung tipe data karakter.
- Untuk mengakses substring, gunakan tanda kurung siku.
#### Contoh :
```
var1 = 'Hello World!'                # penggunaan petik tunggal
var2 = "Python Programming           # penggunaan petik ganda

print("var1[0]: ", var1[0])          # mengambil karakter pertama
print("var2[1:5]: ", var2[1:5])      # mengambil karakter ke-2 s/d ke-5
```
### Mengupdate String (Mempebaharui)
- Anda dapat “memperbarui” string yang ada dengan (kembali) menugaskan variabel ke string lain.
- Nilai baru dapat dikaitkan dengan nilai sebelumnya atau ke string yang sama sekali berbeda sama sekali.
#### Contoh :
```
message = 'Hello World'
print ("Updated String :- ", message[:6] + 'Python')
```
### Latihan 
```
txt = 'Hello World'
```
- Hitung jumlah karakternya
- Ambil karakter terakhir
- Ambil karakter index ke-2 sampai index ke-4 (llo)
- Hilangkan spasi pada text tersebut (HelloWorld)
- Ubah text menjadi huruf besar
- Ubah text menjadi huruf kecil
- Ganti karakter H dengan karakter J

![image](https://user-images.githubusercontent.com/115933294/213002046-0e4d6c00-0ace-4cba-a82b-ac47650ff96e.png)


- Lengkapi kode berikut !
```
umur = 24
txt = 'Hello, nama saya john, dan umur saya adalah ... tahun'

print(txt.format(umur))
```
![image](https://user-images.githubusercontent.com/115933294/213002069-16624bf0-932b-43d9-aba2-8d9f76452fde.png)

