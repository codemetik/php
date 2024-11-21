## Pengenalan Web Server dan Server Side Scripting

### 1. WEB Server
WEB Server merupakan sebuah perangkat lunak dalam server yang berfungsi menerima permintaan (request) berupa halaman web dan mengirimkan kembali (response) hasilnya dalam bentuk halaman-halaman web yang umumnya berbentuk dokumen HTML.

#### Beberapa web werver yang banyak digunakan di Internet antara lain
      1. Apache Web Server (http://www.apache.org)
      2. Internet Information Service, IIS (http://microsoft.com/iis)
      3. Xitami Web Server (http://www.xitami.com)
      4. Sun Java System Web Server (http://www.sun.com/software/products_srvr/home_web_srvr.xml)

### 2. Server Side Scripting
Server Side Scripting merupakan sebuah teknologi _scripting_ atau pemrograman web dimana _script_ (program) dikompilasi atau diterjemahkan di _server_. Dengan _server side scripting_, memungkinkan untuk menghasilkan halaman web yang dinamis.

#### Beberapa contoh Server Side Scripting (Programming)
      1. ASP (Active Server Page) dan ASP.NET
      2. ColdFusion (http://www.macromedia.com/software/coldfusion)
      3. Java Server Pages (http://java.sun.com/products/jsp/)
      4. Perl (http://www.perl.org)
      5. Python (http://www.python.org)
      6. PHP (http://www.php.net)

#### Keistimewaan PHP
      1. Cepat
      2. Free
      3. Mudah dipelajari
      4. Multi-platform
      5. Dukungan _technical-support_
      6. Banyaknya komunikasi PHP
      7. Aman

### 3. Instalasi Apache, PHP dan MySQL dengan XAMPP
Beberapa aplikasi paket antara lain:
####
      1. XAMPP (versi Windows) dan LAMPP (versi linux) yang dapat didownload di http://apachefriends.org.
      2. WAMP Server
      3. APPServ
      4. PHPTriad.

Dalam prakti ini menggunakan aplikasi paket server yaitu XAMPP. 
silahkan Download Source XAMPP versi stabil terbaru di http://apachefriends.org. pilih versi sesuai dengan sistem operasi yang anda gunakan (tersedia versi untuk Windows, Linux, Mac).
Pastikan Komputer yang digunakan untuk praktik berjalan dengan baik dengan kapasitas memori dan hardisk yang masih mencukupi. 

Setelah XAMPP sudah terinstall selanjutkan jalankan XAMPP seperti berikut :
![xampp](https://github.com/user-attachments/assets/e60d4a5c-21f1-48ba-addf-c268e5d9fd75)

Selanjutnya memastikan Web Server sudah bisa digunakan dengan cara buka aplikasi Google Chrome atau web browser lainnya, dan akses url berikut: http://localhost/dashboard/ atau http://127.0.0.1/dashboard/. 
jika berhasil menampilkan halaman dashboard XAMPP maka Web Server sudah bisa digunakan untuk program PHP.

### 4. Instalasi Text Editor
Dalam praktik ini kita menggunakan Sublimtext https://www.sublimetext.com/download namun jika ingin menggunakan VisualCode juga bisa : https://code.visualstudio.com/Download

### 5. Direktory ROOT Project WEB pada Paket Server XAMPP
Direktori root Xampp htdocs adalah folder htdocs yang merupakan direktori default atau home directory pada Xampp. Lokasi folder ini biasanya berada di C:\xampp\htdocs pada Windows

#### Fungsi
      Tempat menyimpan berkas web, seperti HTML, CSS, PHP, gambar, dll. yang dapat diakses melalui URL localhost

### Tips
      Untuk mengorganisir project website, sebaiknya buat folder untuk masing-masing project website.

