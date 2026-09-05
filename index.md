---
---
# Kebijakan Privasi KRAMA

**Berlaku sejak:** 24 Agustus 2026
**Terakhir diperbarui:** 5 September 2026

---

## 1. Siapa kami

KRAMA adalah aplikasi layanan lokal yang menghubungkan pelanggan dengan driver,
merchant, dan terapis untuk layanan antar-jemput, pesan-antar makanan, apotek,
laundry, pengiriman barang, dan pijat panggilan (Krama-Pijat).

Aplikasi ini terdiri dari dua bagian:

- **KRAMA** — untuk pelanggan
- **KRAMA Mitra** — untuk driver, merchant, dan terapis

Pengelola: Havid Munajat (perorangan)
Alamat: Komp Bumi Cigadung Lestari No. 14, Kelurahan Cigadung, Karang Tanjung,
Pandeglang
Kontak privasi: halokrama@gmail.com

## 2. Data yang kami kumpulkan

### 2.1 Data yang Anda berikan sendiri

| Data | Untuk apa | Wajib? |
|---|---|---|
| Nama | Ditampilkan ke mitra saat pesanan berjalan | Ya |
| Nomor telepon | Masuk akun dan dihubungi saat pengantaran | Ya |
| Email | Satu-satunya jalan pemulihan akun kalau lupa password | Ya |
| Password | Masuk akun. **Disimpan dalam bentuk teracak (hash), bukan teks asli** | Ya |
| Foto profil | Ditampilkan di aplikasi | Tidak |
| Rekening bank / e-wallet | **Hanya untuk mitra**, dipakai mencairkan saldo | Tidak |

### 2.2 Data lokasi

KRAMA meminta izin **lokasi presisi** (`ACCESS_FINE_LOCATION`).

- **Kapan diambil:** saat Anda memilih titik jemput/antar; khusus driver dan
  terapis, juga selama status "siap menerima pesanan" atau ada pesanan berjalan,
  agar posisinya bisa dicocokkan dengan pesanan terdekat dan terlihat pelanggan.
- **Untuk apa:** menghitung jarak dan ongkos kirim, menampilkan posisi di peta,
  serta mencocokkan pesanan dengan mitra terdekat.
- **Yang disimpan:** alamat serta koordinat titik jemput dan titik antar pada
  setiap pesanan, dan posisi terakhir mitra yang sedang berstatus siap.

Aplikasi **tidak** melacak lokasi Anda saat tidak ada pesanan berjalan, status
siap dimatikan, dan aplikasi tidak dibuka.

### 2.3 Foto dan berkas

- **Pengiriman barang (Cargo):** foto barang dari pelanggan, serta foto bukti
  dari driver saat pengambilan dan penyerahan.
- **Pendaftaran terapis — foto KTP (WAJIB).** Terapis datang seorang diri ke
  rumah pelanggan, jadi yang dipastikan lebih dulu adalah **identitasnya**.
  Diperiksa admin sebelum akun diaktifkan.

  Foto KTP **disimpan tertutup dan tidak punya alamat publik.** Ia tidak bisa
  dilihat pelanggan maupun mitra lain. Admin pun tidak memegang tautan tetap —
  setiap kali ingin melihatnya, dibuatkan tautan baru yang mati dalam 5 menit.

- **Pendaftaran terapis — sertifikat (opsional).** Boleh dilampirkan bila
  punya. Tidak diwajibkan karena sebagian besar terapis komunitas tidak
  memiliki sertifikat resmi.

Foto diambil dari kamera atau galeri **atas tindakan Anda sendiri**. Aplikasi
tidak membaca galeri Anda di luar berkas yang Anda pilih.

### 2.4 Data transaksi

Riwayat pesanan, saldo dompet, poin kredit, dan mutasi transaksi.

**Kami tidak pernah menyimpan nomor kartu atau data pembayaran Anda.**
Pembayaran non-tunai diproses oleh **Midtrans**, dan data kartu ditangani
sepenuhnya oleh mereka.

### 2.5 Data perangkat

Token notifikasi perangkat, agar aplikasi bisa mengirim pemberitahuan status
pesanan. KRAMA Mitra meminta izin notifikasi (`POST_NOTIFICATIONS`) karena
mitra perlu segera tahu ada pesanan masuk.

### 2.6 Teks yang Anda ketik ke fitur AI

KRAMA punya fitur pemesanan dengan bahasa sehari-hari. Teks yang Anda ketik
dikirim ke layanan AI **Google Gemini** untuk diterjemahkan menjadi rincian
pesanan.

**Jangan menuliskan informasi pribadi yang sensitif** pada kolom tersebut —
cukup tuliskan apa yang ingin Anda pesan.

### 2.7 Pesan dalam aplikasi

Pelanggan dan mitra bisa saling berkirim pesan selama pesanan berjalan. Isi
pesan tersimpan di server dan terkait pada pesanan yang bersangkutan, sehingga
bisa dipakai menyelesaikan sengketa. Hanya kedua pihak dalam pesanan itu yang
bisa membacanya.

### 2.8 Data khusus Krama-Pijat

Layanan pijat panggilan mengumpulkan data yang tidak ada di layanan lain,
karena terapis datang seorang diri ke rumah pelanggan. Alasan tiap data
disebutkan agar jelas kegunaannya:

| Data | Dari siapa | Kenapa dikumpulkan |
|---|---|---|
| **Jenis kelamin terapis** | Terapis | Pelanggan boleh memilih jenis kelamin terapis. Tanpa data ini, permintaan itu tidak bisa dipenuhi. |
| **Foto KTP** | Terapis | WAJIB. Memastikan identitas orang yang datang ke rumah pelanggan. Disimpan tertutup, tanpa alamat publik |
| **Sertifikat** | Terapis | OPSIONAL. Sebagian besar terapis komunitas tidak punya sertifikat resmi |
| **Preferensi jenis kelamin** | Pelanggan | Disimpan pada pesanan, bukan pada profil — preferensi bisa berbeda tiap kali memesan |
| **Waktu mulai & selesai sesi** | Dicatat sistem | Keamanan kedua pihak dan bukti bila ada sengketa soal durasi. **Bukan diketik terapis** |
| **Lokasi saat tombol darurat ditekan** | Penekan tombol | Agar tim Krama bisa menemukan lokasi kejadian. Bisa berbeda dari alamat pesanan |
| **Isi laporan darurat** | Penekan tombol | Menangani keadaan darurat dan menjadi catatan bila berlanjut ke perkara hukum |
| **Persetujuan Ketentuan Layanan** | Pelanggan | Waktu dan versi yang disetujui dicatat pada tiap pesanan |
| **Catatan verifikasi** | Admin | Hasil panggilan telepon verifikasi pelanggan sebelum pesanan pijat pertama |

**Verifikasi pelanggan lewat telepon.** Sebelum bisa memesan Krama-Pijat
pertama kali, tim Krama menelepon nomor pada akun Anda untuk memastikan
datanya benar. Anda boleh menuliskan waktu terbaik dihubungi. Hasil panggilan
dan alasan bila ditolak dicatat, dan alasannya dikirimkan kepada Anda.

**Alarm darurat tidak pernah dihapus.** Catatan alarm hanya ditandai selesai,
tidak dihilangkan — karena bila terjadi perkara hukum, catatan itulah buktinya.

## 3. Dasar dan tujuan pemrosesan

Kami memproses data di atas untuk:

1. Menjalankan layanan yang Anda minta
2. Menghitung tarif dan memproses pembayaran
3. Menghubungkan Anda dengan driver, merchant, atau terapis
4. Mengirim pemberitahuan status pesanan
5. Menangani keluhan, keadaan darurat, dan penyelesaian sengketa
6. Mencegah penyalahgunaan dan penipuan

## 4. Pihak ketiga yang menerima data

| Pihak | Data yang diterima | Untuk apa |
|---|---|---|
| Google Maps Platform | Koordinat & kata kunci alamat | Peta, pencarian alamat, jarak jalan |
| Google Gemini | Teks pesanan yang Anda ketik | Menerjemahkan jadi rincian pesanan |
| Firebase Cloud Messaging | Token perangkat | Mengirim notifikasi |
| Midtrans | Data pembayaran | Memproses pembayaran non-tunai |
| Resend | Alamat email | Mengirim email pemulihan password |
| Neon | Seluruh data aplikasi | Penyimpanan basis data |
| Railway | Seluruh data aplikasi | Tempat aplikasi berjalan |

Sebagian penyedia di atas memproses data di luar wilayah Indonesia.

**Kami tidak menjual data pribadi Anda kepada siapa pun.**

## 5. Data yang terlihat pengguna lain

Saat pesanan berjalan, sebagian data Anda ditampilkan seperlunya:

- **Driver dan merchant melihat:** nama, nomor telepon, alamat, dan titik lokasi
  Anda — agar pesanan bisa diantar
- **Terapis melihat:** nama, nomor telepon, dan alamat lengkap Anda — ia harus
  benar-benar datang ke sana
- **Pelanggan melihat:** nama mitra dan nomor teleponnya; untuk driver juga
  jenis dan nomor kendaraan; untuk terapis juga jenis kelamin, rata-rata
  penilaian, dan jumlah sesi yang pernah dikerjakan

Data ini hanya terlihat selama pesanan berlangsung dan dalam riwayat pesanan
yang bersangkutan.

### Ulasan Krama-Pijat tampil publik

Setelah sesi pijat selesai, pelanggan **wajib** memberi ulasan, dan ulasan itu
**tampil untuk umum** pada profil terapis. Ini mekanisme akuntabilitas utama
layanan tersebut — tidak ada pengawas lain di lokasi.

Nama penulis ulasan **ditampilkan sebagian**, misalnya "Budi S.". Isi ulasan
ditampilkan apa adanya, jadi **jangan menuliskan informasi pribadi** di sana.

Admin dapat menyembunyikan ulasan yang melanggar (memuat data pribadi, ujaran
kebencian, atau spam). Ulasan tidak dihapus, hanya disembunyikan, dan alasannya
wajib dicatat agar keputusannya bisa ditinjau ulang.

## 6. Berapa lama data disimpan

- **Data akun** — selama akun aktif, dan 12 bulan setelah akun dihapus
- **Riwayat pesanan & transaksi** — 10 tahun sejak akhir tahun buku transaksi
  tersebut, mengikuti ketentuan perpajakan (UU KUP)
- **Foto Cargo** — selama pesanan terkait masih dalam masa penyimpanan di atas
- **Foto KTP terapis** — selama akun mitra aktif. Dihapus bila akun mitra
  dinonaktifkan permanen, kecuali sedang dibutuhkan untuk sengketa berjalan
- **Catatan alarm darurat** — disimpan permanen sebagai catatan keselamatan
- **Kode reset password** — 15 menit, atau setelah 5 kali percobaan salah
  (sudah otomatis berjalan di sistem)

## 7. Keamanan

- Password disimpan dalam bentuk teracak (hash bcrypt), tidak pernah sebagai
  teks asli
- Seluruh komunikasi aplikasi dengan server memakai sambungan terenkripsi
  (HTTPS)
- Kode pemulihan password berlaku 15 menit, sekali pakai, dan mati setelah 5
  kali percobaan salah
- Berhasil mengganti password akan mengakhiri seluruh sesi masuk yang lain
- Ruang pesan hanya bisa dibuka oleh pelanggan dan mitra pada pesanan itu

Tidak ada sistem yang sepenuhnya kebal. Bila terjadi kebocoran data yang
berisiko merugikan Anda, kami akan memberitahukannya.

## 8. Hak Anda

Anda berhak untuk:

- **Melihat** data pribadi yang kami simpan tentang Anda
- **Memperbaiki** data yang keliru — sebagian bisa langsung lewat menu Profil
- **Meminta penghapusan** akun beserta datanya — tersedia di dalam aplikasi
  lewat menu Profil, tanpa perlu menghubungi kami
- **Menarik persetujuan** izin lokasi dan notifikasi kapan saja lewat pengaturan
  perangkat

Kirim permintaan ke halokrama@gmail.com. Kami akan menanggapi dalam waktu wajar.

## 9. Anak-anak

KRAMA tidak ditujukan untuk anak di bawah 17 tahun dan kami tidak dengan sengaja
mengumpulkan data mereka.

## 10. Perubahan kebijakan

Bila kebijakan ini berubah, tanggal "Terakhir diperbarui" di atas akan kami
sesuaikan. Perubahan yang berdampak besar akan diberitahukan di dalam aplikasi.

## 11. Menghubungi kami

Pertanyaan atau keberatan soal privasi:

**Email:** halokrama@gmail.com
**Alamat:** Komp Bumi Cigadung Lestari No. 14, Kelurahan Cigadung, Karang
Tanjung, Pandeglang
