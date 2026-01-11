# Aplikasi Streamlit

Aplikasi ini berjalan dengan Streamlit. Ikuti langkah di bawah untuk menyiapkan lingkungan dan menjalankannya.

## Prasyarat
- Python 3.11 (atau kompatibel)
- Pip sudah terpasang

## Setup Lingkungan
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```

## Menjalankan Aplikasi
```bash
streamlit run app.py
```
Aplikasi akan tersedia di `http://localhost:8501`.

## Catatan
- Jika Anda memuat model yang disimpan (pickle/joblib), pastikan versi `scikit-learn` saat menyimpan sama dengan versi saat memuat untuk menghindari peringatan/hasil tidak valid.
- File utama aplikasi berada di [app.py](app.py) dan dependensi di [requirements.txt](requirements.txt).

## Struktur
- [app.py](app.py) — kode aplikasi utama
- [requirements.txt](requirements.txt) — daftar dependensi
- [README.md](README.md) — panduan proyek
