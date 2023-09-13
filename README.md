# Tije EDA

![image](https://github.com/Krioha/Tije/assets/93811161/0161b400-cfbf-4c31-9e18-11861a40014f)

# Intoduction
Semua berwal ketika saya pergi ke Jakarta dengan moda transportasi umum untuk mencapai tempat tujuan <br />
saya dan salah satu moda transportasi yang saya gunakan untuk mencapai tempat tujuan saya adalah Tije <br />
atau yang lebih dikenal sebagai Transjakarta Pertama kali saya gunakan tije untuk mencapai Rasunan Said <br />
jadi saya menggunakan Tije dengan kode trayek 4D atau 6M <br />
untuk mencapai tempat tersebut, dan saya berasal dari halte tije stasiun manggarai. didalam perjalanan tersebut <br />
tidak ada masalah yang menggangu dan saya berhasil mencapai tempatnya dengan tepat waktu. <br />
Perjalan saya selanjutnya ketika saya ingin menuju Gatot Subroto dengan tije yang berasal dari halte Tosari <br />
Saya akan menggunakan Tije dengan kode trayek 6B. Namun saya menggu terlalu lama untuk kedatangan bus 6B <br />
Oleh karna itu saya ingin menganalis data data tije yang dirilis oleh open data Jakarta pada tahun 2021. <br />
Untuk mengetahui apakah kedatangan waktu tije sudah tepat atau belum <br />
# Dataset
Dataset yang digunakan untuk menganalisis data Tije seperti yang sudah saya sebutkan diatas berasal dari <br />
Open data Jakarta dengan judul Data Penumpang Bus Transjakarta Tahun 2021 yang diterbitkan pada <br />
12 April 2022 dengan link sebagai berikut <a href="https://data.jakarta.go.id/dataset/data-penumpang-bus-transjakarta-januari-2021" target="_blank">Open Data</a>

# Data Extraction
Setelah data didapatkan lalu saya melakukan ekstrasi dan melakukan preprocessing pada data <br />
yang akan dilakukan analisis untuk lebih jelasnya bisa dilihat link berikut <a href="https://github.com/Krioha/Tije/blob/main/DataExtractionTJ.ipynb" target="_blank">Data Extraction</a> <br />

# EDA
Analisis yang ingin saya lakukan pertama kali adalah total keseluruhan jumlah pelanggan <br />
dengan tiap tiap kode trayek yang paling banyak digunakan oleh para pelanggan Tije <br />
dapat dilihat pada gambar berikut<br />
![image](https://github.com/Krioha/Tije/assets/93811161/2693a75a-8cdc-4e88-b75b-998ab579fcbf)
Dari hasil gambar diatas didapatkan hasil bahwa kode trayek yang paling banyak digunakan oleh <br />
para pelanggan tije adalah kode trayek 1 dengan relasi Block M - Kota dengan total seluruh pelanggan <br />
8,948,313 pelanggan yang sudah menaiki bus dengan kode trayek tersebut. Disusul oleh trayek lain seperti <br />
9, 3, 8, 5, 7, 10, 6, 2, 13 dengan jumlah pelanggan yang dapat dilihat pada info grafis di kiri atas. <br />
Dibawah grafik tersebut terdapat rata rata pengguna dengan kode trayek terbanyak perbulan dan masih dimpimpin <br />
oleh kode trayek 1 dengan rata rata pengguna sebesar 813,483 pelanggan per bulan yang menggunakan bus pada trayek <br />
tersebut serta rata rata perbulan tidak memiliki perbedaan peringkat dengan total keseluruhanya jadi nilainya dapat <br />
dilihat pada grafik kiri bawah. <br />
Saya Ingin melihat waktu tiap kedatangan bus tiap kode trayek yang saya dapatkan dari google dan saya akan tampikan dibawah ini <br />
• Kode trayek 1 datang setiap 2-5 menit tergantung pemberhentian <br />
• Kode trayek 9 datang setiap 3-7 menit tergantung pemberhentian <br />
• Kode trayek 3 datang setiap 3-7 menit tergantung pemberhentian <br />
• Kode trayek 8 datang setiap 4-10 menit tergantung pemberhentian <br />
• Kode trayek 5 datang setiap 6 menit <br />
• Kode trayek 7 datang setiap 4-6 menit tergantung pemberhentian <br />
• Kode trayek 10 datang setiap 30-40 menit tergantung pemberhentian <br />
• Kode trayek 6 datang setiap 4-12 menit tergantung pemberhentian <br />
• Kode trayek 2 datang setiap 3-7 menit tergantung pemberhentian <br />
• Kode trayek 13 datang setiap 17-20 menit tergantung pemberhentian <br />
<br />
Dari hasil waktu kedatangan di atas dapat disimpulkan bahwa pihak tije sudah cukup baik mengatur jadwalnya <br />
namun pada tryek 10 dan trayek 13 memiliki waktu kedatangan yang relatif cukup lama. Menurut hipotesa saya <br />
data ini berasal dari tahun 2021 sedangkan pihak tije sudah menganalisis data yang terbaru yang menyebabkan bus <br />
pada trayek tersebut datang lebih lama dikarenakkan menyesuaikan dengan jumlah penumpang terbaru <br />
<br />
Selanjutnya terdapat Moda tije yang paling jarang digunakan oleh para pengguna tije yaitu <br />
GR 4 dengan total hanya 232 penggunaan total pada tahun 2021 serta disusul dengan kode trayek <br />
lainya berupa GR5, 6F, 6Q, GR3, 12A, JAK.10B, GR2, JAK 10B, dan 2P merupakan peringkat paling rendah <br />
dibanding dengan trayek yang lain. Kebanyakan jenis transportasinya berasal dari angkutan umum integrasi. <br />
Grafis dibwahnya merupakan grafis rata rata penggunaan terendah pada transportasi tije yang tidak jauh <br/>
berbeda dengan hasil total keseluruhanya. <br />
Menurut hipotesa saya kurangnya penggunaan moda tije yang rendah diakibatkan oleh beberapa faktor <br />
seperti kurangnya strategis tempat pemberhentian, kurangnya informasi tetang moda transportasi tesebut, <br />
serta terdapat altenatif lain yang mungkin lebih nyaman oleh karna itu moda tije tersebut <br />
relatif lebih kecil penggunaanya. <br />
<br />

Analisis selanjutnya yang saya ingin lakukan yaitu tentang time series penggunaanya tiap bulan serta distribusi <br />
jenis moda transportasi tije apa saja yang selalu digunakan oleh pelanggan tije untuk grafisnya dapat dilihat <br />
sebagai berikut <br />
![Screenshot 2023-09-12 190108](https://github.com/Krioha/Tije/assets/93811161/11b1a507-1f2a-4c20-83bc-7bd05fe3750d) <br />
yang pertama merupakan grafis time series total pengguna tiap bulanya, dari bulan 1 sampai bulan 6 relatif terjadi <br />
peningkatan jumlah pelanggan tije namun pada bulan 7 dan 8 terjadi penurunan yang signifikan hingga hampir 2x <br />
lipat dari bulan sebelumnya. namun pada bulan selanjut terjadi lagi peningkatan yang drastis hingga  <br />
puncaknya pada bulan 11 yang memiliki total pelanggan sebesar 12,418,444 merupakan total <br />
tertinggi dari keseluruhan pengguna perbulanya <br />
menurut hipotesa saya mengapa terjadi penurunan pada bulan 7,8 mungkin dikarenakan terdapat libur semester yang <br />
terjadi pada bulan itu sehingga banyak mahasiswa yang biasanya naik tije namun dikarenakan libur maka mereka tidak <br />
menaiki tije pada bulan tersebut. <br />
<br />

Selanjutnya terdapat distribusi jenis tije yang digunakan keseluruhanya yang terbagi kedalam tiga kategori jenis <br />
yaitu BRT, Microtrans, serta angkutan umun integrasi. Awalnya saya berifikir akan terjadi perbedaaan yang <br />
cukup jauh antara BRT dengan moda transportasi lainya dikarenakan penggunaan tertinggi semuanya  <br />
berjenis BRT namun pemikiran awal saya keliru ternyata moda transportasi lainya tidak berbeda jauh <br />
dengan brt seperti microtrans yang hanya memiliki perbedaan 8,430,943 pelanggan dibanding BRT. <br />
Namun Angkutan Umum integrasi memiliki total keseluruhan yang paling sedikit dengan total 11,281,206. <br />
Agkutan umum integrasi memang banyak sekali dalam urutan paling rendah total penggunaanya <br />
sehingga menurut saya untuk moda jenis ini <br />
dapat diberikan pengembangan lagi agar lebih banyak pengguna yang menaiki moda tersebut. <br />
<br />

Analisis terakhir yang saya lakukan merupakan lokasi yang paling banyak didatangi oleh para pengguna moda <br />
transportasi tije dapat dilihat pada grafik dibawah <br />
![Screenshot 2023-09-12 193629](https://github.com/Krioha/Tije/assets/93811161/d2387c05-c1d4-4c29-b972-11836abf5b5f) <br />

