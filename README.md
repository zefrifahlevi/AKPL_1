# Aplikasi Inventori Pengelolaan Stok Barang

### Fiturnya apa saja sih?
Untuk fiturnya sebagai berikut
1. **Fitur Authentikasi**
   
   terdapat fitur untuk login dan logout.
   
2. **Fitur Data Barang**
   
   terdapat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data barang.
   
3. **Fitur Data Customer**

   terdapat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data Cutomer.
   
4. **Fitur Data Supplier**

   terdapat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data Supplier.
   
5. **Fitur Data Petugas**

   terdapat fitur untuk melihat, menambah, mengubah, menghapus dan meng-ekspor data Petugas.
   
6. **Fitur Transaksi Penerimaan**

   terdapat fitur untuk melihat, menambah, menghapus dan meng-ekspor transaksi penerimaan.
   
7. **Fitur Transaksi Pengeluaran**

   terdapat fitur untuk melihat, menambah, menghapus dan meng-ekspor transaksi pengeluaran.

8. **Fitur Manajemen Akun**

   terdapat fitur untuk melihat dan menghapus akun.
	 
### Role
Terdapat Dua Role yaitu `admin` & `petugas`

### Instalasi & Konfigurasi

Untuk cara instalasi dan konfigurasi caranya sangat mudah

1. Kalian download atau clone repositori ini
2. Diusahakan menggunakan Php 8.0 atau 7.4
3. Masuk ke folder project ini
4. Lalu buka terminal dan jalankan `composer install` (Opsional)
5. Selanjutnya kalian bisa buka file `application/config/config.php` 
6. Anda bisa ubah isi dari variable `$config['base_url']` dengan `http://localhost/namafolder/` default:`http://locahost/stokbarang`
7. Untuk `namafolder` silahkan kalian ganti sesuai nama folder dari aplikasi ini di komputer atau laptop kalian
8. Import `db_stokbarang.sql` ke database milik kalian
9. Untuk login `admin` kalian bisa menggunakan username = `admin` dan password `admin`
10. Untuk login `petugas` kalian bisa menggunakan username = `PTGS75` dan password `zefri`
