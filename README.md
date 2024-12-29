# Aplikasi Inventori Pengelolaan Stok Barang

### Fiturnya apa saja sih?
Untuk fiturnya sebagai berikut
1. **Modul Authentikasi**
   
   terdapat fitur untuk login dan logout.
   
2. **Modul Data Barang**
   
   terdapat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data barang.
   
3. **Modul Data Customer**

   terdapat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data Cutomer.
   
4. **Modul Data Supplier**

   terdapat  fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data Supplier.
   
5. **Modul Data Petugas**

   terdapat  fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data Petugas.
   
6. **Modul Transaksi Penerimaan**

   terdapat  fitur untuk melihat, menambah, menghapus dan meng-ekspor transaksi penerimaan.
   
7. **Modul Transaksi Pengeluaran**

   terdapat  fitur untuk melihat, menambah, menghapus dan meng-ekspor transaksi pengeluaran.

8. **Modul Manajemen Akun**

   terdapat fitur untuk melihat dan menghapus akun.
	 
### Role
Terdapat Dua Role yaitu `admin` & `petugas`

### Instalasi & Konfigurasi

Untuk cara instalasi dan konfigurasi caranya sangat mudah

1. Kalian download atau clone repositori ini
2. Masuk ke folder project ini
3. Lalu buka terminal dan jalankan `composer install`
4. Selanjutnya kalian bisa buka file `application/config/config.php` 
5. Ubah isi dari variable `$config['base_url']` dengan `http://localhost/namafolder/`
6. Untuk `namafolder` silahkan kalian ganti sesuai nama folder dari aplikasi ini di komputer atau laptop kalian
7. Import `db_stokbarang.sql` ke database milik kalian
8. Untuk login `admin` kalian bisa menggunakan username = `admin` dan password `admin`
9. Untuk login `petugas` kalian bisa menggunakan username = `PTGS75` dan password `zefri`
