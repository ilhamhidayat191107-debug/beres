# 📑 DOKUMEN BUSINESS OVERVIEW & SOURCE CODE
## PROYEK E-COMMERCE: BITZZ PHONE (Apple Premium Reseller)

Dokumen ini merupakan perencanaan bisnis komprehensif untuk platform e-commerce **BITZZ PHONE**, yang diimplementasikan dalam bentuk prototipe website berbasis HTML, CSS, dan JavaScript.

**Identitas Mahasiswa / Developer:**
- **Nama:** Ilham Hidayat
- **NPM:** 209250014
- **Program Studi:** Administrasi Bisnis
- **Kelas:** ABI 1
- **Universitas:** International Women University

---

## 📊 BAGIAN 1: RENCANA BISNIS KOMPREHENSIF (BUSINESS OVERVIEW)

### 1. Nama Bisnis, Deskripsi, dan Value Proposition
* **Nama Bisnis:** **BITZZ PHONE**
* **Deskripsi Bisnis:** BITZZ PHONE adalah sebuah platform *e-commerce* terspesialisasi yang bertindak sebagai *Apple Premium Reseller*. Platform ini tidak hanya berfungsi sebagai etalase digital, tetapi juga ekosistem belanja end-to-end yang mengelola katalog produk (iPhone, MacBook, iPad), autentikasi pelanggan, manajemen keranjang belanja, hingga penerbitan *invoice* otomatis.
* **Value Proposition (Nilai Jual Unik):**
    * **"Gadget Premium, Pelayanan Bintang Lima!"**
    * *Frictionless User Experience:* Antarmuka dirancang modern, responsif, dan bebas *lag* dengan navigasi berbasis *Single Page Application* (SPA) feel.
    * *Trust & Authenticity:* Jaminan 100% produk orisinal dengan garansi resmi.
    * *Integrated Payment Simulation:* Sistem *checkout* instan yang mensimulasikan integrasi *Payment Gateway* terkini.

### 2. Target Market & Segmentasi Pelanggan
* **Geografis:** Fokus utama pada wilayah urban dan sub-urban di Indonesia (seperti Jabodetabek, Bandung, Surabaya) dengan ekspansi pengiriman nasional.
* **Demografis:** 
    * Usia: 18 – 45 Tahun.
    * Pendapatan: Menengah (*Middle*) hingga Menengah Atas (*Upper-Middle Class*).
    * Profesi: Mahasiswa, profesional muda, desainer grafis, kreator konten, dan eksekutif bisnis.
* **Psikografis:** Masyarakat melek teknologi (*tech-savvy*) yang mengutamakan prestise, gaya hidup modern, efisiensi, dan kualitas perangkat tinggi untuk produktivitas.
* **Perilaku (Behavioral):** Pelanggan yang memiliki loyalitas tinggi terhadap ekosistem merek Apple (Apple Ecosystem Lock-in).

### 3. Analisis Pasar Singkat & Kompetitor (SWOT Approach)
* **Kondisi Pasar:** Penetrasi internet dan adopsi belanja *online* di Indonesia terus meningkat. Permintaan terhadap gawai premium (terutama produk Apple) tetap stabil bahkan cenderung naik karena kebutuhan *remote working* dan *digital creation*.
* **Kompetitor Utama:** 
    * *Authorized Reseller Besar:* iBox, Digimap (Memiliki keunggulan lokasi fisik).
    * *Marketplace / E-commerce:* Tokopedia, Shopee, Blibli (Memiliki keunggulan *traffic* massif).
* **Posisi BITZZ PHONE (Competitive Advantage):** Mengisi celah dengan memberikan pengalaman pengguna yang lebih personal, fokus 100% pada satu niche (Apple), dan proses *checkout* yang lebih singkat tanpa gangguan iklan pihak ketiga.

### 4. Strategi Manajemen Produk & Katalog
* **Kategori Produk Terstruktur:** Katalog dibagi menjadi tiga pilar utama:
    1. **iPhone:** Meliputi seri reguler hingga seri "Pro Max" terbaru (iPhone 14 s/d iPhone 17).
    2. **MacBook:** Varian Air dan Pro dengan integrasi chip Apple Silicon (M1, M2, M3).
    3. **iPad:** Tablet multifungsi (iPad Gen 10, Air, Mini, dan Pro M4).
* **Strategi Visual:** Menggunakan gambar beresolusi tinggi dengan format *background transparent* (PNG) agar menyatu dengan palet warna website yang premium (gelap/elegan). Terdapat sistem "Badge" seperti *Terbaru* atau *Hot Item* untuk menarik perhatian psikologis konsumen.
* **Fitur Pencarian (Live Search):** Implementasi algoritma pencarian instan berbasis JavaScript untuk mendeteksi *keyword* secara *real-time*, sehingga pengguna tidak perlu menavigasi halaman terlalu lama.

### 5. Model Bisnis & Revenue Stream
* **Model Bisnis Utama:** **B2C (Business to Consumer) Retail.** BITZZ PHONE bertindak sebagai *direct retailer* yang mendistribusikan perangkat dari distributor resmi ke konsumen akhir.
* **Aliran Pendapatan (Revenue Stream):**
    * *Primary Stream:* Margin keuntungan dari penjualan unit perangkat keras utama (Hardware).
    * *Secondary Stream (Future Plan):* Penjualan aksesori (Case, Adaptor, MagSafe, AirPods) dan penawaran layanan pelengkap (Pemasangan Screen Protector, Extended Warranty/AppleCare+).

### 6. Strategi Harga, Promosi, dan Diskon
* **Strategi Harga (Pricing Strategy):** 
    * Menggunakan *Premium Pricing Strategy* untuk menjaga *brand image* Apple yang eksklusif.
    * Penerapan *Psychological Pricing* pada beberapa produk (contoh: Rp 5.999.000 untuk iPad 10th Gen).
* **Strategi Promosi:**
    * *Urgensi & Kelangkaan:* Menampilkan label "Hot Item" untuk menciptakan FOMO (*Fear of Missing Out*).
    * *Bundling Strategy (Rencana):* Menawarkan potongan harga jika membeli iPhone beserta AirPods secara bersamaan.
    * *Kemudahan Pembayaran:* Menyediakan metode pembayaran fleksibel (QRIS, e-Wallet, Bank Transfer).

### 7. Proses Checkout & Simulasi Payment Gateway
Platform ini dirancang dengan alur transaksi digital yang sangat mulus (Frictionless Checkout):
1. **Cart Management:** Menggunakan *Local Storage API* agar data keranjang tidak hilang meskipun pengguna menutup browser.
2. **User Authentication:** Formulir pop-up untuk mengumpulkan data penting (Nama, WhatsApp, Alamat Pengiriman) sebelum transaksi, memastikan validitas pembeli.
3. **Simulasi Payment Gateway (Midtrans/Xendit Concept):**
    * Pengguna diberikan pilihan pembayaran instan: **QRIS Standar Dinamis**, **Transfer SeaBank Corporate**, atau **DANA Enterprise**.
    * Setelah metode dipilih, sistem secara otomatis menerbitkan **Faktur/Invoice Digital** yang menampilkan Nomor Invoice acak (INV-XXXXXX), rincian pesanan, total tagihan, dan instruksi pembayaran spesifik (termasuk memunculkan Barcode QRIS *dummy*).

### 8. Rencana SEO, Keamanan, dan Pemeliharaan
* **Search Engine Optimization (SEO):**
    * Penggunaan *Semantic HTML* (Tag `<header>`, `<main>`, `<article>`, `<section>`).
    * Optimasi struktur *Heading* (H1, H2, H3) dan penempatan *alt text* pada gambar agar mudah dirayapi Google bot.
* **Sistem Keamanan:**
    * Sanitasi *input* form pendaftaran berbasis *Front-End JavaScript* (Atribut `required`) untuk mencegah pengiriman data kosong.
    * *(Tahap Produksi)*: Kewajiban menggunakan protokol HTTPS/SSL untuk mengenkripsi transmisi data pelanggan dan *Payment Gateway*.
* **Pemeliharaan (Maintenance):**
    * *Katalog Dinamis:* Update produk secara berkala mengikuti *Apple Event* tahunan.
    * *Audit UI/UX:* Pengecekan responsivitas desain pada berbagai ukuran layar (*Mobile, Tablet, Desktop*).

### 9. Rencana Penggunaan Data Analytics untuk Keputusan
Untuk memaksimalkan konversi, BITZZ PHONE akan mengimplementasikan alat analisis data (seperti Google Analytics / Meta Pixel) guna melacak metrik berikut:
* **User Engagement:** Menganalisis *Click-Through Rate* (CTR) pada *banner* hero dan fitur filter kategori.
* **Search Queries:** Melacak kata kunci apa yang paling sering diketik pelanggan pada *Live Search* bar, guna menyiapkan stok produk yang sesuai.
* **Conversion & Drop-off:** Memantau *Cart Abandonment Rate* (Tingkat pembatalan di keranjang) untuk mengevaluasi apakah proses pendaftaran (Autentikasi) terlalu rumit bagi pengguna.
* **Sales Analytics:** Menentukan *Top-Selling Products* berdasarkan data historis di sistem keranjang, yang akan menjadi panduan untuk strategi pemasaran bulan berikutnya.

---

## 💻 BAGIAN 2: SOURCE CODE (HTML & JAVASCRIPT)

Berikut adalah lampiran kode dari sistem website yang mendasari jalannya fitur-fitur di atas.

### 1. File: `index.html`
```html
<!-- HTML Source Code Missing -->
```

### 2. File: `js/script.js`
```javascript
// JS Source Code Missing
```
