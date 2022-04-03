# Capston-Project-2---Northwind-Suppliers
Purwadhika Capston Project 2 - Northwind (Fokus Analysis : Suppliers)


##Latar Belakang
Untuk proyek, ini kita akan menganalisis database Northwind. Northwind adalah sebuah perusahaan yang bergerak di bidang ekspor impor berbagai macam produk. Sebuah analisis diinginkan untuk mengetahui **gambaran dan performa pemasok / supplier produk Northwind**. Terdapat sebuah database yang menunjukkan profil singkat pemasok dan juga performanya dalam indikator order / pesanan. Analisis lanjutan akan dilakukan untuk mengetahui gambaran pemasok produk Northwind dan juga performanya untuk meningkatkan efisiensi.

##Rumusan Masalah
1.Produk apakah yang paling diminati konsumen?
2.Bagaimanakah gambaran identitas supplier Northwind?
3.Supplier manakah yang paling banyak memasok produk yang diminati konsumen?
4.Siapakah supplier dengan nilai order yang paling besar?
5.Bagaimanakah performa supplier- supplier dengan nilai order yang besar?

##Tahapan Analisis Data
1.Membuat tabel analisis dari database SQL dan menghubungkannya ke Python
2.Membersihkan data dari anomali-anomali
3.Melakukan analisis dengan visualisasi data dan hypotesis testing
4.Membuat implikasi manajerial berdasarkan analisis data

##Temuan Penting
###Produk yang diminati konsumen
Berdasarkan analisis, terlihat produk kategori minuman dan susu merupakan produk yang paling diminati konsumen.

###Hasil Analisis
1.Supplier Northwind sebanyak 28 supplier yang berasal dari 16 negara. Terlihat sebagian besar transaksi berkaitan dengan supplier berasal dari negara AS. 
2.Supplier bernama Plutzer Lebensmittelgromrkte AG, yang sebagian besar memasok produk daging. 
3.Nilai order terbesar berasal dari supplier asal Prancis, yang mendominasi order untuk produk minuman dan susu.
4.Supplier Prancis memasok banyak produk premium yang nilai ordernya besar, sehingga ada baiknya tetap menjalin hubungan yang erat dengan supplier dari Prancis agar memastikan stok barang- barang tersebut dapat senantiasa dipenuhi.
5.Northwind sangat bergantung pada Prancis untuk pasokan susu.
6.Plutzer Lebensmittelgromrkte AG memasok 49,23% dari total order Northwind. Hal ini tentunya tidak ideal dan ada baiknya Northwind melakukan diversifikasi supplier sambil melakukan pendekatan intens dengan supplier Plutzer Lebensmittelgromrkte AG.
7.Hasil testing Kruskal Wallis diatas menunjukkan adanya perbedaan nilai median bila negara asal supplier dibandingkan dengan harga unit dan juga nilai order namun tidak ada perbedaan nilai median bila negara asal supplier dibandingkan dengan kuantitas order. Hal ini mengindikasikan bahwa setiap negara memiliki produk unggulan yang disukai oleh pelanggan. Northwind harus jeli mengidentifikasi produk unggulan di tiap negara agar stok produk yang diminati pelanggan tetap terjaga. Selain itu, Northwind juga bisa mengidentifikasi produk- produk tiap negara agar dapat mendiversifikasi suppliernya dengan baik. 
8.Hasil testing Mann Whitney diatas menunjukkan adanya perbedaan nilai median bila supplier dibandingkan dengan kuantitas order. Sejalan dengan hasil testing Kruskal Wallis, perbedaan tidak hanya ada di negara asal Supplier, namun juga ada di entitas- entitas supplier tersebut. Selain dari screening negara, Northwind juga harus jeli mengidentifikasi kemampuan dan produk unggulan masing- masing supplier di suatu negara.
