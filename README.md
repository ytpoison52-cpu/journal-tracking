# Journal Article Tracker - Al Usariyah

Sistem tracking artikel jurnal dengan fitur manajemen penulis, review, dan pendanaan.

## Fitur Utama

### 1. Input Artikel Baru
- **Multiple Authors**: Tambahkan banyak penulis dengan tombol "+ Tambah Penulis"
- **Afiliasi per Penulis**: Setiap penulis memiliki input afiliasi sendiri
- **Field Tambahan**:
  - Email Penulis (opsional)
  - Link DOI (opsional)
  - Tanggal pengajuan

### 2. Review Form
- **Field Wajib** (ditandai dengan *):
  - Editor (wajib dipilih dari dropdown)
  - Reviewer (wajib dipilih dari dropdown)
- **Field Opsional** (bisa diisi kapan saja):
  - Layout Worker
  - Nomor Terbitan
  - Email Penulis
  - Link DOI

### 3. Dashboard Artikel
- **Tombol "Siap Publish"**: Muncul otomatis ketika semua checklist (Turnitin, EYD, Layout) sudah tercentang
- **Filter Artikel**:
  - Filter berdasarkan status (Semua, Diajukan, Review, Ditolak)
  - Filter berdasarkan Afiliasi (dropdown dinamis)
  - Filter berdasarkan Terbitan (dropdown dinamis)
  - Search box untuk pencarian cepat
- **Pembatas Terbitan**: Visual separator antar terbitan berbeda dengan label terbitan

### 4. Pendanaan
- **Filter Lengkap**:
  - Cari berdasarkan nama (search box)
  - Filter berdasarkan role (Editor, Reviewer, Layout)
  - Filter berdasarkan terbitan
- **Export Data**:
  - Export ke Excel (format CSV)
  - Export ke PDF (print-ready)
- **Pembatas Terbitan**: Separator visual antar terbitan berbeda dalam tabel
- **Summary Cards**: Menampilkan statistik total penugasan per role

### 5. Manajemen Personel
- Kelola daftar Editor, Reviewer, dan Layout Worker
- Tambah/hapus personel dengan mudah
- Personel otomatis muncul di dropdown saat review artikel

## Cara Penggunaan

1. **Tambah Artikel**:
   - Isi judul artikel
   - Tambah penulis (klik "+ Tambah Penulis" untuk menambah lebih banyak)
   - Isi afiliasi untuk setiap penulis
   - Isi email dan DOI (opsional)
   - Klik "Simpan Artikel"

2. **Review Artikel**:
   - Klik tombol "Review" pada artikel yang diajukan
   - Pilih Editor dan Reviewer (wajib)
   - Isi Layout Worker, Terbitan, Email, DOI (opsional)
   - Klik "Simpan Review"

3. **Checklist & Publish**:
   - Centang Turnitin, EYD, dan Layout saat sudah selesai
   - Tombol "Siap Publish" akan muncul otomatis
   - Klik "Siap Publish" untuk menandai artikel siap terbit

4. **Filter & Export**:
   - Gunakan dropdown filter untuk menyaring data
   - Klik tombol "Excel" atau "PDF" untuk export data pendanaan

## Teknologi
- Pure HTML, CSS, JavaScript
- LocalStorage untuk penyimpanan data
- Responsive design
- No dependencies

## Browser Support
- Chrome 90+
- Firefox 88+
- Edge 90+
- Safari 14+