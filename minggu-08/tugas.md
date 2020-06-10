# Buatlah satu diagram yang bisa menggambarkan keterkaitan antara semua point-point di bawah ini:

## Arsitektur Docker

![go Installer](https://github.com/Wahyupr/tekn-cloud-computing/blob/master/minggu-08/images/go/tugas.png)
Gambar diatas merupakan arsitektur docker, dimana docker terdiri dari beberapa element yaitu docker client, docker daemon, docker container, docker images dan docker registry. Docker menggunakan teknologi client server untuk menghubungkan antara docker client dan docker daemon. Penulis akan menjelaskan sedikit mengenai istilah - istilah penting pada docker.



* Docker Daemon
Docker daemon berfungsi untuk membangun, mendistribusikan dan menjalankan container docker. User tidak dapat langsung menggunakan docker daemon, akan tetapi untuk menggunakan docker daemon maka user menggunakan docker client sebagai perantara atau cli.

* Docker Images
Docker images adalah sebuah template yang bersifat read only. Template ini sebenarnya adalah sebuah OS atau OS yang telah diinstall berbagai aplikasi. Docker images berfungsi untuk membuat docker container, dengan hanya 1 docker images kita dapat membuat banyak docker container.

* Docker Container
Docker container bisa dikatakan sebagai sebuah folder, dimana docker container ini dibuat dengan menggunakan docker daemon. Setiap docker container disimpan maka akan terbentuk layer baru tepat diatas docker images atau base image diatasnya. Contohnya misalkan kita menggunakan image ubuntu, kemudian kita membuat sebuah container dari image ubuntu tersebut dengan nama ubuntuku, kemudian kita lakukan instalasi sebuah software misalnya nginx maka secara otomatis container ubuntuku akan berada diatas layer image atau base image ubuntu. Anda dapat membuat banyak docker container dari 1 docker images. Docker container ini nantinya dapat dibuild sehingga akan menghasilkan sebuah docker images, dan docker images yang dihasilkan dari docker container ini dapat kita gunakan kembali untuk membuat docker container yang baru.

* Docker Registry
Docker registry adalah kumpulan docker image yang bersifat private maupun public yang dapat anda akses di docker hub. Dengan menggunakan docker registry, anda dapat menggunakan docker image yang telah dibuat oleh developer yang lain, sehingga mempermudahkan kita dalam pengembangan aplikasi.