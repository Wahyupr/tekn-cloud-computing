# 1. Install Docker, Menggunakan OS Linux ubuntu 20 LTS
## Instalasi Docker

### instal menggunakan repositori
Sebelum Anda menginstal Docker Engine untuk pertama kalinya pada mesin host baru, Anda perlu mengatur repositori Docker. Setelah itu, Anda dapat menginstal dan memperbarui Docker dari repositori.

* Siapkan repositori
Perbarui indeks paket apt dan instal paket untuk memungkinkan apt menggunakan repositori melalui HTTPS:

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-02.png)

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-03.png)

* Tambahkan kunci GPG resmi Docker:

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-04.png)

Pastikan memiliki kunci dengan sidik jari 9DC8 5822 9FC7 DD38 854A E2D8 8D81 803C 0EBF CD88, dengan mencari 8 karakter terakhir dari sidik jari.

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-05.png)

* Gunakan perintah berikut untuk mengatur repositori stabil. Untuk menambahkan nightly atau repositori pengujian, tambahkan kata nightly atau test (atau keduanya) setelah kata stable dalam perintah di bawah ini. Pelajari tentang malam dan uji saluran.

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-06.png)



### INSTALL DOCKER ENGINE
Perbarui indeks paket apt, dan instal versi terbaru dari Docker Engine dan containerd, atau lanjutkan ke langkah berikutnya untuk menginstal versi tertentu:

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-07.png)

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-08.png)

# 2. Kerjakan no 4 pada Materi dan Penjelasan

### Test Docker version

Setelah Anda berhasil menginstal Docker Desktop, buka terminal dan jalankan docker --version untuk memeriksa versi Docker yang terinstal di mesin Anda.

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-10.png)

### Uji Instalasi Docker
* Uji apakah instalasi Anda berfungsi dengan menjalankan gambar Docker hello-world:

![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-11.png)

* Jalankan image docker ls untuk mencantumkan gambar hello-world yang Anda unduh ke mesin Anda.

* Daftar hello-world container (ditimbulkan oleh gambar) yang keluar setelah menampilkan pesannya. Jika masih berjalan, Anda tidak perlu -all option:


![Docker Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-07/images/install%20Docker/gambar-12.png)
