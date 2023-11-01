# Tugas10-PBO
# Menambahkan button upload file csv

## Pengertian

Upload file csv adalah button yang digunakan untuk menambahkan data kedalam database tanpa harus menginputkan satu persatu, tetapi cukup dengan mengupload file bentuk csv. Tetapi dalam file ini harus sesuai dengan kebutuhan setiap kolom pada tabel. Jika bentuknya berbeda maka file tidak akan bisa diinput.

## Langkah - langkah

* Membuat CLASS buku dan berisi bagian bagian yang dibutuhkan (isbn, judul, tahun terbit, 	penerbit)
* Kemudian membuat entity CLASS, yaitu dengan klik kanan pada packages - new - entity class. 	Masukkan database connection kemudian finish
* Buat java gui sesuai kebutuhan
* Pada masing masing tombol tidak lagi menggunakan connection, tetapi menggunakan entity 	manager atau disebut dengan persistence.
* Tambahkan jar csv pada library
