# SIG_2101093003_Teori
SIG Teori


Lubuk Basung adalah sebuah kecamatan yang berada di kabupaten Agam tepatnya di Sumatra Barat. Lubuk Basung adalah ibu kota dari Kabupaten Agam yang pusat pemerintahan nya bertepatan di Lubuk Basung. Saya akan menjelaskan Tata Cara membuat peta di Qgis;

1. Perfoming Table Join
Tidak setiap himpunan data yang ingin Anda gunakan datang dalam format spasial, dan seringkali data akan datang sebagai data tabular seperti CSV, TSV, atau spreadsheet. Anda perlu menghubungkannya dengan data spasial yang ada untuk digunakan dalam analisis Anda. Operasi ini dikenal sebagai Table Join dan dilakukan menggunakan toolbox algoritma dari Processing.

2. Perfoming Spatial Joins
Spatial Join adalah masalah GIS klasik - mentransfer atribut dari satu lapisan ke lapisan lain berdasarkan hubungan spasialnya. Di QGIS, fungsi ini tersedia melalui algoritma Processing.Kami akan menggunakan 2 lapisan - Sebuah shapefile dari batas-batas Borough kota New York dan shapefile lain dari Street Pavement Rating untuk semua jalan di kota New York. Tugas pertama adalah menemukan peringkat rata-rata jalan di setiap wilayah menggunakan gabungan spasial dengan algoritma ringkasan. Tugas kedua adalah menambahkan nama borough ke fitur jalan melalui penggabungan spasial satu-ke-banyak.

3. Perfoming Spatial Queries
Kami akan menggunakan 2 lapisan - Sebuah shapefile dari batas-batas Borough kota New York dan shapefile lain dari Street Pavement Rating untuk semua jalan di kota New York. Tugas pertama adalah menemukan peringkat rata-rata jalan di setiap wilayah menggunakan gabungan spasial dengan algoritma ringkasan. Tugas kedua adalah menambahkan nama borough ke fitur jalan melalui penggabungan spasial satu-ke-banyak.Kami akan bekerja dengan 2 lapisan data untuk kota Melbourne, Australia. Mengingat lapisan data untuk pub dan bar di kota dan lokasi semua stasiun metro, kami ingin mengetahui semua bar dan pub dalam jarak 500 meter dari stasiun metro.

4. Nearest Neighbor Analysis
SIG sangat berguna dalam menganalisis hubungan spasial antar fitur. Salah satu analisis tersebut adalah mencari tahu fitur mana yang paling dekat dengan fitur tertentu. Ada beberapa cara untuk melakukan analisis ini di QGIS. Anda dapat melakukan penggabungan spasial menggunakan Atribut Gabungan oleh Terdekat atau mendapatkan jarak ke semua fitur dari lapisan lain menggunakan alat Matriks Jarak dari Kotak Alat Pemrosesan. Dalam tutorial ini, kita akan menjelajahi alat bernama Jarak ke hub terdekat dari Kotak Alat Pemrosesan yang tidak hanya dapat menemukan jarak ke fitur terdekat tetapi juga menggabungkannya dengan garis untuk memvisualisasikan hasilnya.

5.Sampling Raster Data using Points or Polygons
Banyak kumpulan data ilmiah dan lingkungan datang sebagai raster gridded. Data elevasi (DEM) juga didistribusikan sebagai file raster. Dalam file raster ini, parameter yang diwakili dikodekan sebagai nilai piksel raster. Seringkali, seseorang perlu mengekstrak nilai piksel di lokasi tertentu atau menggabungkannya di beberapa area. Fungsi ini tersedia di QGIS melalui algoritma pengolahan. untuk lapisan titik dan untuk lapisan poligon.

6. Calculating Raster Area 
Banyak aplikasi yang membutuhkan penghitungan pola penggunaan lahan di suatu wilayah. Himpunan data Land Use Land Cover (LULC) hadir sebagai file raster di mana setiap piksel diberi nilai kelas. Analis GIS sering kali perlu menghasilkan laporan berdasarkan data ini dengan menghitung area per kelas di wilayah tertentu. QGIS dilengkapi dengan banyak alat bawaan untuk menghitung dan meringkas area raster.

7. Creating Heatmaps 
Peta panas adalah salah satu alat visualisasi terbaik untuk data titik padat. Heatmap merupakan teknik interpolasi yang berguna dalam menentukan kepadatan fitur input. Peta panas paling sering digunakan untuk memvisualisasikan data kejahatan, insiden lalu lintas, kepadatan perumahan, dll. QGIS memiliki heatmap renderer yang dapat digunakan untuk menata layer titik dan algoritma Pengolahan Heatmap (Kernel Density Estimation) yang dapat digunakan untuk membuat raster dari layer titik.

8. Animating Time Series Data 
Waktu adalah komponen penting dari banyak himpunan data spasial. Seiring dengan informasi lokasi, waktu menyediakan dimensi lain untuk analisis dan visualisasi data. Jika Anda bekerja dengan himpunan data yang berisi stempel waktu atau memiliki pengamatan yang direkam pada beberapa langkah waktu, Anda dapat dengan mudah memvisualisasikannya menggunakan kontrol Temporal. Kontrol temporal memungkinkan Anda untuk melihat dan mengekspor 'irisan' data antara interval waktu tertentu yang dapat digabungkan menjadi animasi.

9. Handling Invalid Geometries
Saat bekerja dengan lapisan data vektor, Anda mungkin mengalami kesalahan geometri. Kesalahan ini sering menjadi bagian dari data Anda setelah menjalankan geoprocessing, digitalisasi, pengeditan, atau konversi data. QGIS3 dilengkapi dengan alat dan algoritma bawaan untuk mendeteksi dan memperbaiki geometri yang tidak valid. Tutorial ini akan menunjukkan kepada Anda alur kerja umum untuk menangani geometri yang tidak valid dalam data Anda.

