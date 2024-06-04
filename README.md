## Inisialisasi dan Konfigurasi Git

1. **Setel email pengguna GitHub:**
    ```sh
    git config --global user.email "email_yang_digunakan_di_github"
    ```

2. **Inisialisasi repository Git:**
    ```sh
    git init
    ```

3. **Inisialisasi repository Git:**
    ```sh
    git add .
    ```

4. **Tambahkan remote repository:**
    ```sh
    git remote add origin https://github.com/DanielNurSandy/si_bolang.git
    ```

5. **Lakukan commit dengan pesan:**
    ```sh
    git commit -m "Perubahan ke-1 seterusnya"
    ```

6. **Push ke branch utama (main atau master):**
    - Jika menggunakan branch `main`:
        ```sh
        git push -u origin main
        ```
    - Jika menggunakan branch `master`:
        ```sh
        git push origin -u master
        ```
7. **Mengambil file dari github**
    ```sh
    git pull
    ```
