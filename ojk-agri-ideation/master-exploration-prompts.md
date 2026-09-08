# 🎯 Master Exploration Prompts untuk Teman di OJK

Prompt di bawah ini dirancang khusus untuk dimasukkan ke **Google Gemini / Claude / ChatGPT** guna membedah, mematangkan ide, dan menyusun materi kompetisi bagi rekan Anda yang bekerja di OJK.

---

## 📌 PROMPT UTAMA: Mega-Ideation & Brainstorming Co-Pilot

> **Cara Penggunaan:**  
> Salin (*copy*) teks di dalam kotak kode di bawah ini, lalu tempel (*paste*) ke Gemini/ChatGPT sebagai prompt pembuka.

```markdown
Bertindaklah sebagai Senior SupTech Strategist & Penasihat Dewan Komisioner OJK bidang Pengawasan Inovasi Teknologi Sektor Keuangan (ITSK). 

Saya sedang mempersiapkan proposal ide untuk kompetisi inovasi pengawasan internal OJK. Fokus ide saya adalah: "Mengatasi Titik Buta Pengawasan Fintech Lending Sektor Pertanian (Agri-P2P) dengan Mengintegrasikan Multi-Agent AI dan Teknologi Pendeteksi Iklim (Remote Sensing Satelit)".

Latar Belakang Masalah Riil:
1. Kegagalan Pengawasan: Baru-baru ini OJK mencabut izin TaniFund (Mei 2024), dan platform lain seperti iGrow serta Crowde menghadapi krisis gagal bayar massal dan gugatan para lender. OJK dinilai publik dan media (seperti ulasan Kontan) lambat dan gagal mengawasi sektor ini.
2. Kelemahan Pola Pikir Saat Ini: Pengawas OJK saat ini hanya berfokus pada penelaahan laporan keuangan tingkat kesehatan PT Penyelenggara (ekuitas minimum Rp 12,5 miliar, rasio kecukupan modal, audit triwulanan). Padahal ini bersifat post-mortem. Di atas kertas fintech terlihat sehat, tapi underlying pinjaman ratusan miliar di sawah sudah musnah karena gagal panen atau proyek fiktif.
3. Manipulasi TKB90/TWP90: TKB dilaporkan sendiri oleh platform dan sering dimanipulasi dengan skema evergreening (pinjaman baru untuk menutupi pinjaman lama yang macet) agar terlihat tetap >95%.
4. Volatilitas Pertanian: Pertanian sangat rentan terhadap anomali iklim (El Niño/La Niña), risiko offtaker (pembeli hasil panen ingkar janji), dan tenor pinjaman bertenor tunggal (bullet payment) yang membuat risiko terkonsentrasi di hari panen.

Bantulah saya mengeksplorasi ide ini secara mendalam dengan menyusun:
1. Executive Pitch & The Winning Hook: Judul inisiatif yang memikat juri (rekomendasikan nama yang berwibawa di lingkungan OJK), satu paragraf problem statement yang menggugah, dan nilai tambah bagi OJK.
2. Problem Framing: Mengapa OJK harus bergeser dari "Audit Administratif Laporan Keuangan" ke "Pengawasan Aset Riil Berbasis Ground-Truth (Synthetic SupTech)"?
3. Mengapa AGENTIC AI (Bukan Machine Learning Biasa): Berikan 3 argumen pembeda yang telak untuk menjawab juri jika mereka bertanya "Kenapa tidak pakai model klasifikasi default XGBoost atau dashboard biasa?".
4. Rekomendasi 4 Agen Spesifik: Rancang 4 autonomous agent yang saling berkolaborasi (Agen Satelit/Iklim, Agen Rantai Pasok/Offtaker, Agen Forensik Aliran Dana TKB, dan Agen Tindakan Regulasi OJK).
5. Output Konkret: Bagaimana sistem ini menghasilkan "Forward-Looking TKB90 (FL-TKB)" dan draf surat pembinaan/sanksi otomatis sesuai POJK 40/2024?
```

---

## 🛰️ PROMPT 2: Eksplorasi Khusus Teknologi Satelit & Deteksi Iklim

```markdown
Bertindaklah sebagai Remote Sensing Data Scientist dan Pakar Asuransi Pertanian Berbasis Indeks Cuaca.

Bantu saya merancang layer teknologi deteksi iklim dan verifikasi lahan untuk ide pengawasan fintech pertanian OJK:

1. Sumber Data Satelit Terbuka & Biaya:
   - Data satelit publik apa saja yang bisa digunakan secara gratis tanpa membebani anggaran OJK (misal: Copernicus Sentinel-2 MSI, Sentinel-1 SAR, data presipitasi CHIRPS, dan API BMKG)?
   - Berapa frekuensi pembaruan citra (revisit time) dan resolusi spasialnya untuk memantau lahan pertanian Indonesia?

2. Deteksi Otonom oleh AI Agent:
   - Bagaimana cara AI Agent memverifikasi "Kebun Fiktif / Ghost Farm" menggunakan indeks vegetasi (NDVI) pada koordinat poligon lahan pinjaman yang didaftarkan fintech?
   - Bagaimana AI Agent mendeteksi anomali stres kekeringan (Drought Stress via NDWI/soil moisture) atau genangan banjir secara real-time di tengah masa tanam?

3. Early Warning ke TKB90:
   - Buat skema logika bagaimana anomali cuaca di suatu klaster pertanian (misal: 20 hari berturut-turut tanpa hujan di Subang) secara otomatis menurunkan skor proyeksi TKB90 60 hari sebelum petani jatuh tempo, sehingga OJK bisa memerintahkan penambahan cadangan risiko lebih awal.
```

---

## 📈 PROMPT 3: Eksplorasi Forensik Manipulasi TKB90 & Regulasi POJK

```markdown
Bertindaklah sebagai Auditor Forensik Keuangan OJK yang menguasai POJK No. 10/POJK.05/2022 dan POJK No. 40 Tahun 2024 tentang Layanan Pendanaan Bersama Berbasis Teknologi Informasi (LPBBTI).

Tolong bantu saya membedah masalah TKB90 / TWP90 pada fintech pertanian:

1. Bongkar 3 modus manipulasi TKB90 yang sering dilakukan platform fintech bermasalah untuk mengelabui pengawas OJK:
   - Skema Evergreening (gali lubang tutup lubang menggunakan peminjam fiktif/lender baru).
   - Skema restrukturisasi terselubung tanpa transparansi ke lender.
   - Penyalahgunaan dana cadangan (reserve fund) internal.

2. Solusi Agentic AI:
   - Bagaimana Autonomous Forensic Agent OJK dapat memindai aliran transaksi di Fintech Data Center (FDC) dan rekening penampungan (escrow) untuk mendeteksi transaksi melingkar (circular transactions) secara otomatis?
   - Rancang formula "Forward-Looking Synthetic TKB90" yang menggabungkan: status pertumbuhan tanaman riil, solvabilitas offtaker, dan integritas aliran kas.
```

---

## ⚖️ PROMPT 4: Simulasi Ujian Juri (Devil's Advocate & Q&A Defense)

```markdown
Bertindaklah sebagai Ketua Dewan Juri Kompetisi Inovasi OJK yang paling kritis, konservatif, dan menguji setiap celah kelemahan peserta.

Saya baru saja mempresentasikan ide: "Project SATRIA-Agri: Pengawasan Fintech Lending Pertanian Berbasis Multi-Agent AI dan Citra Satelit Iklim".

Tugas Anda:
1. Ajukan 4 pertanyaan sanggahan paling mematikan dan menjebak terkait:
   - Kewenangan Hukum OJK: Apakah OJK berhak memantau lahan sawah dan transaksi offtaker fintech swasta?
   - Kondisi Petani Lapangan: Bagaimana mungkin sistem ini jalan jika petani di desa tidak punya smartphone dan sinyal internet lemah?
   - Akurasi Citra Satelit: Indonesia beriklim tropis dengan tutupan awan tinggi, bagaimana jika citra satelit tertutup awan mendung tebal?
   - Prioritas OJK: Portofolio fintech pertanian sangat kecil dibanding pinjol konsumtif/multiguna, kenapa OJK harus membuang sumber daya untuk ini?

2. Setelah itu, lepaskan peran juri dan bertindaklah sebagai Mentor Juara 1 saya. Berikan formulasi JAWABAN TELAK (Winning Counter-Arguments) yang elegan, tak terbantahkan, dan berlandaskan regulasi untuk masing-masing pertanyaan di atas.
```

---

## 📊 PROMPT 5: Pembuatan Struktur Slide Pitch Deck (Format 7 Slide)

```markdown
Bantu saya menyusun kerangka slide presentasi (Pitch Deck) kompetisi inovasi OJK dengan tema: "Pengawasan Fintech Pertanian Berbasis Agentic AI & Climate Intelligence".

Batasan: Maksimal 7 slide, waktu presentasi 5 menit di hadapan pejabat eselon OJK.

Untuk setiap slide, berikan:
1. Headline Slide yang kuat dan *punchy*.
2. Visual Concept (diagram apa yang harus digambar, screenshot satelit seperti apa yang harus ditampilkan).
3. Poin Kunci (Key Talking Points) dalam 3-4 butir kalimat ringkas.
4. Call to Action / Penutup yang meyakinkan juri untuk memilih ide ini sebagai proyek percontohan (Regulatory Sandbox) OJK.
```
