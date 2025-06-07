Kelompok 2
1. 	Baita Hikmah Annisa         	(23050974146)
2. 	Naayla Nurunnabiylah        	(23050974149)
3. 	Fadhea Salfinabila Arianti  	(23050974150)
4. 	Fiby Anggita Ayu Wulandari    (23050974151)

# WealthSync
WealthSync adalah aplikasi manajemen keuangan pribadi yang membantu pengguna mengelola transaksi, memantau pengeluaran, dan merencanakan keuangan mereka dengan mudah. Dengan tampilan yang intuitif dan fitur lengkap, WealthSync dirancang untuk pengguna yang ingin menjaga keuangan mereka tetap sehat dan terorganisir.

Tujuan dari pengembangan aplikasi WealthSync adalah untuk:
- Memberikan solusi digital yang praktis dalam pencatatan transaksi harian.
- Memfasilitasi pengguna dalam memantau arus kas secara real-time.
- Membantu pengguna merencanakan keuangan pribadi dengan lebih baik melalui fitur analisis dan visualisasi data.
- Menyediakan fitur setoran wajib bulanan dan riwayat transaksi lengkap untuk disiplin keuangan.

## 🧩 Fitur Utama & Endpoints API

### 🔐 Autentikasi
- `POST /login` – Login menggunakan email dan password (Firebase Auth).
- `POST /register` – Registrasi pengguna baru.
- `POST /logout` – Logout pengguna.

### 👤 Manajemen Pengguna
- `GET /profile` – Menampilkan profil pengguna.
- `PUT /profile/update` – Memperbarui profil pengguna.

### 💸 Transaksi
- `GET /transactions` – Menampilkan daftar transaksi.
- `POST /transactions` – Menambah transaksi baru.
- `PUT /transactions/:id` – Mengedit transaksi.
- `DELETE /transactions/:id` – Menghapus transaksi.
- `GET /transactions/filter?date=&category=` – Filter transaksi berdasarkan tanggal & kategori.
- `GET /transactions/export/pdf` – Ekspor transaksi ke PDF.
- `GET /transactions/export/excel` – Ekspor transaksi ke Excel.

### 📊 Dashboard & Analisis
- `GET /dashboard/summary` – Ringkasan saldo, pemasukan, dan pengeluaran.
- `GET /dashboard/chart` – Grafik transaksi 7 hari terakhir.
- `GET /dashboard/recent` – Daftar transaksi terbaru.

## 🌐 Alamat Website
👉 https://wealthsync-d8cda.web.app/

