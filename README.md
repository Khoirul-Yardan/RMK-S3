# Rangkuman Mata Kuliah Semester 3
**Oleh:** [Khoirul Yardan Mauluddin Zhorif]
## Daftar Isi
- [Basis Data Lanjut](#basis-data-lanjut)
- [Konsep Jaringan](#konsep-jaringan-komputer)










# Basis Data Lanjut

## 📌 Pengertian
**Basis Data Lanjut (Advanced Database)** adalah lanjutan dari mata kuliah dasar basis data yang membahas topik-topik lanjutan dalam pengelolaan, perancangan, serta optimasi sistem basis data. Materi ini dirancang agar mahasiswa mampu memahami struktur data kompleks, manajemen transaksi, dan teknologi terkini dalam dunia basis data.

---

## 🎯 Tujuan Pembelajaran
- Memahami konsep basis data non-relasional (NoSQL).
- Menguasai teknik optimasi query dan indexing.
- Mempelajari sistem manajemen basis data terdistribusi.
- Menguasai replikasi, backup, dan pemulihan data.
- Menerapkan konsep transaksi dan concurrency control.

---

## 🧩 Materi Utama

### 1. **Normalisasi dan Denormalisasi**
- Proses mengorganisir data untuk mengurangi redundansi.
- Bentuk Normal hingga BCNF.

### 2. **Indexing dan Optimasi Query**
- Membuat dan menggunakan index untuk mempercepat pencarian data.
- Analisis query plan dan tuning SQL.

### 3. **Transaksi dan Manajemen Konsistensi**
- Konsep transaksi (ACID: Atomicity, Consistency, Isolation, Durability).
- Concurrency Control (lock, deadlock, isolation level).

### 4. **Basis Data Terdistribusi**
- Data tersebar di banyak server/lokasi.
- Fragmentasi, replikasi, alokasi data.

### 5. **NoSQL (Not Only SQL)**
- Tipe NoSQL: Dokumen (MongoDB), Kolom (Cassandra), Key-Value (Redis), Graph (Neo4j).
- Kelebihan dan kekurangan NoSQL dibanding SQL.

### 6. **Data Warehouse dan OLAP**
- Sistem analitik untuk pengambilan keputusan.
- Perbedaan OLTP vs OLAP.

### 7. **Keamanan dan Backup Database**
- User privilege, authentication, enkripsi.
- Strategi backup dan recovery (full, incremental).

---

## 🛠️ Tools & Teknologi yang Digunakan
- **RDBMS**: MySQL, PostgreSQL, SQL Server
- **NoSQL**: MongoDB, Redis, Cassandra
- **Tools Tambahan**: pgAdmin, DBeaver, Mongo Compass

---

## ✅ Keterampilan yang Diperoleh
- Mendesain dan mengelola basis data berskala besar.
- Menyusun query SQL yang efisien dan optimal.
- Mengelola replikasi dan keamanan database.
- Menggunakan teknologi basis data modern (SQL & NoSQL).

---

## 💡 Studi Kasus (Contoh Aplikasi)
- Sistem e-commerce: memisahkan data produk dan transaksi menggunakan NoSQL + SQL.
- Sistem monitoring real-time: penggunaan Redis atau MongoDB untuk kecepatan tinggi.
- Data warehouse untuk laporan manajemen perusahaan.

---

## 🔚 Kesimpulan
**Basis Data Lanjut** merupakan fondasi penting untuk menjadi seorang database engineer, backend developer, atau data analyst. Dengan pemahaman mendalam, mahasiswa dapat merancang sistem informasi yang **efisien**, **andal**, dan **skalable**.

---

# Konsep Jaringan Komputer

# 🌐 Konsep Dasar Jaringan Komputer

## 📌 Pengertian
**Jaringan komputer** adalah kumpulan perangkat komputer dan perangkat keras lainnya yang saling terhubung melalui media komunikasi untuk berbagi data, informasi, dan sumber daya.

---

## 🎯 Tujuan Jaringan Komputer
- Berbagi data dan file antar perangkat.
- Mengakses sumber daya bersama (printer, storage).
- Komunikasi cepat (email, chat, video call).
- Efisiensi dan kolaborasi antar pengguna.

---

## 🧱 Komponen Utama Jaringan

| Komponen        | Fungsi                                                                 |
|-----------------|------------------------------------------------------------------------|
| **Node**        | Perangkat yang terhubung ke jaringan (PC, laptop, server).             |
| **Router**      | Menghubungkan jaringan berbeda dan menentukan jalur terbaik.           |
| **Switch**      | Menghubungkan banyak perangkat dalam satu jaringan lokal (LAN).        |
| **Modem**       | Menghubungkan jaringan ke internet melalui ISP.                        |
| **Media Transmisi** | Kabel (UTP, Fiber Optic) atau nirkabel (Wi-Fi).                      |

---

## 🧭 Jenis-Jenis Jaringan

### 1. **LAN (Local Area Network)**
- Jaringan skala kecil seperti di rumah atau kantor.
- Kecepatan tinggi dan cakupan terbatas.

### 2. **MAN (Metropolitan Area Network)**
- Jaringan yang mencakup area kota atau kampus.

### 3. **WAN (Wide Area Network)**
- Jaringan skala luas seperti internet.

### 4. **PAN (Personal Area Network)**
- Jaringan pribadi seperti Bluetooth atau Hotspot HP.

---

## 🌐 Topologi Jaringan

| Topologi        | Karakteristik                                                                          |
|-----------------|------------------------------------------------------------------------------------------|
| **Bus**         | Semua perangkat terhubung ke satu kabel utama.                                          |
| **Star**        | Perangkat terhubung ke switch/hub sebagai pusat.                                        |
| **Ring**        | Perangkat terhubung membentuk lingkaran.                                                |
| **Mesh**        | Semua perangkat saling terhubung secara langsung.                                       |
| **Tree**        | Gabungan topologi star dan bus.                                                         |

---

## 🔒 Protokol Jaringan

### 1. **TCP/IP (Transmission Control Protocol/Internet Protocol)**
- Protokol utama komunikasi di internet.

### 2. **HTTP/HTTPS**
- Digunakan untuk akses web (HTTPS = versi aman).

### 3. **FTP/SFTP**
- Digunakan untuk transfer file.

### 4. **DNS**
- Menerjemahkan nama domain ke IP address.

### 5. **DHCP**
- Memberikan IP address secara otomatis ke perangkat.

---

## 📶 Perangkat Jaringan

- **Access Point**: Menyediakan akses nirkabel ke jaringan.
- **Firewall**: Mengatur dan mengamankan lalu lintas data.
- **Repeater**: Memperluas jangkauan sinyal jaringan.
- **Proxy Server**: Bertindak sebagai perantara antara user dan internet.

---

## 🧠 Konsep IP Address & Subnetting
- IP Address: Alamat unik setiap perangkat dalam jaringan (contoh: `192.168.1.1`).
- Subnetting: Teknik membagi jaringan besar menjadi subnet kecil agar lebih efisien.

---

## 📊 Keamanan Jaringan
- Enkripsi data (SSL/TLS)
- VPN (Virtual Private Network)
- Autentikasi pengguna
- IDS/IPS (Intrusion Detection/Prevention System)

---

## 🛠️ Tools untuk Belajar Jaringan
- **Wireshark** – untuk analisis paket jaringan.
- **Cisco Packet Tracer** – untuk simulasi jaringan.
- **Nmap** – untuk pemindaian jaringan.
- **Netstat, ipconfig/ifconfig** – untuk melihat status jaringan.

---

## 🔚 Kesimpulan
Konsep jaringan komputer adalah pondasi penting dalam dunia IT. Dengan memahami dasar-dasar jaringan, kamu bisa membangun sistem yang terhubung, aman, dan efisien—baik untuk aplikasi lokal maupun berbasis internet.

---

