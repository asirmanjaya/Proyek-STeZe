# 🏨 Steze Kost & Guest House Booking System

Sistem manajemen reservasi untuk kost dan guest house berbasis Laravel, terdiri dari:

- **Frontend (Pelanggan)** – Laravel + Blade
- **Backend (Admin & Resepsionis)** – Laravel + Filament

---

## 📦 Akses Repositori Kode

🔗 GitHub Repository:  
[https://github.com/asirmanjaya/Proyek-STeZe](https://github.com/asirmanjaya/Proyek-STeZe)

📂 Struktur Folder:

```bash
app/
├── Filament/                # Panel admin & resepsionis (Filament)
├── Http/
│   ├── Controllers/
│   │   ├── Frontend/       # Kontrol untuk pelanggan
│   │   └── Admin/          # Kostumisasi panel
├── Models/                 # Model data
resources/
└── views/
    ├── frontend/           # Tampilan Blade pelanggan
routes/
├── web.php                 # Routing pelanggan & publik
├── filament.php            # Routing panel admin/resepsionis
