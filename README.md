# Automatic Detection of Defective Photovoltaic Modules by Aerial Thermographic Inspections
Repo ini menjelaskan tentang projek yang digunakan untuk kebutuhan industri pertanian.

# 1. Pendahuluan
   Energi surya semakin banyak digunakan, namun penggunaannya tidak terlepas dari tantangan. Photovoltaic (PV) modules perlu diperiksa secara rutin untuk mendeteksi kerusakan, baik sebelum distribusi, selama transportasi, saat instalasi, maupun setelah penggunaan. Kebutuhan ini telah mendorong banyak perusahaan untuk mengalihdayakan inspeksi PV modules di perumahan, pabrik industri, dan solar farms.
  Proyek ini mengusulkan solusi inovatif dengan menggunakan drone yang dilengkapi external RGB camera dan thermal camera module yang diarahkan tegak lurus ke tanah. Drone ini juga dilengkapi microprocessor untuk image processing dan drone handling, serta power sources seperti battery dan power regulator.
  Tujuan utama proyek ini adalah mengembangkan sistem yang dapat secara otomatis melakukan navigasi di atas solar field, merekam gambar setiap PV panel, dan menyimpannya untuk post-processing. Setelah drone mendarat, data akan dianalisis menggunakan image classification melalui machine learning. Kerusakan panel surya akan dikategorikan menjadi tiga klasifikasi: hotspots, bypass circuits, dan junction boxes.
  Hasil akhir dari proyek ini adalah informasi yang berisi irregularity data dan posisi setiap PV panel. Pendekatan ini diharapkan dapat membantu mengurangi waktu inspeksi dan meningkatkan frekuensi pemeriksaan.

# 2. Metodologi
  Proses dalam proyek ini dibagi menjadi dua bagian utama:
2.1 Midflight Operation
  Midflight operation mencakup guided navigation di atas solar array dengan memanfaatkan image processing. Simulasi model telah dilakukan dalam ROS environment dan Gazebo simulation, menggunakan bahasa pemrograman Python. Untuk komunikasi, proyek ini menggunakan MavLink protocol pada Ardupilot firmware.
2.2 Post Processing
  Selama penerbangan, drone akan mengambil thermal images sepanjang solar array. Image processing dan machine learning digunakan untuk segmentasi dan klasifikasi defect pada setiap panel.

# 3. Signifikansi Proyek
  Proyek ini memiliki potensi untuk memberikan dampak signifikan dalam industri energi surya:
- Efisiensi: Mengurangi waktu inspeksi dan meningkatkan frekuensi pemeriksaan.
- Akurasi: Memanfaatkan teknologi thermographic dan machine learning untuk deteksi kerusakan yang lebih akurat.
- Keselamatan: Mengurangi risiko keselamatan terkait inspeksi manual pada instalasi surya skala besar.
- Pemeliharaan Proaktif: Memungkinkan identifikasi dini masalah potensial, mengurangi downtime dan biaya perbaikan.

# 4. Kesimpulan
  Proyek "Automatic Detection of Defective Photovoltaic Modules by Aerial Thermographic Inspections" menawarkan pendekatan inovatif untuk meningkatkan efisiensi dan efektivitas dalam pemeliharaan sistem energi surya. Dengan menggabungkan teknologi drone, thermal imaging, dan artificial intelligence, proyek ini berpotensi mengubah cara inspeksi dan pemeliharaan instalasi surya dilakukan, mendukung adopsi energi terbarukan yang lebih luas dan efisien.
