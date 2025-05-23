# SI MONITORING KEHADIRAN KEL 4

UAS PBF dengan laravel mengambil data melalui fetch API Baceknd

### Clone repository backend
```terminal
git clone https://github.com/NalindraDT/Simon-kehadiran.git
```
Nyalakan server backend
```bash
php spark serve
```
Test apakah API endpoint backend sudah berjalan di Postman
```
Matkul
GET matkul : http://localhost:8080/matkul
POST matkul : http://localhost:8080/matkul
PUT matkul : http://localhost:8080/matkul/{kode_matkul}
DELETE matkul : http://localhost:8080/matkul/{kode_matkul}

GET mahasiswa : http://localhost:8080/mahasiswa
POST mahasiswa : http://localhost:8080/mahasiswa
PUT mahasiswa : http://localhost:8080/mahasiswa/{npm}
DELETE mahasiswa : http://localhost:8080/mahasiswa/{npm}
```

### Download database
https://github.com/JiRizkyCahyusna/DBE_Simon.git

### Buat Project Baru Laravel
Langkah:
Buat file project laravel dgn perintah 
```bash
composer create-project laravel/laravel frontend-uas-230102057
```

2. nyalakan server laravel
```bash
php artisan serve
```

#### ubah di .env
```php
APP_NAME=Laravel
APP_URL=http://localhost
SESSION_DRIVER=file
```

### ✅ Status CRUD Kedua Tabel
Fitur	     Status
Tampilkan     ✅
Tambah	      ✅
Edit	      ✅
Hapus	      ✅
