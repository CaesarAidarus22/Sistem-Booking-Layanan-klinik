Nama: M.Caesar Aidarus

NPM: 2308107010072

Website Klinik ini dikembangkan untuk memenuhi project UAS PBW saya dan pada website ini ada 3 role utama:

1. **admin**
    - Bisa mengakses semua fitur
2. **operator**
    - Hanya Fitur administrasi
3. **dokter**
    - Operator dapat melakukan input administrasi.
    - Dokter dapat menginput data hasil diagnosa pasien.

## Cara Penggunaan

1. **Clone atau Download Repository:**

    ```bash
    git clone https://github.com/a3m-nix/klinik-app.git
    ```

2. **Konfigurasi Database:**

    - Buka file `.env` dan konfigurasi nama database sesuai kebutuhan:
        ```env
        DB_CONNECTION=mysql
        DB_HOST=127.0.0.1
        DB_PORT=3306
        DB_DATABASE=nama_database
        DB_USERNAME=nama_pengguna_database
        DB_PASSWORD=kata_sandi_database
        ```

3. **Install Dependencies:**

    ```bash
    composer install
    ```

4. **Generate Application Key:**

    ```bash
    php artisan key:generate
    ```

5. **Create Symbolic Link for Storage:**

    ```bash
    php artisan storage:link
    ```

6. **Run Database Migrations:**

    ```bash
    php artisan migrate
    ```

7. **Seed Database:**

    ```bash
    php artisan db:seed
    ```

8. **Run Artisan Serve:**

    ```bash
    php artisan serve
    ```

9. **Login dengan Akun:**
    - Pengguna: admin@admin.com
    - Kata Sandi: 1
