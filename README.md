# Lab3Web
Nama : Anggita Risqi Nur Clarita

NIM : 312210450

Kelas : TI.22.A.4

## DAFTAR ISI <br>
| No | Description | Link |
|-----|------|-----|
|1|Modul Praktikum 3|[Click Here](https://drive.google.com/file/d/1rD9rNU_AVyMfjs2TD1iXFkMbVSCAYU2p/view)|
|2|Praktikum|[Click Here](#praktikum)|
|3|Pertanyaan dan Tugas|[Click Here](#pertanyaan-dan-tugas)|

## Praktikum
> ### Instruksi Praktikum
> 1. Persiapkan text editor misalnya **VSCode**.
>
> 2. Buat folder baru dengan nama **Lab3Web**.
>
> 3. Ikuti langkah-langkah praktikum yang akan dijelaskan berikutnya.

## Langkah-langkah Praktikum
1. ### Membuat Ordered List
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML Lanjutan</title>
    </head>
    <body>
        <header>
            <h1>Membuat List</h1>
        </header>
    </body>
    </html>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/1.png)
    **Keterangan** : Disini diperintahkan untuk membuat file dengan nama `lab3_list.html`, kemudian menambahkan script yang telah tersedia.

    Kemudian selanjutnya tambahkan kode untuk membuat list sederhana seperti berikut:

    ```html
    <section id="order-list">
        <h2>Ordered List</h2>
        <ol>
            <li>Pemrograman Web</li>
            <li>Sistem Informasi</li>
            <li>Basis Data 2</li>
        </ol>
    </section>
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/2.png)
     **Keterangan** : Script HTML tersebut digunakan untuk membuat **Ordered List**

2. ### Membuat Unorderd List
    ```html
    <section id="unorder-list">
        <h2>Unordered List</h2>
        <ul type="square">
            <li>Jaringan Komputer</li>
            <li>Struktur Data</li>
            <li>Algoritma &amp; Pemrograman</li>
        </ul>
    </section>
    ```

    **Output**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/3.png)
    **Keterangan** : Script HTML tersebut digunakan untuk membuat **Unordered List**, setelah deklarasi *Ordered List* pada section *unordered-list*.


3. ### Membuat Description List
    ```html
    <section id="unorder-list">
        <h2>Description List</h2>
        <dl>
            <dt>Fakultas Teknik</dt>
            <dd>Teknik Industri</dd>
            <dd>Teknik Informatika</dd>
            <dd>Teknik Lingkungan</dd>
            <dt>Fakultas Ekonomi dan Bisnis</dt>
            <dd>Akuntansi</dd>
            <dd>Manajemen</dd>
            <dd>Bisnis Digital</dd>
        </dl>
    </section>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/4.png)
    **Keterangan** : Script HTML tersebut digunakan untuk membuat **Description List** setelah deklarasi *unorderd-list*.


4. ### Membuat Tabel
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML Lanjutan</title>
    </head>
    <body>
        <header>
            <h1>Membuat Table</h1>
        </header>
    </body>
    </html>
    ```

    Kemudian selanjutnya tambahkan kode untuk membuat tabel sederhana seperti berikut:

    ```html
    <table border="1" cellpadding="4" cellspacing="0">
        <thead>
            <tr>
                <th>No.</th>
                <th>Fakultas</th>
                <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td>Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/5.png)
    **Keterangan** : Disini diperintahkan untuk membuat file baru dengan nama `lab3_tabel.html`, kemudian menambahkan script yang telah tersedia.


5. ### Mengatur Margin dan Padding
    ```html
    <table border="1" cellpadding="4" cellspacing="0">
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/6.png)
    **Keterangan** : Script diatas digunakan ntuk mengatur margin dan padding pada cel data, dengan menambahkan atribut *cellpadding* dan *cellspacing* pada tag table.


6. ### Menggabungkan Sel Data
    ```html
    <table border="1" cellpadding="6" cellspacing="0">
        <thead>
            <tr>
            <th>No.</th>
            <th>Fakultas</th>
            <th>Program Studi</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>1.</td>
                <td rowspan="3">Teknik</td>
                <td>Teknik Informatika</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>Teknik Industri</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>Teknik Lingkungan</td>
            </tr>
        </tbody>
    </table>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/7.png)
    **Keterangan** : Untuk menggabungkan sel data, gunakan atribut rowspan dan colspan. Atribut **rowspan** untuk menggabungkan baris (secara vertikal) dan **colspan** untuk menggabungkan kolom (secara horizontal).


7. ### Mengatur Margin dan Padding
    ```html
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>HTML Lanjutan</title>
    </head>
    <body>
        <header>
            <h1>Membuat Form</h1>
        </header>
    </body>
    </html>
    ```

    Kemudian selanjutnya tambahkan kode untuk membuat form sederhana seperti berikut:

    ```html
    <form action="proses.php" method="post">
        <fieldset>
            <legend>Data Pelanggan</legend>
            <p>
                <label for="nama">Nama</label>
                <input type="text" id="nama" name="nama">
            </p>
            <p>
                <label for="alamat">Alamat</label>
                <textarea id="alamat" name="alamat" cols="20" rows="3"></textarea>
            </p>
            <p>
                <label>Jenis Kelamin</label>
                <input id="jk_l" type="radio" name="kelamin" value="L" /><label for="jk_l">Laki-laki</label>
                <input id="jk_p" type="radio" name="kelamin" value="P" /><label for="jk_p">Perempuan</label>
            </p>
            <p><input type="submit" value="Login"></p>
        </fieldset>
    </form>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/8.png)
    **Keterangan** : Disini diperintahkan untuk membuat file baru dengan nama `lab3_form.html`, kemudian menambahkan script yang telah tersedia.


8. ### Menabahkan Style pada Form
    ```css
    <style>
        form p > label {
            display: inline-block;
            width: 100px;
        }
        form input[type="text"], form textarea {
            border: 1px solid #197a43;
        }
        form input[type="submit"] {
            border: 1px solid #197a43;
            background-color: #197a43;
            color: #ffffff;
            font-weight: bold;
            padding: 5px 15px;
        }
    </style>
    ```

    **Output**

    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/9.png)
    **Keterangan** : Disini diperintahkan untuk menambahkan style CSS seperti berikut agar tampilan form lebih menarik, namun saya tambahkan style-nya di dalam HTML langsung di bagian `<head>`.


## Pertanyaan dan Tugas

1. **Buatlah form yang menampilkan *dropdown* menu dan *listbox* dengan multiple selection.**
    
    ![image](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/screenshot/10.png)
    **Keterangan** : Disini saya menambahkan **dropdown** dan **listbox** seperti berikut di tampilan form dari HTML sebelumnya, untuk scriptnya dapat dilihat langsung pada file [lab3_form.html](https://github.com/AnggitaRisqiNC/Lab3Web/blob/main/lab3_form.html)

## Finish