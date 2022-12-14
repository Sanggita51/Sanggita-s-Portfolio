# Sanggita-s-Portfolio

## 1. Kerja Praktik LAPAN (BRIN)
Ketika libur panjang semester 6 saya mengikuti Kerja Praktik di PSTA-LAPAN atau yang sekarang disebut BRIN. saya memilih untuk mempelajari pengamatan dan prediksi komposisi atmosfer untuk pengambilan keputusan dalam rangka peningkatan kualitas udara. Setiap seminggu sekali saya diberi tugas untuk mengikuti meeting dalam rangka pengembangan website LAPAN yang menyediakan info kualitas udara di Indonesia. Selama melakukan Kerja Praktik, saya juga diharuskan untuk membuat penelitian dan saya memilih untuk mengambil topik penelitian dengan judul "Analisis Pengaruh El Nino Kuat Tahun 2015 DAN La Nina Lemah Tahun 2016 Terhadap Konsentrasi PM2.5 Secara Spasial Di Indonesia (Menggunakan Data Reanalisis MERRA-2)".

Dari penelitian ini saya melakukan ploting akumulasi dan anomali curah hujan bulanan secara spasial menggunakan python ketika terjadi El Nino dan La Nina. Akumulasi curah hujan bulanan dapat menunjukkan intensitas hujan di berbagai wilayah Indonesia, sedangkan anomali curah hujan menunjukkan kondisi relatif terhadap klimatologinya. Berdasarkan kedua pengolahan data ini, dapat disimpulkan apakah curah hujan pada bulan tersebut lebih rendah atau tinggi dibandingkan dengan nilai rata-rata klimatologisnya.

Hubungan curah hujan terhadap konsentrasi PM2.5 dilihat dengan membandingkan plot anomali curah hujan bulanan, curah hujan bulanan aktual dan konsentrasi PM2.5 saat periode El Nino dan La Nina pada masing-masing pulau di Indonesia. Dari hasil plot ini dapat diketahui wilayah yang konsentrasi PM2.5nya sangat terpengaruh maupun yang tidak terlalu terpengaruh oleh kejadian El Nino dan La Nina.

Penelitian ini menghasilkan kesimpulan bahwa Anomali negatif (penurunan) curah hujan dari rata-rata klimatologi dengan curah hujan kategori rendah (<100 mm/bulan) akibat kejadian El Nino berpengaruh terhadap peningkatan konsentrasi PM2.5 di wilayah Sumatera, Jawa, Kalimantan, Sulawesi, Maluku dan Papua yang mencapai >12 µg/m3. Anomali positif (peningkatan) curah hujan dari rata-rata klimatologis dengan curah hujan kategori menengah-tinggi (100-500 mm/bulan) akibat kejadian La Nina berpengaruh terhadap penurunan konsentrasi PM2.5 di wilayah Sumatera dan Kalimantan yang mencapai >12 µg/m3.

## 2. Tugas Akhir
Karena ketertarikan saya pada isu pencemaran udara, saya memutuskan untuk mengambil topik pencemaran udara pada tugas akhir dengan judul "Analisis Pengaruh Tutupan Awan terhadap Konsentrasi PM2.5 di Malam Hari (Studi Kasus: DKI Jakarta)". Dalam mengerjakan tugas akhir saya juga menggunakan python sebagai tools untuk membantu saya dalam melakukan visualisasi data. 
#### => Saya menganalisis hubungan tutupan awan (cloud cover) dengan Total radiasi gelombang panjang yang dipancarkan ke bawah (Surface Thermal Radiation Downward / STRD) dengan menggunakan bar plot.
#### => Saya menganalisis korelasi antara total radiasi gelombang panjang di permukaan (Surface net Thermal Radiation / STR) dengan Total radiasi gelombang panjang yang dipancarkan ke bawah (Surface Thermal Radiation Downward) dengan menggunakan scatter plot.
#### => Saya menganalisis tutupan awan secara spasial dan temporal saya menggunakan hovmoller dalam melakukan visualisasi data, dan untuk menganalsiis konsentrasi PM2.5 dan kecepatan angin secara temporal saya menggunakan grafik dalam visualisasi data.
#### Penelitian ini menghasilkan kesimpulan bahwa Tutupan awan pada level rendah dan menengah dapat mempengaruhi laju konsentrasi PM2.5 di malam hari karena dapat meningkatkan STRD secara signifikan walaupun hanya terdapat sedikit tutupan awan di level atas. Laju peningkatan dan penurunan konsentrasi PM2.5 dapat terjadi pada kondisi sebagai berikut:
1. Peningkatan konsentrasi PM2.5 dengan laju tertinggi 3,27 – 8,28 μg m-3 jam-1 terjadi ketika kondisi atmosfer stabil dan terdeteksi inversi suhu pada ketinggian <200m yang diduga dipicu oleh pendinginan radiasi permukaan akibat sedikitnya tutupan awan yang terdeteksi pada TBB diatas 253K pada malam hari.
2. Penurunan konsentrasi PM2.5 dengan laju tertinggi 3,45-12 μg m-3 jam-1 terjadi ketika tutupan awan rendah (LCC) dan menengah (MCC) pada malam hari diatas 40% dengan TBB dibawah 253K yang memicu pemanasan radiasi permukaan (ditandai dengan nilai STR sebesar -29,002 W/m2 yang lebih tinggi dari STR rata-rata pada bulan Desember -34,116 W/m2)

## 3. SQL Course Project
#### => Pada projek pertama saya diminta untuk membuat database bernama tr_penjualan. Kemudian saya harus menghitung total penjualan dan kemudian ditugaskan untuk hanya menampilkan produk dengan total revenue yang lebih dari 100000.
#### => Pada projek kedua saya diminta untuk menghitung:	
1. Total jumlah seluruh penjualan (total/revenue).
2. Total quantity seluruh produk yang terjual.
3. Total quantity dan total revenue untuk setiap kode produk.
4. Rata - Rata total belanja per kode pelanggan.
5. Menambahkan kolom baru dengan nama ‘kategori’ yang mengkategorikan total/revenue ke dalam 3 kategori: High: > 300K; Medium: 100K - 300K; Low: <100K.
#### => Pada projek ketiga saya diminta untuk:
1. meng-query data-data pelanggan yang membeli produk Kotak Pensil DQLab, Flashdisk DQLab 32 GB, dan Sticky Notes DQLab 500 sheets menggunakan tabel ms_pelanggan dan tr_penjualan untuk mendapatkan data - data yang diminta oleh marketing yaitu kode_pelanggan, nama_customer, alamat.
2. Menyiapkan hanya data produk dengan harga di bawah 100K untuk kode produk prod-1 sampai prod-5; dan dibawah 50K untuk kode produk prod-6 sampai prod-10, tanpa mencantumkan kolom no_urut.




