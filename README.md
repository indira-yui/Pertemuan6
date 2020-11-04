# pertemuan6_smt1
Repository ini di buat untuk memenuhi tugas bahasa pemrograman pertemuan ke 6 <br>
Nama  : Indira Aline <br>
Nim   : 312010042 <br>
Kelas : TI.20 A.1 <br>

DAFTAR ISI
| No | Description | Link |
| ----- | ----- | ----- |
| 1 | Tugas Pertemuan 5 | [click here](#pertemuan-5---tugas)
| 2 | Tugas Pertemuan 6 - Lab 1 | [click here](#pertemuan-6---lab-1)
| 3 | Tugas Pertemuan 6 - Lab 1-2 | [click here](#pertemuan-6---lab-1-2)
| 4 | Tugas Pertemuan 6 - Lab 2 | [click here](#pertemuan-6---lab-2)
 
## Pertemuan 5 - Tugas

Pada pertemuan 5 Bahasa Pemrograman saya diberi tugas oleh Dosen untuk membuat Aplikasi Biodata Python (seperti Gambar dibawah ini)
![input biodata](Foto/pertemuanke5.png) <br>

Saat ini saya akan menjelaskan hasil dari tugas tersebut. <br>
Berikut source code nya atau Klik Link berikut <br>
![gitpush](Foto/biodata1.png)): <br>
 ``` python
print("==============================")
print("= NAMA    : Indira Aline     ")
print("= NIM     : 312010042         ")
print("= KELAS   : TI.20 A.1         ")
print("==============================")

print("Please enter your full name : ")
fullname=input()
print("Please enter nickname : ")
nickname=input()
print("Please enter your NPM : ")
npm=int(input())
print("Please enter place of birth : ")
pob=input()
print("Please enter date of birth : ")
date=int(input())
print("Please enter your month of birth : ")
month=input()
print("Please enter year of birth : ")
year=int(input())
print("Please enter your phone number : ")
phone=int(input())
print("Please enter your address : ")
address=input()

dob=2020-year

print("\n\n Assalamu'alaikum. ")
print(f"Let me introduce my self, my name is {fullname}, but you can call me {nickname}, my NPM {npm}, I was born in {pob} and iam {dob} years old, I am very glad if you want to invite my house in {address}, So don't forget to call me before with the number {phone}, \n\n Thanks you ")

```
Berikut Penjelasannya : <br>
```python
print("please enter your full name : ")

```
Source code diatas berfungsi untuk mencetak hasil / output berupa *Please enter your full name :* ". <br>
 Untuk menampilkan output string, saya menggunakan tanda petik dua didalam fungsi print(), sedangkan jika saya ingin menampilkan output atau hasil berupa angka atau interger saya tidak perlu menggunakan tanda petik dua. Contohnya :
 
 ```python
print("Nama saya adalah...")
print(1234567)

```
(Seperti gambar dibawah ini) <br>
![Output Pungsi print](Foto/pra.png) <br>

* Untuk source code berikutnya adalah inputan atau membuat variable. seperti syntax dibawah ini : <br>
```python
fullname=input()

```
Keterangan : <br> 
![Output Fungsi Print](Foto/gitketerangan2.png) <br>

[input](Foto/gitfullname.PNG)
Pada gambar di atas, hasil dari inputan tersebut berwarna hijau <br>

* Untuk memasukan perintah lain seperti Nikname, NPM, Place Of Birth, Date Of Birth, Year Of Birth, Phone Number, and Addres mengikuti perintah sama seperti memasukan fullname <br>

* Untuk menghitung rumus saya menggunakan variable DOB yaitu 2020 (Tahun sekarang) dikurangin dengan Year of Birt, pada source code berikut :<br>

```python
dob=2020-year

```

Pada syntax/source diatas, saya menggunakan variable (dob) dimana untuk menghitung umur (variable *age* pada output), yaitu dengan rumus pada variable dob=2020-year
<br>

* langkah kali ini saya akan menampilkan output yang diminta oleh dosen.<br>
output pertama yang diminta Dosen adalah menampilkan salam, yaitu dengan mengetikkan syntax/source code berikut : 
```python
print("\n\n Assalamu'alaikum. ")

```
Keterangan :
1. Fungsi *\n* pada source code di atas adalah untuk memberi baris baru / enter / (newline)
2. Fungsi print() seperti dijelaskan pada point *Output* diatas
Hasil dari source code diatas adalah seperti gambar dibawah ini :<br>
![Output Fungsi Print](Foto/pyfungsi.png) <br>

```python
print(f"Let me introduce my self, my name is {fullname}, but you can call me {nickname}, my NPM {npm}, I was born in {pob} and iam {dob} years old, I am very glad if you want to invite my house in {address}, So don't forget to call me before with the number {phone}, \n\n Thanks you ")
```

Keterangan : 
1. Fungsi huruf *f* pada perintah print(f"....") adalah fungsi print atau bisa memudahkan programer dalam mencetak statement dalam satu baris dibandingkan dengan metode yang lama yaitu memisahkan string dan variable dengan simbol koma( , ) atau plus ( + )<br>
2. sedangkan fungsi {} pada output tersebut adalah untuk menampilkan hasil dari variable <br>
Hasil dari output tersebut seperti berikut : <br>
![Output Fungsi Print](Foto/pyoutput.png) <br>

<br>
---
<br>

## Pertemuan 6 - Lab 1

Pada halaman ini (Tugas Pertemuan 6 - Lab 1) saya diberikan tugas oleh Dosen yaitu mempelajari operator aritmatika menggunakan bahasa Pemrograman pyhton. Berikut source code yang di berikan oleh dosen :

```python

#penggunaan end
print('A', end='')
print('B', end='')
print('C', end='')
print()
print('X')
print('Y')
print('z')

#penggunaan separator
w, x, y, z = 10, 15, 20, 25
print(w, x, y, z)
print(w, x, y, z, sep=',')
print(w, x, y, z, sep='')
print(w, x, y, z, sep=':')
print(w, x, y, z, sep='.....')

```

Oke, kali ini saya akan menjelaskan tentang materi yang di berikan oleh Dosen. <br>

*Penggunaan END
Penggunaan end digunakan untuk menambahkan karakter yang dicetak di akhir baris. secara default penggunaan end adalah untuk ganti baris. <br>

```python  
print('A', end='')
print('B', end='')
print('C', end='')

```

> Penggunaan print () digunakan untuk mencetak output, seperti syntax dibawah ini :

```python
print()

```

>Syntax dibawah ini digunakan untuk menampilkan output berupa string
```python
print('X')
print('Y')
print('z')

```

Hasil dari source code tersebut seperti gambar dibawah ini : <br>
![Output Fungsi Print](Foto/pyxyz.png) <br>

* Penggunaan separator

>Pendeklarasian beberapa variable beserta nilainya
```python
w,x,y,z=10,15,20,25
```

>Menampilkan hasil dari variable tiap-tiap variable
```python
print(w,x,y,z)
```

>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (koma)
```python
print(w,x,y,z,sep=",")

```
>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah

```python
print(w,x,y,z,sep="")

```

>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah : (titik dua)
```python
print(w,x,y,z,sep=":")

```
>Menampilkan hasil dari tiap-tiap variable dengan menggunakan pemisah -----
```python
print(w,x,y,z,sep="-----")`

```

hasil dari syntax / source code diatas adalah seperti berikut ini : <br>
![Output Fungsi Print](Foto/pysource.png) <br>


<br>
<hr>
<br>

## Pertemuan 6 - Lab 1-2

* String Format<br>
String formatting atau pemformatan string memungkinan kita menyuntikkan item kedalam string dari pada kita mencoba menggabungkan string menggunakan koma atau string concatenation.<br>

Penggunaan source code yang di berikan oleh dosen seperti berikut :
![Output Fungsi Print](Foto/pylab1-2.png) <br>