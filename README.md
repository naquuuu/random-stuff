# 🚀 Random Stuff Workspace (`naquuuu/random-stuff`)

Workspace mandiri untuk eksplorasi bebas, eksperimen acak, drafting ide kompetisi, dan pengujian prototipe di luar pekerjaan MAPCLUB.

---

## 🌐 Live Prototype Demo & Repository
* **Live Interactive Web Demo:** [temporary-flying-teal-nswc3ny.vercel.app](https://temporary-flying-teal-nswc3ny.vercel.app)
* **Live Visual One-Pager / Slide Deck:** [temporary-flying-teal-nswc3ny.vercel.app/onepager.html](https://temporary-flying-teal-nswc3ny.vercel.app/onepager.html)
* **GitHub Repository:** [github.com/naquuuu/random-stuff](https://github.com/naquuuu/random-stuff)

---

## 📂 Panduan Membaca Materi Kompetisi OJK

Folder `ojk-agri-ideation/` dan root repositori memuat seluruh materi kompetisi yang bebas dari jargon kosong (*no AI slop*):

| Dokumen | Deskripsi Utama |
| :--- | :--- |
| **[`onepager.html`](file:///C:/work/random-stuff/onepager.html)** | **ONE-PAGER VISUAL PUBLIK (BISA DICETAK/PDF):** Infografis visual bergaya slide dengan analogi mobil rusak, 4 angka kunci (*Key Figures*), alur flowchart 4 langkah, dan penjelasan 4 agen dalam bahasa awam. |
| **[`onepager.md`](file:///C:/work/random-stuff/onepager.md)** | **VERSI SLIDE DECK & MERMAID FLOWCHART:** Naskah presentasi 5 menit untuk dewan juri dengan diagram alir perbandingan sistem lama vs sistem baru. |
| **[`deep-dive-conceptual-framework.md`](file:///C:/work/random-stuff/ojk-agri-ideation/deep-dive-conceptual-framework.md)** | **BACA INI DULU:** Bedah komprehensif akar masalah regulasi, jeda waktu 135 hari kematian pinjaman (*latency*), alur kerja multi-agent yang realistis, **5 titik kegagalan nyata di lapangan (*Failure Modes*)**, dan uji kelayakan (*feasibility check*). |
| **[`problem-framing-and-analysis.md`](file:///C:/work/random-stuff/ojk-agri-ideation/problem-framing-and-analysis.md)** | Kajian industri: Studi kasus mengapa **Amartha** bertahan vs mengapa **TaniFund / iGrow** kolaps, serta 3 opsi pembingkaian masalah (*problem framing*) untuk dewan juri. |
| **[`master-exploration-prompts.md`](file:///C:/work/random-stuff/ojk-agri-ideation/master-exploration-prompts.md)** | 5 Master Prompts siap pakai untuk di-*copy-paste* ke Gemini / ChatGPT untuk menyusun pitch deck, draf regulasi POJK 40/2024, dan simulasi tanya-jawab juri. |
| **[`index.html`](file:///C:/work/random-stuff/index.html)** | Source code prototipe interaktif *Project SATRIA-Agri* (Alur 3 langkah terpandu, perbandingan Titik Buta, Papan Bukti Satelit/Offtaker/FDC, dan generator surat resmi OJK). |

---

## 🧠 Intisari Konseptual: Mengapa Ide Ini Masuk Akal?

1. **Akar Masalah Nyata:**  
   Di P2P lending, risiko gagal panen 100% ditanggung masyarakat (*lender*), bukan kas PT Penyelenggara. Pengawas OJK selama ini hanya memeriksa laporan keuangan PT Penyelenggara (ekuitas Rp 12,5 Miliar), padahal Rp 300 Miliar dana masyarakat di sawah sudah lenyap 3-4 bulan sebelumnya.
2. **Arsitektur Multi-Agent (Bukan ML Klasifikasi Biasa):**  
   Petani gurem tidak memiliki riwayat SLIK/bank. Sistem ini tidak memakai ML statis, melainkan **4 Agen Otonom Kolaboratif**:
   * **Agent A (Geospatial):** Menghitung indeks vegetasi (NDVI) satelit Sentinel-2 pada koordinat poligon lahan untuk membongkar kebun fiktif (*ghost farm*) dan kekeringan.
   * **Agent B (Value-Chain):** Memverifikasi harga komoditas pangan Bapanas dan solvabilitas pembeli (*offtaker*).
   * **Agent C (FDC Forensics):** Memindai transaksi melingkar (*evergreening/ponzi*) di mana dana lender baru dicairkan untuk menutupi pinjaman lama yang macet.
   * **Agent D (Supervisory Copilot):** Mengagregasi bukti biofisik dan transaksi menjadi rekomendasi tindakan pengawasan berstandar POJK 40/2024.
3. **Titik Lemah Nyata (*Failure Modes*) yang Wajib Diantisipasi:**  
   * *Tutupan Awan Tropis:* Diatasi dengan beralih ke radar Sentinel-1 SAR.
   * *Petak Lahan Sempit & Tumpang Sari:* Dibatasi hanya untuk pembiayaan klaster >5-10 Hektar.
   * *Pemalsuan Titik GPS:* Kroscek dengan peta kadastral ATR/BPN.
   * *Legalitas:* Wajib *Human-in-the-Loop* (AI bertindak sebagai Copilot pemberi rekomendasi, bukan eksekutor sanksi hukum otonom).
