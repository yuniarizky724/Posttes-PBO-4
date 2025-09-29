# Posttes-PBO-4
### Program ini menerapkan CRUD guna mengelola data SewaBusanaButik. Data yang disimpan pada program ini berisi id busana, nama busana, dan kategori busana. Prorgram ini menggunakan ArrayList untuk menampung data-data busana yang tersimpan. User bisa menambahkan data, melihat data, update data, dan juga menghapus data. Dan juga disini saya menambahkan 1 menu baru yaitu menu proses sewa yang berguna untuk menyewa busana. Selanjutnya, program ini menerapkan polymorphism, contoh method tampilinfo() di override pada masing-masing subclass dengan superclass "BusanaService". Ada juga diterapkan pada method hitungHarga() dengan 1 metode yaitu lama hari menyewa.

# Alur Program
### 1. Menu utama ditampilkan
       User memilih salah satu menu dari 6 menu yang tersedia.
### 2. Proses sewa Busana
<img width="483" height="421" alt="image" src="https://github.com/user-attachments/assets/08dd45a8-e327-4f24-9014-628376f1e566" />
       User diminta untuk memilih menu nomor 5 untuk menyewa busana, kemudian user diminta memasukkan   ID busana yang ingin di sewa, lalu user ditanya lama hari menyewa busana, lalu selesai.

### Pada program ini saya abstraction dengan minimal 1 abstrak dan 1 interface. Untuk penerapan abstrak saya terapkan pada class Busana dengan method tampilinfo(); dan wajib diimplementasikan setiap subclass. Kemudian untuk penerapan interface saya terapkan dengan membuat class baru dengan nama interfaces yaitu Sewa. Selanjutnya, penerapan polymorphism dengan minimal 1 overriding, untuk penerapan overriding di class BusanaTradisional, BusanaModern, dan BusanaService
