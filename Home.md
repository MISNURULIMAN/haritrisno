# Welcome to the GarudaCBT wiki!

###  I. REQUIREMENTS
- XAMPP dengan PHP 7.2 ke atas


### II. PERSIAPAN
- Install Xampp jika belum ada
- Buat folder dengan nama **garudacbt** di C:/xampp/htdocs (_asumsi xampp terinstall di partisi C:_)
- Ekstrak file hasil download ke dalam folder **garudacbt**

### III. DATABASE
- masuk ke phpmyadmin via browser, http://localhost/phpmyadmin
- buat database di phpmyadmin dengan nama apa saja, misal garuda_cbt
- buka file application/config/database.php menggunakan notepad atau notepad++
- sesuaikan pengaturannya seperti ini : `'hostname' => 'localhost'`, `'username' => 'sesuai username database, defaultnya root'`, `'password' => 'sesuai password databasae, defaultnya kosongkan'`, `'database' => 'garuda_cbt (sesuaikan dengan nama database yang dibuat pada langkah diatas)'`
- simpan database.php lalu tutup

### IV. IMPORT DATABASE
Database import otomatis:
- Buka url aplikasi, http://localhost/nama_aplikasi, misal : http://localhost/garuda_cbt
- halaman otomatis akan diarahkan ke installasi, atau langsung akses ke http://localhost/garuda_cbt/install
- ikuti langkah installasi

Database import manual:
- masuk ke phpmyadmin via browser, http://localhost/phpmyadmin
- dari database yang baru dibuat, import file master.sql yang berada di dalam folder assets/app/db
- setelah selesai import, jalankan aplikasi

### V. ADMINISTRATOR & PROFIL SEKOLAH
- jalankan aplikasi melalui browser, http://localhost/garuda_cbt
- otomatis akan membuka installer aplikasi seperti ini 
- ![step 1](https://github.com/garudacbt/cbt/blob/master/install1.PNG) 
- klik **Install Sekarang**
- biarkan STEP DATABASE seperti adanya, langsung ke STEP ADMINISTRATOR
- ![step 1](https://github.com/garudacbt/cbt/blob/master/install2.PNG) 
- klik SELANJUTNYA
- isi nama admin, username dan password, PASSWORD minimal 6 karakter
- ![](https://github.com/garudacbt/cbt/blob/master/install3.PNG)
- klik SELANJUTNYA
- pada STEP ini isian yang ditandai bintang harus diisi
- ![](https://github.com/garudacbt/cbt/blob/master/install4.PNG)
- klik SELANJUTNYA
- STEP terakhir pengecekan, pastikan semuanya sudah sesuai dengan keharusan dan keinginan
- klik MULAI APLIKASI
- silahkan login dengan akun administrator yang telah dibuat

