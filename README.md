Face Detection Project

Proyek ini adalah aplikasi pendeteksi wajah menggunakan OpenCV dalam bahasa Python.

Fitur

Mendeteksi wajah dalam video real-time menggunakan webcam.

Menampilkan kotak hijau di sekitar wajah yang terdeteksi.

Menutup jendela dengan menekan tombol 'q'.

Menggunakan Haar Cascade Classifier untuk deteksi wajah.

Optimalisasi gambar dengan konversi ke grayscale.

Prasyarat

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal pustaka berikut:

pip install opencv-python

Cara Menggunakan

Pastikan Anda memiliki file face_ref.xml di direktori yang sama dengan skrip ini.

Jalankan skrip dengan perintah berikut:

python main.py

Tekan tombol 'q' untuk menutup jendela aplikasi.

Struktur Kode

face_detection(frame): Mengubah frame menjadi grayscale dan mendeteksi wajah menggunakan Haar Cascade Classifier.

drawer_box(frame): Menggambar kotak di sekitar wajah yang terdeteksi.

close_window(): Menutup kamera dan menutup jendela aplikasi.

main(): Menjalankan loop utama untuk menangkap frame dan menampilkan hasil deteksi wajah.

Potensi Pengembangan

Menggunakan model deteksi wajah berbasis deep learning untuk akurasi yang lebih tinggi.

Menambahkan fitur deteksi mata dan senyuman.

Menyimpan hasil deteksi dalam bentuk gambar atau video.

Mengintegrasikan dengan sistem keamanan atau aplikasi berbasis AI.

Lisensi

Proyek ini menggunakan lisensi MIT. Anda bebas menggunakan dan memodifikasinya.

Kontribusi

Jika ingin berkontribusi, silakan buat pull request atau buka issue pada repository ini.
