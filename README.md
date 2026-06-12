# Meeting Room Scheduler

Documentation of Meeting Room Scheduler System Design

---

## Deskripsi Project

Meeting Room Scheduler merupakan rancangan sistem pemesanan ruang meeting berbasis web yang dirancang untuk membantu proses pengelolaan penggunaan ruang meeting secara lebih terstruktur, efektif, dan efisien. Sistem ini dibuat sebagai dokumentasi perancangan sistem yang menjelaskan proses bisnis, struktur basis data, serta interaksi antar komponen yang terlibat dalam proses pemesanan ruang meeting.

Dalam suatu organisasi atau perusahaan, penggunaan ruang meeting sering kali menghadapi berbagai permasalahan, seperti bentrokan jadwal, kurangnya informasi mengenai ketersediaan ruang, serta kesulitan dalam melakukan pengelolaan data pemesanan. Oleh karena itu, diperlukan suatu sistem yang mampu mengelola proses booking ruang meeting secara terpusat sehingga penggunaan ruang dapat dilakukan secara lebih optimal.

Dokumentasi ini disusun sebagai bagian dari proses analisis dan perancangan sistem sebelum tahap implementasi dilakukan. Melalui dokumentasi ini, pengguna dapat memahami bagaimana sistem dirancang, bagaimana alur bisnis berjalan, bagaimana struktur basis data dibangun, serta bagaimana setiap komponen saling berinteraksi dalam mendukung proses booking ruang meeting.

---

## Tujuan Project

Tujuan utama dari perancangan sistem Meeting Room Scheduler adalah sebagai berikut:

1. Memudahkan pengguna dalam melakukan pemesanan ruang meeting secara terstruktur.
2. Membantu administrator dalam mengelola data ruang meeting dan data pemesanan.
3. Mengurangi kemungkinan terjadinya bentrokan jadwal penggunaan ruang meeting.
4. Menyediakan informasi ketersediaan ruang meeting secara lebih jelas dan akurat.
5. Menghasilkan dokumentasi sistem yang dapat digunakan sebagai acuan dalam proses implementasi dan pengembangan sistem.
6. Memberikan gambaran menyeluruh mengenai proses bisnis dan kebutuhan sistem melalui berbagai diagram perancangan.

---

## Isi Repository

Repository ini berisi dokumentasi dan diagram yang digunakan dalam proses perancangan sistem Meeting Room Scheduler, yaitu:

- `Activity Diagram.png`
- `BPMN.png`
- `ERD.png`
- `Use Case Diagram.png`
- `Class Diagram.png`
- `Sequence Diagram.png`
- `README.md`

---

## Diagram Sistem

### 1. Activity Diagram

![Activity Diagram](Activity%20Diagram.png)

#### Penjelasan

Activity Diagram digunakan untuk menggambarkan alur aktivitas yang terjadi dalam sistem Meeting Room Scheduler. Diagram ini menunjukkan urutan kegiatan yang dilakukan oleh pengguna dan sistem mulai dari proses mengakses sistem, memilih ruang meeting, melakukan booking, hingga sistem melakukan validasi dan menyimpan data pemesanan.

Melalui diagram ini dapat dipahami bagaimana setiap aktivitas saling berhubungan serta bagaimana sistem merespons tindakan yang dilakukan oleh pengguna selama proses pemesanan ruang meeting berlangsung.

---

### 2. BPMN (Business Process Model and Notation)

![BPMN](BPMN.png)

#### Penjelasan

Business Process Model and Notation (BPMN) digunakan untuk menggambarkan proses bisnis yang terjadi dalam sistem secara menyeluruh. Diagram ini memperlihatkan alur kerja yang melibatkan pengguna, sistem, dan administrator dalam proses pengelolaan ruang meeting.

Melalui BPMN dapat diketahui bagaimana proses dimulai dari pengguna melakukan permintaan booking, sistem melakukan validasi jadwal, hingga data pemesanan berhasil disimpan. BPMN membantu memberikan gambaran yang jelas mengenai proses operasional sistem sebelum dilakukan implementasi.

---

### 3. Entity Relationship Diagram (ERD)

![ERD](ERD.png)

#### Penjelasan

Entity Relationship Diagram (ERD) digunakan untuk menggambarkan struktur basis data yang digunakan pada sistem Meeting Room Scheduler. Diagram ini menunjukkan entitas yang terlibat dalam sistem beserta atribut dan hubungan antar entitas tersebut.

ERD membantu dalam memahami bagaimana data pengguna, data ruang meeting, dan data booking saling berhubungan sehingga proses penyimpanan dan pengelolaan data dapat dilakukan secara terintegrasi dan konsisten.

---

### 4. Use Case Diagram

![Use Case Diagram](Use%20Case%20Diagram.png)

#### Penjelasan

Use Case Diagram digunakan untuk menggambarkan hubungan antara aktor dengan sistem. Diagram ini menunjukkan fungsi-fungsi yang dapat dijalankan oleh setiap aktor sesuai dengan hak akses yang dimiliki.

Dalam sistem Meeting Room Scheduler, aktor yang terlibat terdiri dari pengguna dan administrator. Pengguna dapat melakukan aktivitas seperti melihat ketersediaan ruang dan melakukan booking, sedangkan administrator memiliki tanggung jawab untuk mengelola data ruang dan memantau aktivitas pemesanan yang terjadi.

---

### 5. Class Diagram

![Class Diagram](Class%20Diagram.png)

#### Penjelasan

Class Diagram digunakan untuk menjelaskan struktur kelas yang terdapat dalam sistem. Diagram ini memperlihatkan atribut, metode, serta hubungan antar kelas yang digunakan sebagai dasar dalam proses pengembangan aplikasi.

Melalui Class Diagram, pengembang dapat memahami bagaimana objek dalam sistem saling berinteraksi dan bagaimana data dikelola dalam setiap komponen yang membentuk aplikasi Meeting Room Scheduler.

---

### 6. Sequence Diagram

![Sequence Diagram](Sequence%20Diagram.png)

#### Penjelasan

Sequence Diagram digunakan untuk menggambarkan urutan interaksi antar objek atau komponen sistem selama proses booking berlangsung. Diagram ini menunjukkan bagaimana pengguna mengirimkan permintaan pemesanan, bagaimana sistem melakukan validasi, dan bagaimana data booking disimpan ke dalam basis data.

Dengan adanya Sequence Diagram, alur komunikasi antar komponen dapat dipahami secara lebih rinci sehingga memudahkan proses analisis dan implementasi sistem.

---

## Deskripsi Alur Sistem

Berikut merupakan gambaran umum alur kerja sistem Meeting Room Scheduler:

### 1. Pengguna Mengakses Sistem

Pengguna membuka sistem untuk melihat informasi ruang meeting yang tersedia beserta jadwal penggunaannya.

### 2. Pengguna Memilih Ruang dan Jadwal

Pengguna memilih ruang meeting yang diinginkan serta menentukan tanggal dan waktu penggunaan sesuai kebutuhan.

### 3. Sistem Melakukan Validasi

Sistem melakukan pemeriksaan terhadap jadwal yang dipilih untuk memastikan bahwa ruang masih tersedia dan tidak terjadi bentrokan dengan booking lain yang telah tersimpan sebelumnya.

### 4. Penyimpanan Data Booking

Apabila jadwal yang dipilih masih tersedia, sistem akan menyimpan data booking ke dalam basis data dan memberikan informasi bahwa proses pemesanan berhasil dilakukan.

### 5. Pengelolaan Data oleh Administrator

Administrator bertanggung jawab untuk memantau aktivitas booking, mengelola data ruang meeting, serta memastikan seluruh proses berjalan sesuai dengan kebutuhan organisasi.

### 6. Dokumentasi Sistem

Seluruh proses yang terjadi dalam sistem didokumentasikan melalui berbagai diagram perancangan yang tersedia pada repository ini sebagai dasar implementasi dan pengembangan sistem di masa mendatang.

---

## Struktur File

Meeting-room-scheduler/
├── README.md
├── Activity Diagram.png
├── BPMN.png
├── Class Diagram.png
├── ERD.png
├── Sequence Diagram.png
└── Use Case Diagram.png

---

## Kesimpulan

Berdasarkan hasil analisis dan perancangan yang telah dilakukan, sistem Meeting Room Scheduler dirancang untuk membantu proses pemesanan ruang meeting secara lebih terstruktur, efisien, dan terdokumentasi dengan baik. Melalui pemanfaatan berbagai diagram perancangan seperti Activity Diagram, BPMN, ERD, Use Case Diagram, Class Diagram, dan Sequence Diagram, seluruh kebutuhan sistem dapat digambarkan secara jelas mulai dari proses bisnis, struktur basis data, hingga interaksi antar komponen sistem.

Dokumentasi yang disusun dalam repository ini memberikan gambaran menyeluruh mengenai mekanisme kerja sistem, mulai dari proses pemilihan ruang, validasi jadwal, penyimpanan data booking, hingga proses pengelolaan data oleh administrator. Dengan adanya dokumentasi yang lengkap dan sistematis, proses implementasi aplikasi diharapkan dapat dilakukan dengan lebih terarah karena seluruh kebutuhan fungsional dan struktur sistem telah dirancang sebelumnya.

Selain sebagai dokumentasi akademik, rancangan sistem ini juga dapat menjadi dasar pengembangan aplikasi Meeting Room Scheduler yang lebih kompleks di masa mendatang, baik untuk kebutuhan organisasi, institusi pendidikan, maupun perusahaan yang membutuhkan pengelolaan ruang meeting secara terintegrasi.
