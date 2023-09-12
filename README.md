# Tije EDA

![image](https://github.com/Krioha/Tije/assets/93811161/0161b400-cfbf-4c31-9e18-11861a40014f)

# Intoduction
Semua berwal ketika saya pergi ke Jakarta dengan moda transportasi umum untuk mencapai tempat tujuan saya dan salah satu moda <br />
Transportasi yang saya gunakan untuk mencapai tempat tujuan saya adalah Tije atau yang lebih dikenal sebagai Transjakarta <br />
Pertama kali saya gunakan tije untuk mencapai Rasunan Said jadi saya menggunakan Tije dengan kode trayek 4D dan 6M <br />
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
• Kode trayek 1 datang setiap 2-5 menit tergantung pemberhentian
• Kode trayek 9 datang setiap 3-10 menit tergantung pemberhentian
