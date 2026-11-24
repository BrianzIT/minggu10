# Buku Tamu Kampus — Pertemuan 10

Brian Fernand Prabaswara · A12.2025.07386

Letakkan folder minggu10 di htdocs (XAMPP) atau www (Laragon), jalankan Apache, lalu buka http://localhost/minggu10/. Isi Rani, rani@example.com, dan Halo kampus. Klik Kirim untuk membuka proses.php, lalu klik Kembali ke form.

## Percobaan subbab 10.2

Buka http://localhost/minggu10/latihan.php. Untuk setiap baris, ubah hanya satu nilai di editor, simpan, lalu muat ulang browser.

| Uji | $jumlah | $status | Prediksi tampilan |
| --- | --- | --- | --- |
| W10-01 | 1 | "aktif" | Jumlah pesan: 1 dan Form siap. |
| W10-02 | 3 | "aktif" | Jumlah pesan: 3 dan Form siap. |
| W10-03 | 3 | "tutup" | Jumlah pesan: 3 dan Form ditutup. |

Pada W10-03, echo menampilkan nilai 3 dari $jumlah. Perbandingan $status === "aktif" bernilai false karena status berisi "tutup", sehingga PHP menjalankan else.

Klik kanan halaman latihan dan pilih View Page Source. Bandingkan dengan latihan.php di editor. Browser menerima HTML dengan angka dan paragraf dari cabang yang dipilih. Penugasan variabel dan kondisi if diproses di server.

Untuk diagnosis, hapus sementara tanda titik koma setelah penugasan $jumlah, simpan, lalu muat ulang. Catat pesan aktual di layar atau log PHP. Pasang lagi titik koma dan kembalikan nilai ke 1 dan "aktif".

Buka http://localhost/minggu10/cek-lingkungan.php untuk melihat versi PHP dan status mbstring pada komputer yang digunakan.
