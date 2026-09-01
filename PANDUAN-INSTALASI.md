# Panduan Lengkap Instalasi & Pembaruan Tema SmartNews Blogger

Tema **SmartNews Blogger** telah diperbarui dengan seluruh penyesuaian terbaru sesuai permintaan:

---

## 🌟 Fitur Baru & Pembaruan Utama (Versi Terbaru):

1. **Tombol "Pesan Web" Terhubung & Tampil di Mobile**:
   - Link CTA telah diperbarui ke: **`https://smartnews.berandadigital/penjualan`**.
   - Tombol **Pesan Web** kini tampil rapi di header baik pada tampilan Desktop maupun Mobile / HP.
   - Juga tersedia tombol Pesan Web di dalam menu samping (Offcanvas Drawer).

2. **Hero Slider 5 Berita (Persis Versi Web Aslinya)**:
   - Slider berita utama di bagian atas kini menampilkan **5 berita pilihan** dengan foto, kategori badge, judul, dan durasi video/foto.
   - Pada HP / Mobile: slider menampilkan kartu utama + intipan (*peek preview*) kartu berikutnya untuk navigasi swipe yang sangat nyaman.
   - Pada Desktop: menampilkan 3 slide sekaligus dengan tombol navigasi panah.

3. **Pembersihan Total Teks Artikel (`\n`, `\"`, Kode Tertinggal Hilang 100%)**:
   - Berkas impor database [`smartnews-demo-content.xml`](smartnews-demo-content.xml) telah dibersihkan secara total dari segala baris kode mentah, karakter `\n`, `\r\n`, backslash, dan tag kosong.
   - Template theme juga dilengkapi dengan **Automatic Client-Side DOM Text Cleaner** sehingga artikel lama di blog Anda yang memiliki teks `\n` akan otomatis dibersihkan dan diformat menjadi paragraf rapi saat dibuka pengunjung.

4. **Tampilan Mobile Presisi & Rapi (Persis Desain Asli)**:
   - Header mobile lengkap: Logo SmartNews, tombol Pesan Web, tombol ID/EN, pencarian, mode gelap, dan tombol menu.
   - Bar kategori horizontal yang dapat digeser (*scrollable pills*).
   - Breaking News berjalan dengan animasi titik merah berdenyut (*pulse dot*).
   - Topik hangat trending hashtags (`#HUTRI81`, `#IHSG`, `#MobilListrik`, dll).
   - Feed berita dan sidebar tersusun rapi dan responsif.

5. **Sticky Sidebar Kanan & Dual Bahasa (ID / EN) Berfungsi Penuh**.

---

## 🚀 Langkah Memperbarui (Cukup 1 Menit):

### Langkah 1: Update Tema HTML (Wajib)
1. Buka file **[`smartnews-theme.xml`](smartnews-theme.xml)**.
2. Tekan **Ctrl + A** (Pilih Semua), lalu **Ctrl + C** (Salin kode).
3. Buka dashboard [Blogger.com](https://www.blogger.com) -> Masuk ke menu **Tema (Theme)**.
4. Klik tanda panah di samping tombol **SESUAIKAN** -> Pilih **Edit HTML**.
5. Hapus seluruh kode lama (**Ctrl + A** lalu **Delete**), lalu Tempel kode baru (**Ctrl + V**).
6. Klik ikon **Simpan (Disket)** di pojok kanan atas.

### Langkah 2: Update Isi Berita Bersih (Opsional jika ingin artikel tanpa `\n`)
1. Buka [Blogger.com](https://www.blogger.com) -> **Setelan (Settings)** -> **Kelola Blog (Manage Blog)**.
2. Klik **Impor Konten (Import Content)**.
3. Pilih dan upload file: **[`smartnews-demo-content.xml`](smartnews-demo-content.xml)**.
4. Seluruh 83 artikel akan terimpor dalam kondisi format HTML paragraf yang bersih, rapi, dan sempurna!
