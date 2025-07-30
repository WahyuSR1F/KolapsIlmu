
# Kompetensi 1

### 1.1 Arsitektur dasar sistem operasi berbasis mobile	- Android: Kernel Linux, arsitektur ARM/ARM64/x86, menggunakan HAL untuk komunikasi hardware.
- iOS: Kernel XNU, arsitektur ARM dengan chipset Apple Silicon, integrasi penuh dengan hardware Apple.
### 1.2 Platform sistem operasi berbasis mobile sesuai perangkat keras	- Android: Digunakan pada Samsung, Xiaomi, Oppo, dll., mendukung Snapdragon, MediaTek, Exynos.
- iOS: Eksklusif pada iPhone/iPad dengan chipset Apple Bionic/M series.
### 1.3 Security pada platform sesuai perangkat keras	- Android: Secure Boot, ARM TrustZone (TEE), biometric hardware.
- iOS: Secure Enclave, hardware-based encryption, sandboxing aplikasi.

### 2.1 Kebutuhan user dirancang berdasarkan spesifikasinya	- Jika user membutuhkan perangkat dengan harga terjangkau, fleksibel, dan banyak pilihan hardware, maka Android lebih sesuai.
- Jika user mengutamakan ekosistem tertutup, keamanan tinggi, dan performa optimal, maka iOS menjadi pilihan.
### 2.2 Sistem operasi untuk mengembangkan aplikasi mobile	- Android: Cocok untuk developer yang ingin menjangkau banyak perangkat, menggunakan Android Studio dengan bahasa Java/Kotlin.
- iOS: Cocok untuk pengembangan aplikasi di ekosistem Apple, menggunakan Xcode dengan bahasa Swift/Objective-C.

### 3.1 Jenis bahasa pemrograman berbasis mobile ditentukan	- Android: Java, Kotlin.
- iOS: Swift, Objective-C.
- Cross-platform: Flutter (Dart), React Native (JavaScript).
### 3.2 Bahasa pemrograman berbasis mobile dibandingkan perbedaannya	- Java: Stabil, banyak library, verbose.
- Kotlin: Lebih ringkas, modern, interoperable dengan Java.
- Swift: Cepat, aman, khusus iOS.
- Flutter (Dart): UI konsisten, multi-platform.
### 3.3 Perangkat lunak terkait dikonfigurasi sesuai spesifikasinya	- Android Studio untuk Java/Kotlin.
- Xcode untuk Swift (iOS).
- VS Code untuk Flutter/React Native.
### 3.4 Alur program dihasilkan untuk pembuatan aplikasi mobile	Contoh alur: Desain UI → Tulis kode → Kompilasi → Uji aplikasi di emulator → Deploy ke perangkat.
### 3.5 Konsep variabel dan konstanta dalam bahasa pemrograman ditentukan tipe datanya	- Kotlin: var name: String = "John" (variabel), val PI: Double = 3.14 (konstanta).
### 3.6 Konsep struktur kondisi dan perulangan ditentukan dalam bahasa pemrograman	- Kotlin:
if(score >= 75){ println("Lulus") } else { println("Gagal") }
for(i in 1..5){ println(i) }
### 3.7 Konsep layout dan objek dijelaskan dalam bahasa pemrograman mobile

# Kompetensi 2

### 1.1 Tools desain UI mobile →

Android Studio (Android),

Xcode (iOS),

Figma (UI/UX design),

Flutter (cross-platform).

### 1.2 Menu utama sesuai kebutuhan →

Android Studio: Project, Layout Editor, Palette, Component Tree.

Xcode: Interface Builder, Storyboard.

Figma: Frame, Layers, Components.

### 1.3 Fitur penting →

Drag & drop UI components, preview tampilan, auto-layout, code editor, emulator untuk uji aplikasi.

### 1.4 Rancangan form →

Menggunakan fitur Layout Editor di Android Studio atau Storyboard di Xcode untuk membuat form login, registrasi, dll.

### 2.1 Jumlah form ditentukan sesuai kebutuhan aplikasi, misalnya: form login, dashboard, profil.

### 2.2 Rancangan form dibuat sesuai informasi yang diperlukan, misalnya dashboard menampilkan data utama secara ringkas.

### 2.3 Icon/gambar dipilih sesuai spesifikasi, misalnya icon user untuk profil, icon keranjang untuk belanja.

### 2.4 Jenis font dipilih yang jelas dan sesuai tema aplikasi, misalnya Roboto (Android) atau San Francisco (iOS).

### 2.5 Ukuran font diatur agar nyaman dibaca, misalnya judul 18–24pt, isi 14–16pt.

### 3.1 Tombol/menu dibuat sesuai fungsi aplikasi, misalnya: tombol Login, Register, Save, serta menu navigasi (Home, Profil, Settings).

### 3.2 Ukuran tombol/menu disesuaikan dengan layar agar mudah diklik dan proporsional, misalnya tombol utama berukuran lebar ≥ 44dp (standar Android/iOS).

Kompentesi 3

### 1.1 Rancangan UI ditentukan berdasarkan kebutuhan aplikasi, misalnya aplikasi belanja memerlukan halaman produk, keranjang, dan pembayaran.

### 1.2 Komponen UI dialog diidentifikasi sesuai proses, misalnya form login memerlukan input username, password, dan tombol login.

### 1.3 Urutan akses komponen dijelaskan, misalnya: pengguna → pilih menu → isi form → kirim data → tampilkan hasil.

### 1.4 Mock-up aplikasi dibuat menggunakan tools seperti Figma, Adobe XD, atau Android Studio Layout Editor untuk memvisualisasikan tampilan sebelum pengembangan.

### 2.1 Menu program diterapkan sesuai rancangan, misalnya menu Home, Profil, dan Setting sesuai desain awal.

### 2.2 Penempatan UI dialog diatur secara berurutan (sekuensial) agar alur penggunaan mudah dipahami.

### 2.3 Setting aktif-pasif komponen disesuaikan dengan alur proses, misalnya tombol Submit aktif hanya jika semua input terisi.

### 2.4 Style komponen UI ditentukan (warna, font, ukuran, ikon) agar konsisten dengan tema aplikasi.

### 2.5 Simulasi UI diuji pada emulator/perangkat nyata sehingga rancangan dapat berjalan sebagai aplikasi sesungguhnya.

# Kompetensi 4

### 1.1 Entitas sistem diidentifikasi sesuai dokumen perancangan.

```
Contoh: Pada sistem perpustakaan, entitasnya meliputi Anggota, Buku, Peminjaman, dan Petugas.

### 1.2 Diagram dibuat dari entitas yang telah didefinisikan, seperti ERD (Entity Relationship Diagram) atau Class Diagram, untuk menggambarkan hubungan antar entitas.

### 2.1 Query dibuat untuk menghasilkan informasi yang diperlukan aplikasi secara efisien.

```
Contoh:

```sql
SELECT nama_buku, nama_anggota 
FROM peminjaman 
JOIN buku ON peminjaman.id_buku = buku.id_buku 
JOIN anggota ON peminjaman.id_anggota = anggota.id_anggota;

### 2.2 Diagram entitas dan hubungan (ERD) yang telah diidentifikasi diimplementasikan menggunakan tools seperti MySQL Workbench, phpMyAdmin, atau SQL Server Management Studio untuk membentuk struktur database sesuai rancangan.

# Kompetensi 5

### 1.1 Platform/lingkungan dipilih sesuai kebutuhan aplikasi.

```
Contoh: Android membutuhkan Android Studio di OS Windows/Linux/Mac; iOS membutuhkan Xcode di macOS.

### 1.2 Tools bahasa pemrograman dipilih sesuai kebutuhan pengembangan.

```
Contoh: Kotlin/Java untuk Android, Swift untuk iOS, Flutter (Dart) untuk aplikasi cross-platform.

### 2.1 Tools pemrograman di-install sesuai prosedur resmi, misalnya mengunduh Android Studio dari situs resminya, lalu mengikuti langkah instalasi hingga selesai.

### 2.2 Tools pemrograman dapat dijalankan di lingkungan pengembangan (OS) yang telah ditentukan, misalnya Android Studio berjalan di Windows/Linux/Mac atau Xcode berjalan di macOS.

### 3.1 Script sederhana dibuat menggunakan tools pemrograman yang telah di-install.

```
Contoh (Kotlin – Android Studio):

```kotlin
fun main() {
    println("Hello Mobile App")
}
### 3.2 Script dijalankan dengan benar pada emulator/perangkat dan menghasilkan output sesuai skenario, misalnya menampilkan teks "Hello Mobile App" di layar.

# Kompetensi 6

### 1.1 Target konfigurasi ditentukan, misalnya mengatur SDK Android, emulator perangkat, atau plugin tambahan agar mendukung pengembangan aplikasi.

### 1.2 Tools pemrograman setelah konfigurasi (contohnya Android Studio dengan SDK terbaru) tetap berfungsi normal dan dapat digunakan untuk coding, build, serta menjalankan aplikasi.

### 2.1 Fitur dasar yang dibutuhkan untuk mendukung pembuatan program dengan CI3 diidentifikasi, misalnya:

Code Editor (VS Code, Sublime, PHPStorm) untuk menulis kode PHP.

Web Server (XAMPP, Laragon) untuk menjalankan CI3 di localhost.

Database Tools (phpMyAdmin, MySQL Workbench) untuk mengelola database.

Framework CI3 itu sendiri untuk struktur MVC.

### 2.2 Fitur dasar tools CI3 dikuasai, seperti:

Konfigurasi config.php dan database.php.

Penggunaan Controller, Model, dan View sesuai pola MVC.

Routing, helper, dan library bawaan CI3.

Testing aplikasi melalui browser setelah menjalankan server lokal.

# Kompetensi 7

### 1.1 Parameter masukan dan keluaran diidentifikasi.

```
Contoh: Fungsi getUserById($id) menerima parameter $id dan mengembalikan data user dari database.

### 1.2 Jenis passing parameter di CI3 menggunakan by value (nilai dikirim ke fungsi). Jika ingin efek langsung ke variabel, dapat menggunakan by reference dengan &.

### 1.3 Fungsi reusable diimplementasikan dalam helper atau library CI3 agar dapat digunakan di berbagai controller.

```
Contoh Helper (application/helpers/custom_helper.php):

```php
function formatTanggal($tanggal) {
    return date('d-m-Y', strtotime($tanggal));
}
Fungsi ini bisa dipanggil di seluruh aplikasi setelah helper diload.

### 2.1 Reusable function/module yang sudah ada diidentifikasi.

```
Contoh internal CI3: helper bawaan (url_helper, form_helper), library (session, email), atau helper custom yang dibuat programmer.

### 2.2 Reusable function/module digunakan dalam aplikasi agar kode lebih efisien.

# Kompetensi 8

### 1.1 Penamaan file, fungsi, variabel, dan konstanta dibuat sesuai konteks agar mudah dipahami.

```
Contoh: File User_model.php, fungsi getUserById($id), variabel $userData, konstanta BASE_URL.

### 1.2 Setiap fungsi/prosedur/program diberi komentar di awal berisi:

Deskripsi fungsi

Initial state dan Final state

Author, versi, dan tanggal pembuatan.

### 1.3 Source code dilengkapi dengan komentar penjelas pada baris-baris penting.

### 2.1 Folder dan sub-folder disusun sesuai konteks agar mudah dikelola.

```
Contoh pada CI3:

Copy code
application/
  controllers/
  models/
  views/
  helpers/
  libraries/
assets/
  css/
  js/
  images/
Struktur ini memisahkan logika (MVC) dan aset frontend.

### 2.2 File README dibuat untuk menjelaskan struktur folder dan fungsinya.

# Kompetensi 9

### 1.1 Program menggunakan class dibuat untuk mengelola logika secara OOP.
```
Contoh: Class User digunakan untuk menyimpan dan menampilkan data pengguna.

### 1.2 Properti dan metode (fungsi/prosedur) didefinisikan di dalam class sesuai kebutuhan.
```
Contoh: Properti $name dan metode greet() ditambahkan ke dalam class.

### 1.3 Data dalam class dibuat mandiri (enkapsulasi), tidak bergantung langsung pada variabel global.
```
Contoh: Nilai $name diatur melalui constructor, bukan variabel global.

### 1.4 Hak akses properti/metode diatur menggunakan private, protected, atau public.
```
Contoh Implementasi:

```php
<?php
class User {
    private $name;

    public function __construct($name) {
        $this->name = $name;
    }

    public function greet() {
        return "Halo, " . $this->name . "!";
    }
}

// Pemanggilan class
$user = new User("Wahyu");
echo $user->greet();

### 2.1 Tipe data diidentifikasi.
```
Contoh: Class memiliki properti $name (string) dan $age (integer).

```php
private $name; // string
private $age;  // int
### 2.2 Sintaks program dikuasai dengan bahasa pemrogramannya.
```
Contoh: Constructor digunakan untuk menginisialisasi data, dan metode dibuat dengan sintaks PHP.

```php
public function __construct($name, $age) {
    $this->name = $name;
    $this->age  = $age;
}
### 2.3 Control program dikuasai.
```
Contoh: Menggunakan if-else untuk menentukan status usia.

```php
public function checkAge() {
    if ($this->age >= 18) {
        return $this->name . " sudah dewasa.";
    } else {
        return $this->name . " masih di bawah umur.";
    }
}

### 3.1 Inheritance pada class diterapkan.
```
Contoh: Class Admin mewarisi (extends) class User.

```php
class User {
    protected $name;
    public function __construct($name) {
        $this->name = $name;
    }
    public function getName() {
        return $this->name;
    }
}

class Admin extends User {
    public function getRole() {
        return $this->name . " adalah Admin.";
    }
}
### 3.2 Polymorphism pada class diterapkan.
```
Contoh: Method getRole() di Admin bisa memiliki perilaku berbeda dibanding User.

```php
class Member extends User {
    public function getRole() {
        return $this->name . " adalah Member.";
    }
}

// Penggunaan Polymorphism
$users = [new Admin("Wahyu"), new Member("Andi")];
foreach ($users as $u) {
    echo $u->getRole() . "<br>";
}
```
Output:

```nginx
Wahyu adalah Admin.
Andi adalah Member.
### 3.3 Overloading pada class diterapkan.
Di PHP, overloading dilakukan dengan __call() untuk menangani pemanggilan metode yang tidak ada.

```php
class DynamicCall {
    public function __call($method, $args) {
        return "Metode '$method' dipanggil dengan argumen: " . implode(", ", $args);
    }
}

$obj = new DynamicCall();
echo $obj->sayHello("Wahyu");

### 4.1 Interface class program dibuat.
Interface digunakan untuk mendefinisikan metode yang harus diimplementasikan oleh class.

```php
<?php
interface UserInterface {
    public function getName();
    public function getRole();
}

class Admin implements UserInterface {
    private $name;
    public function __construct($name) {
        $this->name = $name;
    }
    public function getName() {
        return $this->name;
    }
    public function getRole() {
        return "Admin";
    }
}

$admin = new Admin("Wahyu");
echo $admin->getName() . " adalah " . $admin->getRole();
```
Output:

```nginx
Wahyu adalah Admin
### 4.2 Paket dengan program dibuat.
Dalam PHP/CI3, paket bisa diorganisir menggunakan namespace atau folder agar kode lebih terstruktur.

```php
<?php
// File: application/libraries/UserPackage/User.php
namespace UserPackage;

class User {
    public function info() {
        return "Ini dari paket UserPackage.";
    }
}

// File: application/controllers/Test.php
use UserPackage\User;

class Test extends CI_Controller {
    public function index() {
        $u = new User();
        echo $u->info();
    }
}

### 5.1 Kesalahan dapat dikoreksi.
```
Contoh: Saat program dijalankan, jika terjadi error (misalnya salah penulisan nama metode), perbaiki sintaks atau logika.

```php
// Salah: memanggil metode yang tidak ada
echo $user->getname(); // error karena huruf kecil

// Diperbaiki:
echo $user->getName(); // benar
### 5.2 Program bebas salah sintaks dihasilkan.
```
Contoh: Setelah debugging, program dapat dijalankan tanpa error dan menampilkan output yang sesuai.

```php
<?php
class User {
    private $name;
    public function __construct($name) {
        $this->name = $name;
    }
    public function getName() {
        return $this->name;
    }
}

// Program berjalan tanpa error
$user = new User("Wahyu");
echo "Halo, " . $user->getName();

# Kompetensi 10

### 1.1 Class unit-unit reuse (dari aplikasi lain) yang sesuai dapat diidentifikasi.
```
Contoh: Menggunakan class Email bawaan CodeIgniter 3 untuk mengirim email tanpa harus membuat dari nol.

### 1.2 Keuntungan efisiensi dari pemanfaatan komponen reuse dapat dihitung.
```
Contoh: Dengan menggunakan library Email CI3, waktu pengembangan fitur email berkurang drastis karena tidak perlu menulis kode SMTP manual.

### 1.3 Lisensi, Hak cipta, dan hak paten tidak dilanggar dalam pemanfaatan komponen reuse tersebut.
```
Contoh: Library CI3 berlisensi MIT, sehingga aman digunakan dalam proyek.
Jika menggunakan library pihak ketiga, pastikan lisensinya (MIT, GPL, Apache) tidak melanggar hak cipta.

### 2.1 Ketergantungan antar unit diidentifikasi.
Library encryption bawaan CI3 membutuhkan OpenSSL aktif di server.

### 2.2 Penggunaan komponen yang sudah obsolete dihindari.
Gunakan $this->load->library('encryption') dari CI3, bukan metode enkripsi lama seperti mcrypt yang sudah deprecated.

### 2.3 Program yang dihubungkan dengan library ditetapkan.
```
Contoh implementasi enkripsi dan dekripsi:

```php
<?php
class Test extends CI_Controller {

    public function index() {
        // Load library encryption
        $this->load->library('encryption');

        // Data yang akan dienkripsi
        $data = "Rahasia123";

        // Enkripsi data
        $encrypted = $this->encryption->encrypt($data);

        // Dekripsi data
        $decrypted = $this->encryption->decrypt($encrypted);

        // Tampilkan hasil
        echo "Data Asli: " . $data . "<br>";
        echo "Hasil Enkripsi: " . $encrypted . "<br>";
        echo "Hasil Dekripsi: " . $decrypted;
    }
}

### 3.1 Cara-cara pembaharuan library atau komponen pre-existing diidentifikasi.

Mengecek versi terbaru library di dokumentasi resmi CI3 atau GitHub.

Mengganti file library lama di application/libraries atau memperbarui framework CI3 secara keseluruhan.

Memastikan kompatibilitas kode setelah pembaruan.

### 3.2 Pembaharuan library atau komponen pre-existing berhasil dilakukan.
```
Contoh: Update library Encryption CI3 dengan versi terbaru agar mendukung algoritma enkripsi yang lebih kuat.

# Kompetensi 11

### 1.1 Perangkat lunak aplikasi SQL telah dipasang.
```
Contoh: Menginstal MySQL/MariaDB menggunakan XAMPP, Laragon, atau installer resmi MySQL.

```bash
# Contoh instalasi di Linux
sudo apt install mysql-server
### 1.2 Perangkat lunak aplikasi SQL dijalankan.
```
Contoh: Menjalankan MySQL dari terminal atau service control.

```bash
# Menjalankan MySQL Service
sudo service mysql start

# Masuk ke MySQL
mysql -u root -p

### 2.1 Fitur pengolahan DML diidentifikasikan.
DML (Data Manipulation Language) meliputi:

SELECT → mengambil data

INSERT → menambah data

UPDATE → memperbarui data

DELETE → menghapus data

### 2.2 Fitur pengolahan DML dieksekusi sesuai kebutuhan.
```
Contoh query DML di MySQL:

```sql
-- Menambahkan data
INSERT INTO users (name, email) VALUES ('Wahyu', 'wahyu@example.com');

-- Mengambil data
SELECT * FROM users;

-- Memperbarui data
UPDATE users SET email = 'baru@example.com' WHERE name = 'Wahyu';

-- Menghapus data
DELETE FROM users WHERE name = 'Wahyu';

### 3.1 Tabel diisi data menggunakan perintah DML.
```
Contoh:

```sql
INSERT INTO users (id, name, email) VALUES (1, 'Wahyu', 'wahyu@example.com');
### 3.2 Indeks dibangkitkan.
```
Contoh:

```sql
CREATE INDEX idx_email ON users(email);
Indeks mempercepat pencarian data berdasarkan kolom email.

### 3.3 View tabel dibentuk sesuai kebutuhan.
```
Contoh:

```sql
CREATE VIEW user_view AS
SELECT name, email FROM users WHERE id > 0;
View user_view menampilkan data yang sudah difilter dari tabel users.

### 4.1 Fitur pengolahan DML diidentifikasikan.
Fitur DML yang digunakan: JOIN, UNION, INSERT, UPDATE, DELETE, dan SELECT dengan kondisi relasi antar tabel.

### 4.2 Perintah DML dipergunakan untuk manipulasi antar tabel.
```
Contoh menggunakan JOIN antar tabel users dan orders:

```sql
SELECT users.name, orders.product 
FROM users 
JOIN orders ON users.id = orders.user_id;
### 4.3 Perintah DML dipergunakan untuk manipulasi antar-view.
```
Contoh manipulasi menggunakan view:

```sql
-- Membuat view gabungan
CREATE VIEW user_orders AS
SELECT u.name, o.product 
FROM users u 
JOIN orders o ON u.id = o.user_id;

-- Mengambil data dari view
SELECT * FROM user_orders;
### 4.4 Perintah DML ditulis secara efisien.
```
Contoh penggunaan alias dan kondisi untuk optimasi:

```sql
SELECT u.name, COUNT(o.id) AS total_order 
FROM users u 
LEFT JOIN orders o ON u.id = o.user_id 
WHERE u.status = 'active' 
GROUP BY u.name;

### 5.1 Stored procedure dibuat dengan perintah SQL.
```
Contoh membuat stored procedure untuk mengambil data user berdasarkan ID:

```sql
DELIMITER $$

CREATE PROCEDURE getUserById(IN userId INT)
BEGIN
    SELECT name, email 
    FROM users 
    WHERE id = userId;
END$$

DELIMITER ;
### 5.2 Prosedur diuji diperiksa input dan output-nya.
```
Contoh pengujian prosedur:

```sql
CALL getUserById(1);
```
Output:

```sql
+-------+--------------------+
| name  | email              |
+-------+--------------------+
| Wahyu | wahyu@example.com |
+-------+--------------------+

### 6.1 Function dibuat dengan perintah SQL.
```
Contoh membuat SQL function untuk menghitung total pesanan user:

```sql
DELIMITER $$

CREATE FUNCTION totalOrders(userId INT) 
RETURNS INT
DETERMINISTIC
BEGIN
    DECLARE total INT;
    SELECT COUNT(*) INTO total 
    FROM orders 
    WHERE user_id = userId;
    RETURN total;
END$$

DELIMITER ;
### 6.2 Perintah SQL pada function ditulis secara efisien.
Fungsi menggunakan query COUNT(*) dengan filter WHERE, sehingga hanya satu query yang dieksekusi.

```
✅ Pengujian Function
```sql
SELECT totalOrders(1) AS jumlah_pesanan;

### 7.1 Trigger didefinisikan dengan perintah SQL.
```
Contoh membuat trigger untuk mencatat log setiap kali data user ditambahkan:

```sql
CREATE TABLE user_log (
    id INT AUTO_INCREMENT PRIMARY KEY,
    user_id INT,
    action VARCHAR(50),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);

DELIMITER $$

CREATE TRIGGER after_user_insert
AFTER INSERT ON users
FOR EACH ROW
BEGIN
    INSERT INTO user_log(user_id, action) 
    VALUES (NEW.id, 'User Ditambahkan');
END$$

DELIMITER ;
### 7.2 Kesesuaian hasil trigger diuji.
Pengujian dengan menambahkan data baru:

```sql
INSERT INTO users (name, email) VALUES ('Andi', 'andi@example.com');
SELECT * FROM user_log;

### 8.1 Perubahan data dengan perintah commit dilakukan.
```
Contoh: Menyimpan data user dengan transaksi dan commit jika berhasil.

```php
$this->db->trans_start();

$this->db->insert('users', [
    'name'  => 'Wahyu',
    'email' => 'wahyu@example.com'
]);

$this->db->trans_complete(); // otomatis commit jika tidak ada error
### 8.2 Pembatalan penulisan data dilakukan dengan rollback.
Jika terjadi error, transaksi dibatalkan secara otomatis atau manual dengan rollback.

```php
$this->db->trans_begin();

$this->db->insert('users', [
    'name'  => 'Andi',
    'email' => 'andi@example.com'
]);

if ($this->db->trans_status() === FALSE) {
    $this->db->trans_rollback(); // batalkan perubahan
} else {
    $this->db->trans_commit();   // simpan perubahan
}

# Kompetensi 12

### 1.1 Data dapat disimpan/diubah ke dalam format basis data.
```
Contoh menyimpan dan mengubah data menggunakan Query Builder CI3:

```php
// Insert data
$this->db->insert('users', [
    'name'  => 'Wahyu',
    'email' => 'wahyu@example.com'
]);

// Update data
$this->db->where('id', 1);
$this->db->update('users', ['email' => 'baru@example.com']);
### 1.2 Informasi yang diinginkan dapat dihasilkan menggunakan query tersebut.
```
Contoh mengambil data dengan kondisi tertentu:

```php
$query = $this->db->get_where('users', ['id' => 1]);
$user  = $query->row();
echo $user->name . " - " . $user->email;
### 1.3 Indeks dipergunakan untuk mempercepat akses.
Indeks dibuat di database (MySQL) agar query lebih cepat.
```
Contoh membuat indeks dengan raw query CI3:

```php
$this->db->query("CREATE INDEX idx_email ON users(email)");

### 2.1 Library akses basis data dapat diterapkan.
CI3 menyediakan Database Library untuk memudahkan koneksi dan query database.
Aktifkan otomatis di application/config/autoload.php:

```php
$autoload['libraries'] = array('database');
### 2.2 Perintah akses data yang relevan dengan teknologi atau jenis baru data diterapkan untuk mengakses data.
Gunakan Query Builder CI3 untuk akses database secara aman dan efisien.

```
✅ Contoh Prosedur Akses (Menggunakan Model)
```php
<?php
class User_model extends CI_Model {

    // Ambil semua data user
    public function getAll() {
        return $this->db->get('users')->result();
    }

    // Ambil user berdasarkan ID
    public function getById($id) {
        return $this->db->get_where('users', ['id' => $id])->row();
    }

    // Simpan user baru
    public function insert($data) {
        return $this->db->insert('users', $data);
    }

    // Hapus user
    public function delete($id) {
        return $this->db->delete('users', ['id' => $id]);
    }
}
```
✅ Contoh Penggunaan di Controller
```php
<?php
class Users extends CI_Controller {

    public function index() {
        $this->load->model('User_model');
        $data['users'] = $this->User_model->getAll();
        $this->load->view('user_list', $data);
    }
}

### 3.1 Teknologi koneksi yang sesuai dipilih.
CI3 menggunakan Database Driver (MySQLi, PDO, Postgre, SQLite, dll).
```
Contoh konfigurasi MySQLi di application/config/database.php:

```php
$db['default'] = array(
    'dsn'      => '',
    'hostname' => 'localhost',
    'username' => 'root',
    'password' => '',
    'database' => 'db_ci3',
    'dbdriver' => 'mysqli',
    'dbprefix' => '',
    'pconnect' => FALSE,
    'db_debug' => (ENVIRONMENT !== 'production'),
);
### 3.2 Keamanan koneksi ditentukan.
Gunakan username & password database yang aman.

Nonaktifkan pconnect untuk mencegah persistent connection yang tidak terkontrol.

Terapkan SSL jika koneksi ke database eksternal.

Hindari query manual tanpa query binding untuk mencegah SQL Injection.

```
Contoh Query Binding CI3:

```php
$this->db->query("SELECT * FROM users WHERE email = ?", array($email));
### 3.3 Hak setiap pengguna ditentukan.
Buat akun database dengan hak akses terbatas.

Misalnya, user aplikasi hanya diberi hak SELECT, INSERT, UPDATE, tanpa hak DROP.

```
Contoh SQL untuk membuat user dengan hak terbatas:

```sql
CREATE USER 'ci3_user'@'localhost' IDENTIFIED BY 'passwordku';
GRANT SELECT, INSERT, UPDATE ON db_ci3.* TO 'ci3_user'@'localhost';
FLUSH PRIVILEGES;

### 4.1 Skenario pengujian disiapkan.
Siapkan database dengan tabel dan data sample.

Tentukan skenario uji: insert, update, delete, dan select.

Pastikan juga pengujian meliputi kasus normal dan kasus error.

### 4.2 Logika pemrograman mengacu pada kinerja statement akses data yang akan dibaca.
Uji logika query pada model CI3, misalnya mengambil user berdasarkan ID.

```php
$user = $this->User_model->getById(1);
if ($user) {
    echo "User ditemukan: " . $user->name;
} else {
    echo "User tidak ditemukan";
}
### 4.3 Performansi mengacu pada kinerja statement akses data yang akan dibaca data diuji.
Uji performa query dengan profiling CI3 untuk melihat waktu eksekusi query.

Aktifkan database profiler di controller:

```php
$this->output->enable_profiler(TRUE);
Profiler akan menampilkan waktu eksekusi query, jumlah query, dan informasi performa lainnya.

# Kompetensi 13

### 1.1 Tipe data telah dijelaskan sesuai kaidah pemrograman.
Tipe data adalah jenis nilai yang dapat disimpan dalam variabel, seperti:

Integer (int): angka bulat

String: teks

Boolean: true/false

Float/Double: angka desimal

```
Contoh di PHP (CI3):

```php
$umur = 25;          // int
$nama = "Wahyu";     // string
$isActive = true;    // boolean
### 1.2 Variabel telah dijelaskan sesuai kaidah pemrograman.
Variabel adalah tempat menyimpan data yang nilainya dapat berubah (varian).

Penamaan harus jelas dan sesuai konvensi.

```
Contoh:

```php
$userEmail = "user@example.com"; // nilai dapat berubah
### 1.3 Konstanta telah dijelaskan sesuai kaidah pemrograman.
Konstanta adalah variabel yang nilainya tidak dapat diubah (invarian).

Di PHP, konstanta didefinisikan dengan define atau const.

```
Contoh:

```php
define("APP_NAME", "My CI3 App");
echo APP_NAME; // tidak dapat diubah

### 2.1 Metode yang sesuai ditentukan.
Pilih metode pemrograman: Prosedural atau OOP (Object-Oriented Programming).

Untuk CI3, umumnya menggunakan metode MVC (Model-View-Controller).

### 2.2 Komponen yang dibutuhkan ditentukan.
Komponen utama dalam CI3:

Model → mengakses database

Controller → mengatur alur logika

View → menampilkan output ke user

### 2.3 Relasi antar komponen diterapkan.
Controller memanggil Model → Model mengambil data → Controller mengirim data ke View → View menampilkan hasil.

### 3.1 Algoritma untuk sorting dibuat.
Sorting digunakan untuk mengurutkan data.
```
Contoh algoritma Bubble Sort di PHP:

```php
function bubbleSort($arr) {
    $n = count($arr);
    for ($i = 0; $i < $n - 1; $i++) {
        for ($j = 0; $j < $n - $i - 1; $j++) {
            if ($arr[$j] > $arr[$j+1]) {
                $temp = $arr[$j];
                $arr[$j] = $arr[$j+1];
                $arr[$j+1] = $temp;
            }
        }
    }
    return $arr;
}

$data = [5, 3, 8, 1];
print_r(bubbleSort($data));
```
Output:
[1, 3, 5, 8]

### 3.2 Algoritma untuk searching dibuat.
Searching digunakan untuk mencari data dalam array.
```
Contoh algoritma Linear Search:

```php
function linearSearch($arr, $target) {
    foreach ($arr as $index => $value) {
        if ($value == $target) {
            return $index; // posisi ditemukan
        }
    }
    return -1; // tidak ditemukan
}

$data = [10, 20, 30, 40];
echo linearSearch($data, 30); // output: 2

### 4.1 Konsep penggunaan kembali prosedur dan fungsi dapat diidentifikasi.
Prosedur: sekumpulan perintah yang dapat dipanggil berulang tanpa mengembalikan nilai.

Fungsi: mirip prosedur, tetapi mengembalikan nilai.

Keduanya membantu code reuse agar tidak menulis kode yang sama berulang-ulang.

### 4.2 Prosedur dapat digunakan.
```
Contoh prosedur sederhana di PHP:

```php
function tampilkanPesan($nama) {
    echo "Halo, $nama! Selamat datang.";
}

// Pemanggilan prosedur
tampilkanPesan("Wahyu");
### 4.3 Fungsi dapat digunakan.
```
Contoh fungsi yang mengembalikan nilai:

```php
function hitungLuasPersegi($sisi) {
    return $sisi * $sisi;
}

// Pemanggilan fungsi
$luas = hitungLuasPersegi(5);
echo "Luas persegi: $luas";

### 5.1 Kompleksitas waktu algoritma diidentifikasi.
Kompleksitas waktu (Time Complexity) mengukur berapa lama algoritma berjalan seiring bertambahnya jumlah data (n).

Umumnya dinyatakan dalam Big-O Notation, misalnya:

O(1) → konstan, tidak tergantung jumlah data.

O(n) → linear, bertambah seiring jumlah data.

O(n²) → kuadratik, sangat lambat untuk data besar.

```
Contoh:

Linear Search → O(n)

Bubble Sort → O(n²)

### 5.2 Kompleksitas penggunaan memori algoritma diidentifikasi.
Kompleksitas memori (Space Complexity) mengukur berapa banyak memori yang digunakan algoritma.

Jika algoritma membutuhkan array tambahan, memori akan meningkat.

```
Contoh:

Bubble Sort → O(1) (tidak butuh memori tambahan).

Merge Sort → O(n) (butuh array tambahan untuk penggabungan).

# Kompetensi 14

### 1.1 Pengertian konsep penerapan versi kode program dapat dijelaskan.
Version Control System (VCS) adalah sistem yang mencatat setiap perubahan pada kode program.

Dengan VCS, developer dapat melacak, membatalkan, atau menggabungkan perubahan dengan mudah.

```
Contoh: Git, SVN, Mercurial.

### 1.2 Proses branching, merging, commit, check-in, check-out, dan cloning dapat dijelaskan.
Branching: Membuat cabang pengembangan terpisah.

```bash
git branch fitur-login
git checkout fitur-login
Merging: Menggabungkan perubahan dari branch ke branch utama.

```bash
git merge fitur-login
Commit: Menyimpan perubahan ke riwayat versi.

```bash
git add .
git commit -m "Menambahkan fitur login"
Check-in / Push: Mengirim perubahan ke repository remote (misalnya GitHub).

```bash
git push origin main
Check-out: Berpindah ke versi atau branch tertentu.

```bash
git checkout main
Cloning: Mengambil salinan repository dari remote.

```bash
git clone https://github.com/user/project.git
### 1.3 Konsep repository dapat dijelaskan.
Repository adalah tempat penyimpanan seluruh riwayat versi kode.

Ada dua jenis:

Local Repository: tersimpan di komputer developer.

Remote Repository: tersimpan di server (GitHub, GitLab, Bitbucket).

### 2.1 Guna dari alat/tools dapat ditunjukkan.
Git digunakan untuk menyimpan, melacak perubahan, dan mengatur versi kode.

Memudahkan kolaborasi antar developer.

### 2.2 Alat/tools dapat diusulkan.
Tools yang dapat digunakan:

Git (open-source, paling populer)

SVN (Apache Subversion)

Mercurial

Hosting: GitHub, GitLab, Bitbucket

### 2.3 Karakteristik dari tools/alat dapat dijelaskan atau ditunjukkan.
Git bersifat distributed (setiap developer punya salinan penuh repository).

Mendukung branching dan merging dengan mudah.

Dapat bekerja offline dan sinkronisasi ke remote repository.

### 2.4 Proses branching, merging, commit, check-in, check-out, dan cloning dilakukan.
```
Contoh penerapan Git:

```bash
# Clone repository
git clone https://github.com/user/project.git

# Buat dan pindah ke branch baru
git checkout -b fitur-baru

# Tambahkan dan commit perubahan
git add .
git commit -m "Menambahkan fitur baru"

# Gabungkan branch ke main
git checkout main
git merge fitur-baru

# Kirim perubahan ke repository remote
git push origin main

# Kompetensi 5

### 1.1 Peralatan pengujian ditentukan sesuai dengan kebutuhan pengujian.
Pilih tools yang sesuai untuk pengujian integrasi aplikasi.

```
Contoh tools:

Postman → untuk menguji API

Selenium → untuk pengujian UI otomatis

PHPUnit → untuk pengujian unit & integrasi di PHP

Xdebug → untuk debugging aplikasi CI3

### 1.2 Dokumen pendukung pengujian disiapkan.
Siapkan dokumen berisi:

Lingkungan pengujian (server, database, framework yang digunakan).

Skenario pengujian (apa yang diuji, input-output).

Hasil pengujian (log error, hasil sukses/gagal).

```
Contoh Dokumen Sederhana:

No	Fitur Diuji	Input	Output Diharapkan	Hasil
1	Login User	Email & Password benar	Redirect ke dashboard	✅
2	Login User	Password salah	Pesan error tampil	✅

### 2.1 Data uji integrasi program diidentifikasi.
Tentukan data yang akan digunakan untuk menguji integrasi antar modul/aplikasi.

Jenis data uji:

Data valid → untuk memastikan fitur berjalan benar.

Data tidak valid → untuk menguji penanganan error.

Data batas (boundary) → untuk menguji input ekstrem.

```
Contoh (pengujian login di CI3):

Data valid: email=user@test.com, password=12345

Data invalid: email=kosong, password=salah

### 2.2 Data uji integrasi program dibangkitkan.
Data uji dapat dibuat manual atau otomatis (menggunakan script atau generator).

Untuk pengujian database, dapat menggunakan dummy data dengan SQL atau Faker library.

```
Contoh Membuat Data Dummy di SQL:

```sql
INSERT INTO users (name, email, password) 
VALUES ('Test User', 'user@test.com', MD5('12345'));
```
Contoh Menggunakan Faker di CI3:

```php
$this->load->library('faker');
for ($i = 0; $i < 10; $i++) {
    $data = [
        'name'  => $this->faker->name,
        'email' => $this->faker->email,
        'password' => md5('12345')
    ];
    $this->db->insert('users', $data);
}

### 3.1 Modul program dijalankan sesuai dengan prosedur yang ditetapkan.
Jalankan setiap modul (controller, model, view di CI3) sesuai urutan integrasi.

Pastikan pengujian mengikuti prosedur: setup → eksekusi → verifikasi hasil.

```
Contoh:

Uji modul Login → modul Dashboard → modul Transaksi.

### 3.2 Data atau kondisi sebagai masukkan, diimplementasikan ke dalam program.
Gunakan data uji (valid, invalid, boundary) yang telah disiapkan.

Lakukan pengujian menggunakan skenario yang berbeda.

```
Contoh:

Input: email=user@test.com, password=12345 → harus login berhasil.

Input: email=user@test.com, password=salah → harus tampil pesan error.

### 3.3 Hasil pengujian dicatat dalam lembar pengujian.
Catat setiap hasil pengujian (sukses/gagal) dalam tabel dokumentasi.

```
Contoh Lembar Pengujian:

No	Modul	Input	Output Diharapkan	Hasil
1	Login	Email & Password benar	Redirect ke Dashboard	✅
2	Login	Password salah	Tampilkan pesan error	✅
3	Transaksi	Data kosong	Validasi error muncul	✅

### 4.1 Modul yang terkait dianalisis sesuai dengan standar pengembangan perangkat lunak yang berlaku.
Analisis dilakukan berdasarkan standar pengujian (misalnya ISO/IEC 29119 atau standar internal proyek).

Periksa apakah modul berfungsi sesuai spesifikasi.

### 4.2 Data hasil keluaran dievaluasi kesesuaiannya dengan data yang direncanakan.
Bandingkan output aktual dari pengujian dengan expected output.

Jika ada perbedaan, catat untuk perbaikan.

```
Contoh:

Expected: Login sukses → Dashboard tampil.

Actual: Dashboard tidak tampil → modul perlu diperbaiki.

### 4.3 Status pada lembar pengujian dari hasil perbandingan data tersebut dicatat ke dalam lembar pengujian.
Status hasil pengujian diberi tanda:

```
✅ Pass jika sesuai

❌ Fail jika tidak sesuai

```
Contoh Lembar Pengujian:

No	Modul	Input	Expected Output	Actual Output	Status
1	Login	user@test.com / 12345	Redirect Dashboard	Redirect Dashboard	✅
2	Login	user@test.com / salah	Pesan Error	Pesan Error	✅
3	Transaksi	Data Kosong	Validasi Error	Tidak Ada Validasi	❌

### 5.1 Peralatan yang digunakan untuk pengujian dicatat ke dalam lembar peralatan pengujian.
Catat semua tools/software yang digunakan untuk pengujian.

```
Contoh:

No	Peralatan	Versi	Keterangan
1	Postman	v10.20	Pengujian API
2	PHPUnit	v9.5	Pengujian Unit & Integrasi
3	CI3 Framework	3.1.13	Lingkungan aplikasi

### 5.2 Kondisi yang terjadi selama pengujian dicatat ke dalam lembar pengujian.
Catat semua kondisi (normal atau error) selama proses pengujian.

```
Contoh:

Saat pengujian login, sistem sempat lambat karena koneksi database.

Saat pengujian transaksi, muncul error Undefined variable.

### 5.3 Data yang diimplementasikan dan data hasil pengujian dicatat.
Rekam input data yang digunakan serta output yang dihasilkan.

```
Contoh:

Input Data	Expected Output	Actual Output
email=user@test.com	Redirect Dashboard	Redirect Dashboard
email=user@test.com pwd=sal	Pesan Error	Pesan Error

### 5.4 Analisis hasil pengujian dicatat sesuai dengan standar dokumentasi.
Analisis hasil pengujian dilakukan, dicatat dalam dokumen, dan mengikuti standar (misalnya template laporan pengujian).

Berisi: ringkasan hasil, status pass/fail, dan rekomendasi perbaikan.

```
Contoh Analisis:

Modul login PASS (berfungsi sesuai spesifikasi).

Modul transaksi FAIL (validasi tidak berjalan, perlu perbaikan pada fungsi controller).

### 6.1 Hasil pengujian didokumentasikan menjadi laporan.
Semua hasil pengujian (status pass/fail, catatan error, rekomendasi perbaikan) disusun dalam laporan.

Laporan berisi: tujuan pengujian, metode, data uji, hasil, analisis, kesimpulan.

### 6.2 Dokumentasi hasil pengujian dilaporkan.
Laporan diserahkan kepada pihak terkait (developer, QA, project manager).

Dapat berupa dokumen PDF, spreadsheet, atau laporan di sistem manajemen proyek.

### 6.3 Dokumentasi hasil pengujian diarsipkan.
Semua dokumen hasil pengujian disimpan di repository atau server dokumentasi agar dapat diakses untuk audit/pengembangan berikutnya.

```
Contoh Struktur Laporan Pengujian Integrasi (CI3)
1. Identitas Pengujian:

Nama aplikasi: Sistem Penjualan

Versi: 1.0

Tanggal: 29/07/2025

2. Ringkasan Pengujian:

Modul diuji: Login, Transaksi, Laporan

Tools: Postman, PHPUnit

3. Hasil Pengujian:

Modul	Status	Catatan
Login	✅ Pass	Berjalan normal
Transaksi	❌ Fail	Validasi error tidak muncul
Laporan	✅ Pass	Data sesuai

4. Analisis & Rekomendasi:

Modul transaksi perlu perbaikan fungsi validasi input.

Kempetensi 16

### 1.1 Kemampuan sistem diidentifikasi.
Tentukan fitur dan kemampuan utama sistem.

```
Contoh: Sistem penjualan mampu melakukan login, manajemen produk, transaksi, dan laporan.

### 1.2 Kebutuhan pelanggan disusun.
Susun daftar kebutuhan pengguna berdasarkan hasil analisis.

```
Contoh:

Pengguna dapat melihat produk.

Admin dapat menambah dan menghapus produk.

Sistem harus memberikan laporan penjualan.

### 1.3 Referensi petunjuk pelanggan ditentukan.
Tentukan sumber atau standar yang digunakan dalam penyusunan petunjuk teknis (manual pengguna, dokumentasi API, standar UI).

```
Contoh: Mengacu pada User Manual Template ISO 9126.

### 1.4 Laporan petunjuk dibuat.
Buat dokumen petunjuk teknis yang berisi cara penggunaan, instalasi, dan pemecahan masalah.

```
Contoh Ringkas Petunjuk Teknis CI3:

Instalasi:

Extract file project ke htdocs.

Konfigurasi database di application/config/database.php.

Cara Penggunaan:

Akses aplikasi melalui http://localhost/nama_aplikasi.

Pemecahan Masalah:

Jika database tidak terkoneksi, cek konfigurasi host dan user MySQL.

### 2.1 Petunjuk diberikan sesuai laporan petunjuk teknis.
Petunjuk yang disampaikan kepada pengguna harus mengacu pada dokumen petunjuk teknis yang telah dibuat.

Disampaikan secara jelas, baik secara tatap muka maupun online.

```
Contoh:

Memberikan demo penggunaan aplikasi penjualan CI3 sesuai langkah pada user manual.

Menjelaskan cara login, input data, dan mencetak laporan sesuai panduan.

### 2.2 Pelatihan diberikan sesuai laporan petunjuk teknis.
Lakukan pelatihan pengguna berdasarkan materi yang telah disiapkan.

Pelatihan dapat berupa: workshop, video tutorial, atau sesi langsung.

```
Contoh:

Mengadakan sesi pelatihan untuk admin toko mengenai cara mengelola produk dan transaksi di aplikasi.

Memberikan latihan langsung kepada pengguna untuk mencoba fitur-fitur aplikasi.

### 3.1 Masukan dari pelanggan dievaluasi.
Semua feedback dari pengguna (bug, saran fitur, kendala penggunaan) harus dicatat, dianalisis, dan ditindaklanjuti.

```
Contoh:

Pelanggan melaporkan error pada modul transaksi → tim mengevaluasi log error dan memperbaikinya.

Pelanggan meminta fitur export laporan → dimasukkan ke daftar pengembangan berikutnya.

### 3.2 Petunjuk teknis dapat dilakukan secara mandiri oleh pelanggan.
Pastikan dokumentasi petunjuk teknis cukup jelas agar pengguna dapat mengatasi masalah sederhana tanpa bantuan developer.

```
Contoh:

User manual menyediakan langkah pemecahan masalah koneksi database.

FAQ disediakan untuk menjawab pertanyaan umum pengguna.

# Kompetensi 17

### 1.1 Rencana instalasi perangkat lunak sesuai perangkat keras yang dibuat.
Pastikan perangkat keras mendukung software yang akan diinstal.

```
Contoh:

Untuk CI3, server harus memiliki PHP ≥ 5.6, MySQL, dan Apache/Nginx.

Untuk aplikasi Android, perangkat harus memiliki Android Studio dengan RAM minimal 8GB.

### 1.2 Langkah-langkah instalasi diidentifikasikan.
Identifikasi setiap tahapan instalasi sebelum eksekusi.

```
Contoh Langkah Instalasi CI3:

Download CodeIgniter 3 dari website resmi.

Extract ke folder htdocs (XAMPP) atau public_html (hosting).

Konfigurasi file application/config/config.php dan database.php.

Uji akses melalui browser http://localhost/ci3_app.

### 2.1 Instalasi perangkat lunak yang diakses secara langsung dilakukan.
Laksanakan proses instalasi sesuai langkah yang telah diidentifikasi.

```
Contoh Instalasi CI3:

Salin folder CI3 ke htdocs.

Konfigurasi base URL di config.php.

Atur koneksi database di database.php.

Jalankan di browser untuk memastikan instalasi berhasil.

### 2.2 Permasalahan instalasi perangkat keras diselesaikan.
Jika instalasi software terhambat karena hardware, lakukan troubleshooting.

```
Contoh:

Error karena Apache tidak jalan → periksa port XAMPP.

Laptop tidak mendukung virtualisasi → aktifkan fitur virtualisasi di BIOS.'

# Kompetensi 18

### 1.1 Informasi kritikal yang perlu untuk di log diidentifikasi.
Tentukan data penting yang harus dicatat untuk keperluan monitoring, debugging, dan keamanan.

```
Contoh pada aplikasi CI3:

Aktivitas login (user, waktu, IP).

Error sistem (query gagal, exception).

Akses API (endpoint, status response).

### 1.2 Lama penyimpanan informasi log ditentukan.
Tentukan kebijakan retensi log berdasarkan kebutuhan aplikasi dan regulasi.

```
Contoh:

Log error disimpan 90 hari untuk analisis bug.

Log aktivitas pengguna disimpan 1 tahun sesuai kebijakan keamanan.

### 2.1 Mekanisme pembuatan log aplikasi ditentukan.
Tentukan cara aplikasi mencatat log, misalnya:

Menggunakan logging bawaan CI3 (log_message()).

Menyimpan log ke file custom di folder tertentu.

Menyimpan log ke database untuk audit yang lebih detail.

```
Contoh Mekanisme di CI3:

Semua error dan aktivitas penting akan dicatat menggunakan fungsi log_message('level', 'pesan');.

### 2.2 Modul pembuatan log dari aplikasi berjalan dibuat.
Buat modul yang menangani pencatatan log otomatis.

```
Contoh Implementasi di CI3:

```php
<?php
defined('BASEPATH') OR exit('No direct script access allowed');

class Log_model extends CI_Model {

    // Simpan log ke database
    public function save_log($user, $action, $detail) {
        $data = [
            'user'      => $user,
            'action'    => $action,
            'detail'    => $detail,
            'log_time'  => date('Y-m-d H:i:s')
        ];
        $this->db->insert('app_logs', $data);
    }
}
Pemanggilan di Controller:

```php
$this->load->model('Log_model');
$this->Log_model->save_log('admin', 'login', 'User admin berhasil login');
Alternatif Logging ke File (Bawaan CI3):

```php
log_message('info', 'User admin berhasil login pada ' . date('Y-m-d H:i:s'));

### 3.1 Mekanisme pengumpulan log aplikasi untuk analisis ditentukan.
Tentukan cara pengumpulan log agar dapat dianalisis dengan mudah, misalnya:

Membaca log dari file (application/logs/).

Mengambil log dari database jika log disimpan di tabel.

Filter log berdasarkan tanggal, user, atau level (info, error, debug).

```
Contoh Mekanisme di CI3:

Log error disimpan di file log CI3.

Log aktivitas user disimpan dalam tabel app_logs agar dapat di-query.

### 3.2 Modul pengambilan data log dari aplikasi berjalan dibuat.
Buat modul (Model + Controller) untuk membaca log dari database atau file.

```
✅ Contoh Modul Pengambilan Log dari Database
```
Model: Log_model.php

```php
<?php
defined('BASEPATH') OR exit('No direct script access allowed');

class Log_model extends CI_Model {

    // Ambil semua log
    public function get_logs($limit = 50) {
        return $this->db->order_by('log_time', 'DESC')
                        ->limit($limit)
                        ->get('app_logs')
                        ->result();
    }

    // Ambil log berdasarkan user
    public function get_logs_by_user($user) {
        return $this->db->where('user', $user)
                        ->order_by('log_time', 'DESC')
                        ->get('app_logs')
                        ->result();
    }
}
```
Controller: Logs.php

```php
<?php
defined('BASEPATH') OR exit('No direct script access allowed');

class Logs extends CI_Controller {

    public function index() {
        $this->load->model('Log_model');
        $data['logs'] = $this->Log_model->get_logs();
        $this->load->view('logs_view', $data);
    }
}
```
View: logs_view.php

```php
<h3>Daftar Log Aplikasi</h3>
<table border="1" cellpadding="5">
    <tr><th>User</th><th>Aksi</th><th>Detail</th><th>Waktu</th></tr>
    <?php foreach($logs as $log): ?>
    <tr>
        <td><?= $log->user ?></td>
        <td><?= $log->action ?></td>
        <td><?= $log->detail ?></td>
        <td><?= $log->log_time ?></td>
    </tr>
    <?php endforeach; ?>
</table>

# Kompetensi 19

### 1.1 Referensi standar keamanan informasi diidentifikasi.
Identifikasi standar yang relevan untuk melindungi aset informasi organisasi.

```
Contoh Standar yang digunakan:

SNI-ISO/IEC 27001: standar internasional untuk Sistem Manajemen Keamanan Informasi (SMKI).

COBIT: framework untuk tata kelola dan manajemen TI.

NIST Cybersecurity Framework: panduan keamanan siber.

```
Contoh Penerapan:
Organisasi memilih SNI-ISO 27001 sebagai acuan untuk pengelolaan risiko keamanan informasi.

### 1.2 Prioritas penerapan standar keamanan informasi organisasi disetujui oleh pimpinan organisasi.
Setelah standar diidentifikasi, dibuat rencana prioritas penerapan (misalnya tahap audit, pelatihan, implementasi kontrol).

Persetujuan dari manajemen diperlukan agar standar dapat diterapkan secara efektif.

```
Contoh:

Tim keamanan TI menyusun roadmap implementasi ISO 27001 (tahun 1: audit awal, tahun 2: penerapan kontrol keamanan).

Pimpinan menyetujui prioritas ini melalui rapat manajemen.

### 2.1 Daftar komponen pokok standar keamanan untuk kebutuhan organisasi disusun.
Susun daftar kontrol keamanan utama dari standar (misalnya ISO 27001, COBIT) yang relevan dengan organisasi.

```
Contoh Komponen ISO 27001:

Kebijakan keamanan informasi.

Manajemen akses dan kontrol pengguna.

Pengelolaan aset TI dan enkripsi data.

Prosedur penanganan insiden keamanan.

```
Contoh Penerapan:
Organisasi e-commerce menyusun daftar kontrol seperti proteksi data pelanggan, backup sistem, dan audit akses pengguna.

### 2.2 Rekomendasi hasil analisa standar keamanan untuk kebutuhan strategis organisasi dibuat.
Lakukan analisis apakah setiap kontrol dapat diterapkan dengan efektif.

Berikan rekomendasi langkah strategis yang perlu dilakukan.

```
Contoh Rekomendasi:

Hasil Analisa: Sistem saat ini belum memiliki log aktivitas lengkap.

Rekomendasi: Implementasikan sistem SIEM (Security Information and Event Management) untuk monitoring.

Hasil Analisa: Tidak ada kebijakan enkripsi data pelanggan.

Rekomendasi: Terapkan enkripsi AES-256 untuk database sensitif.

### 3.1 Rincian pekerjaan untuk setiap peran/jabatan dalam organisasi dan akuntabilitas informasi untuk masing-masing peran/jabatan tersebut diidentifikasi.
Identifikasi role (peran) dalam organisasi serta hak akses yang sesuai untuk keamanan informasi.

```
Contoh Skema Role-Based Access Control (RBAC):

Admin Sistem: akses penuh ke konfigurasi server dan database.

Manajer TI: akses laporan keamanan, tidak bisa mengubah konfigurasi inti.

Staf Operasional: akses hanya pada aplikasi operasional sesuai tugasnya.

Pengguna Umum: akses terbatas hanya ke data pribadinya.

### 3.2 Prosedur tentang tugas dan tanggung jawab yang terkait dengan keamanan sistem informasi dibuat.
Susun prosedur yang menjelaskan tugas keamanan untuk setiap peran.

Prosedur harus mencakup:

Penggunaan akun dan password (misalnya kebijakan password kuat).

Pembatasan akses data berdasarkan peran.

Pelaporan insiden keamanan.

```
Contoh Penerapan:

Buat dokumen SOP keamanan informasi yang mengatur siapa yang dapat mengakses database, siapa yang bertanggung jawab atas backup, dan siapa yang menangani insiden siber.

### 4.1 Risiko sistem informasi, analisa dampak bisnis, dan rencana mitigasi disusun.
Identifikasi risiko yang dapat mengancam sistem informasi (contoh: serangan siber, kebocoran data, kerusakan hardware).

Analisis dampak bisnis dilakukan untuk melihat konsekuensi jika risiko terjadi.

Rencana mitigasi dibuat untuk meminimalkan dampak risiko.

```
Contoh Penerapan:

Risiko: Serangan ransomware.

Dampak: Gangguan operasional, kehilangan data.

Mitigasi: Backup rutin, patch keamanan, pelatihan karyawan.

### 4.2 Referensi untuk pembuatan kebijakan dan prosedur keamanan informasi diseleksi.
Pilih standar keamanan yang sesuai dengan kebutuhan organisasi.

```
Contoh Standar yang dapat dipilih:

ISO/IEC 27001 → untuk sistem manajemen keamanan informasi (SMKI).

COBIT → untuk tata kelola TI.

NIST CSF → untuk framework keamanan siber.

```
Contoh Penerapan:
Perusahaan memilih ISO 27001 sebagai acuan untuk kebijakan keamanan, karena sesuai dengan kebutuhan sertifikasi internasional.

Keomptensi 20

### 1.1 Laporan proyek, rencana navigasi, dan spesifikasi teknis untuk suatu produk multimedia dipelajari.

Pelajari dokumen proyek (flow navigasi, requirement teknis, dan tujuan aplikasi).

```
Contoh: Developer membaca dokumen proyek aplikasi e-learning yang berisi struktur menu, kebutuhan fitur, dan spesifikasi teknis.

### 1.2 Konsep dan spesifikasi didiskusikan dengan personel terkait untuk mengetahui konsep atau metafora desain.

Lakukan diskusi dengan tim (UI/UX designer, developer, client) untuk menentukan gaya interface.

```
Contoh: Tim sepakat menggunakan metafora desain card UI untuk aplikasi e-commerce.

### 1.3 Anggaran, halangan teknis, dan sumber diidentifikasi untuk memastikan bahwa seluruh persyaratan dipertimbangkan pada tiap tahapan desain.

Evaluasi budget, kendala teknologi (misalnya keterbatasan perangkat), dan ketersediaan sumber daya (designer, tools).

```
Contoh: Desain harus ringan karena target pengguna memakai smartphone low-end.

### 1.4 Kebutuhan klien dan pengguna/audience diklarifikasi untuk menentukan format interface yang digunakan.
Pastikan interface sesuai dengan kebutuhan pengguna akhir dan ekspektasi klien.

```
Contoh: Klien menginginkan aplikasi berbasis mobile-first dengan navigasi sederhana untuk pengguna awam.


```
