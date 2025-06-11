# Tugas Kode Review - Sistem Rental Mobil

## Sumber Asli
Sistem ini diambil dari [GitHub Repository](https://github.com/fakhrulnugroho/rental-mobil).

## Versi PHP
- PHP Version: **7.x.x**

## Database
- MySQL digunakan sebagai database untuk menyimpan data terkait rental mobil.

### Struktur Database
1. **`tbl_akun`**
   - **Fungsi**: Menyimpan data akun pengguna sistem (admin, dsb).

2. **`tbl_jenis_bayar`**
   - **Fungsi**: Menyimpan jenis pembayaran (Cash, Kredit).

3. **`tbl_merk`**
   - **Fungsi**: Menyimpan data merk mobil (Toyota, Suzuki).

4. **`tbl_mobil`**
   - **Fungsi**: Menyimpan data mobil yang tersedia untuk disewa, termasuk merk, warna, nomor polisi, dan jumlah kursi.

5. **`tbl_pemesan`**
   - **Fungsi**: Menyimpan data pemesan mobil (nama, alamat, jenis kelamin, foto).

6. **`tbl_perjalanan`**
   - **Fungsi**: Menyimpan informasi perjalanan (asal, tujuan, jarak).

7. **`tbl_pesanan`**
   - **Fungsi**: Menyimpan data pesanan penyewaan mobil (harga, tanggal pinjam, tanggal kembali, ID pemesan, ID mobil, ID perjalanan, ID jenis bayar).

## Akun Admin
- **Username**: admin
- **Password**: admin

## Fitur Utama
1. **Modul Master Mobil**
   
   Di modul ini saya membuat fitur untuk melihat, menambah, mengubah dan menghapus master mobil.
   
2. **Modul Master Pemesan**
   
   Di modul ini saya membuat fitur untuk melihat, menambah, mengubah dan menghapus data pemesan.
   
3. **Modul Master Pesanan**

   Di modul ini saya membuat fitur untuk melihat, menambah, mengubah dan menghapus data pesanan.
   
4. **Modul Manajemen Akun**

   Di modul ini saya membuat fitur untuk melihat, menambah dan menghapus data akun atau pengguna.

## Instruksi Setup
1. **Clone repository** ke server lokal:
   ```bash
   git clone https://github.com/fakhrulnugroho/rental-mobil.git
### Instalasi & Konfigurasi
2. Selanjutnya kalian bisa buka file `config.php` 
3. Ubah isi dari konstanta `BASE_URL` dengan `http://localhost/namafolder/`
4. Untuk `namafolder` silahkan kalian ganti sesuai nama folder dari aplikasi ini di komputer atau laptop kalian
5. Ubah juga konfigurasi database di file `config.php` 
6. Untuk login kalian bisa register terlebih dahulu atau menggunakan username = `admin` dan password `admin`

