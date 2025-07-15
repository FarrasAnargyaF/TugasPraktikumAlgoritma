Panduan Instalasi dan Konfigurasi

1. Persiapan
Buka browser dan akses Google Colab.
Klik File > New Notebook untuk membuat file baru.

2. Menjalankan Program
Salin seluruh kode program ke dalam sel (cell) di Google Colab.
Jalankan setiap sel dengan klik tombol ▶ atau tekan Shift + Enter.
Untuk bagian input(), kamu bisa:
Menjalankan versi kode asli di local runtime via terminal (jika support).
ATAU, gunakan versi kode yang sudah dimodifikasi agar tidak memakai input() (simulasi dengan variabel langsung).


Tutorial Penggunaan Aplikasi 

Saat program dijalankan, akan muncul menu utama:

=== MESIN KASIR SEDERHANA ===
1. Tambah Item
2. Hapus Item
3. Cetak Struk & Bayar
4. Keluar
Pilih menu (1-4):

Fungsi-fungsi:

1. Tambah Item
Masukkan nama barang, harga satuan, dan jumlah. Barang akan disimpan ke keranjang.

2. Hapus Item
Menampilkan daftar isi keranjang dan memberi opsi untuk menghapus berdasarkan nomor urutan.

3. Cetak Struk & Bayar
Menampilkan struk belanja lengkap dengan waktu, total, dan meminta jumlah uang pembayaran. Jika cukup, akan menghitung kembalian dan mengosongkan keranjang.

4. Keluar
Menutup program.



FAQ dan Troubleshooting Guide

Q: Bagaimana jika saya salah input harga atau jumlah barang?
A: Hapus item tersebut lewat menu 2, lalu input ulang lewat menu 1.

Q: Kenapa program menolak pembayaran?
A: Pastikan jumlah uang yang dimasukkan lebih besar atau sama dengan total belanja.

Q: Kenapa muncul pesan 'Input tidak valid'?
A: Kemungkinan besar Anda memasukkan huruf di kolom angka. Masukkan angka saja, tanpa huruf atau simbol.

Masalah Umum:

Keranjang kosong saat cetak struk:
Pastikan Anda sudah menambahkan item sebelum mencetak.
