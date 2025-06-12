# 🏨 Steze Kost & Guest House Booking System

Sistem manajemen reservasi untuk kost dan guest house berbasis Laravel, terdiri dari:

- **Frontend (Pelanggan)** – Laravel + Blade
- **Backend (Admin & Resepsionis)** – Laravel + Filament

---

## 📦 Akses Repositori Kode

🔗 GitHub Repository:  
[https://github.com/asirmanjaya/Proyek-STeZe](https://github.com/asirmanjaya/Proyek-STeZe)

📁 Struktur Database:

- **Struktur SQL**: `database/structure.sql`
- **Seeder**: `database/seeders/`

---

## 🚀 Panduan Instalasi & Deployment

### 📌 Persyaratan

- PHP 8.1+
- Composer
- MySQL
- Laravel 10.x
- Filament V+3

### ⚙️ Langkah Instalasi

```bash
git clone https://github.com/asirmanjaya/Proyek-STeZe.git
cd Proyek-STeZe

composer install
cp .env.example .env

# Konfigurasi file .env (DB, Email, dst.)
php artisan key:generate
php artisan migrate --seed

php artisan storage:link
php artisan optimize:clear

## 🔗 URL Sistem Live

### Frontend (Pelanggan)
🔗 [https://steze.biz.id](https://steze.biz.id)

### Backend (Admin & Resepsionis)
- 🔗 [https://steze.biz.id/admin](https://steze.biz.id/admin)
- 🔗 [https://steze.biz.id/resepsionis](https://steze.biz.id/resepsionis)

---

## 🔐 Kredensial Login Demo

**Admin**  
- 📧 Email: `admin@gmail.com`  
- 🔑 Password: `12345`

---

## 👥 Tim Pengembang

| Peran          | Nama                        |
|----------------|-----------------------------|
| Frontend Dev   | Kanaya – Blade pelanggan    |
| Backend Dev    | Asirman Jaya – Filament     |

---

## ✅ Fitur Utama

- 📅 **Booking online dengan kode unik**
- 📧 **Notifikasi email otomatis**
- 🛠 **Panel admin & resepsionis via Filament**
- 📊 **Statistik & laporan reservasi**
- 🔐 **Hak akses berbasis role (RBAC)**
- 📂 **CRUD data kamar, pelanggan, dan transaksi**

---

## 📖 Lisensi

Proyek ini berada di bawah lisensi **MIT**.  
Silakan gunakan, distribusikan, dan modifikasi sesuai kebutuhan Anda.

---

## 🚀 Kontribusi

Kontribusi sangat terbuka! Jangan ragu untuk membuat pull request atau membuka issue jika menemukan bug atau punya ide pengembangan baru.

---

## 📬 Kontak

Untuk pertanyaan lebih lanjut, silakan hubungi tim pengembang melalui profil GitHub atau email masing-masing.




