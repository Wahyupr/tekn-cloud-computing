# Latihan TCC Minggu-06
###### A. Membuat program Go untuk koneksi dan membaca data dari MySQL
Sebelum melakukan pembuatan program kita diwajibkan untuk menginstall Mysql Community Edition, compiler Go, dan Mysql driver untuk Go.

*  Setelah proses instalasi selesai kita langsung membuat sebuah database yang akan digunakan untuk melakukan koneksi, dan pembacaan data menggunakann Go.


* Lalu membuat program menggunakan bahasa Go untuk melakukan koneksi, dan membaca data yang sudah dibuat sebelumnya di database mysql. Program Go Mysql


###### B. Membuat program Go untuk koneksi dan membaca data dari MongoDB
Sebelum melakukan pembuatan program kita diwajibkan untuk menginstall MongoDB (atau gunakan versi cloudnya MongoDB atlas), compiler Go, dan Mongo driver untuk Go. cara instalasi nya terdapat dibawah :

* Setelah proses instalasi selesai kita langsung membuat sebuah database yang akan digunakan untuk melakukan koneksi, dan pembacaan data menggunakann Go.Karena saya menggunakan MongoDB Atlas maka harus membuat akun untuk bisa membuat cluster sendiri.

* Lalu mendapatkan URI string dari MongoDB Atlas agar dapat mengakses cluster dan databasenya. Jika tidak menggunakan MongoDB Atlas cukup isi URI string dengan port localhost, dan nama databasenya.

* Setelah mendapatkan URI string kita sudah bisa melakukan proses coding dengan Go untuk melakukan koneksi, dan membaca data dari database yang ada di MongoDB. Program Go MongoDB

* Untuk output yang disorot warna hijau output yang dikeluarkan jika sukses melakukan koneksi, dan output yang disorot warna kuning adalah isi collection yang ada di database.



# Instalasi Go 

### Download installer GO di link [Installer Go](https://golang.org/doc/install) atau bisa dilihat Proses Instalasi nya di bawah ini :

Download sesuai link diatas maka seperti ini jika sudah di download.

![go Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/go/01.png)

Kemuadian klik installer yang telah didownload, lalu ->Next ->pilih direktory go ->Next lalu install , seperti di bawah ini

![go Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/go/0.png)

![go Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/go/03.png)

![go Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/go/04.png)

# Instalasi Mongodb

### Download installer Mongodb di link [Installer Mongodb](https://docs.mongodb.com/manual/installation/) atau bisa dilihat Proses Instalasi nya di bawah ini :

Download instaler nya di website atau link diatas kemudian ikutin langkah langkah seperti dibawah ini :

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-01.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-02.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-03.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-04.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-05.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-06.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-07.png)

![Mongodb Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/Mongodb/gambar-08.png)

# Instalasi Mysql

### Download installer Mysql di link [Installer Mysql](https://dev.mysql.com/downloads/installer/) atau bisa dilihat Proses Instalasi nya di bawah ini :

ownload installer nya di website atau link diatas kemudian ikutin langkah langkah seperti dibawah ini :


![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-01.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-02.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-03.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-04.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-05.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-06.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-07.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-08.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-09.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-10.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-11.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-12.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-13.png)
![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-14.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-15.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-16.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-17.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-18.png)

![Mysql Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-06/images/mysql/gambar-19.png)

