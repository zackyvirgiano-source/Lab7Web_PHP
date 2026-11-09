# PRAKTIKUM 7

### IDENTITAS MAHASISWA
- Nama: Muhammad Zacky Virgiano
- NIM: [312510349]
- Kelas: [I251B]
- Mata Kuliah: Pemrograman Web

---

## A. TUJUAN PRAKTIKUM

1. Memahami perbedaan pemrosesan client-side dan server-side.
2. Mengenal sintaks dasar pemrograman PHP.
3. Menggunakan variabel, tipe data, operator, dan percabangan.
4. Memahami penggunaan perulangan, array, dan function.
5. Memproses data form menggunakan metode GET dan POST.
6. Melakukan validasi dan sanitasi input pengguna.
7. Membuat aplikasi sederhana menggunakan PHP.

## B. PERANGKAT YANG DIGUNAKAN

- Laptop/PC
- Visual Studio Code
- XAMPP
- PHP
- Google Chrome

## C. CARA MENJALANKAN PROGRAM

1. Buka aplikasi XAMPP.
2. Jalankan Apache dengan menekan tombol Start.
3. Simpan folder Lab7Web_PHP ke dalam direktori htdocs.
4. Buka folder proyek menggunakan Visual Studio Code.
5. Pastikan Apache sudah berjalan.
6. Buka browser Google Chrome.
7. Masukkan alamat localhost sesuai folder latihan.

Contoh:

http://localhost/Lab7Web_PHP/index.php/

Untuk menjalankan latihan lainnya, ganti nama folder latihan sesuai program yang ingin dibuka.

## D. STRUKTUR FOLDER

Lab7Web_PHP/
- index.php/ 
- mahasiswa.php
- README.md 

## E. HASIL PRAKTIKUM

### 1. Latihan 1 - Menjalankan PHP

Pada latihan pertama, dilakukan pengujian untuk menjalankan kode PHP melalui server lokal XAMPP. Program menampilkan teks bahwa PHP berhasil dijalankan.

**Screenshot:**

<img width="1343" height="366" alt="image" src="https://github.com/user-attachments/assets/346e02f4-193c-42a7-b66b-97ecb8919f49" />
<img width="829" height="258" alt="image" src="https://github.com/user-attachments/assets/216897c1-bbbc-498d-a24e-27c8769a0ccf" />



### 2. Latihan 2 - Variabel, Operator, dan Percabangan

Pada latihan kedua, digunakan variabel untuk menyimpan data mahasiswa dan nilai tugas, UTS, serta UAS. Program menghitung nilai akhir berdasarkan bobot yang ditentukan dan menampilkan predikat nilai menggunakan percabangan if dan elseif.

**Screenshot:**

<img width="1260" height="524" alt="image" src="https://github.com/user-attachments/assets/0a5f1137-dfdd-4eca-bfaa-c8f6a143c6ca" />
<img width="922" height="95" alt="image" src="https://github.com/user-attachments/assets/9822b70a-dd45-47be-b8ba-3f652d5413ff" />


### 3. Latihan 3 - Perulangan dan Array

Pada latihan ketiga, digunakan array untuk menyimpan beberapa nama mahasiswa. Perulangan foreach digunakan untuk menampilkan seluruh data mahasiswa.

**Screenshot:**

<img width="981" height="259" alt="image" src="https://github.com/user-attachments/assets/e98bc3bb-bf20-481d-8d54-4de456cb1322" />
<img width="857" height="169" alt="image" src="https://github.com/user-attachments/assets/99b6267d-bc31-41ef-8c2d-70b22f72d83a" />


### 4. Latihan 4 - Function

Pada latihan keempat, dibuat function untuk menghitung harga setelah diskon. Function menerima parameter harga dan persentase diskon, kemudian mengembalikan hasil perhitungan.

**Screenshot:**

<img width="1062" height="243" alt="image" src="https://github.com/user-attachments/assets/695ae27f-a62a-4ae1-8d9d-4021961fbddd" />
<img width="723" height="36" alt="image" src="https://github.com/user-attachments/assets/f2751334-b537-47e4-bccd-e091da65a0bf" />


### 5. Latihan 5 - Pemrosesan Form GET

Pada latihan kelima, dibuat form pencarian sederhana menggunakan metode GET. Data yang dimasukkan pengguna dikirim melalui parameter URL dan ditampilkan kembali oleh PHP.

**Screenshot:**

<img width="1028" height="308" alt="image" src="https://github.com/user-attachments/assets/7852894f-7158-4999-b262-ddc7349b38b1" />
<img width="763" height="50" alt="image" src="https://github.com/user-attachments/assets/252ddd7c-75ec-48a2-b317-61e9665798be" />


### 6. Latihan 6 - Pemrosesan Form POST

Pada latihan keenam, dibuat form data mahasiswa yang berisi nama dan program studi. Data dikirim menggunakan metode POST, kemudian diperiksa dan ditampilkan oleh PHP.

**Screenshot:**

<img width="1330" height="549" alt="image" src="https://github.com/user-attachments/assets/1db21f9e-307e-4742-89ef-15f98963ce22" />
<img width="976" height="28" alt="image" src="https://github.com/user-attachments/assets/edb39d2c-9f60-48e9-9dbb-31768dde76d0" />


### 7. Latihan 7 - Pengolahan Data Sederhana

Pada latihan ketujuh, dibuat form transaksi yang menerima nama barang, harga, dan jumlah barang. PHP melakukan validasi input dan menghitung subtotal transaksi.

**Screenshot:**

<img width="1418" height="837" alt="image" src="https://github.com/user-attachments/assets/33c42223-02f8-49b9-9a7d-0e258c6048cc" />
<img width="1001" height="48" alt="image" src="https://github.com/user-attachments/assets/3f95c2cf-c530-4d79-bab6-3a6f502815a9" />


### 8. Mini Project - Formulir Data Mahasiswa

Pada mini project, dibuat aplikasi formulir data mahasiswa yang terdiri dari nama, NIM, program studi, semester, dan email.

Program menggunakan metode POST untuk mengirim data, melakukan validasi di sisi server, dan menampilkan ringkasan data mahasiswa apabila seluruh input valid.

**Screenshot:**

<img width="1455" height="792" alt="image" src="https://github.com/user-attachments/assets/41a0f22a-cbbd-4578-83ea-0fd12491b7bd" />
<img width="1435" height="769" alt="image" src="https://github.com/user-attachments/assets/f83c3adb-fbb4-47d4-950f-7dec06977bc3" />
<img width="1465" height="810" alt="image" src="https://github.com/user-attachments/assets/4cce369c-9dab-4d1c-b504-b7f086963c09" />
<img width="1339" height="649" alt="image" src="https://github.com/user-attachments/assets/b6f0a875-f558-4a36-ac68-f9e9180a789e" />
<img width="1373" height="363" alt="image" src="https://github.com/user-attachments/assets/2feb13e3-1b0b-440c-b5a9-2e2e230d0557" />
<img width="1083" height="454" alt="image" src="https://github.com/user-attachments/assets/aa4c712e-4cb5-477d-8fc8-4bcc9a3ff827" />


**Pemrograman Web - Praktikum 7**

**Pertanyaan Evaluasi**

1. Apa perbedaan pemrosesan client-side dan server-side?
Client-side adalah pemrosesan data yang dilakukan di browser pengguna, sedangkan server-side adalah pemrosesan data yang dilakukan di server.

2. Mengapa file PHP harus dijalankan melalui web server?
Karena PHP merupakan bahasa pemrograman server-side yang membutuhkan web server untuk memproses kode PHP dan menampilkan hasilnya ke browser.

3. Apa fungsi tanda $ pada variabel PHP?
Tanda $ digunakan untuk menandai atau mendefinisikan sebuah variabel dalam PHP.

4. Apa perbedaan metode GET dan POST?
GET mengirimkan data melalui URL, sedangkan POST mengirimkan data melalui bagian body HTTP sehingga data tidak terlihat langsung di URL.

5. Mengapa input pengguna perlu divalidasi di sisi server?
Agar data yang masuk sesuai dengan aturan, mencegah kesalahan, dan menghindari serangan seperti SQL Injection.

6. Apa fungsi htmlspecialchars() ketika menampilkan data dari form?
Untuk mengubah karakter khusus HTML menjadi bentuk aman sehingga mencegah serangan XSS (Cross-Site Scripting).

7. Apa manfaat penggunaan function dalam program PHP?
Untuk membuat kode lebih rapi, mengurangi pengulangan kode, mempermudah pemeliharaan, dan membuat program lebih mudah dipahami.



