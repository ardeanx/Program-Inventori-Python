
![Logo](https://i.imgur.com/JTB841z.png)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
# Program Inventori

Program inventori sederhana dibuat menggunakan bahasa permograman Python dan Tkinter untuk GUI nya (Graphcial User Interface). Saya buat program ini bertujuan untuk membantu anda lebih mudah dalam mengelola inventori yang anda miliki di Toko, Gudang, dll. Semoga bermanfaat.
## Fitur

- Menambah Data
- Menghapus Data
- Memperbarui Data
- Ekspor ke Excel
- Tampilan User-Friendly
- Penggunaan yang mudah
- Open-Source


## Tampilan Program

![App Screenshot](https://i.imgur.com/IHFuL1s.png)

![App Screenshot](https://i.imgur.com/x5hH2Kr.png)
## Requirements

Silahkan install beberapa Packages berikut ini sebelum menjalankan program. Jika belum di install, dapat dipastikan akan terjadi error pada saat anda menjalankannya.

- Tkinter
- Numpy
- PyMysql
- Auto PY-To-EXE (Disarankan)
    
## Install

Pertama, silahkan install dulu requirements nya

```bash
  pip install -r requirements.txt
```
```bash
pip install tk
```
Opsional:

Anda bisa menginstall `AUTO-PY-TO-EXE` agar dapat membuat versi Executablenya:

```bash
pip install auto-py-to-exe
```
## PENTING

Sebelum menjalankan dan membuat file executable nya. Anda harus membuat database nya terlebih dahulu di PhpMyAdmin. Bisa akses di `localhost/PhpMyAdmin`. Berikut step nya:

- Aktifkan Apache server nya. Disarankan menggunakan `XAMPP`
- Buka Browser, lalu ketik `localhost/phpmyadmin`
- Buat Database baru

Setelah itu, cari kode ini di script python saya:

```
def connection():
    conn=pymysql.connect(
        host='localhost',
        user='root',
        password='admin123',
        db='inventory'
    )
    return conn
```

Ganti `db` sesuai dengan nama database kalian. Kalau `MYSQL` kalian tidak menggunakan Password, silahkan dikosongkan.
## Build & Deploy

Untuk menjalankan kode diatas, cukup ketik:

```bash
python inventori.py
```
Pada terminal kalian.

Jika ingin Build versi Executablenya bisa dengan menjalankan perintah berikut:

```bash
auto-py-to-exe
```
Setelah menjalankan perintah tersebut, anda akan melihat tampilan awal `auto-py-to-exe` nya.

![App Screenshot](https://i.imgur.com/6J4ziu5.png)

Silahkan untuk mengikuti setelan saya seperti ini:

![App Screenshot](https://i.imgur.com/DpKuct6.png)

Berikut penjelasan dari tiap opsi yang saya pilih:

- Masukan PATH Script Python anda pertama
- Klik Opsi `Satu Berkas`
- Klik Opsi `Berdasarkan Jendela(Sembunyikan Konsol)`

Satu berkas, akan membuat file Executablenya menjadi 1 file saja.

Berdasarkan Jendela akan menyembunyikan konsol yang terbuka saat menjalankan file .EXE nya.
## Kustomisasi

Jika anda ingin menambahkan Kategori, anda bisa cari kode berikut:

```
categoryArray=['']
```
## FAQ

#### Apa tujuan program ini?

Program Inventori ini saya harapkan agar dapat memudahkan pengguna dalam menginput data produk yang dimiliki di toko, gudang, maupun penggunaan lainnya. Selain itu, awalnya juga saya bertujuan agar dapat lebih mudah untuk melihat harga produk tanpa menghafalnya.

#### Apa alasan program ini dibuat?

Awalnya saya lihat banyak sekali pembeli di toko saya, saya sedikit kewalahan dan kadang keliru dengan memberikan harga-harga dari item di toko saya. Maka, saya berinisiatfi dengan membuat progam ini untuk memudahkan saya dalam mengingat harga-harga item yang ada di toko saya.

#### Apakah program ini gratis dan tidak berbayar?

Ya, program ini gratis dan tidak berbayar. Apabila anda menemukannya di suatu tempat dan melihatnya di jual. Anda bisa melaporkan ini ke saya. Saya memberikan program ini gratis kepada seluruh pengguna.

#### Apakah program ini akan di update kedepannya?

Tergantung, jika anda ingin mengkustomisasi progam ini. Anda dapat menghubungi saya dengan membahasnya. Atau jika anda bisa silahkan modifikasi sendiri. Program ini memiliki lisensi `GNU/GPL`.

#### Apakah saya dapat memodifikasi, menggandakan, dan merepublish program ini?

Silahkan anda lakukan, jangan lupa memberikan credit author.

#### Apakah saya dapat menjual program ini?

Tidak, anda tidak boleh menjual program gratis ini kepada siapapun. Saya membuat program ini agar dapat bermanfaat bagi banyak orang. Sangat tidak etis jika anda mengambil kesempatan tersebut.

