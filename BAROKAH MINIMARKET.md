# Barokah Minimarket
![enter image description here](https://image.freepik.com/free-vector/mini-market-cafe-flat-style-icon_81894-606.jpg)

**Pak Adi** adalah seorang pemilik toko kelontong di pinggir jalan. Toko pak adi sangat ramai dikunjungi oleh pembeli karena terkenal memiliki harga yang paling murah.
Semua proses dalam toko Pak Adi dilakukan dengan cara manual dan tradisional, tanpa melibatkan sistem apapun.
**Tahun depan**, Pak Adi berencana merubah toko kelontongnya menjadi sebuah minimarket dengan nama ***Barokah Minimarket***. 
*Tetapi*, sebuah minimarket harus ada suatu sistem yang menangani inventarisasi stok barang. Sehingga Pak Adi membutuhkan programmer untuk membuatkannya.

**Bantulah pak adi untuk membuat program berbasis web untuk invetarisasi stok di minimarket barunya.
spesifikasi program Pak Adi dijelaskan sebagai berikut:**
1. ada pengakategorian barang. misalkan minuman, makanan, atk, dsb
2. pak adi bisa memanajemen data (CRUD) kategori
3. setiap barang akan dicatat: SKU, nama barang, kategori, jumlah stok, harga satuan (CRUD)
4. ada fitur pencarian barang berdasarkan SKU/nama barang/kategori
5. ada filter berdasarkan range harga

----------------------------------------------------
**SOAL SUSULAN**

 1. tambahkan table di database: table penjualan dan table detail penjualan
 2. table penjualan berisi informasi barang yang dibeli oleh pelanggan. data yang disimpan adalah kode penjualan, nama pembeli, tanggal dan waktu, total harga yang harus dibayar.
 3. table detail penjualan berisi daftar detail dari barang-barang yang dibeli oleh pembeli. table penjualan memiliki hubungan one-to-many terhadap table detail penjualan
 4. setiap peroses pembelian, secara otomatis akan mengurangi stock suatu barang
 5. jika ada update/delete dari data penjualan, maka juga akan ada update di data stock. misal: barang tidak jadi dibeli/delete/dikurangi kuantitasnya maka data stock akan ditambahkan/dikurangi secara otomatis

**yang dikumpulkan:**
1. source code program
2. screenshot hasil program 


