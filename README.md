# Sales Analysis Project

Bakery Sales Analysis
Sales analysis merupakan proses evaluasi dan penelitian yang dilakukan terhadap data penjualan untuk memahami kinerja penjualan suatu produk atau layanan. Analisis penjualan melibatkan pengumpulan, interpretasi, dan pemahaman data penjualan dengan tujuan untuk membuat keputusan yang lebih baik, meningkatkan efisiensi, dan mengidentifikasi peluang pertumbuhan.

Berikut ini terdapat data penjualan pada toko roti. Dataset ini menyediakan detail transaksi pelanggan yang memesan berbagai barang dari toko roti ini secara online selama periode waktu dari 26-01-11 hingga 27-12-03. Dataset ini memiliki 20507 entri, lebih dari 9000 transaksi, dan 5 kolom (TransactionNo, Items, DateTime, Daypart, DayType). Data ini diambil dari kaggle.com.

Pertama, akan dilakukan pengubahan format DateTime menjadi Date, Time, Days, Month, Year. Hal ini berguna untuk melihat detail transaksi.

![dataset.png](https://github.com/Imeldap12/bakery-sales-analysis/blob/main/images/dataset.png)
Selanjutnya akan dibuat pivot table yang berguna untuk untuk menghitung, meringkas, dan menganalisis data lembar kerja Anda untuk melihat pola dan tren tersembunyi.

Pivot table untuk Total Sales by DayPart

![pivot_1.png](https://github.com/Imeldap12/bakery-sales-analysis/blob/main/images/pivot_1.png)

Pivot table untuk Total Sales by Day

![pivot_2.png](https://github.com/Imeldap12/bakery-sales-analysis/blob/main/images/pivot_2.png)

Pivot table untuk Total Sales by Month

![pivot_3.png](https://github.com/Imeldap12/bakery-sales-analysis/blob/main/images/pivot_3.png)

Pivot table untuk Top 10 Sales Item

![pivot_3New.png](https://github.com/Imeldap12/bakery-sales-analysis/blob/main/images/pivot_3New.png)

Berdasarkan pivot tablel yang telah dibuat, selanjutnya akan dibuat timeline, slicer, dan chart untuk masing-masing pivot table serta disusun dalam dashboard. Tampilan timeline, slicer, PivotChart dicustom agar terlihat lebih menarik. Berikut ini adalah dashboard Bakery Sales.

![dashboard.png](https://github.com/Imeldap12/bakery-sales-analysis/blob/main/images/dashboard.png)

### Ringkasan EDA (Exploratory Data Analysis):

- Kopi merupakan produk terlaris dengan jauh, diikuti oleh roti dan teh. 
- Toko roti ini nampaknya melakukan sebagian besar penjualan pada afternoon (siang) hari setiap hari, dengan lebih dari 56% dari total penjualan. Penjualan kemudian mengalami penurunan tajam setelah itu (evening/sore). 
- Toko roti ini juga berhasil mencatat penjualan yang cukup baik di (morning) pagi hari. 
- Penjualan meningkat secara signifikan selama akhir pekan. Namun, penjualan tampak cukup seragam pada hari-hari lainnya. 
- Toko roti ini tampaknya sangat ramai dan berhasil melakukan sebagian besar bisnisnya dari bulan November hingga Maret.
