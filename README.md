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
1. **Login/Logout** untuk admin
2. **Manajemen Mobil** (Tambah, Edit, Hapus mobil)
3. **Manajemen Transaksi** (Melihat riwayat transaksi, status pembayaran)
4. **Manajemen Pengguna** (Menambah, mengedit data pengguna)

## Instruksi Setup
1. **Clone repository** ke server lokal:
   ```bash
   git clone https://github.com/fakhrulnugroho/rental-mobil.git
