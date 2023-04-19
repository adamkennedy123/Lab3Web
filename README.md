~ Buat Nama Database
````
CREATE DATABASE LATIHAN1;
````
~ Buat Table Database
````
USE LATIHAN1;
CREATE TABLE data_barang(
    id_barang int(11) PRIMARY KEY AUTO_INCREMENT,
    nama_barang varchar(30) NOT NULL,
    kategori_barang varchar(30) NOT NULL,
    gambar_barang text NOT NULL,
    harga_beli decimal(10,0) NOT NULL,
    harga_jual decimal(10,0) NOT NULL,
    stok int(4) NOT NULL
);
````
UNTUK TAMPILAN BISA DILIHAT FILE DIATAS

~ Hasil Ada Di(tampilan.php)

![Screenshot (117)](https://user-images.githubusercontent.com/92745982/232947312-db07c81f-fb5b-457d-9d6f-9e3a6b9dd849.png)

~ Hasil Ada Di(tambah.php)

![Screenshot (118)](https://user-images.githubusercontent.com/92745982/232950705-5fa9c22e-1712-4c22-b322-23256f93bcfc.png)

~ Hasil Ada Di(ubah.php)

![Screenshot (119)](https://user-images.githubusercontent.com/92745982/232950756-f96f132c-ef5c-491b-b226-8c8c922b8f1b.png)
