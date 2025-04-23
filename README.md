# 🚦 Sistem-Deteksi-Kepadatan-Lalu-Lintas-Pelanggaran-Helm-Berbasis-YOLOv9-M
Proyek ini mengembangkan sistem cerdas untuk mendeteksi kepadatan lalu lintas serta pengendara motor yang tidak menggunakan helm, dengan kemampuan analisis secara real-time maupun dari rekaman video.​

# 🔧 Fitur Utama
1. Deteksi Helm Otomatis: Mendeteksi pengendara motor yang tidak menggunakan helm menggunakan model YOLOv9 versi M.​
2. Estimasi Kepadatan Lalu Lintas: Menghitung jumlah kendaraan pada area tertentu untuk menilai tingkat kepadatan lalu lintas.​
3. Dukungan Real-time dan Statis: Berfungsi baik untuk analisis langsung dari kamera maupun dari video yang telah direkam.​
4. Pelabelan Data dengan Roboflow: Menggunakan Roboflow untuk proses pelabelan data yang efisien dan akurat.​
5. Pelatihan Model di Google Colab: Model dilatih menggunakan Google Colab, memanfaatkan sumber daya komputasi awan.​

# 🧠 Teknologi yang Digunakan
1. YOLOv9-M: Versi terbaru dari algoritma deteksi objek yang menawarkan peningkatan akurasi dan efisiensi Home.
2. Roboflow: Platform untuk pelabelan dan manajemen dataset yang mendukung berbagai format dan integrasi dengan model deteksi objek.​
3. Google Colab: Lingkungan pemrograman berbasis cloud yang memungkinkan pelatihan model tanpa memerlukan perangkat keras lokal.​

# 🚀 Cara Memulai
1. Download script program beserta dataset atau models (9v-m) yang sudah di training
2. install library python ultralytics dengan script seperti berikut : !pip install ultralytics
3. jalankan script program.

# 📌 Tampilan
1. Tampilan Pengambilan video secara real-time
![Realtime Video](assets/screenshot_main_page.png)
2. Tampilan Pengambilan video Statis
![Statis Video](assets/screenshot_main_page.png)
