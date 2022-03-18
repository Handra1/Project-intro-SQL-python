# Project-intro-SQL-python
This project about learning introduction to sql in python (In Indonesia)

Bahasa pemrograman SQL dapat digunakan untuk berbagai macam database. Termasuk select data, insert data baru, update data yang sudah ada, delete data, create table, alter table, delete table dan kolom.
SQL statement pertama yang akan dipelajari yaitu select. Format penulisannya adalah ‘select COLUMNS from TABLE CONDITIONS’. Sebagai contoh, disini kita akan menampilkan semua nama kolom dari tabel census dengan simbol asterik (*).
- SELECT * FROM census

Objek yang digunakan disebut dengan ResultProxy dan itu dapat kita gunakan dengan berbagai macam variasi untuk mendapatkan data dari query.
Misalnya ketika kita gunakan method fetch yaitu fetchall pada ResultProxy. Maka kita akan mendapatkan ResultSets dari actual data yang kita tulis pada query.
Jika kita ingin mendapatkan nama kolom yang ada pada baris tersebut kita dapat menggunakan method keys(). Lalu untuk mendapatkan baris pertama dari nama kolom tertentu kita bisa panggil nama kolom yang kita inginkan.
SQLAlchemy Select Statement:
- Membutuhkan list untuk satu atau lebih (tabel / kolom)
- Jika menggunakan tabel maka akan memilih semua kolom di dalamnya
