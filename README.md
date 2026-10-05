# Media Pembelajaran Kimia Interaktif: Bentuk Molekul & Hibridisasi sp³d (Senyawa PCl₅)

Media pembelajaran berbasis web (*single-file interactive web app*) yang dirancang untuk memfasilitasi pemahaman peserta didik mengenai konsep bentuk molekul, teori hibridisasi orbital, konfigurasi elektron subkulit (Aufbau), hingga visualisasi geometri molekul 3D trigonal bipiramida pada senyawa fosfor pentaklorida ($\text{PCl}_5$).

---

## 👩‍🔬 Profil Pengembang
- **Nama Penyusun:** Raudhatul Jannah
- **NIM:** 06101182530001
- **Program Studi / Institusi:** Pendidikan Kimia, Universitas Sriwijaya

---

## 🎯 Capaian & Tujuan Pembelajaran
1. **Capaian Pembelajaran (CP):**
   - Peserta didik mampu menentukan bentuk molekul yang memiliki hibridisasi $\text{sp}^3\text{d}$ berdasarkan persebaran elektron pada subkulit atom pusat.
2. **Tujuan Pembelajaran (TP):**
   - Peserta didik mampu memahami konsep dasar pembentukan 5 orbital hibrida $\text{sp}^3\text{d}$ yang setara energinya.
   - Peserta didik mampu mengidentifikasi dan memvisualisasikan geometri molekul nyata ($\text{PCl}_5$) secara interaktif tiga dimensi.

---

## ✨ Fitur Unggulan Media
1. **Alur Belajar Terstruktur (Slide Deck Terpadu):**
   - Navigasi slide yang ramah pengguna dengan indikator posisi (*dots indicator*) dan tombol kontrol yang intuitif.
2. **Visualisasi Aturan Aufbau Interaktif:**
   - Diagram alur pengisian elektron diagonal dari subkulit $1s$ hingga $8s$ berbasis SVG dinamis dengan penekanan visual khusus pada subkulit aktif $3s$, $3p$, dan $3d$.
3. **Diagram Kotak Orbital & Eksitasi Elektron:**
   - Ilustrasi transisi elektron dari keadaan dasar (*ground state*) menuju keadaan tereksitasi (*excited state*) dengan simbol spin elektron presisi ($\uparrow$ dan $\downharpoonleft\upharpoonright$).
4. **Manipulator Geometri Molekul 3D Real-Time:**
   - Model 3D $\text{PCl}_5$ (trigonal bipiramida) berbasis proyeksi vektor matematika SVG murni (tanpa beban pustaka eksternal).
   - Fitur *auto-rotation* yang halus serta kontrol sentuh/kursor (*drag & rotate*) bebas 360 derajat.
5. **Kuis Evaluasi Formatif Interaktif:**
   - Latihan soal pilihan ganda dengan validasi jawaban otomatis dan perhitungan skor langsung di akhir sesi.
6. **Desain Modern & Responsif:**
   - Mengusung estetika *modern pastel glassmorphism*, tipografi elegan (*Fraunces* & *Inter*), serta dukungan *Dark Mode* otomatis.

---

## 🛠️ Arsitektur Teknologi
- **Bahasa:** HTML5, CSS3 murni, Vanilla JavaScript (ES6+).
- **Grafis & Interaksi 3D:** Proyeksi trigonometri 3D ke 2D menggunakan SVG dinamis.
- **Portabilitas:** *Self-contained* / mandiri (aset logo terenkapsulasi langsung sebagai base64, siap dijalankan langsung di peramban tanpa instalasi atau koneksi internet).

---

## 🚀 Panduan Menjalankan Media
1. **Secara Lokal (Offline):**
   - Unduh atau kloning repositori ini.
   - Buka file `index.html` menggunakan peramban web modern apa pun (Google Chrome, Edge, Firefox, Safari).
2. **Secara Daring (GitHub Pages):**
   - Repositori ini telah dikonfigurasi dengan file `index.html` pada cabang utama (`main`), sehingga dapat diakses langsung oleh siswa melalui tautan GitHub Pages:
     ```
     https://<username-github>.github.io/<nama-repo>/
     ```
