# 🛒 Aplikasi Pencatatan Produk Toko (ProdukToko)

**ProdukToko** adalah aplikasi desktop berbasis **JavaFX** yang dirancang untuk mencatat dan mengelola inventaris produk toko secara efisien. Proyek ini dibangun menggunakan arsitektur **MVC (Model-View-Controller)**, di mana antarmuka penggunanya didesain menggunakan **JavaFX Scene Builder (FXML)** dan disesuaikan menggunakan CSS.

Data produk pada aplikasi ini disimpan secara *In-Memory* (data tersimpan selama aplikasi berjalan). Hal ini membuat aplikasi sangat ringan, praktis, dan siap langsung diuji coba oleh siapa saja tanpa perlu melakukan instalasi atau konfigurasi *database* tambahan.

### ✨ Fitur Utama
- **Manajemen Produk**: Form input untuk menambahkan produk baru dengan validasi otomatis (nama wajib diisi, harga harus berupa angka positif).
- **Kategori Produk**: Pilihan *dropdown* kategori (Makanan atau Minuman).
- **Lampiran Gambar Produk**: Fitur untuk memilih dan mengunggah gambar produk secara lokal (format PNG/JPEG, maksimal 5 MB) yang dilengkapi dengan *preview* langsung.
- **Tabel Daftar Produk Interaktif**: Tabel yang menampilkan daftar produk secara rapi, lengkap dengan **thumbnail gambar produk** di dalam baris tabel, kode produk otomatis (PRD001, dst.), nama, kategori, dan harga.
- **Pencarian & Filter**: Fitur pencarian *real-time* berdasarkan nama atau kode produk, serta filter khusus berdasarkan kategori.
- **Format Mata Uang**: Harga produk secara otomatis diformat ke dalam standar mata uang Rupiah (Rp).
- **Halaman Detail**: Halaman khusus yang menampilkan informasi lengkap dari sebuah produk beserta gambar dalam resolusi yang lebih besar.

### 🛠️ Teknologi yang Digunakan
- **Bahasa Pemrograman**: Java (JDK 17 atau lebih baru)
- **Framework UI**: JavaFX 21
- **Build Tool**: Apache Maven
- **Desain UI**: FXML & CSS
- **IDE yang Disarankan**: Apache NetBeans

---

## 🚀 Cara Mengunduh dan Menjalankan Proyek

Jika Anda ingin mencoba menjalankan aplikasi ini di komputer Anda menggunakan **Apache NetBeans**, silakan ikuti langkah-langkah berikut:

### 1. Unduh Proyek dari GitHub
1. Pada halaman utama repositori ini, klik tombol hijau bertuliskan **<> Code**.
2. Pilih opsi **Download ZIP**.
3. Setelah selesai diunduh, **ekstrak (unzip)** file tersebut ke dalam sebuah folder di komputer Anda (misalnya di folder *Documents* atau *Downloads*).

### 2. Buka Proyek di NetBeans
1. Buka aplikasi **Apache NetBeans**.
2. Klik menu **File** di pojok kiri atas, lalu pilih **Open Project...** (atau klik ikon folder kuning terbuka di *toolbar* atas).
3. Cari folder `ProdukToko` hasil ekstraksi tadi. Folder ini biasanya akan ditandai dengan ikon berhuruf **[ma]**, yang menandakan bahwa ini adalah proyek berbasis Maven.
4. Pilih folder tersebut, lalu klik tombol **Open Project**.

### 3. Tunggu Sinkronisasi Maven (Sangat Penting!)
Karena aplikasi ini menggunakan sistem Maven, saat pertama kali dibuka, NetBeans membutuhkan koneksi internet untuk mengunduh pustaka atau *library* yang dibutuhkan (seperti JavaFX).
* Perhatikan pojok kanan bawah layar NetBeans Anda. Jika terdapat *loading bar* yang sedang berjalan, **tunggu sampai proses tersebut benar-benar selesai** sebelum melanjutkan ke langkah berikutnya.

### 4. Build dan Jalankan Aplikasi
1. Di jendela *Projects* (berada di sebelah kiri layar), klik kanan pada nama proyek **ProdukToko**.
2. Pilih menu **Clean and Build**. Tunggu beberapa saat sampai muncul pesan teks bertuliskan *BUILD SUCCESS* di jendela *Output* bagian bawah.
3. Setelah proses *build* sukses, klik kanan kembali pada proyek **ProdukToko**, lalu pilih **Run** (atau Anda juga bisa mengklik ikon tombol *Play* berwarna hijau di deretan menu atas).
4. Aplikasi Pencatatan Produk Toko akan langsung terbuka dan siap untuk Anda gunakan!

---


Contoh Tampilan awal nya:

<img width="1195" height="907" alt="image" src="https://github.com/user-attachments/assets/ae3892e5-d12f-4505-b95b-8aa9bd18e349" />
