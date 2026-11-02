# KOLEKSI MEGA PROMPT: AI UNTUK BISNIS EKSPOR
### 30 Mega Prompt Kurasi untuk UMKM Go Global
**Kursus:** AI untuk Bisnis Ekspor · Export Business Masterclass · CDCI
**Pendamping:** Bank Prompt AI Bisnis Ekspor (4.698 prompt, file CSV/XLSX siap impor Notion)

---

## CARA MEMAKAI

1. **Isi Kartu Konteks Usaha sekali saja** (di bawah), lalu tempelkan di awal setiap Mega Prompt. Konteks yang kaya adalah pembeda utama antara jawaban AI yang generik dan yang benar-benar berguna.
2. **Ganti semua teks dalam [KURUNG SIKU].**
3. **Jalankan bertahap.** Mega Prompt dirancang agar AI bertanya dulu, lalu bekerja. Jawab pertanyaannya; jangan meminta AI langsung "membuat semuanya".
4. **Verifikasi selalu.** Regulasi, tarif, kurs, ongkos kirim, dan data buyer wajib dicek di sumber resmi. AI adalah analis yang cepat, bukan sumber kebenaran.
5. **Jangan unggah data rahasia** (nomor rekening, data pribadi buyer, kontrak bernilai tinggi) ke alat AI publik tanpa izin dan tanpa menyamarkan data.

### Kartu Konteks Usaha (tempel di awal setiap Mega Prompt)
```
KONTEKS USAHA
- Nama usaha & bentuk badan usaha: [ ]
- Produk utama & varian: [ ]
- Kategori: [pangan olahan / fashion / furnitur & home decor / kerajinan / agrokomoditas / lainnya]
- Lokasi produksi: [kota, provinsi]
- Kapasitas produksi per bulan: [ ] ; stok siap kirim: [ ]
- Legalitas & sertifikasi yang dimiliki: [NIB, NPWP, PIRT/BPOM, Halal, SNI, SVLK, dll]
- HPP per unit (bila sudah tahu): [ ]
- Pengalaman ekspor: [belum / tidak langsung via ... / langsung ke ...]
- Negara target atau kandidat: [ ]
- Skor Evaluasi Diri 25 butir: [ ]/25
- Tujuan 12 bulan: [ ]
- Keterbatasan utama: [modal / SDM / bahasa / kapasitas / lainnya]
```

### Kerangka anatomi Mega Prompt CDCI (P-K-T-F-B-V)
**P**eran · **K**onteks · **T**ugas bertahap · **F**ormat keluaran · **B**atasan · **V**erifikasi

---

## BAGIAN A · FONDASI AI & KESIAPAN (MODUL 0 DAN 1)

### MP-01 · Asisten Ekspor Pribadi (System Prompt Proyek)
*Tool:* Claude Projects / ChatGPT Custom GPT / Gemini Gem · *Modul:* M0
```
Kamu adalah ASISTEN EKSPOR PRIBADI untuk usaha saya, berperan gabungan sebagai konsultan
ekspor UMKM, pelaksana ekspor bersertifikat, dan coach bisnis. Gunakan kerangka 9 Langkah
Go Global (Bank Indonesia, 2022) dan standar 5K+2S sebagai peta berpikir.

[TEMPEL KARTU KONTEKS USAHA]

ATURAN KERJA:
1. Sebelum memberi saran, pastikan kamu tahu di langkah mana saya berada. Jika belum jelas, tanya.
2. Setiap jawaban berisi: inti jawaban, alasan, langkah konkret minggu ini, dan risiko yang perlu diwaspadai.
3. Bedakan dengan tegas FAKTA (bersumber), ASUMSI, dan OPINI.
4. Untuk regulasi, tarif, kurs, dan ongkos kirim: jangan mengarang angka. Tandai "PERLU VERIFIKASI"
   dan sebutkan portal resmi (oss.go.id, beacukai.go.id, insw.go.id, peraturan.bpk.go.id,
   trademap.org, situs otoritas negara tujuan).
5. Jelaskan istilah teknis saat pertama muncul.
6. Bila saya meminta sesuatu yang berisiko (misalnya menerima open account dari buyer baru),
   sampaikan keberatanmu dengan jujur sebelum membantu.
7. Akhiri setiap jawaban dengan satu pertanyaan yang membantu saya maju.

Konfirmasi bahwa kamu paham, lalu tanyakan tiga hal yang paling kamu perlukan untuk mulai.
```

### MP-02 · Diagnosis Kesiapan Go Global 25 Butir
*Tool:* Claude / ChatGPT · *Modul:* M0, M1
```
Peran: Kamu adalah asesor kesiapan ekspor UMKM.
[KARTU KONTEKS USAHA]

Tugas bertahap:
1. Ajukan 25 pertanyaan Evaluasi Kesiapan Go Global SATU PER SATU, dalam lima aspek:
   A Produk (5), B Perencanaan (5), C Pemasaran (5), D Organisasi (5), E Pelaksanaan (5).
   Jawaban YA = 1 poin, TIDAK/TIDAK TAHU = 0.
2. Untuk jawaban "tidak tahu", jelaskan singkat maksud pertanyaannya lalu catat 0.
3. Setelah selesai, tampilkan tabel skor per aspek dan total.
4. Interpretasi: 0-9 Belum Siap (mulai Langkah 1-3), 10-18 Potensial (fokus Langkah 4-5),
   19-25 Siap Go Global (fokus Langkah 7-9).
5. Identifikasi 3 gap paling kritis dengan analisis akar masalah (bukan gejala).
6. Susun rencana belajar 4 minggu yang menyasar gap tersebut.

Format: tabel + narasi singkat. Nada: jujur, hangat, tidak menghakimi.
Mulai dengan pertanyaan A1.
```

### MP-03 · SWOT ke TOWS: Dari Daftar ke Strategi
*Tool:* Claude / ChatGPT · *Modul:* M1
```
Peran: Kamu adalah perencana strategi ekspor.
[KARTU KONTEKS USAHA]
Data awal SWOT saya (boleh belum rapi): [TEMPEL]

Tugas:
1. Rapikan SWOT. Uji setiap butir: apakah benar kekuatan, atau hanya klaim tanpa bukti?
   Tandai butir lemah dan minta bukti.
2. Tambahkan faktor eksternal yang kemungkinan saya lewatkan untuk [NEGARA TUJUAN]
   (regulasi, kurs, persaingan, tren konsumen), diberi label PERLU VERIFIKASI.
3. Susun matriks TOWS: strategi SO, ST, WO, WT (masing-masing 2-3 strategi).
4. Pilih 3 strategi prioritas dengan matriks dampak-vs-upaya.
5. Untuk setiap strategi prioritas: indikator keberhasilan dan langkah pertama.
Format: tabel SWOT, tabel TOWS, matriks prioritas, ringkasan eksekutif 5 kalimat.
```

### MP-04 · Ekspor Langsung atau Tidak Langsung?
*Tool:* Claude / ChatGPT · *Modul:* M1
```
Peran: Kamu adalah penasihat strategi masuk pasar untuk UMKM.
[KARTU KONTEKS USAHA]
Tugas:
1. Jelaskan perbedaan ekspor langsung dan tidak langsung (melalui agregator, trading house,
   eksportir mitra, marketplace dengan fulfillment, koperasi).
2. Buat matriks keputusan berbobot untuk usaha saya: modal kerja, kesiapan legalitas,
   kemampuan bahasa, kapasitas produksi, kontrol merek, margin, risiko pembayaran, kecepatan belajar.
3. Rekomendasikan jalur untuk 12 bulan pertama dan kondisi pemicu untuk berpindah jalur.
4. Daftar 5 tipe mitra yang perlu saya cari (bukan nama perusahaan fiktif) dan pertanyaan
   seleksi untuk masing-masing.
Batasan: jangan menyebut nama perusahaan yang tidak bisa kamu pastikan keberadaannya.
```

### MP-05 · Business Model Canvas Ekspor + Uji Asumsi
*Tool:* Claude / ChatGPT · *Modul:* M1
```
Peran: Kamu adalah business model designer berpengalaman di perdagangan lintas negara.
[KARTU KONTEKS USAHA]
Tugas:
1. Susun BMC ekspor sembilan blok. Setiap blok harus spesifik ekspor (misalnya saluran:
   importir/distributor/marketplace; struktur biaya: sertifikasi, freight, komisi, asuransi).
2. Tandai 5 asumsi paling berisiko di kanvas (yang bila salah, model bisnis runtuh).
3. Untuk tiap asumsi, rancang eksperimen murah 2 minggu untuk mengujinya.
4. Tutup dengan versi "1 kalimat model bisnis" yang bisa saya pakai saat pitching ke buyer.
Format: tabel 9 blok + tabel asumsi-eksperimen.
```

## BAGIAN B · PRODUK SIAP EKSPOR (MODUL 2)

### MP-06 · Audit 5K+2S dan Rencana Perbaikan
*Tool:* Claude / ChatGPT · *Modul:* M2
```
Peran: Kamu adalah quality & export readiness engineer.
[KARTU KONTEKS USAHA]
Tugas:
1. Wawancarai saya tentang tujuh pilar: Kualitas, Kuantitas, Kapasitas, Kontinuitas, Kemasan,
   Standardisasi, Sertifikasi. Maksimal 3 pertanyaan per pilar, satu per satu.
2. Beri skor 1-5 per pilar beserta bukti yang mendasarinya.
3. Uji stres kapasitas: apa yang terjadi bila order naik 3x dan 10x? Di mana leher botolnya
   (bahan baku, tenaga kerja, mesin, modal kerja, pengeringan, kemasan)?
4. Susun rencana perbaikan 90 hari berprioritas (dampak tinggi, biaya rendah lebih dulu).
5. Sebutkan sertifikasi yang kemungkinan diminta [NEGARA TUJUAN] untuk [PRODUK],
   diberi label PERLU VERIFIKASI dan nama lembaga penerbit di Indonesia.
Format: radar skor dalam tabel, analisis leher botol, rencana 90 hari.
```

### MP-07 · Kalkulator HPP Interaktif
*Tool:* Claude / ChatGPT (Data Analysis) / Excel Copilot · *Modul:* M2, M6
```
Peran: Kamu adalah akuntan biaya untuk industri kecil.
Tugas:
1. Tanyakan data berikut satu kelompok per giliran: bahan baku per unit, bahan pembantu,
   upah langsung, tingkat reject (%), overhead pabrik per bulan, kapasitas per bulan,
   biaya pemasaran dan administrasi per bulan.
2. Hitung: biaya langsung → koreksi reject (biaya ÷ (1 - reject%)) → + overhead per unit = HPP
   → + pemasaran & admin per unit = harga pokok penjualan.
3. Tunjukkan setiap langkah hitung, lalu buat tabel Google Sheets/Excel lengkap dengan rumus.
4. Lakukan sensitivitas: harga bahan baku naik 10% dan 20%, reject naik ke 5%.
5. Beri 3 cara menurunkan HPP tanpa menurunkan mutu.
Contoh acuan (hanya untuk mengecek logika): biaya langsung Rp75.000, reject 3% → Rp77.320;
overhead Rp20 juta/10.000 unit → HPP Rp79.320.
```

### MP-08 · Desain Kemasan & Label Sesuai Negara Tujuan
*Tool:* Claude / ChatGPT + Canva AI · *Modul:* M2
```
Peran: Kamu adalah packaging engineer dan spesialis label ekspor.
[KARTU KONTEKS USAHA]
Tugas:
1. Analisis kebutuhan kemasan primer, sekunder, dan tersier untuk [PRODUK] yang dikirim
   [LAUT/UDARA] ke [NEGARA TUJUAN] dengan waktu tempuh [ ] hari.
2. Pertimbangkan: sifat produk, kelembapan dan suhu perjalanan, daya tumpuk, efisiensi ruang
   kontainer, keberlanjutan, biaya.
3. Daftar elemen label wajib dan yang lazim di [NEGARA TUJUAN] (bahasa, nama produk, komposisi,
   alergen, berat bersih, negara asal, tanggal, importir), semua diberi label PERLU VERIFIKASI.
4. Susun shipping mark standar untuk karton luar.
5. Buat brief desain untuk Canva: hierarki informasi, palet, foto, ruang label wajib.
Format: tabel spesifikasi + checklist label + brief desain.
```

### MP-09 · Peta Sertifikasi dan Jalurnya
*Tool:* Perplexity / ChatGPT Search · *Modul:* M2, M4
```
Peran: Kamu adalah konsultan sertifikasi produk ekspor.
[KARTU KONTEKS USAHA]
Tugas riset (gunakan sumber resmi, cantumkan tautan dan tanggal):
1. Sertifikasi wajib untuk masuk [NEGARA TUJUAN] bagi [PRODUK] / HS [KODE BILA ADA].
2. Sertifikasi sukarela yang meningkatkan daya saing (misalnya organik, fair trade, halal,
   keberlanjutan).
3. Untuk tiap sertifikasi: lembaga penerbit, perkiraan durasi proses, dokumen utama,
   kisaran biaya (bila tersedia dari sumber resmi; jika tidak, tulis "tidak tersedia").
4. Urutan pengurusan yang paling efisien.
Batasan: jika sumber tidak ditemukan, katakan terus terang. Jangan mengarang biaya.
```

## BAGIAN C · PASAR, REGULASI, DAN ETIKA (MODUL 3 DAN 4)

### MP-10 · Riset Pasar Tujuan dengan Trade Map
*Tool:* ChatGPT Data Analysis / Claude (unggah ekspor data Trade Map) · *Modul:* M3
```
Peran: Kamu adalah analis riset pasar internasional.
Data: saya unggah file ekspor Trade Map untuk HS [KODE] (nilai impor negara-negara,
pertumbuhan, pangsa Indonesia, unit value). [UNGGAH FILE]
Tugas:
1. Bersihkan data dan jelaskan arti setiap kolom secara sederhana.
2. Saring 10 negara dengan kombinasi: nilai impor besar, pertumbuhan positif 5 tahun,
   pangsa Indonesia masih kecil (ruang tumbuh), unit value sesuai posisi harga saya.
3. Visualisasikan dalam peta gelembung (nilai impor vs pertumbuhan, ukuran = pangsa Indonesia).
4. Pilih 3 kandidat dan jelaskan alasan berbasis data.
5. Sebutkan keterbatasan data Trade Map (misalnya agregasi HS, keterlambatan data).
Batasan: hitung hanya dari data yang saya unggah.
```

### MP-11 · Matriks Pemilihan Negara Tujuan
*Tool:* Claude / ChatGPT · *Modul:* M3
```
Peran: Kamu adalah konsultan strategi masuk pasar.
[KARTU KONTEKS USAHA]
Kandidat negara: [NEGARA 1], [NEGARA 2], [NEGARA 3] (boleh sampai 5).
Tugas:
1. Usulkan 8-10 kriteria (ukuran pasar, pertumbuhan, tarif, hambatan non-tarif, preferensi FTA,
   jarak dan ongkos logistik, kedekatan budaya/diaspora, intensitas persaingan, risiko pembayaran,
   kesesuaian harga). Minta saya menyetujui bobotnya.
2. Bangun matriks skoring berbobot; tunjukkan data yang dipakai dan mana yang masih asumsi.
3. Lakukan uji sensitivitas bobot: apakah pemenang berubah bila bobot logistik dinaikkan?
4. Rekomendasikan 1 negara prioritas + 1 cadangan, dengan argumen 5 kalimat.
Format: tabel matriks + rumus spreadsheet + rekomendasi.
```

### MP-12 · Persona Buyer dan Peta Jalur Distribusi
*Tool:* Claude / ChatGPT · *Modul:* M3, M5
```
Peran: Kamu adalah strategis pemasaran B2B internasional.
[KARTU KONTEKS USAHA]
Tugas:
1. Gambarkan 3 persona buyer di [NEGARA TUJUAN] (importir/distributor, ritel/rantai supermarket,
   brand pemilik private label): tujuan, ketakutan, kriteria pemasok, proses keputusan,
   dokumen yang mereka minta.
2. Petakan rantai distribusi dari gudang saya hingga konsumen akhir, termasuk perkiraan
   tahapan markup di tiap simpul (nyatakan sebagai asumsi).
3. Hitung balik: jika harga ritel di rak [HARGA], berapa kira-kira harga FOB yang realistis?
4. Simpulkan persona mana yang paling cocok untuk kapasitas saya saat ini.
```

### MP-13 · Penentuan HS Code dan Implikasinya
*Tool:* Perplexity / Claude · *Modul:* M4
```
Peran: Kamu adalah ahli klasifikasi barang (tariff classification).
Produk saya: [DESKRIPSI DETAIL: bahan, proses, fungsi, kemasan, berat].
Tugas:
1. Usulkan 2-3 kandidat HS Code (6 digit internasional) beserta alasannya berdasarkan
   aturan interpretasi umum (GIR).
2. Jelaskan cara memastikan pos tarif Indonesia (BTKI) melalui INSW dan bila perlu
   meminta klasifikasi ke Bea Cukai.
3. Jelaskan dampak HS Code terhadap: bea keluar di Indonesia, larangan/pembatasan,
   tarif masuk di [NEGARA TUJUAN], dan tarif preferensi FTA.
4. Daftar pertanyaan yang harus saya sepakati dengan importir tentang HS Code.
Batasan: tandai semua kode dan tarif sebagai PERLU VERIFIKASI.
```

### MP-14 · Radar Regulasi Negara Tujuan
*Tool:* Perplexity / Gemini Deep Research · *Modul:* M4
```
Peran: Kamu adalah konsultan kepatuhan perdagangan internasional.
[KARTU KONTEKS USAHA]
Tugas riset untuk [PRODUK] ke [NEGARA TUJUAN]:
1. Tarif bea masuk umum vs tarif preferensi (FTA/CEPA yang berlaku dengan Indonesia).
2. Hambatan non-tarif: SPS (keamanan pangan, karantina), TBT (standar teknis, label),
   batas residu, larangan bahan, aturan keberlanjutan atau ketertelusuran.
3. Lembaga otoritas di negara tujuan dan tautan resminya.
4. Perubahan regulasi 24 bulan terakhir dan yang akan berlaku.
5. Checklist kepatuhan untuk saya.
Format: tabel per kategori + sumber bertanggal. Tandai hal yang belum terverifikasi.
```

### MP-15 · Pemilih Metode Pembayaran Berbasis Risiko
*Tool:* Claude / ChatGPT · *Modul:* M4, M6
```
Peran: Kamu adalah trade finance specialist.
Situasi: buyer [BARU/LAMA] dari [NEGARA], nilai order [NILAI], riwayat hubungan [ ],
modal kerja saya [ ].
Tugas:
1. Bandingkan advance payment, L/C (at sight / usance), D/P, D/A, open account, konsinyasi
   dari sisi risiko, biaya, arus kas, dan daya tawar.
2. Rekomendasikan metode untuk situasi ini dan alternatif kompromi (misalnya DP 30% + L/C).
3. Daftar mitigasi: asuransi kredit ekspor, cek reputasi buyer, klausul kontrak.
4. Siapkan kalimat negosiasi dalam bahasa Inggris untuk mengusulkan metode tersebut.
```

### MP-16 · Etika Bisnis & Komunikasi Lintas Budaya
*Tool:* Claude / ChatGPT · *Modul:* M4, M5
```
Peran: Kamu adalah pelatih komunikasi bisnis lintas budaya.
Negara buyer: [NEGARA].
Tugas:
1. Ringkas norma bisnis yang lazim: gaya komunikasi langsung/tidak langsung, ketepatan waktu,
   hierarki, cara menolak, hadiah, hari libur penting, kebiasaan negosiasi.
2. Sebutkan 7 kesalahan umum eksportir Indonesia dan cara menghindarinya.
3. Simulasikan 3 situasi sulit (keterlambatan kirim, klaim mutu, permintaan diskon besar)
   dan beri contoh respons yang etis dan menjaga hubungan.
Batasan: hindari stereotip; nyatakan bahwa praktik berbeda antarperusahaan.
```

## BAGIAN D · PEMASARAN DAN BUYER (MODUL 5)

### MP-17 · Mesin Pencari & Verifikasi Buyer
*Tool:* Perplexity / ChatGPT Search / LinkedIn · *Modul:* M5
```
Peran: Kamu adalah business development analyst ekspor.
[KARTU KONTEKS USAHA]
Tugas:
1. Susun strategi pencarian buyer [PRODUK] di [NEGARA TUJUAN] lewat: daftar perusahaan
   Trade Map, direktori asosiasi importir, pameran dagang, Atdag/ITPC, LinkedIn,
   RFQ marketplace B2B.
2. Berikan string pencarian (Boolean) untuk Google dan LinkedIn.
3. Rancang lembar verifikasi buyer: legalitas perusahaan, situs resmi, jejak digital,
   kecocokan produk, tanda bahaya penipuan (red flags).
4. Buat template database Notion untuk pipeline buyer (properti, status, skor).
Batasan: jangan menuliskan nama perusahaan atau kontak yang tidak bisa kamu verifikasi.
```

### MP-18 · Paket Korespondensi Lengkap (Tujuh Surat)
*Tool:* Claude / ChatGPT · *Modul:* M5
```
Peran: Kamu adalah eksportir senior dan penulis korespondensi bisnis berbahasa Inggris.
[KARTU KONTEKS USAHA]
Data buyer: [NAMA PERUSAHAAN, KONTAK, NEGARA, SUMBER KONTAK].
Tugas: susun rangkaian surat berikut secara berurutan, masing-masing dengan subjek email:
1. Introduction letter (maks. 150 kata, di badan email, dengan bukti kredibilitas).
2. Contoh inquiry yang mungkin dikirim buyer (untuk latihan saya membalas).
3. Offering letter: produk, spesifikasi, MOQ, harga [INCOTERMS + PELABUHAN], kemasan,
   waktu kirim, pembayaran, masa berlaku penawaran.
4. Balasan negosiasi yang mempertahankan harga dengan menukar konsesi lain.
5. Confirming letter.
6. Draf Purchase Order dari sisi buyer.
7. Daftar klausul Sales Contract yang perlu disepakati.
Setelah setiap surat, beri catatan "mengapa ditulis begini" dalam bahasa Indonesia.
```

### MP-19 · Listing Marketplace Global yang Menjual
*Tool:* Claude / ChatGPT · *Modul:* M5
```
Peran: Kamu adalah spesialis listing marketplace B2B/B2C internasional dan SEO produk.
Platform: [ALIBABA / AMAZON / ETSY / LAINNYA]. Produk: [ ].
Tugas:
1. Riset kata kunci yang dipakai pembeli internasional (beri daftar dan alasannya).
2. Tulis judul produk, 5 bullet manfaat, deskripsi, spesifikasi teknis, FAQ, dan backend
   keywords sesuai aturan platform.
3. Daftar foto dan video yang wajib disiapkan (shot list).
4. Tulis jawaban siap pakai untuk 5 pertanyaan buyer yang paling sering muncul.
Batasan: hindari klaim kesehatan atau keberlanjutan tanpa bukti sertifikat.
```

### MP-20 · Persiapan Pameran & Business Matching
*Tool:* Claude / ChatGPT · *Modul:* M5, M9
```
Peran: Kamu adalah trade show coach.
Pameran: [NAMA PAMERAN / VIRTUAL], tanggal [ ], produk [ ].
Tugas:
1. Rencana T-60 sampai T+30 hari (pra-pameran, saat pameran, tindak lanjut).
2. Elevator pitch 30 detik dan 2 menit dalam bahasa Inggris.
3. Daftar pertanyaan kualifikasi buyer (BANT yang disesuaikan untuk ekspor).
4. Template catatan kontak dan skor prospek.
5. Rangkaian email tindak lanjut hari ke-1, ke-7, dan ke-21.
```

## BAGIAN E · HARGA, KEUANGAN, DAN PEMBIAYAAN (MODUL 6)

### MP-21 · Kalkulator Harga Ekspor EXW-FOB-CFR-CIF
*Tool:* Claude / ChatGPT (Data Analysis) / Excel Copilot · *Modul:* M6
```
Peran: Kamu adalah export pricing analyst.
Tugas:
1. Tanyakan: harga pokok penjualan per unit, biaya bunga modal kerja, target profit (%),
   kurs anggaran, local handling per kontainer, jumlah unit per kontainer, komisi agen (%),
   ruang diskon negosiasi (%), sea freight per kontainer, tarif asuransi (%).
2. Hitung berurutan: EXW = harga pokok ÷ (1 - profit%) → FOB = EXW + handling/unit →
   + komisi → ÷ (1 - diskon%) → CFR = + freight/unit → CIF = + asuransi (tarif × 110% × CFR).
3. Tunjukkan setiap langkah, cek ulang dengan cara kedua, dan sajikan tabel rumus spreadsheet.
4. Buat versi retrograde: dari harga target buyer [HARGA CIF], hitung mundur apakah margin
   saya masih positif.
5. Analisis sensitivitas kurs ±5% dan freight ±30%.
Acuan logika: garden chair EXW USD 9,811 → FOB 9,931 → +3% komisi 10,229 →
÷90% 11,366 → +freight 0,250 = CFR 11,616 → +asuransi 0,038 = CIF 11,654.
```

### MP-22 · Proyeksi Arus Kas Satu Siklus Order
*Tool:* Claude / ChatGPT (Data Analysis) · *Modul:* M6
```
Peran: Kamu adalah CFO UMKM ekspor.
Order: [VOLUME] unit, nilai [NILAI], pembayaran [METODE + TERMIN], lead time produksi [ ] hari,
transit [ ] hari.
Tugas:
1. Petakan arus kas mingguan dari PO diterima sampai dana diterima (bahan baku, upah,
   kemasan, sertifikasi, inland transport, handling, freight bila CFR/CIF, asuransi, biaya bank).
2. Hitung kebutuhan modal kerja puncak dan lama dana tertahan (cash conversion cycle).
3. Usulkan opsi pembiayaan: pembiayaan pra-pengapalan, pasca-pengapalan, uang muka buyer,
   fasilitas lembaga pembiayaan ekspor; bandingkan biaya dan syaratnya (PERLU VERIFIKASI).
4. Sajikan grafik saldo kas mingguan dan rumus spreadsheet.
```

### MP-23 · Pemeriksa Syarat Letter of Credit
*Tool:* Claude / ChatGPT · *Modul:* M6, M8
```
Peran: Kamu adalah document checker trade finance dengan pengalaman UCP 600.
Draf L/C: [TEMPEL TEKS L/C, SAMARKAN NOMOR REKENING].
Tugas:
1. Ekstrak semua syarat ke tabel: jenis L/C, nilai dan toleransi, tanggal kedaluwarsa,
   latest shipment date, periode presentasi, pelabuhan, partial/transhipment, Incoterms,
   daftar dokumen dan detail setiap dokumen.
2. Tandai syarat yang berisiko atau mustahil dipenuhi (misalnya sertifikat yang tidak bisa
   terbit tepat waktu, deskripsi barang tidak cocok).
3. Susun daftar amandemen yang perlu saya minta ke buyer sebelum produksi.
4. Buat checklist presentasi dokumen agar bebas discrepancy.
Batasan: ini bukan nasihat hukum; sarankan konfirmasi dengan bank advising.
```

## BAGIAN F · LEGALITAS DAN ORGANISASI (MODUL 7)

### MP-24 · Peta Legalitas Eksportir
*Tool:* Perplexity / Claude · *Modul:* M7
```
Peran: Kamu adalah konsultan perizinan usaha Indonesia.
[KARTU KONTEKS USAHA]
Tugas:
1. Bandingkan bentuk usaha (perorangan, CV, PT, PT perorangan, koperasi) untuk kebutuhan ekspor.
2. Jelaskan alur NIB di OSS, pemilihan KBLI yang relevan, dan bahwa NIB berfungsi sebagai
   akses kepabeanan.
3. Cek apakah [PRODUK] termasuk barang bebas, dibatasi, atau dilarang ekspor dan perizinan
   khusus yang mungkin diperlukan (eksportir terdaftar, persetujuan ekspor, laporan surveyor).
4. Susun checklist legalitas berurutan dengan estimasi waktu.
Batasan: rujuk regulasi terbaru (Permendag 23/2023 beserta perubahannya, peraturan OSS
terbaru) dan tandai PERLU VERIFIKASI di oss.go.id dan peraturan.bpk.go.id.
```

### MP-25 · Company Profile Berstandar Global
*Tool:* Claude / ChatGPT + Gamma / Canva · *Modul:* M7
```
Peran: Kamu adalah penulis company profile B2B internasional.
[KARTU KONTEKS USAHA]
Tugas:
1. Wawancarai saya dengan 12 pertanyaan (sejarah, visi, produk, kapasitas, fasilitas,
   QA/QC, sertifikasi, pasar yang dilayani, tim, keberlanjutan, testimoni, kontak).
2. Tulis company profile bahasa Inggris 2 halaman: headline nilai, about us, product range,
   capacity & quality, certifications, sustainability & traceability, why partner with us.
3. Buat versi satu paragraf (100 kata) untuk email dan versi 3 kalimat untuk LinkedIn.
4. Buat outline 10 slide untuk Gamma atau Canva.
Batasan: hanya gunakan klaim yang saya konfirmasi.
```

### MP-26 · Desain Organisasi & SOP Tim Ekspor
*Tool:* Claude / ChatGPT / Notion AI · *Modul:* M7
```
Peran: Kamu adalah konsultan pengembangan organisasi untuk UMKM.
Tim saat ini: [JUMLAH, PERAN]. Volume target: [ ] kontainer per tahun.
Tugas:
1. Rancang struktur peran ekspor minimum (export manager, admin dokumen, QC, marketing),
   mana yang dirangkap, mana yang di-outsource (PPJK, forwarder, konsultan).
2. Buat matriks RACI untuk 12 aktivitas utama dari inquiry sampai pembayaran.
3. Susun SOP ringkas untuk 3 proses paling kritis.
4. Rencana peningkatan kompetensi termasuk sertifikasi Pelaksana Ekspor.
```

## BAGIAN G · KONTRAK, DOKUMEN, KEPABEANAN, LOGISTIK (MODUL 8)

### MP-27 · Generator Set Dokumen Ekspor Konsisten
*Tool:* Claude / ChatGPT · *Modul:* M8
```
Peran: Kamu adalah pelaksana ekspor bersertifikat (unit KOP.EK02.012.01 dan .010.01).
Data transaksi dari PO/Sales Contract: [TEMPEL: shipper, consignee, notify party, produk,
HS, jumlah, kemasan, berat bersih/kotor, dimensi, harga, Incoterms, pelabuhan muat/bongkar,
kapal, tanggal, metode pembayaran].
Tugas:
1. Susun draf: Commercial Invoice, Packing List, Shipping Instruction, draf B/L,
   isian data untuk PEB, dan isian data untuk SKA/COO.
2. Buat tabel konsistensi lintas dokumen (nama pihak, deskripsi, jumlah koli, berat, nilai,
   shipping mark) dan tandai setiap selisih.
3. Daftar data yang masih kosong dan siapa yang harus menyediakannya.
Batasan: draf untuk latihan dan persiapan; finalisasi mengikuti format resmi instansi,
forwarder, dan sistem Bea Cukai.
```

### MP-28 · Simulator Prosedur Kepabeanan & Pemeriksaan Fisik
*Tool:* Claude / ChatGPT (roleplay) · *Modul:* M8
```
Peran ganda: (1) mentor kepabeanan, (2) dalam simulasi, petugas Bea Cukai dan petugas karantina.
Produk: [PRODUK], HS [ ], tujuan [NEGARA], moda [LAUT/UDARA].
Tugas:
1. Jelaskan alur: NIB sebagai akses kepabeanan → cek tata niaga → HS Code dan bea keluar →
   dokumen dasar → PEB → NPE → pemeriksaan fisik bila diperlukan → stuffing → muat.
2. Tentukan pemeriksaan fisik yang mungkin diperlukan (karantina, surveyor, internal, Bea Cukai),
   kapan dilakukan, dokumen aplikasinya, dan pihak yang dihubungi.
3. Jalankan simulasi tanya jawab 8 giliran sebagai petugas; beri skor kesiapan saya.
4. Tutup dengan checklist H-14 sampai H+1 pengapalan.
Batasan: tandai ketentuan waktu dan prosedur sebagai PERLU VERIFIKASI di beacukai.go.id.
```

### MP-29 · Perencana Muatan Kontainer & Pemilihan Moda
*Tool:* Claude / ChatGPT (Data Analysis) · *Modul:* M8
```
Peran: Kamu adalah logistics planner.
Data: dimensi karton [P×L×T cm], berat per karton [kg], dapat ditumpuk [ya/tidak, maks lapis],
palet [ya/tidak], volume order [ ].
Tugas:
1. Hitung kapasitas untuk 20 ft (dalam 589×235×238 cm), 40 ft, dan 40 ft HC dengan menguji
   semua orientasi karton; pilih susunan optimal, cek batas berat.
2. Bandingkan FCL vs LCL vs kargo udara untuk volume ini (biaya per unit sebagai rumus,
   waktu, risiko kerusakan), tanpa mengarang tarif.
3. Buat stuffing plan (urutan muat, penguat, dunnage, foto dokumentasi).
4. Daftar pertanyaan untuk memilih forwarder.
Acuan cek: karton 30×33×30 cm di 20 ft → 19×7×7 = 931 karton.
```

## BAGIAN H · PERTUMBUHAN DAN OTOMATISASI (MODUL 9)

### MP-30 · Rencana Aksi Ekspor 90 Hari + Sistem Kerja Berbantuan AI
*Tool:* Claude / ChatGPT / Notion AI · *Modul:* M9 (Capstone)
```
Peran: Kamu adalah coach ekspor dan perancang sistem kerja berbantuan AI.
[KARTU KONTEKS USAHA]
Artefak yang sudah saya miliki: [skor evaluasi, SWOT/TOWS, BMC, laporan 5K+2S, matriks negara,
brief regulasi, daftar buyer, price sheet, company profile, set dokumen latihan].
Tugas:
1. Gunakan model GROW untuk menajamkan tujuan 90 hari (tanya satu per satu).
2. Susun rencana 30-60-90 hari: target terukur, aktivitas, PIC, anggaran, mitra
   (program pendukung, Atdag/ITPC, diaspora, lembaga pembiayaan), indikator.
3. Rancang "Export OS" di Notion: database Buyer Pipeline, Order Tracker, Dokumen,
   Kalender Pengapalan, Regulasi Watchlist, Prompt Library.
4. Untuk 6 pekerjaan berulang (riset buyer, balas inquiry, hitung harga, draf dokumen,
   pantau regulasi, laporan mingguan), tetapkan prompt dari Bank Prompt, alat AI, dan titik
   pemeriksaan manusia.
5. Premortem: 5 alasan rencana ini bisa gagal dan mitigasinya.
Format: rencana dalam tabel + struktur database Notion + daftar prompt.
```

---

## LAMPIRAN · PROMPT PENJAGA KUALITAS (TEMPEL DI AKHIR PROMPT MANA PUN)

**Penjaga Verifikasi**
```
Sebelum menjawab, periksa: apakah ada angka, nomor regulasi, tarif, nama perusahaan, atau
syarat negara yang tidak bisa kamu pastikan? Jika ada, tandai PERLU VERIFIKASI, sebutkan sumber
resmi untuk mengecek, dan jangan menyajikannya sebagai fakta.
```

**Penjaga Konsistensi Dokumen**
```
Setelah membuat dokumen, buat tabel pembanding untuk nama pihak, deskripsi barang, HS Code,
jumlah koli, berat bersih/kotor, volume, nilai, Incoterms, pelabuhan. Laporkan setiap selisih.
```

**Penjaga Berpikir Kritis**
```
Sebelum memberi rekomendasi akhir, sebutkan 3 asumsi yang kamu pakai, 1 argumen terkuat yang
menentang rekomendasimu, dan kondisi yang akan membuat rekomendasi berubah.
```

**Penjaga Privasi**
```
Saya akan menyamarkan data sensitif. Jangan meminta nomor rekening, nomor identitas, atau
data pribadi buyer. Jika dibutuhkan untuk dokumen, gunakan placeholder.
```

---

## SUMBER RUJUKAN (APA)

Bank Indonesia, & LPEM FEB UI. (2022). *Panduan persiapan UMKM go global: 9 langkah terstruktur untuk go global dengan lebih terencana*. Bank Indonesia.

International Chamber of Commerce. (2019). *Incoterms® 2020*. ICC.

International Chamber of Commerce. (2007). *Uniform customs and practice for documentary credits (UCP 600)*. ICC.

Kementerian Koperasi dan UKM Republik Indonesia. (2019). *Materi diklat dan uji kompetensi pelaksana ekspor*. Deputi Bidang Pengembangan SDM.

Kementerian Perdagangan Republik Indonesia. (2023). *Peraturan Menteri Perdagangan Nomor 23 Tahun 2023 tentang kebijakan dan pengaturan ekspor* (sebagaimana telah beberapa kali diubah).
