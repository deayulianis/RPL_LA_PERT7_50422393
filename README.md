# 📘 **README – Penjelasan ACT 3, ACT 4, ACT 5, ACT 6 (RPL 2)**

Dokumen ini berisi rangkuman singkat dan jelas mengenai isi setiap ACT (Activity) pada mata praktikum **Rekayasa Perangkat Lunak 2**, mulai dari konsep dasar MVC hingga implementasi Spring Boot + Hibernate.

---

## 🧩 **ACT 3 – Penerapan Model–View–Controller (MVC)**

### **Deskripsi Singkat**

ACT 3 membahas implementasi arsitektur **MVC (Model–View–Controller)** pada aplikasi Java.

### **Isi Utama**

* **Model**

  * Berisi struktur data Mahasiswa serta logic untuk mengakses database.
* **View**

  * Antarmuka GUI (Java Swing) untuk menampilkan dan menginput data mahasiswa.
* **Controller**

  * Mengatur alur data antara View dan Model.
* **Konfigurasi pom.xml**

  * Menambahkan dependensi yang dibutuhkan.
* **Output Program**

  * Menampilkan aplikasi mahasiswa berbasis MVC.

### **Fokus Pembelajaran**

✔ Memahami pemisahan tugas antara Model, View, dan Controller.
✔ Membuat kode lebih terstruktur dan mudah dirawat.

---

## 🧩 **ACT 4 – Pengembangan CRUD dalam Struktur MVC**

### **Deskripsi Singkat**

ACT 4 melanjutkan ACT 3 dengan menambahkan fitur **CRUD** (Create, Read, Update, Delete) ke dalam arsitektur MVC.

### **Isi Utama**

* Form input data mahasiswa.
* Tabel untuk menampilkan seluruh data.
* Controller yang mengatur fungsi tambah, hapus, edit, dan tampil data.
* Penyempurnaan interaksi View ↔ Controller ↔ Model.

### **Fokus Pembelajaran**

✔ Mengimplementasikan CRUD ke dalam arsitektur MVC.
✔ Mengelola alur data dari GUI ke database.

---

## 🧩 **ACT 5 – Implementasi Hibernate & ORM**

### **Deskripsi Singkat**

ACT 5 mengenalkan penggunaan **Hibernate/JPA** sebagai ORM (Object Relational Mapping) untuk menggantikan SQL manual.

### **Isi Utama**

* Entity dengan anotasi Hibernate (`@Entity`, `@Id`, dll).
* Repository untuk mengakses database tanpa query SQL.
* Konfigurasi Hibernate di `application.properties`.
* Interaksi CRUD melalui ORM.

### **Fokus Pembelajaran**

✔ Mengenal ORM untuk mempermudah pemetaan data ke database.
✔ Memahami cara Hibernate otomatis membuat query.

---

## 🧩 **ACT 6 – Spring Boot + Hibernate + MVC + Dependency Injection**

### **Deskripsi Singkat**

ACT 6 adalah tahap paling lanjut, mengintegrasikan **Spring Boot**, **Hibernate**, dan **Java Swing**.

### **Isi Utama**

* **pom.xml**

  * Menggunakan dependensi Spring Boot, Spring Data JPA, MySQL.
* **ModelMahasiswa & ModelTabelMahasiswa**

  * Entity + model tabel untuk GUI.
* **Repository (JpaRepository)**

  * Akses database otomatis tanpa query manual.
* **Service Layer**

  * Logika bisnis, menggunakan **Dependency Injection** (`@Autowired`).
* **Controller**

  * Menghubungkan View ↔ Service.
* **View (Swing)**

  * Menu input, tombol CRUD, tabel data.
* **Application Properties**

  * Konfigurasi database + Hibernate.
* **MahasiswaApp**

  * Class utama untuk menjalankan Spring Boot & membuka GUI.

### **Fokus Pembelajaran**

✔ Integrasi Spring Boot dengan aplikasi desktop (Swing).
✔ Penerapan Dependency Injection pada Service dan Repository.
✔ Penggunaan Hibernate melalui JpaRepository.

---

## 🏁 **Kesimpulan Akhir**

Setiap ACT membangun kemampuan secara bertahap:

| ACT       | Fokus Utama                  | Teknologi                     |
| --------- | ---------------------------- | ----------------------------- |
| **ACT 3** | Pemahaman MVC                | Java Swing + Database         |
| **ACT 4** | CRUD dalam MVC               | Java Swing                    |
| **ACT 5** | ORM dengan Hibernate         | JPA + Hibernate               |
| **ACT 6** | Spring Boot + Hibernate + DI | Spring Boot, Hibernate, Swing |

Semakin lanjut ACT, semakin kompleks integrasi dan arsitektur yang digunakan.
