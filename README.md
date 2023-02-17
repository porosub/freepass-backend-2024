# Backend Freepass Challenge

TEMA dari project wajib memilih salah satu dari:

- Manajemen Perpustakaan
- Manajemen Keuangan
- E-Learning

Ketentuan :

- Dikerjakan secara individu.
- Fitur-fitur yang dibuat bebas dan sesuai kreativitas dengan syarat harus sesuai tema yang dipilih
- Bahasa pemrograman yang digunakan bebas (disarankan JS untuk back-end)
- Mematuhi aturan lisensi apabila menggunakan kode sumber eksternal
- Bebas menggunakan framework/library
- Challenger harus menyelesaikan minimal 3/4 task yang ada untuk mendapatkan freepass

## TASK

1. Buatlah backend web service sesuai dengan tema yang ada.

2. Web service boleh menggunakan database server seperti mysql atau mariadb

2. Buat sebuah berkas yaml docker-compose atau dockerfile untuk deploy web service anda.
	- Web Environment : Harus memiliki service berupa 1 Load Balancer, 1 Database Server, 1 Web Server
Ketentuan : Kemudian pastikan semua service bisa berjalan dan diakses dari luar container dan file docker-compose yang telah dibuat harus bisa digunakan user tanpa harus melakukan konfigurasi apapun lagi. Untuk web environment cukup buat halaman website sederhana saja tidak perlu membuat landing page.

3. Jika yang dibuat adalah dockerfile, silahkan push hasil image dari dockerfile tersebut ke docker hub.



5. Buat dokumentasi pada folder yang berbeda-beda untuk setiap tasknya. Kemudian dokumentasi ditulis dalam markdown dengan nama README.md agar dapat terlihat langsung ketika mengakses folder task yang bersangkutan. Buatlah dokumentasi dengan lengkap dan rapi yang harus berisikan:

 	- Nama challenger
  	- Penjelasan singkat tentang task yang dikerjakan
  	- Penjelasan singkat tentang source code yang dibuat
  	- Foto/Screenshot WIP (Work in Progress) dan hasil akhirnya

6. Apabila web service terhubung dengan jaringan, manfaatkan fitur Firewall/SELinux sebaik-baiknya

7. Untuk service yang mempergunakan database, minimal ada 1 user (non root) dengan 1 database berisi 1 tabel berisi >= 4 query yang merupakan operasi CRUD

8. Halaman website & database SQL dibuat di luar container/virtual machine (manfaatkan fitur dump, backup, restore, move, copy, volumes, dsb)

9. Challenger tidak boleh mengubah apapun di dalam container/virtual machine setelah container docker berjalan (Output apa adanya tanpa sentuhan apapun lagi). Semua perubahan harus dilakukan pada source code sebelum dijalankan.

10. Upload source code dan write up ke repositori GitHub atau alternatif lainnya.

11. Kumpulkan link github ke form berikut https://docs.google.com/forms/d/e/1FAIpQLSehThONCfaAFO8vmhsPN0zjf5-Ux2sZo8w4G1icW0IK2Mzh0A/viewform


