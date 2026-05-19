# LogicSense

LogicSense adalah Sistem Monitoring Progres Belajar Siswa Berbasis Web yang dirancang khusus untuk mendigitalisasi, memantau, dan mendiagnosis capaian kompetensi siswa secara *real-time*. Sistem ini dilengkapi dengan modul **Sistem Pakar** untuk menganalisis rata-rata kognitif kelas guna memberikan rekomendasi strategi pengajaran yang tepat.

---

## 🚀 Fitur Utama
- **Direktori & CRUD Master**: Pengelolaan data sekolah tempat mengajar beserta roster siswa terintegrasi.
- **Timeline Jadwal otomatis**: Pengurutan jadwal mengajar berdasarkan hari aktif secara berurutan.
- **Omset Tracker Engine**: Kalkulator finansial otomatis berbasis log kehadiran dan rate kontrak kerja sama.
- **Sistem Pakar Forward Chaining**: Modul AI berbasis aturan untuk mendiagnosis rata-rata kognitif kelas secara berkala.
- **Automated Ledger Export**: Ekspor transkrip capaian kompetensi siswa dalam format dokumen PDF formal.

## 🛠️ Tech Stack & Arsitektur
Aplikasi ini dibangun menggunakan arsitektur *decoupled/microservices*:
- **Frontend**: Next.js (React Framework) & Tailwind CSS (Modern Minimalist & Industrial Bold).
- **AI/Logic Engine**: Python (FastAPI Framework).
- **Database & Auth**: Supabase (PostgreSQL BaaS).

## 📁 Struktur Monorepo
```text
logicsense/
├── backend-ai/          # Server Python & Mesin Sistem Pakar (FastAPI)
└── frontend-web/        # Antarmuka Web & Manajemen State (Next.js)
