# LA7_RPL2_KHANSA

## Daftar dan Penjelasan Isi Folder

### pert1_rpl2

Proyek Java dasar menggunakan Maven. Berisi program sederhana pada file `Pert1_rpl2.java` sebagai penerapan dasar bahasa pemrograman Java.
Folder `target/` berisi file hasil kompilasi otomatis Maven.

---

### pert2_rpl2

Implementasi konsep Object-Oriented Programming (OOP).
Terdapat class `User`, `Admin`, `Seller`, dan `Buyer` yang menunjukkan penerapan inheritance dan polimorfisme.
Folder `target/` merupakan hasil kompilasi program.

---

### pert3_rpl2

Penerapan arsitektur MVC (Model - View - Controller) dalam aplikasi pengelolaan data mahasiswa.
Struktur utama:

* Model: `ModelMahasiswa`, `MahasiswaDAO`
* View: `MahasiswaView`
* Controller: `MahasiswaController`

Aplikasi menyediakan antarmuka sederhana untuk manipulasi data mahasiswa.

---

### pert4_rpl2

Pengembangan aplikasi menggunakan arsitektur MVC yang terhubung ke database melalui Hibernate (ORM).
Fitur utama:

* Operasi CRUD pada data mahasiswa
* GUI menggunakan Swing
* Pemisahan layer Controller, Model, dan View secara lebih terstruktur
  Dilengkapi file konfigurasi Hibernate `hibernate.cfg.xml`.

---

### pert5_rpl2

Proyek Spring Boot untuk pengelolaan data mahasiswa berbasis REST.
Struktur aplikasi terdiri dari Controller, Model, dan Repository sebagai dasar pengembangan aplikasi backend dengan Spring.

---

### pert6_rpl2

Penggabungan Spring Boot dengan tampilan GUI desktop menggunakan Swing.
Struktur aplikasi meliputi:

* Service: logika bisnis
* Controller: pengendali alur data
* Repository: pengelolaan database
* View: antarmuka pengguna

Konfigurasi aplikasi terdapat pada `application.properties`.
