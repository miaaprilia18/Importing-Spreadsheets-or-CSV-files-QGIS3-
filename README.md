# Langkah -langkah Importing Spreadsheets or CSV files (QGIS3)

1.	Pertama kita download terlebih dahulu https://www.qgistutorials.com/downloads/earthquakes_2021_11_25_14_31_59_+0530.tsv file ini 
2.	 Klik tombol Buka Manajer Sumber Data pada Toolbar Sumber Data. Anda juga dapat menggunakan pintasan keyboard Ctrl + L.
3.	Dalam kotak dialog Manajer Sumber Data, beralihlah ke tab Teks Terbatas. Klik tombol ... di sebelah Nama file.
4.	Tergantung pada sistem operasi, Anda mungkin atau mungkin tidak melihat file di lokasi yang diunduh. Dalam Format file, beralihlah ke Semua file (*; *.*) untuk melihat file tsv.
5.	Sekarang Anda akan melihat file yang diunduh. Pilih itu dan klik Buka.
6.	Dalam kotak dialog Manajer Sumber Data, jalur ke file akan tersedia di Nama File. Ubah nama Layer menjadi 1900_2000_earthquakes. Di bagian Format file, pilih Pembatas kustom dan centang Tab. Di bagian Definisi geometri, pilih Koordinat titik. Secara default bidang X dan nilai bidang Y akan diisi secara otomatis jika menemukan bidang nama yang sesuai di input. Anda dapat mengubahnya jika impor memilih bidang yang salah. Anda dapat membiarkan Geometry CRS ke EPSG:4326 - WGS 84 CRS default. Jika file Anda berisi koordinat dalam CRS yang berbeda, Anda dapat memilih CRS yang sesuai di sini. Klik Tambahkan.
7.	Anda sekarang akan melihat bahwa data akan diimpor dan ditampilkan di kanvas QGIS sebagai layer baru yang disebut 1900_2000_earthquakes dengan CRS EPSG:4326.

