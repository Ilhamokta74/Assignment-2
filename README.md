# Assignment 2

Ini adalah Assignment ke 2 dari kelas Scalable Web Service with Golang - DTS Kominfo, dalam Assignment ke 2 ini, diminta harus menggunakan Gin dan GORM untuk membangun API dengan basis data PostgreSQL.

## Prasyarat

Sebelum menjalankan aplikasi ini, pastikan Anda memiliki yang berikut terpasang di sistem Anda:

- Go 1.16 atau versi terbaru: [Panduan Instalasi](https://golang.org/doc/install)
- PostgreSQL: [Unduh & Instalasi](https://www.postgresql.org/download/)
- Golang Migrate (untuk migrasi basis data): [Panduan Instalasi](https://github.com/golang-migrate/migrate/tree/master/cmd/migrate)

## Instalasi

1. Klon repositori:

   ```bash
   git clone https://github.com/Ilhamokta74/Assignment-2.git

2. Pindah ke direktori proyek:

    ```bash
    cd <Nama Folder>
    ```

3. Download depedensi dengan perintah:

    ```bash
    go mod download
    ```

4. Buat file .env lalu isi dengan perintah ini:

    ```bash
    DB_HOST=localhost
   DB_USER=postgres [sesuaikan dengan user database milik anda]
   DB_PASSWORD=password [sesuaikan dengan password database milik anda]
   DB_PORT=5432
   DB_NAME=assignment-2 [sesuaikan dengan nama table milik anda]

    ```

5. Jalankan aplikasi dengan perintah:

    ```bash
    go run main.go
    ```

# Cara Penggunaan
### silahkan import file [Assignment-2.postman_collection.json] yang berada di repo/folder ini ke Postman


