# PROJECT-PKL-KESRA

[Deskripsi singkat project: untuk apa website ini, siapa penggunanya, dan fitur utamanya.]

Website ini dibuat menggunakan Django.

## Langkah Penggunaan

### 1. Clone Repository

```bash
git clone https://github.com/alfithoDinopa/PROJECT-PKL-KESRA.git
cd PROJECT-PKL-KESRA
```

### 2. Buat Virtual Environment

```bash
python -m venv venv

# Aktifkan:
source venv/bin/activate    # Linux / macOS
venv\Scripts\activate       # Windows
```

### 3. Install Dependensi

```bash
pip install django
```

### 4. Setup Database

1. Install dan jalankan MySQL
2. Buat database `projectsaya`
3. Jalankan migrasi:

```bash
python manage.py migrate
```

### 5. Jalankan Server

```bash
python manage.py runserver
```

Buka http://127.0.0.1:8000 di browser.
