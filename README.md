Data yang digunakan pada proyek visualisasi ini tertera pada folder data. 

Data yang digunakan pada visualisasi merupakan data sekunder yang diperoleh dari publikasi BPS “Indikator Tujuan Pembangunan Berkelanjutan Indonesia 2020”, publikasi BPS “Indikator Tujuan Pembangunan Berkelanjutan Indonesia 2021”, sdgs.bappenas.go.id, dan katadata.co.id. Berikut penjelasan mengenai variabel-variabel yang akan digunakan untuk menyusun visualisasi.
1.	Persentase penduduk yang hidup di bawah garis kemiskinan, menurut provinsi, nasional, jenis kelamin, jenis kelamin kepala rumah tangga, kelompok umur, daerah tempat tenggal, dan status disabilitas.
Persentase penduduk yang hidup di bawah garis kemiskinan nasional adalah banyaknya penduduk yang berada di bawah garis kemiskinan nasional dibagi dengan jumlah penduduk pada periode waktu yang sama dinyatakan dalam satuan persen (%).
3.	Prevalensi ketidakcukupan konsumsi pangan.
Merupakan estimasi proporsi dari suatu populasi tertentu, dimana konsumsi energi biasanya sehari-hari dari makanan tidak cukup untuk memenuhi tingkat energi yang dibutuhkan untuk hidup normal, aktif dan sehat, yang dinyatakan dalam bentuk persentase. 
3.	Unmet Need Pelayanan Kesehatan.
Merupakan perbandingan antara banyaknya penduduk yang memiliki keluhan kesehatan dan terganggu aktifitasnya namun tidak berobat jalan dan jumlah penduduk, dinyatakan dalam satuan persen (%).
4.	Total Fertility Rate (TFR).
TFR dihitung dengan banyaknya kelahiran dari perempuan umur 15-49 tahun selama periode tertentu dibagi jumlah perempuan umur 15-49 tahun pada periode yang sama.
5.	Cakupan Jaminan Kesehatan Nasional.
Cakupan Jaminan Kesehatan Nasional (JKN) adalah perbandingan banyaknya penduduk yang mendapatkan perlindungan kesejahteraan dengan jumlah seluruh penduduk dan dinyatakan dalam satuan persen (%).
6.	Kepadatan dan Distribusi Tenaga Kesehatan.
Merupakan kepadatan tenaga kesehatan disuatu wilayah dapat digunakan rasio tenaga kesehatan per 1.000 penduduk.


Menurut Charu C. Aggarwal, tahapan preprocessing data merupakan tahapan penting dalam proses data mining. Proses data cleaning merupakan proses yang sangat penting untuk menangani kesalahan yang sering terjadi akibat data yang tidak lengkap akibat proses pengumpulan data yang kurang teliti Tahapan yang dilakukan pada data cleaning diantaranya menangani missing values, menangani hasil entry data yang salah, dan melakukan scaling dan normalisasi.


Kemudian, pada tahapan clustering terlebih dahulu dilakukan standardisasi data. Kemudian, setelah dilakukan standardisasi maka dilakukan pemilihan metode jarak yang akan digunakan. Metode jarak yang digunakan merupakan metode dengan nilai cophenetic yang paling tinggi. Klasterisasi dilakukan dengan menggunakan hierarchical clustering dengan metode jarak terpilih.


Selanjutnya, metode analisis yang digunakan adalah analisis deskriptif yaitu statistik yang digunakan untuk menganalisis data dengan cara mendeskripsikan atau menggambarkan data yang telah terkumpul sebagaimana adanya tanpa bermaksud membuat kesimpulan yang berlaku untuk umum atau generalisasi. Visualisasi yang akan ditampilkan adalah sebagai berikut.
1.	Persentase penduduk yang hidup di bawah garis kemiskinan menurut provinsi, nasional, jenis kelamin, jenis kelamin kepala rumah tangga, kelompok umur, daerah tempat tinggal, dan status disabilitas.
2.	Distribusi penduduk yang hidup di bawah garis kemiskinan tahun 2015-2020.
3.	Prevalensi ketidakcukupan pangan tahun 2020.
4.	Unmet need pelayanan kesehatan, TFR, cakupan jaminan kesehatan nasional, dan kepadatan dan distribusi tenaga kesehatan.
5.	Visualisasi hasil klasterisasi dari indikator tujuan 1, tujuan 2, dan tujuan 3.

Hasil visualisasi dapat diakses pada link berikut

SDGs Goal 1: Tanpa Kemiskinan
https://public.tableau.com/views/SDGsGoal1TanpaKemiskinan/Dashboard3?:language=en-US&:display_count=n&:origin=viz_share_link

SDGs Goal 1 : Persebaran Penduduk yang Hidup di Bawah Garis Kemiskinan
https://public.tableau.com/views/SDGs1PersebaranPendudukyangHidupdiBawahGarisKemiskinan/Dashboard2?:language=en-US&:display_count=n&:origin=viz_share_link

SDGs Goal 2: Tanpa Kelaparan
https://public.tableau.com/views/SDGsGoal2TanpaKelaparan/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

SDGs Goal 3 :Kehidupan Sehat dan Sejahtera
https://public.tableau.com/views/SDGsGoal3KesehatanBerkualitas/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

Hasil Klasterisasi
https://public.tableau.com/views/KlasteringPilarSosialSDGsyangTerdampakTinggiCOVID-19/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link

Kesimpulan :
Berdasarkan visualisasi tiga tujuan SDGs yang terdampak tinggi Covid-19, indikator-indikator pada ketiga tujuan pilar sosial cenderung mengalami penurunan dari target SDGs. Salah satu penyebab penurunan kualitas dari ketiga pilar sosial tersebut adalah adanya pandemic Covid-19.
Hasil klastering berhasil mengelompokan provinsi-provinsi di Indonesia menjadi klaster dengan pilar sosial yang rendah, sedang, dan tinggi. Dari hasil analisis ini diharapkan pemerintah dapat memberikan perhatian lebih kepada klaster dengan pilar sosial yang rendah serta terus mendukung kebijakan maupun program yang mendorong SDGs di semua provinsi di Indonesia.
