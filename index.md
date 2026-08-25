---
---
# Kebijakan Privasi KRAMA

**Berlaku sejak:** 24 Agustus 2026
**Terakhir diperbarui:** 24 Agustus 2026
1. Siapa kami

KRAMA adalah aplikasi layanan lokal yang menghubungkan pelanggan dengan driver
dan merchant untuk layanan antar-jemput, pesan-antar makanan, apotek, laundry,
dan pengiriman barang.

Aplikasi ini terdiri dari dua bagian:

* **KRAMA** — untuk pelanggan
* **KRAMA Mitra** — untuk driver dan merchant

Pengelola: PERORANGAN
Alamat: Komp Bumi Cigadung Lesatari No.14 Kelurahan Cigadung, Karang Tanjung, Pandeglang
Kontak privasi: halokrama@gmail.com

## 2\. Data yang kami kumpulkan

### 2.1 Data yang Anda berikan sendiri

|Data|Untuk apa|Wajib?|
|-|-|-|
|Nama|Ditampilkan ke driver/merchant saat pesanan berjalan|Ya|
|Nomor telepon|Masuk akun dan dihubungi saat pengantaran|Ya|
|Email|Satu-satunya jalan pemulihan akun kalau lupa password|Ya|
|Password|Masuk akun. **Disimpan dalam bentuk teracak (hash), bukan teks asli**|Ya|
|Foto profil|Ditampilkan di aplikasi|Tidak|
|Rekening bank / e-wallet|**Hanya untuk mitra**, dipakai mencairkan saldo|Tidak|

### 2.2 Data lokasi

KRAMA meminta izin **lokasi presisi** (`ACCESS\_FINE\_LOCATION`).

* **Kapan diambil:** saat Anda memilih titik jemput/antar, dan — khusus driver —
selama pesanan berjalan agar posisinya terlihat pelanggan.
* **Untuk apa:** menghitung jarak dan ongkos kirim, menampilkan posisi di peta,
serta mencocokkan pesanan dengan driver terdekat.
* **Yang disimpan:** alamat serta koordinat titik jemput dan titik antar pada
setiap pesanan.

Aplikasi **tidak** melacak lokasi Anda saat tidak ada pesanan berjalan dan
aplikasi tidak dibuka.

### 2.3 Foto

Untuk layanan pengiriman barang (Cargo), aplikasi meminta foto:

* **Foto barang** dari pelanggan — agar driver memastikan barang yang diangkut
benar, dan jadi pembanding bila ada klaim kerusakan
* **Foto bukti** dari driver saat pengambilan dan penyerahan barang

Foto diambil dari kamera atau galeri **atas tindakan Anda sendiri**. Aplikasi
tidak membaca galeri Anda di luar foto yang Anda pilih.

### 2.4 Data transaksi

Riwayat pesanan, saldo dompet, poin kredit, dan mutasi transaksi.

**Kami tidak pernah menyimpan nomor kartu atau data pembayaran Anda.**
Pembayaran non-tunai diproses oleh **Midtrans**, dan data kartu ditangani
sepenuhnya oleh mereka.

### 2.5 Data perangkat dan izin aplikasi

|Izin Android|Untuk apa|Berlaku di app|
|-|-|-|
|`ACCESS\_FINE\_LOCATION`|Lokasi presisi (lihat Bagian 2.2)|KRAMA \& KRAMA Mitra|
|`CAMERA`|Mengambil foto barang/bukti Cargo (lihat Bagian 2.3)|KRAMA \& KRAMA Mitra|
|Akses galeri/foto|Memilih foto yang sudah ada, sebagai alternatif kamera|KRAMA \& KRAMA Mitra|
|`POST\_NOTIFICATIONS`|Notifikasi pesanan masuk \& perubahan status|Terutama KRAMA Mitra (driver/merchant perlu tahu segera)|

Aplikasi juga menyimpan **token notifikasi perangkat**, agar bisa mengirim
pemberitahuan status pesanan ke perangkat yang tepat.

### 2.6 Teks yang Anda ketik ke fitur AI

KRAMA punya fitur pemesanan dengan bahasa sehari-hari. Teks yang Anda ketik
dikirim ke layanan AI **Google Gemini** untuk diterjemahkan menjadi rincian
pesanan.

**Jangan menuliskan informasi pribadi yang sensitif** pada kolom tersebut —
cukup tuliskan apa yang ingin Anda pesan.

## 3\. Dasar dan tujuan pemrosesan

Kami memproses data di atas untuk:

1. Menjalankan layanan yang Anda minta
2. Menghitung tarif dan memproses pembayaran
3. Menghubungkan Anda dengan driver atau merchant
4. Mengirim pemberitahuan status pesanan
5. Menangani keluhan dan penyelesaian sengketa
6. Mencegah penyalahgunaan dan penipuan

## 4\. Pihak ketiga yang menerima data

|Pihak|Data yang diterima|Untuk apa|
|-|-|-|
|Google Maps Platform|Koordinat \& kata kunci alamat|Peta, pencarian alamat, jarak jalan|
|Google Gemini|Teks pesanan yang Anda ketik|Menerjemahkan jadi rincian pesanan|
|Firebase Cloud Messaging|Token perangkat|Mengirim notifikasi|
|Midtrans|Data pembayaran|Memproses pembayaran non-tunai|
|Resend|Alamat email|Mengirim email pemulihan password|
|Neon|Seluruh data aplikasi|Penyimpanan basis data|
|Railway|Seluruh data aplikasi|Tempat aplikasi berjalan|

**Transfer data ke luar Indonesia:** sebagian penyedia di atas (termasuk
Google, dan kemungkinan Neon/Railway tergantung lokasi server yang dipilih)
memproses atau menyimpan data di server yang berlokasi di luar wilayah
Indonesia. Kami mengambil penyedia yang memiliki standar keamanan data yang
memadai, namun pemrosesan lintas negara ini tunduk pada ketentuan transfer
data pribadi lintas batas negara sebagaimana diatur dalam UU No. 27 Tahun
2022 tentang Pelindungan Data Pribadi (UU PDP). Dengan menggunakan aplikasi
ini, Anda memahami dan menyetujui kemungkinan pemrosesan data lintas negara
tersebut, sepanjang diperlukan untuk menjalankan layanan sebagaimana
dijelaskan di Bagian 3.

**Kami tidak menjual data pribadi Anda kepada siapa pun.**

## 5\. Data yang terlihat pengguna lain

Saat pesanan berjalan, sebagian data Anda ditampilkan seperlunya:

* **Driver dan merchant melihat:** nama, nomor telepon, alamat, dan titik lokasi
Anda — agar pesanan bisa diantar
* **Pelanggan melihat:** nama driver, nomor telepon, jenis dan nomor kendaraan

Data ini hanya terlihat selama pesanan berlangsung dan dalam riwayat pesanan
yang bersangkutan.

## 6\. Berapa lama data disimpan

|Jenis data|Lama disimpan|Dasar|
|-|-|-|
|Riwayat pesanan \& transaksi|**10 tahun** sejak akhir tahun buku transaksi tersebut|Pasal 28 ayat (11) UU KUP jo. Pasal 11 UU No. 8/1997 tentang Dokumen Perusahaan — kewajiban hukum, bukan pilihan|
|Data akun|Selama akun aktif, dan 12 bulan setelah akun dihapus|Kebutuhan operasional layanan|
|Foto Cargo|6-12 bulan setelah pesanan selesai|Bukti pendukung bila ada klaim kerusakan|
|Kode reset password|15 menit, sekali pakai|Sudah berlaku otomatis di sistem|


## 7\. Keamanan

* Password disimpan dalam bentuk teracak (hash bcrypt), tidak pernah sebagai
teks asli
* Seluruh komunikasi aplikasi dengan server memakai sambungan terenkripsi
(HTTPS)
* Kode pemulihan password berlaku 15 menit, sekali pakai, dan mati setelah 5
kali percobaan salah
* Berhasil mengganti password akan mengakhiri seluruh sesi masuk yang lain

Tidak ada sistem yang sepenuhnya kebal. Bila terjadi kebocoran data yang
berisiko merugikan Anda, kami akan memberitahukannya.

## 8\. Hak Anda

Anda berhak untuk:

* **Melihat** data pribadi yang kami simpan tentang Anda
* **Memperbaiki** data yang keliru — sebagian bisa langsung lewat menu Profil
* **Meminta penghapusan** akun beserta datanya
* **Menarik persetujuan** izin lokasi, kamera, dan notifikasi kapan saja lewat
pengaturan perangkat

Kirim permintaan ke halokrama@gmail.com. Kami akan menanggapi dalam waktu wajar.

> Catatan: sebagian data transaksi tetap kami simpan meski akun dihapus,
> sepanjang diwajibkan peraturan perpajakan (lihat Bagian 6) atau dibutuhkan
> untuk menyelesaikan sengketa yang sedang berjalan.

## 9\. Anak-anak

KRAMA tidak ditujukan untuk anak di bawah 17 tahun dan kami tidak dengan sengaja
mengumpulkan data mereka.

## 10\. Perubahan kebijakan

Bila kebijakan ini berubah, tanggal "Terakhir diperbarui" di atas akan kami
sesuaikan. Perubahan yang berdampak besar akan diberitahukan di dalam aplikasi.

## 11\. Menghubungi kami

Pertanyaan atau keberatan soal privasi:

**Email:** halokrama@gmail.com
**Alamat:** Komp Bumi Cigadung Lesatri No.14 Kelurahan Cigadung, Karang Tanjung Pandeglang

