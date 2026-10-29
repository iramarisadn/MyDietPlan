# MyDietPlan

Jurnal diet pribadi: status BMI dan lingkar perut (indikator hijau/kuning/merah), kalori BMR/TDEE, pilihan defisit kalori, meal plan, catatan makan, saran olahraga, impor screenshot Strava, dan Progress Tracker dengan kalender kalori.

## Cara memakai

Saat pertama dibuka, buat akun lewat halaman **Daftar** (nama lengkap, nama pengguna, dan password), lalu masuk dengan nama pengguna dan password tersebut. Tekan "Keluar" di menu untuk berganti akun.

Akun dan datanya tersimpan di browser perangkat yang dipakai saat mendaftar. Setiap akun di perangkat yang sama punya data sendiri-sendiri. Password disimpan dalam bentuk hash dan tidak bisa dipulihkan.

Buka situsnya lewat GitHub Pages. Semua data disimpan di browser perangkat yang Anda pakai (localStorage), tidak dikirim ke server mana pun dan tidak tersimpan di repository ini.

## Catatan

- Akun tidak tersinkron antar perangkat: akun yang dibuat di HP tidak bisa dipakai untuk masuk di laptop.
- Sistem akun ini berjalan sepenuhnya di browser dan bukan sistem keamanan penuh. Jangan menyimpan informasi rahasia di website ini.
- Fitur AI (analisis kondisi, meal plan, perkiraan kalori dari foto, komentar AI, gambar menu, baca screenshot Strava) hanya berjalan saat halaman dibuka sebagai Artifact di Claude. Di GitHub Pages, fitur tersebut tidak aktif dan semua data diisi manual.
- Data di satu browser tidak otomatis pindah ke browser atau perangkat lain.
- Perhitungan memakai rumus Mifflin-St Jeor (BMR), klasifikasi BMI Asia-Pasifik, dan batas lingkar perut 90 cm (pria) / 80 cm (wanita). Hasilnya bukan pengganti saran dokter atau ahli gizi.
