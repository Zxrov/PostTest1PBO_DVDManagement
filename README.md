# 🎬 Sistem Manajemen Penyewaan DVD/Film Online

## Deskripsi Program

Project ini dibuat untuk **Post Test Praktikum Pemrograman Berorientasi Objek (PBO)**.  
Aplikasi berbasis console ini mensimulasikan sistem rental DVD sederhana dengan fitur:
- Menambahkan, melihat, mengubah, dan menghapus data DVD
- Menambahkan dan melihat data pelanggan
- Melakukan transaksi penyewaan DVD (pinjam & kembali)
- Menampilkan daftar transaksi penyewaan

## Struktur Class
Program ini menggunakan 3 class utama (dalam satu file `Main.java`):
- `DVD` → menyimpan data film (id, judul, genre, tahun, status pinjam)
- `Pelanggan` → menyimpan data pelanggan (id, nama)
- `Transaksi` → menyimpan data penyewaan (id transaksi, pelanggan, DVD, tanggal pinjam & kembali)

## Fitur Utama
- ➕ Tambah data DVD baru
- 📋 Lihat daftar DVD yang tersimpan
- ✏️ Ubah data DVD berdasarkan ID
- ❌ Hapus data DVD berdasarkan ID

## Struktur Program
- `DVD` → class inner untuk menyimpan data DVD (ID, judul, genre, tahun)
- `Main` → class utama berisi menu interaktif dan logika CRUD


## Tampilan Menu Program

<img width="365" height="179" alt="image" src="https://github.com/user-attachments/assets/264ed29e-a798-4b40-a6a8-065651cd47c5" />
User diminta untuk memilih 1 menu dari ke-5 menu yang tersedia.

## Menu 1 -> Tambah Data (CREATE)


