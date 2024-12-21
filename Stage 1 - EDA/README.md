# EDA-Homecredit
Proyek ini mencakup statistik deskriptif, analisis univariat dan multivariat, serta insight bisnis untuk dataset Home Credit. Langkah-langkah utama meliputi identifikasi masalah kualitas data, visualisasi distribusi, analisis korelasi fitur, dan penarikan rekomendasi bisnis yang dapat diimplementasikan berdasarkan insight yang diperoleh.

[Dataset: Home Credit Default Risk](https://www.kaggle.com/competitions/home-credit-default-risk/data)

## 1. Distribusi Jumlah Kredit yang Diajukan
![0. Distribusi Jumlah Kredit yang Diajukan](https://github.com/hijirdella/EDA-Homecredit/blob/bd1d5234e6c158e3e27dc9651fdc0c21cfa86a28/BI%20Graph/0.%20Distribusi%20Jumlah%20Kredit%20yang%20Diajukan.png)
Insight: Sebagian besar nasabah mengajukan kredit di bawah 500 ribu

Hasil: Sebagian besar nasabah mengajukan kredit dalam jumlah relatif kecil (di bawah 500 ribu), sementara hanya sedikit nasabah yang mengajukan kredit di atas 1 juta.

Rekomendasi Bisnis: Fokuskan strategi produk kredit pada segmen nasabah yang mengajukan pinjaman kecil. Misalnya, tawarkan kredit mikro dengan bunga yang lebih kompetitif atau produk yang disesuaikan untuk segmen ini.


## 2. Hubungan Pendapatan Nasabah dan Jumlah Kredit yang Diajukan
![1. Hubungan Pendapatan Nasabah dan Jumlah Kredit yang Diajukan](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/1.%20Hubungan%20Pendapatan%20Nasabah%20dan%20Jumlah%20Kredit%20yang%20Diajukan.png)
Insight: Nasabah dengan pendapatan tinggi cenderung mengajukan kredit lebih besar
Hasil: Ada kecenderungan bahwa nasabah dengan pendapatan lebih tinggi mengajukan kredit lebih besar, meskipun beberapa nasabah dengan pendapatan rendah juga mengajukan kredit besar.

Rekomendasi Bisnis: Lakukan verifikasi pendapatan secara ketat untuk nasabah dengan pendapatan rendah yang mengajukan kredit besar, untuk menghindari risiko gagal bayar.

## 3. Distribusi Usia Nasabah
![2. Distribusi Usia Nasabah](https://github.com/hijirdella/EDA-Homecredit/blob/309ba6e9033ac43c48c74b15e6e020a80e260c26/BI%20Graph/2.%20Distribusi%20Usia%20Nasabah.png)
Insight: Sebagian besar nasabah berada di rentang usia 30-50 tahun

Hasil: Sebagian besar nasabah yang mengajukan kredit berada di rentang usia 30-50 tahun.

Rekomendasi Bisnis: Fokuskan pemasaran produk kredit pada segmen usia 30-50 tahun, misalnya untuk kredit perumahan atau kendaraan.

## 4. Hubungan Lama Bekerja (Tahun) dan Jumlah Kredit yang Diajukan
![3. Hubungan Lama Bekerja (Tahun) dan Jumlah Kredit yang Diajukan](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/3.%20Hubungan%20Lama%20Bekerja%20(Tahun)%20dan%20Jumlah%20Kredit%20yang%20Diajukan.png)

"Nasabah dengan riwayat kerja lebih lama cenderung mengajukan kredit lebih besar" tidak sepenuhnya tepat berdasarkan grafik ini. 

Insight: Nasabah dengan lama bekerja cenderung mengajukan jumlah kredit yang bervariasi, tanpa adanya pola yang jelas antara lama bekerja dan jumlah kredit yang diajukan.

Rekomendasi: Perlu analisis lebih lanjut untuk menemukan faktor-faktor lain (misalnya, pendapatan atau jabatan) yang mungkin memiliki hubungan lebih kuat dengan jumlah kredit yang diajukan. Penawaran kredit bisa difokuskan pada segmen nasabah dengan kriteria stabilitas pendapatan dan profil risiko, bukan hanya lama bekerja.

## 5. Analisis Perilaku Pembayaran Secara Keseluruhan:
![4. Distribution of Days Instalment vs Days Entry Payment](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/4.%20Distribution%20of%20Days%20Instalment%20vs%20Days%20Entry%20Payment.png)
Insight: Mayoritas nasabah cenderung membayar cicilan mereka tepat waktu atau bahkan lebih awal dari tanggal jatuh tempo. Hal ini menunjukkan bahwa nasabah memiliki perilaku keuangan yang baik dan bertanggung jawab.

Rekomendasi: Buat program loyalitas atau tawarkan insentif seperti pengurangan suku bunga bagi nasabah yang konsisten melakukan pembayaran lebih awal. Ini dapat mendorong nasabah untuk terus membayar tepat waktu dan memperkuat hubungan dengan nasabah.

## 6. Korelasi Antara Jumlah Cicilan dan Jumlah Pembayaran
![5. Distribution of Days Instalment vs Days Entry Payment](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/5.%20Amount%20Instalment%20vs%20Amount%20Payment.png)
Insight: Terdapat korelasi positif yang kuat antara jumlah cicilan yang dijadwalkan dengan jumlah pembayaran aktual. Namun, ada beberapa nasabah yang sering membayar di bawah jumlah cicilan yang dijadwalkan, yang mengindikasikan adanya potensi kesulitan keuangan.

Rekomendasi: Segmentasi nasabah berdasarkan perilaku pembayaran mereka. Lakukan komunikasi proaktif dan tawarkan solusi yang disesuaikan (misalnya, program refinancing atau fleksibilitas pembayaran) bagi nasabah yang mengalami kesulitan membayar. Langkah ini dapat membantu mencegah terjadinya gagal bayar dan menjaga portofolio kredit yang sehat.

## 7. Analisis Versi Cicilan vs Jumlah Cicilan
![6. Box Plot of Instalment Version vs Instalment Number](https://github.com/hijirdella/EDA-Homecredit/blob/cd34f9cd4389f666ba2bbf8d31e7b73124580ae6/BI%20Graph/6.%20Box%20Plot%20of%20Instalment%20Version%20vs%20Instalment%20Number.png)
Insight: Versi cicilan yang lebih rendah cenderung memiliki jumlah cicilan yang lebih tinggi dan bervariasi. Sebaliknya, versi cicilan yang lebih tinggi (produk cicilan yang lebih baru) cenderung memiliki jumlah cicilan yang lebih sedikit dan lebih seragam. Ini mengindikasikan adanya tren ke arah produk pinjaman dengan jangka waktu lebih pendek atau standar produk yang lebih ketat.
Rekomendasi: Pertimbangkan untuk menawarkan produk cicilan baru dengan durasi yang lebih singkat, karena ini tampaknya lebih diminati oleh nasabah. Untuk nasabah dengan jumlah cicilan yang tinggi, lakukan peninjauan kembali dan restrukturisasi pinjaman agar lebih sesuai dengan kemampuan finansial mereka, guna mengurangi risiko gagal bayar.

## 8. Preferensi Pelanggan - Penarikan Tunai (ATM) vs. Transaksi POS
![7. Preferensi Pelanggan - Penarikan Tunai (ATM) vs. Transaksi POS](https://github.com/hijirdella/EDA-Homecredit/blob/376eaaf5eb78cc644b710595cbec4bf1eafc137d/BI%20Graph/8.%20Preferensi%20Pelanggan%20-%20Penarikan%20Tunai%20(ATM)%20vs.%20Transaksi%20POS.png)

AMT_CREDIT_LIMIT_ACTUAL menunjukkan batas kredit yang diberikan kepada pelanggan. Distribusinya sangat skewed ke arah bawah, menunjukkan bahwa sebagian besar pelanggan memiliki batas kredit rendah, meskipun ada beberapa outliers dengan batas kredit sangat tinggi.
AMT_BALANCE menggambarkan saldo kredit yang tersisa atau total kredit yang masih dimiliki pelanggan. Sebagian besar pelanggan memiliki saldo kredit rendah, tetapi ada segelintir dengan saldo yang tinggi, mengindikasikan pemanfaatan kredit yang lebih besar.

Kesimpulan: Banyak pelanggan yang memiliki batas kredit rendah tidak menggunakan kredit mereka secara maksimal, terlihat dari saldo kredit yang juga rendah. Hal ini bisa berarti ada potensi untuk mendorong pelanggan agar menggunakan kredit lebih banyak. Sementara itu, pelanggan dengan batas kredit yang lebih tinggi juga cenderung memiliki saldo besar, menunjukkan bahwa mereka aktif menggunakan kredit. Rekomendasi: Dorong pelanggan dengan batas kredit rendah untuk menggunakan kredit mereka lebih sering melalui program promosi cicilan tanpa bunga atau cashback pada pembelian tertentu.

## 9. Jumlah Pinjaman vs Anuitas
![10. Jumlah Pinjaman vs Anuitas](https://github.com/hijirdella/EDA-Homecredit/blob/376eaaf5eb78cc644b710595cbec4bf1eafc137d/BI%20Graph/9.%20Jumlah%20Pinjaman%20vs%20Anuitas.png)

CNT_DRAWINGS_ATM_CURRENT mencatat jumlah penarikan tunai melalui ATM. Sebagian besar pelanggan melakukan penarikan dalam jumlah kecil atau tidak sama sekali.
CNT_DRAWINGS_POS_CURRENT mencatat jumlah transaksi yang dilakukan melalui point of sale (POS). Jumlah transaksinya juga rendah bagi kebanyakan pelanggan, meski ada segelintir yang aktif bertransaksi di POS.

Kesimpulan: Ada kecenderungan bahwa penarikan tunai melalui ATM lebih sering dilakukan oleh pelanggan daripada penggunaan kartu untuk transaksi di POS. Ini mungkin menunjukkan kebergantungan pada uang tunai dalam bertransaksi, meskipun ada sebagian kecil pelanggan yang aktif bertransaksi di POS.

Rekomendasi: Tingkatkan penggunaan transaksi non-tunai dengan program cashback atau poin reward untuk transaksi melalui POS. Ini dapat mengurangi kebergantungan pada penarikan tunai dan berpotensi mengurangi biaya pengelolaan uang tunai bagi perusahaan.


## 10. Distribusi Rasio Uang Muka
![11. Distribusi Rasio Uang Muka](https://github.com/hijirdella/EDA-Homecredit/blob/51b7d1f3727f22ca4935d0cd0bd5509097c60098/BI%20Graph/10.%20Distribusi%20Rasio%20Uang%20Muka.png)

Rata-rata rasio uang muka relatif rendah (sekitar 7.96%), namun ada beberapa outlier yang memiliki rasio uang muka sangat tinggi (hingga 100%). Suku bunga utama yang rendah menunjukkan bahwa sebagian besar peminjam mendapatkan suku bunga yang terjangkau, tetapi terdapat variasi yang signifikan di antara beberapa aplikasi.

## 11. Korelasi yang Kuat Antara Harga Barang dan Jumlah Kredit
![12. Harga Barang vs Jumlah Kredit](https://github.com/hijirdella/EDA-Homecredit/blob/2b7ce664391a7d9e5209de50118b91367b41b920/BI%20Graph/11.%20Harga%20Barang%20vs%20Jumlah%20Kredit.png)
Ada korelasi sangat kuat antara harga barang yang dibiayai dan jumlah kredit yang diberikan. Hal ini menunjukkan bahwa peminjam sering kali mengambil kredit yang sesuai dengan nilai barang yang ingin mereka beli, terutama untuk barang-barang dengan harga tinggi.

## 12. Rata-rata Jumlah Hari Tunggakan (SK_DPD) Berdasarkan Bulan
![13. Rata-rata Jumlah Hari Tunggakan (SK_DPD) Berdasarkan Bulan](https://github.com/hijirdella/EDA-Homecredit/blob/e1a5eb1644642621168dbcb82152b042228c053f/BI%20Graph/13.%20Rata-rata%20Jumlah%20Hari%20Tunggakan%20(SK_DPD)%20Berdasarkan%20Bulan.png)
Berdasarkan grafik yang menampilkan rata-rata jumlah hari tunggakan (SK_DPD) berdasarkan bulan (MONTHS_BALANCE), berikut business insight yang bisa diambil:

Ada peningkatan risiko keterlambatan pembayaran pada awal dan pertengahan periode pinjaman.
Perusahaan perlu memperhatikan nasabah sekitar bulan -50, di mana risiko keterlambatan pembayaran paling tinggi.
Intervensi yang tepat setelah puncak tunggakan dapat membantu menurunkan risiko gagal bayar di masa berikutnya.
Mendekati akhir masa pinjaman, nasabah cenderung lebih disiplin dalam melakukan pembayaran. Lonjakan kecil di akhir periode dapat diatasi dengan strategi restrukturisasi atau bantuan pembayaran agar nasabah dapat menyelesaikan kewajiban mereka.

## 13. Average Months Balance per Status
![14. Average Months Balance per Status](https://github.com/hijirdella/EDA-Homecredit/blob/e1a5eb1644642621168dbcb82152b042228c053f/BI%20Graph/14.%20Average%20Months%20Balance%20per%20Status.png)
Berdasarkan dari analisis yang telah kita lakukan didapatkan bahwa nasabah cenderung tidak memilih untuk membayar cicilan dengan tenor yang lebih lama.

Pada MONTHS_BALANCE rata-rata pembayaran dengan ternor tertinggi terdapat pada STATUS 3 sebesar ~50.3 bulan.

## 14. Total SK_ID_BUREAU per Status
![15. Total SK_ID_BUREAU per Status](https://github.com/hijirdella/EDA-Homecredit/blob/e1a5eb1644642621168dbcb82152b042228c053f/BI%20Graph/15.%20Total%20SK_ID_BUREAU%20per%20Status.png)
Sedangkan pada SK_ID_BUREAU nasabah terbanyak terdapat pada STATUS 6 sebesar ~13646993 nasabah.

Sehingga secara keseluruhan dapat kita simpulkan bahwa nasabah terbanyak terdapat pada STATUS 6 dengan rata-rata tenor pembayaran ~28.1 atau 2,3 tahun. Berdasarkan hal tersebut kita dapat membuat skema untuk membuat program dengan skema cicilan dengan jangka pendek sekitar 2,8 tahun atau 34 bulan.

## 15. Distribusi Status Kredit - Aktif vs Ditutup
![16. Distribusi Status Kredit - Aktif vs Ditutup](https://github.com/hijirdella/EDA-Homecredit/blob/e1a5eb1644642621168dbcb82152b042228c053f/BI%20Graph/16.%20Distribusi%20Status%20Kredit%20-%20Aktif%20vs%20Ditutup.png)
Kredit Aktif dan Ditutup:
grafik ini membantu perusahaan dalam memahami jumlah kredit aktif yang masih berjalan versus yang sudah ditutup, serta memberikan indikasi tentang seberapa baik portofolio kredit perusahaan saat ini.

Analisis: Terdapat dua status utama untuk kredit, yaitu "Active" dan "Closed." Banyak nasabah yang memiliki status "Closed," yang menunjukkan bahwa mereka telah menyelesaikan kewajiban pinjaman mereka.
Insight: Perusahaan dapat memanfaatkan data nasabah yang memiliki status "Closed" untuk mengidentifikasi profil nasabah yang berhasil dalam pengelolaan utang. Program penghargaan atau tawaran khusus dapat dirancang untuk nasabah ini agar tetap setia.

## 16. Distribusi Jumlah Kredit berdasarkan Jenis Kredit 
![17. Distribusi Jumlah Kredit berdasarkan Jenis Kredit](https://github.com/hijirdella/EDA-Homecredit/blob/e1a5eb1644642621168dbcb82152b042228c053f/BI%20Graph/17.%20Distribusi%20Jumlah%20Kredit%20berdasarkan%20Jenis%20Kredit.png)

Distribusi Kredit Berdasarkan Jenis:
Grafik ini memberikan wawasan mengenai distribusi jumlah kredit berdasarkan jenis produk kredit, membantu perusahaan memahami jenis kredit mana yang paling berisiko atau paling menguntungkan.

Analisis: CREDIT_TYPE mengindikasikan jenis kredit yang diambil nasabah. Dengan adanya variasi jenis kredit (misalnya, "Consumer credit" dan "Car loan"), perusahaan dapat memahami preferensi nasabah.

Insight: Memperluas penawaran produk berdasarkan preferensi kredit nasabah dapat meningkatkan penjualan. Misalnya, nasabah dengan pinjaman mobil mungkin lebih tertarik pada produk asuransi mobil atau layanan lain yang terkait.

## 17. Distribution of Amount of Credit vs Amount of Goods Price
![18. Distribution of Amount of Credit vs Amount of Goods Price](https://github.com/hijirdella/EDA-Homecredit/blob/4017a642236299d2725e0e0910d335ad85975954/BI%20Graph/18.%20Distribution%20of%20Amount%20of%20Credit%20vs%20Amount%20of%20Goods%20Price.png)

Business Insight:
Kedua variabel cenderung memiliki pola distribusi yang mirip, dengan puncak distribusi terjadi pada rentang nilai di bawah 500.000 (dalam satuan tertentu). Ini mengindikasikan bahwa mayoritas kredit yang diajukan berada pada jumlah yang relatif rendah.
Perbedaan signifikan antara "Amount of Credit" dan "Amount of Goods Price" terjadi di beberapa rentang nilai tertentu, yang menunjukkan ada gap atau ketidaksesuaian antara harga barang dengan jumlah kredit yang diberikan. Hal ini bisa berarti ada kelebihan atau kekurangan dalam pendanaan.

Rekomendasi:
Perusahaan dapat memanfaatkan insight ini untuk meninjau kembali kebijakan pemberian kredit, terutama pada rentang nilai di mana terjadi ketidaksesuaian antara harga barang dan jumlah kredit yang diberikan.
Pertimbangkan untuk menyesuaikan skema kredit dengan kebutuhan nyata pelanggan untuk meningkatkan kepuasan dan kesesuaian kredit dengan barang yang diinginkan.

## 18. Amount Income Total vs Amount Annuity
![19. Amount Income Total vs Amount Annuity](https://github.com/hijirdella/EDA-Homecredit/blob/4017a642236299d2725e0e0910d335ad85975954/BI%20Graph/19.%20Amount%20Income%20Total%20vs%20Amount%20Annuity.png)

Business Insight:
Mayoritas data berkelompok di rentang "Amount Income Total" di bawah 500.000. Ini menunjukkan bahwa sebagian besar nasabah memiliki pendapatan total yang relatif rendah.
Sebagian besar "Amount Annuity" berada di bawah 75.000, yang berarti pembayaran angsuran tahunan (annuity) juga cenderung rendah, menyesuaikan dengan pendapatan nasabah.
Garis merah (garis referensi) menunjukkan bahwa ada beberapa outlier yang memiliki "Amount Income Total" dan "Amount Annuity" yang lebih tinggi dari tren umum. Ini mungkin nasabah dengan profil keuangan yang berbeda atau ada ketidaknormalan yang perlu diperiksa lebih lanjut.

Rekomendasi:
Perusahaan dapat menyesuaikan penawaran produk kredit dengan memperhatikan kluster utama nasabah, yaitu mereka yang memiliki pendapatan rendah dan menengah. Ini dapat berupa produk kredit dengan angsuran lebih terjangkau atau suku bunga yang lebih fleksibel.
Lakukan analisis lebih lanjut terhadap outlier untuk memastikan tidak ada risiko kredit yang tinggi. Jika outlier ini adalah nasabah yang sebenarnya memiliki profil risiko rendah, perusahaan bisa mempertimbangkan penawaran produk premium untuk mereka.

# Conclusion
Berikut adalah 3 kesimpulan penting dari Exploratory Data Analysis Home Credit:

## Mayoritas Nasabah Mengajukan Jumlah Kredit Kecil 
Sebagian besar nasabah mengajukan kredit di bawah 500 ribu. Strategi bisnis dapat difokuskan pada pengembangan produk kredit mikro dengan bunga yang kompetitif untuk memenuhi kebutuhan segmen ini.

## Hubungan Positif antara Pendapatan dan Jumlah Kredit 
Nasabah dengan pendapatan lebih tinggi cenderung mengajukan jumlah kredit yang lebih besar. Untuk mengurangi risiko, verifikasi ketat diperlukan bagi nasabah dengan pendapatan rendah yang mengajukan kredit besar.

## Nasabah Utama Berada pada Rentang Usia 30-50 Tahun
Sebagian besar nasabah yang mengajukan kredit berusia antara 30-50 tahun. Pemasaran produk dapat diarahkan pada segmen usia ini, misalnya melalui produk kredit perumahan atau kendaraan.
