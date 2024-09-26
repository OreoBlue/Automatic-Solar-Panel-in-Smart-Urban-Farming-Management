# Deteksi-Otomatis-Modul-Fotovoltaik-Rusak-dengan-Inspeksi-Termografis-Udara
Repo ini menjelaskan tentang projek yang digunakan untuk kebutuhan industri pertanian.
1. Pendahuluan
  Energi surya semakin banyak digunakan, namun penggunaannya tidak terlepas dari tantangan. Modul fotovoltaik (PV) perlu diperiksa secara rutin untuk mendeteksi kerusakan, baik sebelum distribusi, selama transportasi, saat instalasi, maupun setelah penggunaan. Kebutuhan ini telah mendorong banyak perusahaan untuk mengalihdayakan inspeksi modul PV di perumahan, pabrik industri, dan ladang surya.
  Proyek ini mengusulkan solusi inovatif dengan menggunakan drone yang dilengkapi kamera RGB eksternal dan modul kamera termal yang diarahkan tegak lurus ke tanah. Drone ini juga dilengkapi mikroprosesor untuk pemrosesan gambar dan pengendalian drone, serta sumber daya seperti baterai dan pengatur daya.
  Tujuan utama proyek ini adalah mengembangkan sistem yang dapat secara otomatis melakukan navigasi di atas ladang surya, merekam gambar setiap panel PV, dan menyimpannya untuk pemrosesan lebih lanjut. Setelah drone mendarat, data akan dianalisis menggunakan klasifikasi gambar melalui pembelajaran mesin. Kerusakan panel surya akan dikategorikan menjadi tiga klasifikasi: hotspot, sirkuit bypass, dan kotak persimpangan.
  Hasil akhir dari proyek ini adalah informasi yang berisi data ketidakteraturan dan posisi setiap panel PV. Pendekatan ini diharapkan dapat membantu mengurangi waktu inspeksi dan meningkatkan frekuensi pemeriksaan.

2. Metodologi
  Proses dalam proyek ini dibagi menjadi dua bagian utama:
 2.1 Operasi Penerbangan
    Operasi penerbangan mencakup navigasi terpandu di atas array surya dengan memanfaatkan pemrosesan gambar. Simulasi model telah dilakukan dalam lingkungan ROS dan simulasi Gazebo, menggunakan bahasa pemrograman Python. Untuk komunikasi, proyek ini menggunakan protokol MavLink pada firmware Ardupilot.
 2.2 Pemrosesan Pasca Penerbangan
    Selama penerbangan, drone akan mengambil gambar termal sepanjang array surya. Pemrosesan gambar dan pembelajaran mesin digunakan untuk segmentasi dan klasifikasi kerusakan pada setiap panel.

3. Signifikansi Proyek
  Proyek ini memiliki potensi untuk memberikan dampak signifikan dalam industri energi surya:
- Efisiensi: Mengurangi waktu inspeksi dan meningkatkan frekuensi pemeriksaan.
- Akurasi: Memanfaatkan teknologi termografi dan pembelajaran mesin untuk deteksi kerusakan yang lebih akurat.
- Keselamatan: Mengurangi risiko keselamatan terkait inspeksi manual pada instalasi surya skala besar.
- Pemeliharaan Proaktif: Memungkinkan identifikasi dini masalah potensial, mengurangi downtime dan biaya perbaikan.

4. Kesimpulan
  Proyek "Deteksi Otomatis Modul Fotovoltaik Rusak dengan Inspeksi Termografis Udara" menawarkan pendekatan inovatif untuk meningkatkan efisiensi dan efektivitas dalam pemeliharaan sistem energi surya. Dengan menggabungkan teknologi drone, pencitraan termal, dan kecerdasan buatan, proyek ini berpotensi mengubah cara inspeksi dan pemeliharaan instalasi surya dilakukan, mendukung adopsi energi terbarukan yang lebih luas dan efisien.
