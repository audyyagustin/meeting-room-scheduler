# Meeting Room Scheduler

## Documentation of Meeting Room Scheduler System Design

---

## Deskripsi Project

Meeting Room Scheduler adalah sistem berbasis web yang dirancang untuk memudahkan proses pemesanan ruang meeting secara terstruktur dan efisien. Sistem ini dibuat untuk mendokumentasikan rancangan sistem booking ruang meeting yang mencakup alur proses bisnis, struktur data, relasi antar entitas, serta interaksi antar komponen sistem.

Dokumentasi pada repository ini disusun sebagai bagian dari pengembangan sistem dan ditujukan untuk menjelaskan secara rinci perancangan aplikasi sebelum implementasi penuh dilakukan. Melalui dokumentasi ini, pengguna dapat memahami bagaimana sistem bekerja, bagaimana data disusun, serta bagaimana alur booking berlangsung dari awal hingga akhir.

---

## Tujuan Project

Tujuan utama dari project ini adalah:

1. Memudahkan pengguna dalam melakukan pemesanan ruang meeting.
2. Membantu admin dalam mengelola data ruang dan data pemesanan.
3. Mencegah terjadinya bentrokan jadwal penggunaan ruang meeting.
4. Menghasilkan dokumentasi sistem yang jelas dan mudah dipahami.
5. Menjadi acuan dalam proses implementasi sistem di tahap berikutnya.

---

## Isi Repository

Repository ini berisi beberapa diagram dan dokumentasi sistem, yaitu:

- Activity Diagram.png
- ERD.png
- BPMN.png
- Use Case Diagram.png
- Class Diagram.png
- Sequence Diagram.png
- README.md

---

# Diagram Sistem

## 1. Activity Diagram

![Activity Diagram](Activity%20Diagram.png)

### Penjelasan

Activity Diagram digunakan untuk menggambarkan alur aktivitas yang terjadi dalam sistem Meeting Room Scheduler. Diagram ini menunjukkan urutan aktivitas mulai dari pengguna mengakses sistem, memilih ruang meeting, melakukan pemesanan, hingga sistem melakukan validasi dan menyimpan data booking.

Diagram ini membantu memahami alur kerja sistem secara keseluruhan sebelum proses implementasi dilakukan.

---

## 2. Entity Relationship Diagram (ERD)

![ERD](ERD.png)

### Penjelasan

Entity Relationship Diagram (ERD) digunakan untuk menggambarkan struktur basis data yang digunakan dalam sistem booking ruang meeting. Diagram ini menunjukkan entitas utama, atribut masing-masing entitas, serta hubungan antar entitas yang ada di dalam sistem.

Melalui ERD, hubungan antara data pengguna, data ruang meeting, dan data booking dapat dipahami dengan lebih jelas sehingga proses perancangan database menjadi lebih terstruktur dan konsisten.

---

## 3. BPMN (Business Process Model and Notation)

![BPMN](BPMN.png)

### Penjelasan

BPMN digunakan untuk menjelaskan proses bisnis yang terjadi dalam sistem secara menyeluruh. Diagram ini memperlihatkan tahapan aktivitas yang dilakukan oleh pengguna, sistem, dan admin selama proses pemesanan ruang meeting berlangsung.

BPMN membantu memberikan gambaran mengenai bagaimana proses booking dilakukan mulai dari pengajuan pemesanan hingga penyimpanan data ke dalam sistem.

---

## 4. Use Case Diagram

![Use Case Diagram](Use%20Case%20Diagram.png)

### Penjelasan

Use Case Diagram digunakan untuk menggambarkan interaksi antara aktor dengan sistem. Diagram ini menunjukkan siapa saja pihak yang terlibat dalam penggunaan sistem serta fungsi-fungsi yang dapat diakses oleh masing-masing aktor.

Pada sistem ini, aktor yang terlibat terdiri dari pengguna dan administrator.

---

## 5. Class Diagram

![Class Diagram](Class%20Diagram.png)

### Penjelasan

Class Diagram digunakan untuk menggambarkan struktur kelas yang terdapat dalam sistem. Diagram ini menunjukkan atribut, method, serta hubungan antar kelas yang digunakan sebagai dasar pengembangan aplikasi.

Dengan adanya Class Diagram, pengembang dapat memahami bagaimana objek dalam sistem saling berinteraksi dan bagaimana data dikelola dalam aplikasi.

---

## 6. Sequence Diagram

![Sequence Diagram](Sequence%20Diagram.png)

### Penjelasan

Sequence Diagram digunakan untuk menggambarkan urutan interaksi antar komponen sistem selama proses booking berlangsung. Diagram ini menunjukkan bagaimana pengguna mengirimkan permintaan pemesanan, bagaimana sistem melakukan validasi data, dan bagaimana data booking disimpan ke dalam database.

Diagram ini membantu menjelaskan alur komunikasi antar komponen secara lebih rinci dan sistematis.

---

# Deskripsi Alur Sistem

Berikut merupakan gambaran umum alur kerja sistem Meeting Room Scheduler:

### 1. Pengguna Mengakses Sistem

Pengguna membuka sistem untuk melihat informasi ruang meeting yang tersedia beserta jadwal penggunaannya.

### 2. Pengguna Memilih Ruang dan Jadwal

Pengguna memilih ruang meeting yang diinginkan serta menentukan tanggal dan waktu penggunaan sesuai kebutuhan.

### 3. Sistem Melakukan Validasi

Sistem melakukan pemeriksaan terhadap jadwal yang dipilih untuk memastikan bahwa ruang masih tersedia dan tidak terjadi bentrokan dengan booking lain.

### 4. Penyimpanan Data Booking

Apabila jadwal masih tersedia, sistem akan menyimpan data booking ke dalam database dan memberikan informasi bahwa proses pemesanan berhasil dilakukan.

### 5. Pengelolaan Data oleh Admin

Admin bertugas memantau aktivitas booking, mengelola data ruang meeting, serta memastikan seluruh proses berjalan sesuai kebutuhan organisasi.

### 6. Dokumentasi Sistem

Seluruh proses yang terjadi dalam sistem didokumentasikan melalui diagram yang tersedia pada repository ini sebagai dasar implementasi dan pengembangan sistem di masa mendatang.

---

## Struktur File

```text
meeting-room-scheduler/
├── README.md
├── Activity Diagram.png
├── BPMN.png
├── Class Diagram.png
├── ERD.png
├── Sequence Diagram.png
└── Use Case Diagram.png
```

---

# Kesimpulan

Berdasarkan hasil perancangan yang telah dilakukan, sistem Meeting Room Scheduler dirancang untuk membantu proses pemesanan ruang meeting secara lebih terstruktur, efisien, dan terdokumentasi dengan baik.

Melalui penggunaan Activity Diagram, ERD, BPMN, Use Case Diagram, Class Diagram, dan Sequence Diagram, seluruh kebutuhan sistem dapat digambarkan secara jelas mulai dari proses bisnis, struktur data, hingga interaksi antar komponen sistem.

Dokumentasi ini diharapkan dapat menjadi acuan dalam proses implementasi maupun pengembangan sistem di masa mendatang sehingga aplikasi dapat dibangun secara lebih terarah, terstruktur, dan sesuai dengan kebutuhan pengguna.
