# Analisis Pembatalan Pemesanan Hotel dan Faktor-Faktor Lain yang Mempengaruhi Pendapatan Tahunan hotel


## Daftar Isi

1. [Latar Belakang](#Latar-Belakang)
2. [Masalah](#Masalah)
3. [Memahami Dataset](#Memahami-Dataset)
4. [Pembersihan Data](#Pembersihan-Data)
5. [Eksplorasi Awal](#Eksplorasi-Awa)
6. [Analisis Spesifik](#Analisis-Spesifik)
7. [Wawasan dan Narasi Keseluruhan](#Wawasan-dan-Narasi-Keseluruhan)
8. [Kesimpulan dan Rekomendasi](#Kesimpulan-dan-Rekomendasi)
9. [Team](#Team)
10. [Ucapan Terima Kasih](#Ucapan-Terima-Kasih)

## Latar Belakang

Hotel adalah sebuah bangunan, atau perusahaan yang akan menyediakan sebuah jasa. Umumnya jasa yang ditawarkan oleh hotel berupa penginapan. Akan tetapi, masih banyak lagi jasa yang bisa ditawarkan oleh suatu hotel. Seperti menyediakan berbagai makanan dan minuman, membuat resto atau kafe, dapat digunakan untuk menggelar sebuah acara, dan lain sebagainya. Seluruh fasilitas yang ada di dalam hotel akan diperuntukan bagi pengunjungnya. Hotel adalah tempat yang sering digunakan untuk seseorang menginap atau beristirahat. Seperti untuk para wisatawan di sebuah daerah tempat wisata.

![gambar](https://hackmd.io/_uploads/SyKSyTLUkx.jpg)


Industri perhotelan merupakan salah satu sektor utama dalam perekonomian global, berperan penting dalam menarik wisatawan dan mendukung berbagai kegiatan bisnis. Dalam beberapa tahun terakhir, dengan meningkatnya persaingan serta perubahan perilaku konsumen, manajemen hotel menghadapi tantangan untuk mempertahankan pendapatan yang stabil dan meminimalkan kerugian akibat pembatalan pemesanan. Pembatalan pemesanan hotel, yang sering kali terjadi karena perubahan rencana tamu, kendala finansial, atau kondisi eksternal seperti cuaca buruk atau pandemi, dapat berdampak signifikan pada pendapatan tahunan hotel.

Penelitian tentang pembatalan pemesanan hotel menjadi semakin relevan dalam membantu manajemen hotel mengidentifikasi faktor-faktor yang mempengaruhi tingkat pembatalan. Faktor-faktor ini mencakup profil pelanggan, metode pemesanan, musim pemesanan, jenis kamar yang dipesan, hingga kebijakan pembatalan yang diterapkan oleh hotel. Dengan memahami pola pembatalan ini, hotel dapat mengembangkan strategi yang lebih efektif untuk mengurangi dampaknya, seperti kebijakan pembayaran di muka, penawaran diskon untuk pemesanan yang tidak dapat dibatalkan, atau optimalisasi alokasi kamar.

Selain itu, faktor lain yang memengaruhi pendapatan tahunan hotel mencakup tingkat hunian kamar, strategi harga, loyalitas pelanggan, serta tingkat pelayanan yang diberikan. Teknologi modern seperti analitik data dan pembelajaran mesin dapat dimanfaatkan untuk menganalisis data pemesanan dan memberikan prediksi yang lebih akurat terkait tren pembatalan dan pendapatan.

Dalam konteks ini, penelitian tentang analisis pembatalan pemesanan dan faktor-faktor yang mempengaruhi pendapatan tahunan hotel bertujuan untuk memberikan wawasan yang lebih dalam kepada manajemen hotel. Dengan demikian, mereka dapat mengambil keputusan yang lebih tepat untuk meningkatkan efisiensi operasional dan memaksimalkan pendapatan tahunan.


## Masalah

![Cancelled stock vector_ Illustration of caution, communications - 5427911](https://hackmd.io/_uploads/rJ-dZ68Ike.jpg)


Dalam beberapa tahun terakhir, City Hotel dan Resort Hotel telah mengalami peningkatan yang signifikan dalam tingkat pembatalan. Akibatnya, kedua hotel tersebut saat ini menghadapi berbagai tantangan, seperti berkurangnya pendapatan dan kamar hotel yang kurang termanfaatkan. Oleh karena itu, prioritas utama bagi kedua hotel adalah mengurangi tingkat pembatalan, yang akan meningkatkan efisiensi mereka dalam menghasilkan pendapatan. Laporan ini berfokus pada analisis pembatalan pemesanan hotel dan faktor-faktor lain yang tidak secara langsung berdampak pada bisnis dan pendapatan tahunan mereka.

## Memahami Dataset
Dataset ini juga mencakup variabel tambahan seperti asal tamu, jumlah tamu dewasa dan anak-anak, metode pembayaran, preferensi kamar, serta ulasan tamu terkait pengalaman mereka. Analisis lebih lanjut dapat memberikan wawasan tentang perilaku pelanggan, seperti preferensi kamar tertentu berdasarkan asal geografis, pengaruh metode pembayaran terhadap pembatalan, atau pola loyalitas pelanggan. Selain itu, identifikasi tren musiman dapat membantu hotel dalam merancang penawaran khusus pada periode tertentu, sementara pemahaman mendalam tentang penyebab pembatalan dapat mendorong implementasi kebijakan yang lebih efektif untuk menguranginya. Wawasan ini akan menjadi dasar yang kuat bagi pengambilan keputusan strategis yang berorientasi pada peningkatan pengalaman pelanggan dan profitabilitas jangka panjang.

link dataset : [download](https://www.dropbox.com/sh/qwdaldzkp8yrqwj/AADTj_WQcuKA0bsEeCKU__98a?dl=1) 

Dataset akan ditinjau untuk memahami strukturnya:
1. Berapa banyak kolom dan baris yang ada?
2. Apa saja tipe data pada masing-masing kolom?
3. Adakah nilai yang hilang, outlier, atau data yang tidak konsisten?

Proses ini akan membantu menentukan langkah-langkah pembersihan dan eksplorasi data berikutnya.

## Pembersihan Data
Dataset akan dibersihkan dengan langkah-langkah berikut:

1. Mengisi atau menghapus nilai yang hilang berdasarkan konteks.
2. Menstandarisasi format tanggal, teks, dan nilai kategori.

Setelah data bersih, dataset akan diringkas untuk memberikan gambaran umum, termasuk deskripsi statistik seperti rata-rata, nilai maksimum, dan minimum untuk variabel kunci.

## Eksplorasi Awal
Pada tahap ini, pola umum dalam data akan dianalisis:

1. Tren Pemesanan: Jumlah pemesanan berdasarkan bulan dan tahun.
2. Distribusi Tipe Pelanggan: Proporsi pelanggan bisnis vs liburan.
3. Pembatalan Reservasi: Tingkat pembatalan secara keseluruhan dan faktor-faktor awal yang mungkin mempengaruhinya.

Visualisasi yang digunakan mencakup diagram batang, grafik garis, dan pie chart.

## Analisis Spesifik
Analisis akan difokuskan pada poin-poin berikut:

### 1. Pembatalan Reservasi:
![download (2)](https://hackmd.io/_uploads/Sydy16I81x.png)

Faktor utama pembatalan (durasi menginap, metode pemesanan, atau harga kamar). Dari hasil analisis dan visualisasi yang tersedia, berikut adalah poin-poin penting untuk menjawab pertanyaan terkait faktor utama pembatalan:

* Deposit Type

Faktor jenis deposit yang diminta oleh penginapan memainkan peran penting dalam mempengaruhi keputusan pembatalan. Deposit mencerminkan komitmen finansial pelanggan terhadap reservasi mereka dan dapat dibagi menjadi tiga kategori utama: "No Deposit," "Non Refundable," dan "Refundable."


| Deposit Type | Status Pembatalan | Jumlah |
| ------------ | ----------------- | ------ |
| No Deposit   | Not Canceled      | 74,947 |
| No Deposit   | Canceled          | 29,694 |
| Non Refund   | Canceled          | 14,494 |
| Non Refund   | Not Canceled      | 93     |
| Refundable   | Not Canceled      | 126    |
| Refundable   | Canceled          | 36     |

Dari tabel di atas, terlihat bahwa:
* No Deposit: Sebagian besar reservasi menggunakan jenis deposit ini, dengan proporsi pembatalan yang lebih rendah dibandingkan reservasi yang tidak dibatalkan.
* Non Refundable: Meskipun menawarkan tarif lebih rendah, reservasi dengan jenis deposit ini memiliki tingkat pembatalan yang sangat tinggi, menunjukkan bahwa kebijakan pengembalian dana berpengaruh besar pada keputusan pelanggan.
* Refundable: Jenis deposit ini memiliki jumlah reservasi paling sedikit, namun tetap memiliki risiko pembatalan yang tidak dapat diabaikan.

### 2. Durasi Menginap: 
![image](https://hackmd.io/_uploads/Bk3KNALUJe.png)
Segmen dengan Durasi Menginap Terpanjang:
* Offline TA/TO memiliki durasi menginap rata-rata tertinggi, yaitu 3.90 malam. Ini menunjukkan bahwa tamu yang memesan melalui agen perjalanan offline cenderung menginap lebih lama, mungkin karena paket perjalanan yang lebih komprehensif atau kebutuhan untuk akomodasi yang lebih lama.
* Aviation dan Online TA juga menunjukkan durasi menginap yang cukup tinggi, masing-masing 3.61 malam dan 3.57 malam, yang menunjukkan bahwa tamu dari segmen ini juga cenderung menginap lebih lama.

Segmen dengan Durasi Menginap Terpendek:

* Undefined memiliki durasi menginap rata-rata terendah, yaitu 1.50 malam, Undefined" menunjukkan bahwa ada tamu yang tidak terklasifikasi dengan baik, yang bisa disebabkan oleh permintaan anonimitas atau data yang tidak lengkap.
* Complementary juga menunjukkan durasi menginap yang pendek, yaitu 1.65 malam, yang mungkin mencerminkan tamu yang menginap hanya untuk tujuan tertentu, seperti acara singkat atau kunjungan.

Segmen Lainnya:
* Direct dan Groups memiliki durasi menginap rata-rata yang cukup baik, masing-masing 3.21 malam dan 2.99 malam. Ini menunjukkan bahwa tamu yang memesan langsung atau dalam grup juga cenderung menginap lebih lama dibandingkan dengan segmen yang lebih pendek.

**Kesimpulan**:
Data ini memberikan wawasan penting tentang perilaku menginap tamu berdasarkan segmen pasar. Manajemen hotel dapat menggunakan informasi ini untuk merancang penawaran yang lebih sesuai dengan kebutuhan masing-masing segmen, seperti paket untuk tamu yang menginap lebih lama atau promosi untuk menarik tamu dari segmen dengan durasi menginap yang lebih pendek. Selain itu, pemahaman tentang durasi menginap rata-rata dapat membantu dalam perencanaan kapasitas dan pengelolaan sumber daya hotel.

### 3. Lead Time 
Lead time adalah perbedaan hari antara tanggal pemesanan dengan tanggal yang dijadwalkan untuk customer untuk tiba di hotel

![WhatsApp Image 2025-01-04 at 21.44.09_05d2275c](https://hackmd.io/_uploads/SyUsn68IJx.jpg)

Berdasarkan histogram yang menunjukkan korelasi pembatalan reservasi dengan lead time (waktu antara pemesanan dan tanggal kedatangan), berikut analisisnya:

* Lead Time Pendek (0-100 hari): Jumlah pembatalan sangat tinggi pada rentang lead time yang pendek. Ini mengindikasikan bahwa semakin dekat waktu pemesanan dengan tanggal kedatangan, semakin besar kemungkinan pembatalan terjadi. Puncak pembatalan berada pada lead time di bawah 30 hari.
* Lead Time Menengah (100-300 hari): Pembatalan mulai menurun secara bertahap. Namun, jumlah pembatalan masih signifikan di rentang ini, menunjukkan bahwa pelanggan yang memesan jauh hari sebelumnya tetap memiliki kemungkinan pembatalan, meskipun lebih rendah dibandingkan dengan lead time yang lebih pendek.
* Lead Time Panjang (lebih dari 300 hari): Pembatalan sangat jarang terjadi ketika lead time lebih dari 300 hari, menandakan bahwa reservasi yang dilakukan jauh-jauh hari biasanya lebih stabil dan cenderung tidak dibatalkan.

Kesimpulan
* Semakin pendek lead time, semakin tinggi risiko pembatalan reservasi.
* Strategi pengelolaan risiko dapat mencakup penerapan kebijakan deposit atau diskon non-refundable untuk pemesanan dengan lead time singkat guna meningkatkan komitmen pelanggan.
* Program loyalitas atau penawaran fleksibel dapat diberikan untuk pelanggan yang memesan dengan lead time panjang untuk memastikan keberlanjutan reservasi mereka.

### 4. Korelasi Negara
![image](https://hackmd.io/_uploads/BJWVQAI8Jx.png)

Perilaku pelanggan berdasarkan asal geografis atau jenis kamar yang dipesan.

- Segmentasi Pelanggan Berdasarkan Asal Geografis

| TOP 10 Negara | Jumlah Pengunjung |
| ------------- | ----------------- |
| PRT           | 48590             |
| GBR           | 12129             |
| FRA           | 10415             |
| ESP           | 8568              |
| DEU           | 7287              |
| ITA           | 3766              |
| IRL           | 3375              |
| BEL           | 2342              |
| BRA           | 2224              |
| NLD           | 2104              |

Top 10 Negara Asal Pelanggan menunjukkan bahwa sebagian besar pelanggan berasal dari Portugal (PRT) dengan jumlah yang jauh lebih tinggi dibandingkan negara lainnya (48.590 pelanggan). Negara-negara berikutnya adalah Inggris (GBR), Prancis (FRA), Spanyol (ESP), dan Jerman (DEU). Ini menunjukkan bahwa sebagian besar pelanggan berasal dari Eropa, mencerminkan dominasi pelanggan regional. Negara dengan jumlah pelanggan yang lebih rendah, seperti Belgia (BEL) dan Belanda (NLD), mungkin menjadi peluang untuk meningkatkan strategi pemasaran agar menarik lebih banyak pelanggan dari wilayah ini.

- Segmentasi Berdasarkan Tipe Kamar yang Dipesan

Harga rata-rata per tipe kamar menunjukkan bahwa tipe kamar dengan ID 15 memiliki harga rata-rata 0, mungkin karena tipe kamar ini belum digunakan atau merupakan data yang tidak valid. Ini perlu diperiksa lebih lanjut. Tipe kamar dengan harga rata-rata tertinggi adalah tipe 7 (188.22) dan 6 (175.99), menunjukkan bahwa kamar-kamar ini mungkin termasuk dalam kategori premium atau mewah. Tipe kamar 0 dan 1 memiliki harga rata-rata yang relatif rendah (~90), menunjukkan bahwa kamar ini mungkin termasuk kategori standar atau ekonomi. Tipe kamar 2, 3, dan 4 memiliki harga rata-rata dalam kisaran 120–160, kemungkinan merupakan kamar kelas menengah yang cukup populer di kalangan pelanggan dengan anggaran lebih tinggi.

### 5. Korelasi Pemesanan
![image](https://hackmd.io/_uploads/BkNymAULke.png)
Distribution channel merujuk pada cara atau saluran di mana pemesanan (booking) dilakukan untuk layanan seperti akomodasi, tur, atau perjalanan. Dalam konteks ini, dua istilah yang disebutkan, yaitu "TA" dan "TO", memiliki arti "Travel Agents" dan "Tour Operator"

Saluran Distribusi:
* TA/TO (Travel Agent/Tour Operator) memiliki jumlah transaksi tertinggi baik yang tidak dibatalkan (57718) maupun yang dibatalkan (40152). Ini menunjukkan bahwa saluran ini sangat aktif, tetapi juga memiliki tingkat pembatalan yang signifikan.
* Direct juga menunjukkan angka yang cukup tinggi, dengan 12088 transaksi tidak dibatalkan dan 2557 dibatalkan, menunjukkan bahwa banyak pelanggan memilih untuk memesan langsung.
* Corporate memiliki jumlah transaksi yang lebih rendah dibandingkan dengan TA/TO dan Direct, tetapi masih menunjukkan proporsi yang signifikan.
* GDS memiliki jumlah transaksi yang paling rendah, baik yang tidak dibatalkan maupun yang dibatalkan, menunjukkan bahwa saluran ini mungkin kurang populer atau digunakan dalam konteks ini.
* Undefined menunjukkan sangat sedikit transaksi, yang mungkin menunjukkan data yang tidak lengkap atau tidak terklasifikasi.

Tingkat Pembatalan:
* Dari data, terlihat bahwa saluran TA/TO memiliki jumlah pembatalan yang tinggi, yang bisa menjadi perhatian bagi manajemen untuk memahami alasan di balik tingginya angka pembatalan ini.
* Saluran GDS memiliki tingkat pembatalan yang sangat rendah, yang mungkin menunjukkan kepuasan pelanggan yang lebih tinggi atau proses pemesanan yang lebih stabil.

Kesimpulan:
Data ini memberikan wawasan penting tentang perilaku pelanggan berdasarkan saluran distribusi dan status pembatalan. Manajemen dapat menggunakan informasi ini untuk mengidentifikasi saluran yang paling efektif, memahami pola pembatalan, dan merumuskan strategi untuk meningkatkan kepuasan pelanggan serta mengurangi tingkat pembatalan.

### 6. Korelasi dengan previous_cancellations
Previous cancellation adalah istilah yang biasanya merujuk pada catatan atau riwayat pembatalan reservasi sebelumnya yang dilakukan oleh pelanggan. Dalam konteks pengelolaan akomodasi atau reservasi, data mengenai previous cancellation sering digunakan untuk menganalisis perilaku pelanggan, seperti seberapa sering mereka membatalkan reservasi dan alasan di balik pembatalan tersebut. Informasi ini dapat membantu manajemen untuk mengambil keputusan strategis, seperti menerapkan kebijakan pembatalan yang lebih fleksibel, memberikan insentif bagi pelanggan yang jarang membatalkan, atau mengenali pola risiko terkait pembatalan untuk meminimalkan kerugian. Selain itu, variabel ini sering digunakan dalam model prediksi untuk mengidentifikasi kemungkinan pelanggan membatalkan reservasi di masa depan.

| **Previous Cancellations** | **Count** |
| -------------------------- | --------- |
| 0                          | 38,282    |
| 1                          | 5,714     |
| 24                         | 48        |
| 2                          | 38        |
| 26                         | 26        |
| 25                         | 25        |
| 3                          | 20        |
| 19                         | 19        |
| 14                         | 14        |
| 13                         | 11        |
| 11                         | 10        |
| 4                          | 7         |
| 6                          | 7         |
| 5                          | 2         |
| 21                         | 1         |

**Analisis:**
Tingkat Pembatalan Sebelumnya:

- 0 Pembatalan Sebelumnya: Dengan 38,282 pemesanan, sebagian besar pelanggan tidak memiliki riwayat pembatalan. Ini menunjukkan bahwa banyak tamu adalah pelanggan baru atau memiliki tingkat kepuasan yang tinggi.
- 1 Pembatalan Sebelumnya: Terdapat 5,714 pemesanan, menunjukkan bahwa sebagian kecil pelanggan memiliki satu riwayat pembatalan. Ini bisa menunjukkan bahwa mereka mungkin mengalami masalah di masa lalu tetapi masih memilih untuk memesan lagi.
- 2 atau lebih Pembatalan Sebelumnya: Jumlah pemesanan dengan dua atau lebih pembatalan sebelumnya sangat rendah (misalnya, hanya 38 pemesanan untuk dua pembatalan sebelumnya). Ini menunjukkan bahwa pelanggan dengan riwayat pembatalan yang lebih tinggi cenderung lebih sedikit.

**Pola Pembatalan:**
Data menunjukkan bahwa semakin banyak pembatalan sebelumnya, semakin sedikit jumlah pemesanan yang dilakukan. Hal ini bisa menunjukkan bahwa pelanggan yang memiliki riwayat pembatalan yang tinggi mungkin lebih cenderung untuk tidak melakukan pemesanan di masa depan, atau mereka mungkin lebih berhati-hati dalam melakukan pemesanan.

**Kesimpulan :**
Memahami pola pembatalan dapat membantu dalam perencanaan kapasitas dan pengelolaan sumber daya hotel. Dengan memahami riwayat pembatalan pelanggan, manajemen dapat mengambil langkah-langkah proaktif untuk mengurangi tingkat pembatalan dan meningkatkan loyalitas pelanggan.

### 7. Rekomendasi Strategi

- Geografis:
![download](https://hackmd.io/_uploads/H1LVT0UIyg.png)

Tingkatkan promosi di negara-negara dengan jumlah pelanggan yang rendah namun berpotensi, seperti Belgia (BEL) dan Belanda (NLD). Fokus pada mempertahankan dan meningkatkan loyalitas pelanggan dari Portugal, Inggris, dan Prancis, yang merupakan pasar utama.

| **Country** | **Count** |
| ----------- | --------- |
| PRT         | 21,071    |
| GBR         | 9,676     |
| FRA         | 8,481     |
| ESP         | 6,391     |
| DEU         | 6,069     |
| IRL         | 2,543     |
| ITA         | 2,433     |
| BEL         | 1,868     |
| NLD         | 1,717     |
| USA         | 1,596     |

- Jenis Kamar:
![download (1)](https://hackmd.io/_uploads/HJpYp0IIke.png)

**Berdasarkan data Average Daily Rate (ADR) dan Total Reservation untuk masing-masing tipe kamar:**

a. Tipe Kamar A merupakan tipe yang paling populer dengan jumlah reservasi tertinggi mencapai 52,364, meskipun memiliki nilai ADR yang relatif rendah sebesar 89.16. Hal ini menunjukkan bahwa tipe kamar ini mungkin lebih diminati karena harganya yang lebih terjangkau.

b. Tipe Kamar H memiliki ADR tertinggi sebesar 180.87, namun jumlah reservasinya relatif rendah, hanya 356. Hal ini menunjukkan bahwa kamar ini kemungkinan lebih eksklusif dan menyasar segmen pasar premium.

c. Tipe Kamar G dan F juga memiliki ADR yang tinggi, masing-masing sebesar 169.24 dan 159.24, dengan total reservasi yang cukup signifikan, yaitu 1,331 dan 2,017. Ini menandakan bahwa kamar-kamar ini berada di segmen menengah-atas yang masih cukup diminati.

d. Tipe Kamar L memiliki jumlah reservasi paling sedikit, hanya 4, dengan ADR sebesar 151.00. Hal ini menunjukkan bahwa tipe kamar ini mungkin jarang ditawarkan atau tidak banyak tersedia.

e. Kamar dengan ADR menengah, seperti Tipe D (116.37) dan Tipe E (119.06), juga menunjukkan performa yang baik dalam hal total reservasi, masing-masing mencapai 13,099 dan 4,621. Ini menandakan keseimbangan antara harga yang wajar dan daya tarik kamar.

| **Reserved Room Type** | **ADR**    | **Total Reservation** |
| ---------------------- | ---------- | --------------------- |
| A                      | 89.156889  | 52,364                |
| B                      | 87.425000  | 750                   |
| C                      | 153.020609 | 624                   |
| D                      | 116.371997 | 13,099                |
| E                      | 119.067942 | 4,621                 |
| F                      | 159.242142 | 2,017                 |
| G                      | 169.237483 | 1,331                 |
| H                      | 180.870112 | 356                   |
| L                      | 151.000000 | 4                     |


## Wawasan dan Narasi Keseluruhan
1. Pembatalan Reservasi
* Faktor Deposit: Jenis deposit yang diminta oleh penginapan sangat mempengaruhi keputusan pembatalan.
* No Deposit: Memiliki jumlah reservasi tertinggi dan proporsi pembatalan yang lebih rendah.
* Non Refundable: Meskipun tarif lebih rendah, tingkat pembatalan sangat tinggi, menunjukkan pengaruh besar dari kebijakan pengembalian dana.
* Refundable: Meskipun jumlah reservasi paling sedikit, tetap ada risiko pembatalan yang signifikan.

2. Durasi Menginap
* Durasi Terpanjang: Tamu yang memesan melalui agen perjalanan offline cenderung menginap lebih lama (3.90 malam), diikuti oleh Aviation dan Online TA.
* Durasi Terpendek: Tamu dengan durasi menginap terpendek (1.50 malam) adalah dari segmen Undefined, yang menunjukkan adanya data yang tidak lengkap. Complementary juga menunjukkan durasi pendek (1.65 malam).
* Segmen Lainnya: Tamu yang memesan langsung atau dalam grup memiliki durasi menginap yang lebih baik dibandingkan dengan segmen yang lebih pendek.

3. Lead Time
* Lead Time Pendek (0-100 hari): Tingkat pembatalan sangat tinggi, terutama di bawah 30 hari.
* Lead Time Menengah (100-300 hari): Pembatalan mulai menurun, tetapi masih signifikan.
* Lead Time Panjang (>300 hari): Pembatalan jarang terjadi, menunjukkan stabilitas reservasi.

4. Korelasi Negara
* Asal Geografis: Sebagian besar pelanggan berasal dari Portugal, diikuti oleh Inggris, Prancis, dan Spanyol. Negara dengan jumlah pelanggan rendah seperti Belgia dan Belanda menunjukkan potensi untuk strategi pemasaran yang lebih baik.
* Tipe Kamar: Tipe kamar premium (ID 7 dan 6) memiliki harga rata-rata tertinggi, sedangkan tipe kamar standar memiliki harga yang lebih terjangkau.

5. Korelasi Pemesanan
Saluran Distribusi: TA/TO memiliki jumlah transaksi tertinggi, tetapi juga tingkat pembatalan yang signifikan. Saluran GDS menunjukkan tingkat pembatalan yang rendah, mungkin mencerminkan kepuasan pelanggan yang lebih tinggi.
6. Korelasi dengan Previous Cancellations
Riwayat Pembatalan: Sebagian besar pelanggan tidak memiliki riwayat pembatalan, menunjukkan kepuasan tinggi. Namun, semakin banyak pembatalan sebelumnya, semakin sedikit jumlah pemesanan yang dilakukan.
7. Rekomendasi Strategi
* Promosi Geografis: Tingkatkan promosi di negara-negara dengan potensi rendah seperti Belgia dan Belanda, sambil mempertahankan loyalitas pelanggan dari negara-negara utama seperti Portugal dan Inggris.
* Tipe Kamar: Fokus pada tipe kamar yang paling populer dengan harga terjangkau, sambil mempertimbangkan strategi untuk kamar premium yang memiliki permintaan lebih rendah.

Kesimpulan
Data yang dianalisis memberikan wawasan mendalam tentang perilaku pelanggan dalam reservasi hotel. Manajemen hotel dapat menggunakan informasi ini untuk merancang strategi pemasaran yang lebih efektif, meningkatkan kepuasan pelanggan, dan mengurangi tingkat pembatalan. Dengan memahami faktor-faktor yang mempengaruhi pembatalan, manajemen dapat mengambil langkah-langkah proaktif untuk meningkatkan loyalitas pelanggan dan memaksimalkan pendapatan.

## Kesimpulan dan Rekomendasi 
Kesimpulan dari analisis data reservasi hotel menunjukkan bahwa jenis deposit berpengaruh signifikan terhadap pembatalan, dengan "No Deposit" memiliki tingkat pembatalan yang lebih rendah dibandingkan "Non Refundable." Tamu yang memesan melalui agen perjalanan offline cenderung menginap lebih lama, sementara lead time yang pendek meningkatkan risiko pembatalan. Sebagian besar pelanggan berasal dari Portugal, dan saluran distribusi TA/TO memiliki tingkat pembatalan yang tinggi.

Rekomendasi untuk manajemen hotel meliputi penawaran opsi deposit yang lebih fleksibel, pembuatan paket promosi untuk tamu yang menginap lebih lama, dan penerapan kebijakan ketat untuk pemesanan dengan lead time pendek. Selain itu, fokuskan pemasaran di negara-negara dengan potensi rendah seperti Belgia dan Belanda, serta tingkatkan kerjasama dengan saluran distribusi yang menunjukkan tingkat pembatalan rendah. Dengan langkah-langkah ini, manajemen dapat meningkatkan kepuasan pelanggan dan memaksimalkan pendapatan.

## Team 
**Nama dan NIM Anggota Kelompok :**
**Kelas : Analisis Big Data B**

Angga Rofiul Putra (202110370311421)
Muhammad Alif Nasrulloh (202110370311437)
Anisha Wulandari P (202110370311438)

## Ucapan Terima Kasih
Kepada Yth. Bapak Yuda Munarko
Dosen Pengajar Mata Kuliah Analisis Big Data

Dengan hormat,

Kami, segenap mahasiswa/i mata kuliah Analisis Big Data, ingin menyampaikan rasa terima kasih yang sebesar-besarnya atas bimbingan dan ilmu yang telah Bapak berikan selama perkuliahan ini.

Kami sangat menghargai dedikasi Bapak dalam memberikan materi dengan jelas, memotivasi kami untuk terus belajar, dan mendukung perkembangan pemahaman kami terhadap [Data Sains]. Kehangatan dan kesabaran yang Bapak tunjukkan telah menciptakan suasana belajar yang menyenangkan sekaligus penuh makna.

Semoga ilmu yang telah kami peroleh dapat bermanfaat bagi kami di masa depan. Kami juga mendoakan agar Bapak selalu diberikan kesehatan, kesuksesan, dan keberkahan dalam menjalankan tugas mulia ini.

Sekali lagi, terima kasih banyak atas segalanya.

Hormat kami,
Kelompok Kami
