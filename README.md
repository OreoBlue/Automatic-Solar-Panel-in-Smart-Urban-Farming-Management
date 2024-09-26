# Automatic Detection of Defective Photovoltaic Modules in Smart Urban Farming Management
Repo ini menjelaskan tentang projek solar panel yang digunakan untuk kebutuhan industri pertanian.

# 1. Pendahuluan
   Dalam era Smart Urban Farming Management, integrasi teknologi renewable energy menjadi semakin penting. Solar energy, khususnya, memegang peran kunci dalam mendukung keberlanjutan urban farming. Namun, efisiensi photovoltaic (PV) modules perlu dijaga melalui inspeksi rutin untuk mendeteksi kerusakan, baik sebelum distribusi, selama transportasi, saat instalasi, maupun setelah penggunaan.
   Proyek ini mengusulkan solusi inovatif dengan menggunakan drone untuk inspeksi otomatis PV modules yang digunakan dalam Smart Urban Farming. Drone dilengkapi dengan external RGB camera dan thermal camera module yang diarahkan tegak lurus ke tanah, microprocessor untuk image processing dan drone handling, serta power sources seperti battery dan power regulator.
   Tujuan utama proyek ini adalah mengembangkan sistem yang dapat secara otomatis melakukan navigasi di atas urban farming solar installations, merekam gambar setiap PV panel, dan menyimpannya untuk post-processing. Setelah drone mendarat, data akan dianalisis menggunakan image classification melalui machine learning. Kerusakan panel surya akan dikategorikan menjadi tiga klasifikasi: hotspots, bypass circuits, dan junction boxes.

# 2. Integrasi dengan Smart Urban Farming Management
   Dalam Smart Urban Farming Management, proyek ini memiliki beberapa aspek penting:
- Energy Efficiency: Memastikan PV modules berfungsi optimal untuk mendukung kebutuhan energi urban farming, seperti sistem irigasi otomatis dan pencahayaan.
- Resource Optimization: Integrasi dengan sistem manajemen sumber daya pertanian perkotaan, memungkinkan alokasi energi yang efisien untuk berbagai proses pertanian.
- Sustainable Practice: Mendukung praktik pertanian berkelanjutan dengan memastikan sumber energi terbarukan berfungsi optimal.
- Data-Driven Decision Making: Informasi dari inspeksi PV modules dapat diintegrasikan dengan data pertanian lainnya untuk pengambilan keputusan yang lebih baik.

# 3. Metodologi
Proses dalam proyek ini dibagi menjadi dua bagian utama:
   3.1 Midflight Operation
   Midflight operation mencakup guided navigation di atas urban farming solar installations dengan memanfaatkan image processing. Simulasi model telah dilakukan dalam ROS environment dan Gazebo simulation, menggunakan bahasa pemrograman Python. Untuk komunikasi, proyek ini menggunakan MavLink protocol pada Ardupilot firmware.
   3.2 Post Processing
   Selama penerbangan, drone akan mengambil thermal images sepanjang solar array. Image processing dan machine learning digunakan untuk segmentasi dan klasifikasi defect pada setiap panel. Data ini kemudian diintegrasikan dengan sistem manajemen urban farming yang lebih luas.

# 4. Signifikansi Proyek
   Proyek ini memiliki potensi untuk memberikan dampak signifikan dalam Smart Urban Farming Management:
- Efisiensi Energi: Memastikan suplai energi yang stabil dan efisien untuk operasi urban farming.
- Keberlanjutan: Mendukung praktik pertanian perkotaan yang lebih berkelanjutan melalui penggunaan energi terbarukan yang optimal.
- Integrasi Teknologi: Mendemonstrasikan integrasi teknologi drone, AI, dan energi terbarukan dalam konteks urban farming.
- Optimalisasi Sumber Daya: Memungkinkan alokasi sumber daya yang lebih baik dalam ekosistem urban farming.

# 5. Kesimpulan
   Proyek "Automatic Detection of Defective Photovoltaic Modules in Smart Urban Farming Management" menawarkan pendekatan inovatif untuk meningkatkan efisiensi dan keberlanjutan dalam sistem pertanian perkotaan modern. Dengan menggabungkan teknologi drone, thermal imaging, dan artificial intelligence, proyek ini tidak hanya meningkatkan pemeliharaan infrastruktur energi surya, tetapi juga berkontribusi pada optimalisasi keseluruhan sistem Smart Urban Farming. Integrasi ini menunjukkan potensi besar dalam mendukung ketahanan pangan perkotaan dan praktik pertanian yang lebih berkelanjutan di masa depan.

## Referensi
https://github.com/titangil/Automatic-Detection-of-Defective-Photovoltaic-Modules-by-Aerial-Thermographic-Inspections
