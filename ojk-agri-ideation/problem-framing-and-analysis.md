# 🌾 Analisis Industri & Problem Framing: Pengawasan Fintech Pertanian OJK Berbasis Agentic AI

Kajian ini disusun sebagai fondasi strategis bagi rekan Anda di OJK dalam memilih sudut pandang (*problem framing*), memahami realitas industri *agri-fintech*, dan menyusun ide kompetisi berbasis **Agentic AI** (bukan sekadar machine learning tradisional).

---

## 1. Peta Masalah Industri: Mengapa Sektor Pertanian Begitu Volatil?

Fintech P2P lending di sektor pertanian (seperti **TaniFund**, **iGrow**, dan **Crowde**) menghadapi krisis gagal bayar massal, berujung pada pencabutan izin usaha TaniFund oleh OJK (Mei 2024) dan gugatan hukum para *lender* kepada iGrow.

### A. Anatomi Risiko Unik Sektor Pertanian (The Tri-Fold Volatility)
1. **Risiko Biologis & Iklim (Exogenous Shocks):**
   * Pertanian terikat erat pada anomali cuaca (El Niño kekeringan ekstrem, La Niña banjir, atau ledakan hama wereng/ulat grayak).
   * Pinjaman budidaya pertanian umumnya bertenor 3–6 bulan dengan sistem pembayaran pokok dan imbal hasil di akhir periode panen (*bullet payment/yarnen*). Jika gagal panen terjadi, *cashflow* petani langsung **nol**.
2. **Risiko Rantai Pasok & Pembeli Siaga (Offtaker Risk):**
   * Panen berhasil bukan jaminan pinjaman kembali. Jika harga komoditas anjlok di pasar lokal atau *offtaker* ingkar janji menampung hasil panen, petani terpaksa menjual rugi dan gagal melunasi pinjaman.
3. **Asimetri Informasi & Proyek Fiktif (Moral Hazard):**
   * Banyak pinjaman yang disalurkan bukan kepada petani langsung di sawah, melainkan kepada perantara, kelompok tani fiktif, atau pihak terafiliasi yang kemudian mengalihkan dana ke proyek lain (*misappropriation of funds*).

### B. Studi Kasus: Mengapa Amartha Berhasil, Sementara TaniFund/iGrow Kolaps?
* **Amartha:**
  * **Model Pembiayaan:** Menggunakan sistem *tanggung renteng* (*group lending*) yang fokus pada perempuan pengusaha mikro pedesaan.
  * **Diversifikasi:** Portofolio pembiayaan tersebar ke berbagai usaha mikro harian (warung klontong, pengrajin, pedagang pasar) sehingga tidak bergantung 100% pada satu kali masa panen.
  * **Field Presence:** Memiliki puluhan ribu *field officers* (*Business Partner Specialist*) yang setiap minggu hadir fisik di desa memantau angsuran mingguan.
* **TaniFund / iGrow:**
  * Fokus pada pembiayaan proyek budidaya pertanian murni skala menengah/kelompok.
  * Pembayaran bergantung penuh pada hasil panen (*single-point of failure*).
  * Verifikasi lapangan minim, mengandalkan foto atau laporan berkala dari mitra yang rentan dimanipulasi.

---

## 2. Mengapa Pengawasan OJK Saat Ini Dinilai Gagal? (The Supervisory Blind Spot)

Kritik tajam dari media dan publik (sebagaimana disorot *Kontan*) bertumpu pada **keterbatasan pola pikir pengawasan konvensional**:

```
                       POLA PIKIR PENGAWASAN SAAT INI
┌─────────────────────────────────────────────────────────────────────────────┐
│  Fokus: Laporan Keuangan Tingkat Kesehatan PT Penyelenggara                 │
│  - Memeriksa ekuitas minimum (Rp 12,5 Miliar sesuai POJK 40/2024)           │
│  - Memeriksa rasio modal, neraca, dan kepatuhan administratif kuartalan     │
│  - Mengandalkan TKB90/TWP90 yang dilaporkan sendiri oleh platform           │
└──────────────────────────────────────┬──────────────────────────────────────┘
                                       │
                                       ▼ MASALAH FATAL
┌─────────────────────────────────────────────────────────────────────────────┐
│  1. Post-Mortem: Audit kuartalan terlambat 3-5 bulan dari kejadian lapangan. │
│  2. Evergreening: Platform mencairkan pinjaman baru untuk membayar pinjaman │
│     lama agar TKB90 tetap terlihat >95%.                                    │
│  3. Blind on Assets: OJK tidak tahu apakah sawah yang dibiayai benar-benar  │
│     ada atau sedang terendam banjir El Niño.                                │
└─────────────────────────────────────────────────────────────────────────────┘
```

### Bagaimana TKB90/TWP90 Bisa Dikontrol Secara Obyektif?
OJK tidak bisa mengontrol TKB hanya dengan meminta platform "menjaga TKB di atas 95%". Yang dibutuhkan OJK adalah **Synthetic Ground-Truth Surveillance**:
* Menggeser indikator dari **Reported-TKB90** (yang dilaporkan platform) ke **Forward-Looking Synthetic TKB (FL-TKB)** yang dihitung secara independen oleh sistem OJK dengan menggabungkan: status vegetasi tanaman via satelit, cuaca BMKG, dan data e-faktur *offtaker*.

---

## 3. Pilihan Problem Framing untuk Kompetisi OJK

Rekan Anda dapat memilih 1 dari 3 opsi pembingkaian (*framing*) masalah berikut:

### 🏆 Opsi 1 (Sangat Direkomendasikan): "Synthetic SupTech — Menutup Titik Buta Pengawasan Aset Riil"
* **Judul Ide:** *Project SATRIA-Agri (Surveillance & Automated TKB Resilience Intelligence Agents)*
* **Pernyataan Masalah:** "OJK selama ini mengawasi *entitas hukum* (PT Penyelenggara) secara administratif, namun buta terhadap *risiko aset riil* di lapangan. Akibatnya, krisis gagal bayar fintech pertanian selalu terlambat dideteksi hingga izin usaha terpaksa dicabut dan dana masyarakat lenyap."
* **Solusi:** Sistem pengawasan otonom berbasis *Multi-Agent AI* yang memantau kesehatan tanaman dari luar angkasa (satelit), memvalidasi rantai pasok offtaker, dan mendeteksi manipulasi TKB90 secara harian.
* **Kelebihan di Hadapan Juri:** Menjawab langsung isu aktual pencabutan izin TaniFund/iGrow dan menawarkan terobosan teknologi yang belum pernah ada di OJK.

### Opsi 2: "Climate-Resilient SupTech — Early Warning Ketahanan Pangan Nasional"
* **Judul Ide:** *Agri-Shield: Climate-Integrated Prudential Framework for Agricultural P2P Lending*
* **Pernyataan Masalah:** "Perubahan iklim global (El Niño/La Niña) menciptakan syok sistemik pada portofolio pinjaman pertanian. OJK tidak memiliki instrumen *prudential stress-test* berbasis data iklim, sehingga fintech yang menyalurkan modal ke petani rentan bangkrut mendadak."
* **Solusi:** Mengintegrasikan indeks anomali iklim BMKG dan satelit ke dalam perhitungan modal kerja dan batas maksimum penyaluran dana (*exposure limits*) secara otomatis.
* **Kelebihan di Hadapan Juri:** Relevan dengan agenda prioritas nasional (Ketahanan Pangan) dan Taksonomi Hijau OJK (*Indonesia Green Taxonomy*).

### Opsi 3: "Forensik TKB & Anti-Evergreening Engine"
* **Judul Ide:** *Truth-TKB: Graph-Based Autonomous Forensic Engine for P2P Lending*
* **Pernyataan Masalah:** "Metrik TKB90 saat ini adalah ilusi yang mudah dimanipulasi melalui skema ponzi internal / evergreening antar-kelompok pinjaman."
* **Solusi:** Multi-agent yang membedah aliran dana *Fintech Data Center (FDC)* dan rekening escrow untuk mendeteksi restrukturisasi semu dan merevisi skor TKB secara otomatis.
* **Kelebihan di Hadapan Juri:** Sangat kuat dari sisi regulasi perlindungan konsumen dan penegakan hukum POJK 40/2024.

---

## 4. Mengapa Harus AGENTIC AI, Bukan Sekadar Traditional ML?

Jika peserta lain membawa ide *"Machine Learning untuk prediksi kredit macet"*, itu adalah solusi usang yang mudah dibantah oleh juri. Berikut argumen kuat mengapa harus **Agentic AI**:

| Parameter | Traditional Machine Learning (XGBoost / Random Forest) | Agentic AI (Multi-Agent System) |
| :--- | :--- | :--- |
| **Karakter Data** | Bergantung pada data tabular historis (SLIK, slip gaji). **Petani gurem tidak punya riwayat perbankan.** | Mampu mengolah data **multi-modal & non-invasif** (citra satelit, API cuaca, nota timbang panen). |
| **Sifat Evaluasi** | **Statis (Single-Shot):** Memprediksi probabilitas gagal bayar di hari pertama pinjaman diajukan. | **Dinamis & Berkelanjutan:** Memantau tanaman setiap 5 hari (sesuai lintasan satelit) sepanjang tenor 90-120 hari. |
| **Agency & Inisiatif** | Pasif. Hanya menerima input data dan mengeluarkan satu angka probabilitas. | **Otonom & Tool-Using:** Bisa berinisiatif memanggil API luar, mendeteksi anomali, melakukan konfirmasi silang, dan merumuskan draf surat peringatan. |
| **Penyelesaian Masalah** | Model tunggal (*black-box*) yang tidak transparan bagi pengawas. | **Spesialisasi Kolaboratif:** Agen Satelit fokus pada lahan, Agen Offtaker fokus pada pembeli, Agen Forensik fokus pada dana, dan Agen Regulasi mengambil keputusan. |
