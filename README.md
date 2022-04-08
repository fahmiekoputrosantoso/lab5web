| Nama      | Fahmi Eko Putro Santoso |
| ----------- | ----------- |
| NIM     | 312010046       |
| Kelas   | TI.20.A.1        |

## Langkah langkah praktikum 5
Persiapan membuat dokumen HTML dengan nama file lab5_javascript.html seperti gambar dibawah ini.

![imgintro!](assets/img/intro.png)

![imgintro!](assets/img/intro2.png)

## 1. Javascript Dasar
Pemakaian Alert sebagai property window

![img1!](assets/img/1/1.png)

Pemakaian method dalam objek

![img1!](assets/img/1/1-1.png)

Pemakaian Prompt


![img1!](assets/img/1/1-3.png)

Pembuatan fungsi dan cara pemanggilannya

![img1!](assets/img/1/1-4.png)

## 2. Dasar Pemrograman Di Javascript
Operasi dasar aritmatika

![img2!](assets/img/2/1.png)

Seleksi kondisi (if..else)

disini saya memasukkan data 90

![img2!](assets/img/2/1-22.png)

Penggunaan operator switch untuk seleksi kondisi

![img2!](assets/img/2/1-3.png)

![img2!](assets/img/2/1-33.png)

## 3. pembuatan Form
Form input

saya coba input nilai 8

![img3!](assets/img/3/1.png)

Form button

![img3!](assets/img/3/2.png)


## 4. HTML DOM
Pilihan menggunakan checkBox dengan perhitungan otomatis

![img4!](assets/img/4/1.png)

## Pertanyaan dan Tugas
1. Buat script untuk melakukan validasi pada isian form

## Jawab

Membuat validasi nama, no.telp, Email

## 1. Nama
Saya akan memberikan Validasi berupa inputan hanya boleh mengguankan Huruf/Alphabet saja. Contoh: Fahmi Eko (benar), Fahmi Eko 1 (salah).

![imgpraktikum!](assets/img/praktikum/1-1.png)

Penjelasan
- Pertama membuat nama function Alphabet, dengan parameter dinamis yaitu (nilai, pesan) dan data yang boleh dimasukkan adalah berupa "a-zA-Z".
- Jika selain data "a-zA-Z" ini dimasukkan, maka akan muncul pesan Alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/1.png)

## 2. Nomor Telp
Pada bagian ini akan saya berikan validasi berupa hanya angka saja yang boleh di inputkan, contoh: 12345 (benar), 123ABC (salah).

![imgpraktikum!](assets/img/praktikum/2.png)

Penjelasan:
- var numberExp = /^[0-9]+$/; merupakan variabel numberExp yang diberi batasan validasi angka 0-9
- Arti Match pada "if(nilai.value.match(numberExp))" adalah string.match(), mencari string menggunakan Regular Expression (Regex)
- Jika salah atau inputan tidak benar maka akan ada pesan alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/2-1.png)

## 3. Email
Pada email akan diberikan validasi masih berupa Regular Expression. Contoh: fahmieko73@gamil.com.com (benar), fahmi eko@gmail. (salah).

![imgpraktikum!](assets/img/praktikum/3.png)

Penjelasan:
- membuat variabel email " var email = /^([a-zA-Z0-9_.+-])+@(([a-zA-Z0-9-])+.)+([a-zA-Z0-9]{2,4})+$/; " berupa huruf, angka dan simbol yang diperbolehkan dalam input sebuah email. Jika email salah maka akan ada pesan alert "alert(pesan);"

![imgpraktikum!](assets/img/praktikum/3-1.png)

## Berikut ini adalah contoh penulisan form.

![imgpraktikum!](assets/img/praktikum/4.png)









