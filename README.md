Face Detection dengan OpenCV

Proyek ini adalah implementasi deteksi wajah menggunakan OpenCV. Sistem dapat mendeteksi wajah secara real-time menggunakan webcam dengan bantuan Haar Cascade Classifier.

📌 Fitur

Mendeteksi wajah menggunakan Haar Cascade Classifier.

Menampilkan kotak hijau di sekitar wajah yang terdeteksi.

Menutup jendela dengan menekan tombol 'q'.

Menggunakan OpenCV untuk pemrosesan gambar.

🛠️ Persyaratan

Sebelum menjalankan proyek ini, pastikan Anda telah menginstal dependensi berikut:

Python 3.x

OpenCV (cv2)

🚀 Instalasi

Clone repository ini:

git clone https://github.com/yourrepo/face_detection.git
cd face_detection

Buat virtual environment (opsional tetapi disarankan):

python -m venv venv
source venv/bin/activate  # Untuk macOS/Linux
venv\Scripts\activate    # Untuk Windows

Instal dependensi:

pip install opencv-python

🎯 Cara Menjalankan

Jalankan skrip utama dengan perintah berikut:

python main.py

Setelah dijalankan, kamera akan aktif dan mulai mendeteksi wajah secara real-time.

📂 Struktur Proyek

face_detection/
│── main.py         # File utama untuk menjalankan deteksi wajah
│── face_ref.xml    # Model deteksi wajah Haar Cascade
│── requirements.txt # Daftar dependensi
│── .gitignore      # Mengabaikan file yang tidak perlu
│── README.md       # Dokumentasi proyek

📝 Catatan

Jika kamera tidak berfungsi, pastikan webcam terhubung dan tidak digunakan oleh aplikasi lain.

Jika performa lambat, coba kurangi resolusi frame dalam kode OpenCV.

🤝 Kontribusi

Jika Anda ingin berkontribusi, silakan fork repository ini dan buat pull request dengan perbaikan atau fitur tambahan.

📜 Lisensi

Proyek ini dilisensikan di bawah MIT License.

✨ Dibuat dengan ❤️ oleh Naufal Daffa Erlangga
