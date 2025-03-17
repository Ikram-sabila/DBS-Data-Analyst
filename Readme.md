Bike Sharing Dashboard

📌 Deskripsi Proyek

Proyek ini adalah dashboard interaktif untuk menganalisis data penyewaan sepeda berdasarkan berbagai faktor seperti cuaca, jam penyewaan, dan jumlah pengguna. Dashboard ini dibuat menggunakan Streamlit dan memvisualisasikan data dengan Matplotlib dan Seaborn.

🚀 Cara Menjalankan Proyek

1️⃣ Clone Repository GitHub

Pastikan Anda telah menginstal Git di komputer Anda. Kemudian jalankan perintah berikut di terminal:

# Clone repository
git clone https://github.com/username/repo-name.git

# Masuk ke folder proyek
cd repo-name

2️⃣ Buat Virtual Environment (Opsional)

Disarankan menggunakan virtual environment untuk menghindari konflik dependensi:

# Buat virtual environment
python -m venv venv

# Aktifkan virtual environment
# Windows
venv\Scripts\activate

# MacOS/Linux
source venv/bin/activate

3️⃣ Instal Dependensi

Pastikan Anda memiliki Python 3.8 atau lebih baru, lalu jalankan:

pip install -r requirements.txt

4️⃣ Jalankan Aplikasi Streamlit

Masuk ke folder `dashboard` terlebih dahulu:

cd dashboard

5️⃣ Jalankan Aplikasi Streamlit

streamlit run dashboard.py

Aplikasi akan terbuka secara otomatis di browser dengan alamat:

http://localhost:8501

🌐 Menjalankan di Streamlit Cloud

Proyek ini juga dapat diakses secara online melalui Streamlit Community Cloud.

🔗 Akses Dashboard: Klik di sini (ganti dengan link Streamlit Anda)

Jika ingin menjalankan ulang aplikasi di Streamlit Cloud:

Buka halaman Manage App di Streamlit Cloud.

Klik Reboot App atau lakukan commit perubahan terbaru ke GitHub agar otomatis ter-update.

🛠 Teknologi yang Digunakan

Python

Streamlit (untuk membuat dashboard interaktif)

Matplotlib & Seaborn (untuk visualisasi data)

Pandas (untuk manipulasi data)

📝 Catatan

Pastikan file dashboard/data_ready_day.csv dan dashboard/data_ready_hour.csv ada di dalam folder proyek.

Jika menggunakan Streamlit Cloud, pastikan semua dependensi sudah ada di requirements.txt.

Selamat mencoba! 🚀

