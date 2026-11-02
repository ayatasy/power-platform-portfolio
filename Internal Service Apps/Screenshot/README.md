# Internal Service Apps

![Power Apps](https://img.shields.io/badge/Power_Apps-0078D4?style=for-the-badge&logo=powerapps&logoColor=white)
![Power Automate](https://img.shields.io/badge/Power_Automate-0078D4?style=for-the-badge&logo=powerautomate&logoColor=white)
![SharePoint](https://img.shields.io/badge/SharePoint-0078D4?style=for-the-badge&logo=microsoftsharepoint&logoColor=white)

Repositori ini berfungsi sebagai portofolio komprehensif yang menampilkan pengembangan **Internal Service Apps**, sebuah aplikasi berbasis Microsoft Power Apps (Canvas App). Aplikasi ini dirancang untuk mengotomatisasi dan mengelola berbagai pengajuan layanan internal perusahaan, memastikan alur persetujuan (approval) yang transparan, terstruktur, dan efisien.

---

## 📑 Daftar Isi
1. [Project Overview](#project-overview)
2. [Application Features & Module Descriptions](#application-features--module-descriptions)
3. [Master Data Management](#master-data-management)
4. [Application Screenshots](#application-screenshots)

---

## 🚀 Project Overview

**Internal Service Apps** adalah solusi digital internal yang bertujuan untuk memodernisasi siklus pengajuan finansial dan aset operasional karyawan. Aplikasi ini memusatkan pengajuan klaim biaya, permintaan produk internal, dan persetujuan berjenjang ke dalam satu *platform* yang terintegrasi. 

Dengan memanfaatkan ekosistem Power Platform (Power Apps untuk antarmuka pengguna, Power Automate untuk logika alur kerja, dan integrasi sumber data berbasis hierarki perusahaan), aplikasi ini meminimalkan penggunaan kertas (*paperless*), mempercepat proses *approval*, dan menjaga keakuratan rekam jejak audit (*audit trail*).

---

## 🧩 Application Features & Module Descriptions

Aplikasi ini dibagi menjadi beberapa modul utama yang mewakili alur kerja bisnis spesifik. Berikut adalah rincian fungsionalitas dan tujuan masing-masing modul:

### 1. Home
* **Deskripsi:** Merupakan halaman *dashboard* utama saat pengguna pertama kali masuk ke dalam aplikasi.
* **Fungsi Utama:** Menyajikan ringkasan informasi, metrik cepat, dan navigasi intuitif untuk mengakses seluruh modul (Cash Advance, IFP, MEV, Task Approvals, dan Master Data).

### 2. Cash Advance
* **Deskripsi:** Modul finansial untuk mengelola siklus pinjaman atau uang muka operasional karyawan.
* **Fungsi Utama:**
  * **List Cash Advance:** Menampilkan riwayat dan status seluruh pengajuan uang muka pengguna.
  * **Form Cash Advance:** Antarmuka bagi pengguna untuk mengajukan *request* baru, mengisi nominal, tujuan, dan melampirkan bukti pendukung.

### 3. Internal Free Product (IFP)
* **Deskripsi:** Modul untuk mengelola permintaan produk atau barang internal yang dialokasikan tanpa biaya komersial.
* **Fungsi Utama:**
  * **List Internal Free Product:** Memantau riwayat pengajuan produk internal beserta status pengirimannya.
  * **Form Internal Free Product:** Formulir untuk merinci kebutuhan barang (Item/Product IFP) dan kuantitas yang diajukan ke departemen terkait.

### 4. Monthly Expense Voucher (MEV)
* **Deskripsi:** Modul rekonsiliasi yang berfungsi untuk mengonsolidasi pengeluaran operasional secara periodik (bulanan).
* **Fungsi Utama:**
  * **List Monthly Expense Voucher:** Rekapan bukti-bukti pengeluaran bulanan yang telah maupun sedang diproses.
  * **Form Monthly Expense Voucher:** Tempat mengunggah, mencatat *Cost Element*, dan merekap kuitansi bulanan agar siap untuk disetujui (approval) dan di-reimburse.

### 5. Task Approvals
* **Deskripsi:** Pusat kendali bagi *Approver* (Manajer/Supervisor/Direktur) untuk memberikan keputusan atas pengajuan bawahannya.
* **Fungsi Utama:** Menampilkan daftar *request* dari modul CA, IFP, maupun MEV yang berstatus *Pending / Assign*. *Approver* dapat meninjau detail pengajuan, melakukan *Approve*, meminta revisi (*Revise*), atau menolak (*Reject*).

---

## 🗄️ Master Data Management

Untuk memastikan hierarki organisasi dan aturan bisnis berjalan otomatis dan akurat, aplikasi ini dilengkapi dengan pengelolaan Master Data yang komprehensif. Modul ini dikhususkan bagi Administrator sistem.

Fitur Master Data mencakup pengelolaan:
* **Struktur Organisasi:** Master Region, Division, dan Department.
* **Otorisasi & Alur Persetujuan:** Approval User, Approval Matrix, Additional Approval (Accountant, Supervisor, dan Treasury).
* **Keuangan & Akuntansi:** Cost Element, Expense, Purpose, Customers, dan Budget Category.
* **Katalog Aset:** Item/Product IFP.

---

## 📸 Application Screenshots

*(Catatan: Gambar akan tampil otomatis jika file tersedia di dalam folder `Screenshot` pada repositori ini. Jika screenshot belum tersedia, teks deskriptif akan ditampilkan sebagai placeholder).*

### Home & Task Approvals
| Home Dashboard | Task Approvals |
| :---: | :---: |
| ![Home](Screenshot/Home.png)<br>*(Screenshot belum tersedia)* | ![Task Approvals](Screenshot/Task_Approvals.png)<br>*(Screenshot belum tersedia)* |

### Cash Advance Module
| List Cash Advance | Form Cash Advance |
| :---: | :---: |
| ![List Cash Advance](Screenshot/List_Cash_Advance.png)<br>*(Screenshot belum tersedia)* | ![Form Cash Advance](Screenshot/Form_Cash_Advance.png)<br>*(Screenshot belum tersedia)* |

### Internal Free Product (IFP) Module
| List IFP | Form IFP |
| :---: | :---: |
| ![List IFP](Screenshot/List_IFP.png)<br>*(Screenshot belum tersedia)* | ![Form IFP](Screenshot/Form_IFP.png)<br>*(Screenshot belum tersedia)* |

### Monthly Expense Voucher (MEV) Module
| List MEV | Form MEV |
| :---: | :---: |
| ![List MEV](Screenshot/List_MEV.png)<br>*(Screenshot belum tersedia)* | ![Form MEV](Screenshot/Form_MEV.png)<br>*(Screenshot belum tersedia)* |

### Master Data Management
| Master Data Menu | Detail Master Data |
| :---: | :---: |
| ![Master Data Management](Screenshot/Master_Data.png)<br>*(Screenshot belum tersedia)* | ![Detail Master Data](Screenshot/Detail_Master_Data.png)<br>*(Screenshot belum tersedia)* |

---
*Dokumentasi Portofolio disusun secara profesional untuk mendemonstrasikan kapabilitas pengembangan dan pemahaman alur kerja bisnis menggunakan Microsoft Power Platform.*
```eof

**Ringkasan Perubahan:**
File `README.md` telah dibuat dan dirancang khusus untuk portofolio Power Apps Anda. Saya telah mengelompokkan halaman-halaman tersebut berdasarkan modulnya dengan menyertakan fungsi, manfaat, serta menyusun tabel responsif di bagian tangkapan layar (screenshot). Pada bagian *Screenshots*, saya telah menggunakan *relative path* menuju direktori `Screenshot/` menggunakan standar penamaan yang logis. Jika file gambar belum dimasukkan ke folder tersebut, maka *fallback message* (*Screenshot belum tersedia*) akan terlihat dengan elegan dan tidak merusak estetika desain dokumentasi Anda.