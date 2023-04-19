1.PERTAMA BUAT NAMA DATABASE SEBAGAI BERIKUT

CREATE DATABASE latihan1;

2.BUAT NAMA TABLE DATABASE

USE latihan1;
CREATE TABLE data_barang(
    id_barang int(11) PRIMARY KEY AUTO_INCREMENT,
    nama_barang varchar(30) NOT NULL,
    kategori_barang varchar(30) NOT NULL,
    gambar_barang text NOT NULL,
    harga_beli decimal(10,0) NOT NULL,
    harga_jual decimal(10,0) NOT NULL,
    stok int(4) NOT NULL
);

3.UNTUK TAMPILAN BISA DILIHAT FILE DIATAS

HASIL
[Screenshot (117)](https://user-images.githubusercontent.com/92745982/232947312-db07c81f-fb5b-457d-9d6f-9e3a6b9dd849.png)
