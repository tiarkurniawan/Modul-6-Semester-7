# Modul-6-Semester-7

# Modul6


# Aplikasi Klasifikasi Gambar dengan Flask

## Gambaran Umum
Repositori ini berisi contoh sederhana implementasi model klasifikasi gambar menggunakan Flask. Model dilatih menggunakan MobileNetV2 untuk mengklasifikasikan gambar ke dalam tiga kelas. Aplikasi web memungkinkan pengguna mengunggah gambar dan mendapatkan prediksi secara real-time.

## Struktur Proyek
|- static
|- templates
|- app.py
|- model.h5
|- README.md


## Dependensi
Pastikan untuk menginstal library yang dibutuhkan sebelum menjalankan aplikasi:
bash
pip install flask tensorflow


## Pelatihan Model
Model klasifikasi gambar dilatih menggunakan CNN. Model disimpan sebagai model.h5. Sesuaikan jumlah unit keluaran di lapisan terakhir dan fungsi aktivasi sesuai dengan jumlah kelas.

## Aplikasi Flask
Aplikasi web Flask (app.py) berfungsi sebagai antarmuka untuk model klasifikasi gambar. Aplikasi menggunakan model yang disimpan untuk membuat prediksi pada gambar yang diunggah oleh pengguna.

## Cara Menjalankan

bash
Copy code
python app.py
Buka browser dan akses http://127.0.0.1:5000/. Anda dapat mengunggah gambar dan mendapatkan prediksi.
