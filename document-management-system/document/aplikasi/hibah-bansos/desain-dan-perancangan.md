---
layout: document
title: Desain dan Perancangan E-HibahBansos
description: Desain dan perancangan untuk aplikasi ehibahbansos yang digunakan pada Provinsi Banten.
group: aplikasi
cat: E-hibahbansos
toc: true
---

## ABSTRAK
Dewasa ini perkembangan teknologi komputer sangatlah pesat. Dengan menggunakan aplikasi komputer akan didapat informasi mengenai suatu tampilan objek yang ditampilkan lebih hidup dan menarik. Adanya kemajuan teknologi ini memungkinkan Sistem untuk menjalankan prosedur pemberian dana hibah dan bantuan sosial dapat berjalan lebih baik dan membantu masyarakat dan Pemerintah Provinsi Banten dalam menjalankan kegiatan yang berkaitan dengan hibah dan bantuan sosial yang lebih terstruktur dan lebih transparansi.


## 1. PENDAHULUAN

### 1.1 Latar Belakang
Pembangunan Sistem informasi / aplikasi / website saat ini yang berlangsung di lingkungan Pemerintah Provinsi Banten seakan – akan berjalan sendiri – sendiri.
Meskipun sudah ada Peraturan Gubernur No. 35 Tahun 2008 dan Peraturan Gubernur No. 80, belum menjadikan panduan dalam mengembangkan sistem informasi / aplikasi tersebut.
Agar terdapatnya sebuah sitem yang baik dalam menyelenggarakan kegiatan hibah dan bansos maka perlu dibuatnya suatu fasilitas untuk mendukung kegiatan tersebut. dengan dibuatnya aplikasi E-hibahbansos diharapkan dapat memudahkan segala proses kegiatan E-hibahbansos baik dari sisi pemerintahan maupun masyarakat Provinsi Banten.
### 1.2 Maksud dan Tujuan
#### a) Maksud
Maksud dari kegiatan ini adalah untuk melakukan kegiatan pengembangan Sistem Informasi E-hibahbansos.
#### b) Tujuan
Sistem ehibahbansos Provinsi Banten dibangun dengan tujuan untuk terciptanya efisiensi proses, perbaikan prosedur, peningkatan transparansi dan akuntabilitas belanja hibah, bantuan sosial dan bantuan keuangan pada Pemerintah Provinsi Banten.
### 1.3 Ruang Lingkup Pekerjaan
Ruang lingkup pekerjaan ini adalah pengembangan sistem informasi ini dilakukan di Dinas Komunikasi Informasi Statistika dan Persandian Provinsi Banten, adapun hasil dari kegiatan ini untuk dapat digunakan pada instansi dan masyarakat dilingkungan Pemerintah Provinsi Banten.
### 1.4 Ruang Lingkup Sistem Informasi / Aplikasi
a) Menyediakan situs bagi seluruh Organisasi Perangkat Daerah yang ada dilingkungan Pemerintah Provinsi Banten untuk menyimpan Prosedur Operasional Baku yang berlaku dilingkungannya secara digital,
b) Menyediakan proses pengaduan pengadaan / pengembangan sistem informasi / aplikasi / website secara digital untuk seluruh Organisasi Perangkat Daerah dilingkungan Pemeeritah Provinsi Banten.
### 1.5 Keluaran yang diinginkan
a) Tersedianya sistem informasi e-hibahbansos bagi sistem informasi / aplikasi / website,
b) Tersedianya dokumen API yang digunakan.
### 1.6 Waktu dan Jadwal Pelaksanaan dan Lokasi Kegiatan
a) Waktu pelaksanaan kegiatan : 3 bulan sejak dikeluarkan SPK sampai dengan pemakaian,
b) Lokasi kegiatan : Kantor OPD terkait dan Dinas Komunikasi Informasi Statistika dan Persandian Pemerintah Provinsi Banten.
## 2. METODE PENELITIAN
Untuk memperoleh data yang dapat menunjang aplikasi ini, maka di perlukan data teoritis dan data dinas terkait untuk mendapatkan data dan informasi yang berhubungan dengan aplikasi ini.
Adapun penyusun melakukan beberapa penelitian yang dilakukan dengan :
### 2.1 Metode Yang digunakan
Menggunakan metode *prototyping* untuk melakukan perancangan sistem informasi berbasis web.
Ilustrasi alur *prototyping*
[![ilustrasi-alur-prototyping](../hibah-bansos/images/desain-dan-perancangan/alur-prototype.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/alur-prototype.png)
### 2.2 Metode Pengumpulan Data
Untuk mengumpulkan data yang diperlukan untuk membangun sistem ini diadakan wawancara dan studi pustaka. Pengumpulan data ini diperlukan untuk mengetahui permasalahan dan gambaran sistem yang sedang berjalan sehingga dapat mengembangkannya untuk membentuk sistem baru yang dapat mendukung sistem yang sedang berjalan.
1). Wawancara ini dilakukan kepada Pemprov Banten. Wawancara dilakukan kepada sistem analist Pemprov Banten untuk mengetahui permasalahan dalam proses pendataan yang sedang berjalan sekarang.
2). Studi Pustaka, Melakukan pengumpulan melalui buku text, internet sebagai referensi.
## 3. HASIL PEMBAHASAN
### 3.1 Perencanaan Aplikasi
Sistem informasi e-hibahbansos adalah untuk mempermudah pemerintah dan masyarakat dalam menyenggarakan kegiatan hibah dan bantuan sosial.
### 3.2. Perancangan Sistem
Permodelan rancangan sistem yang digunakan adalah UML (Unified Modeling Language). Menurut Whitten dan Bentley (2007, p.381), Unified Modeling Language adalah kumpulan rancangan diagram untuk membangun sebuah sistem atau aplikasi yang dimana setiap diagram menyediakan sistem informasi kepada tim pengembang dengan berbagai sudut pandang yang berbeda-beda. UML yang kami gunakan terdiri dari use case diagram, activity diagram, sequence diagram, state chart diagram, class diagram, deploymen diagram dan technology diagram.

### 3.2.1 Use Cace Diagram
#### 3.2.1.1 Use Case Diagram Super Admin
[![use-case-diagram-super-admin](../hibah-bansos/images/desain-dan-perancangan/usecase_superadmin.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/use-case-super-admin.jpg)

#### 3.2.1.1 Use Case Diagram Pendaftar Hibah
[![use case diagram Pendaftar Hibah](../hibah-bansos/images/desain-dan-perancangan/usecase_pelapor.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/use-case-diagram-admin.jpg)
#### 3.2.1.2 Use Case Diagram Organisasi Perangkat Daerah (OPD)
[![use-case-diagram-opd](../hibah-bansos/images/desain-dan-perancangan/usecase_opd.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/use-case-dinas.jpg)
#### 3.2.1.3 Use Case Diagram Inspektorat
[![use-case-diagram-Inspektorat](../hibah-bansos/images/desain-dan-perancangan/usecase_inspektorat.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/use-case-dinas.jpg)
#### 3.2.1.4 Use Case Diagram TAPD
[![use-case-diagram-TAPD](../hibah-bansos/images/desain-dan-perancangan/usecase_tapd.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/use-case-dinas.jpg)
#### 3.2.1.5 Use Case Diagram BPKAD
[![use-case-diagram-BPKAD](../hibah-bansos/images/desain-dan-perancangan/usecase_bpkad.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/use-case-dinas.jpg)

### 3.2.2 Activity Diagram

#### 3.2.2.1 Activity Diagram Super Admin
[![activity-diagram-super-admin](../hibah-bansos/images/desain-dan-perancangan/activitydiagram_superadmin.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/activity-diagram-super-admin.jpg)
#### 3.2.2.2 Activity Diagram Kegiatan Belanja Hibah Bansos
[![activity-diagram-kegiatan-belanja-dana-hibah-bansos](../hibah-bansos/images/desain-dan-perancangan/activitydiagram_workflow-hibahbansos.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/activity-diagram-input-data-super-admin.jpg)
### 3.2.3 Sequence Diagram
#### 3.2.3.1 Sequence Diagram Login Super Admin
[![sequence-diagram-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-super-admin.jpg)
#### 3.2.3.2 Sequence Diagram Input Data Super Admin
[![sequence-diagram-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-super-admin.jpg)
#### 3.2.3.3 Sequence Diagram Edit Data Super Admin
[![sequence-diagram-edit-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-edit-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-edit-data-admin.jpg)
#### 3.2.3.4 Sequence Diagram Delete Data Super Admin
[![sequence-diagram-delete-data-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-delete-data-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-delete-data-super-admin.jpg)
#### 3.2.3.5 Sequence Diagram View Data Super Admin
[![sequence-diagram-view-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-view-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-view-super-admin.jpg)
#### 3.2.3.6 Sequence Diagram Login Admin
[![sequence-diagram-login-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-login-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-login-admin.jpg)
#### 3.2.3.7 Sequence Diagram Input Data Admin
[![sequence-diagram-input-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-input-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-input-data-admin.jpg)
#### 3.2.3.8 Sequence Diagram Edit Data Admin
[![sequence-diagram-edit-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-edit-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-edit-data-admin.jpg)
#### 3.2.3.9 Sequence Diagram Delete Data Admin
[![sequence-diagram-delete-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-delete-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-delete-data-admin.jpg)
#### 3.2.3.10 Sequence Diagram View Data Admin
[![sequence-diagram-view-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-view-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-view-data-admin.jpg)
#### 3.2.3.11 Sequence Diagram Login Gubernur
[![sequence-diagram-login-gubernur](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-login-gubernur.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-login-gubernur.jpg)
#### Sequence Diagram View Gubernur
[![sequence-diagram-view-gubernur](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-view-gubernur.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/sequence-diagram-view-gubernur.jpg)
### 3.2.4 State Chart Diagram
#### 3.2.4.1 State Chart Diagram Login Super Admin
[![state-chart-diagram-login-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-login-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-login-super-admin.jpg)
#### 3.2.4.2 State Chart Diagram Input Data Super Admin
[![state-chart-diagram-input-data-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-input-data-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-input-data-super-admin.jpg)
#### 3.2.4.3 State Chart Diagram Edit Data Super Admin
[![state-chart-diagram-edit-data-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-edit-data-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-edit-data-super-admin.jpg)
#### 3.2.4.4 State Chart Diagram Delete Data Super Admin
[![state-chart-diagram-delete-data-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-delete-data-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-delete-data-super-admin.jpg)
#### 3.2.4.5 State Chart Diagram View Data Super Admin
[![state-chart-diagram-view-data-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-view-data-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-view-data-super-admin.jpg)
#### 3.2.4.6 State Chart Diagram Login Admin
[![state-chart-diagram-login-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-login-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-login-admin.jpg)
#### 3.2.4.7 State Chart Diagram Input Data Admin
[![state-chart-diagram-input-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-input-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-input-data-admin.jpg)
#### 3.2.4.8 State Chart Diagram Edit Data Admin
[![state-chart-diagram-edit-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-edit-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-edit-data-admin.jpg)
#### 3.2.4.9 State Chart Diagram Delete data Admin
[![state-chart-diagram-delete-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-delete-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-delete-data-admin.jpg)
#### 3.2.4.10 State Chart Diagram View Data Admin
[![state-chart-diagram-view-data-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-view-data-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-view-data-admin.jpg)
#### 3.2.4.11 State Chart Diagram Gubernur
[![state-chart-diagram-login-gubernur](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-login-gubernur.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-login-gubernur.jpg)
#### 3.2.4.12 State Chart Diagram View Data Gubernur
[![state-chart-diagram-view-data-gubernur](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-view-data-gubernur.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/state-chart-diagram-view-data-gubernur.jpg)
### 3.2.5 Deployment Diagram
[![deployment-diagram](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/deployment-diagram.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/deployment-diagram.jpg)

### 3.2.6 Technology Stack Diagram
[![technology-stack-diagram](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/technology-stack-diagram.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/technology-stack-diagram.jpg)

### 3.3 Tahapan Pekerjaan :
Tahap-tahap atau langkah yang dilakukan dalam mengembangkan Sistem Informasi E-hibahbansos adalah sebagai berikut:
#### a) Analisis dan Perancangan
1). Analisis
Tim pengembang aplikasi akan melakukan analisis jika diperlukan dapat dilakukan survey pendahuluan untuk melihat sejauh mana kebutuhan pengguna akan sistem yang akan dibangun, data-data yang dibutuhkan, dll. Dalam analisis ini dilakukana diskusi-diskusi baik dengan bagian terkait pada satuan kerja.

2). Perancangan Sistem
Perancangan sistem dilaksanakan setelah proses analisis dilaksanakan dan telah disepakati modul dan prosedur-prosedur yang akan diterapkan dalam sistem. Perancangan sistem meliputi kegiatan: penetapan alur data/dokumen, penetapan prosedur, perancangan database, perancangan form dan perancangan interface/dialog layar.
#### b) Pembangunan Sistem
Setelah proses analisis dan perancangan sistem selesai dilakukan, tahapan selanjutnya adalah pembangunan sistem, yang meliputi kegiatan. Pembuatan struktur database, pembuatan kode program/koding, pembuatan laporan-laporan.
#### c) Integrasi dan Pengujian
1). Integrasi
Setelah proses pengembangan sistem selasai dilakukan, tahap selanjutnya adalah Integrasi sistem, yang meliputi kegiatan: pembuatan struktur database terkait integrasi, pembuatan kode program/coding terkait integrasi, pembuatan laporan-laporan terkait integrasi.
Penggunaan webservices / API yang telah disiapkan oleh sistem informasi / aplikasi yang ada.
2). Pengujian
Sistem yang telah selesai dibuat akan diuji coba menggunakan data test sebelum sistem dijalankan. Dalam uji coba sistem ini akan diterapkan metode prototye, yaitu jika terjadi kesalahan/kekurangan baik proses maupuan output sistem, maka kesalahan/kekurangan tersebut akan diperbaiki/ditambahkan, sehingga memungkinkan pengembang untuk kembali ke tahapan pertama yaitu analisa (jika kekurangan sistem memang tidak terdefinisikan dalam dokumen perancangan sistem).

### 3.4 Hasil
Berikut ini adalah hasil eksekusi sistem informasi Dashboard
#### 3.4.1 Struktur Menu Dashboard Pimpinan
[![dashboard-struktur-menu-pimpinan](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-struktur-menu-pimpinan.jpeg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-struktur-menu-pimpinan.jpeg)
#### 3.4.2 Layout Tampilan Depan
[![layout-dashboard-awal](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/layout-dashboard-awal.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/layout-dashboard-awal.jpg)
#### 3.4.3 Layout Tampilan Login
[![dashboard-awal-login](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-awal-login.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-awal-login.jpg)
#### 3.4.4 Layout Tampilan Super Admin
[![dashboard-super-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-super-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-super-admin.jpg)
#### 3.4.5 Layout Tampilan Admin
[![dashboard-admin](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-admin.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-admin.jpg)
#### 3.4.6 Layout Tampilan Gubernur
[![dashboard-gubernur](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-gubernur.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-gubernur.jpg)
#### 3.4.7 Layout Dashboard Kependudukan
[![dashboard-kependudukan](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kependudukan.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kependudukan.jpg)
#### 3.4.8 Layout Dashboard Kepegawaian
[![dashboard-kepegawaian](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kepegawaian.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kepegawaian.jpg)
#### 3.4.9 Layout Dashboard Kependidikan
[![dashboard-kependidikan](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kependidikan.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kependidikan.jpg)
#### 3.4.10 Layout Dashboard Kesehatan
[![dashboard-kesehatan](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kesehatan.jpg)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-kesehatan.jpg)

## 4.PENUTUP

Dengan adanya pembuatan dari sistem  terciptanya efisiensi proses, perbaikan prosedur, peningkatan transparansi dan akuntabilitas belanja hibah, bantuan sosial dan bantuan keuangan pada Pemerintah Provinsi Banten.