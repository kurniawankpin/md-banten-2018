---
layout: item
title: "Desain dan Perancangan"
date: 2018-05-16 16:25:06 +0700
comments: true
toc: true
---


## ABSTRAK
Dewasa ini perkembangan teknologi komputer sangatlah pesat. Dengan menggunakan aplikasi komputer akan didapat informasi mengenai suatu tampilan objek yang ditampilkan lebih hidup dan menarik. Adanya kemajuan teknologi ini memungkinkan Sistem untuk menjalankan prosedur pemberian dana hibah dan bantuan sosial dapat berjalan lebih baik dan membantu masyarakat dan Pemerintah Provinsi Banten dalam menjalankan kegiatan yang berkaitan dengan hibah dan bantuan sosial yang lebih terstruktur dan lebih transparansi.

## Daftar Isi
* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

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
![my photo]({{ site.url }}images/desain-dan-perancangan/alur-prototype.png)
### 2.2 Metode Pengumpulan Data
Untuk mengumpulkan data yang diperlukan untuk membangun sistem ini diadakan wawancara dan studi pustaka. Pengumpulan data ini diperlukan untuk mengetahui permasalahan dan gambaran sistem yang sedang berjalan sehingga dapat mengembangkannya untuk membentuk sistem baru yang dapat mendukung sistem yang sedang berjalan.
1). Wawancara ini dilakukan kepada Pemprov Banten. Wawancara dilakukan kepada sistem analist Pemprov Banten untuk mengetahui permasalahan dalam proses pendataan yang sedang berjalan sekarang.
2). Studi Pustaka, Melakukan pengumpulan melalui buku text, internet sebagai referensi.
## 3. HASIL PEMBAHASAN
### 3.1 Perencanaan Aplikasi
Sistem informasi e-hibahbansos adalah untuk mempermudah pemerintah dan masyarakat dalam menyenggarakan kegiatan hibah dan bantuan sosial.
### 3.2. Perancangan Sistem
Permodelan rancangan sistem yang digunakan adalah UML (Unified Modeling Language). Menurut Whitten dan Bentley (2007, p.381), Unified Modeling Language adalah kumpulan rancangan diagram untuk membangun sebuah sistem atau aplikasi yang dimana setiap diagram menyediakan sistem informasi kepada tim pengembang dengan berbagai sudut pandang yang berbeda-beda. UML yang kami gunakan terdiri dari use case diagram, activity diagram, sequence diagram, state chart diagram, class diagram, deploymen diagram dan technology diagram.

#### 3.2.1 Use Cace Diagram
##### 3.2.1.1 Use Case Diagram Super Admin
![my photo]({{ site.url }}images/desain-dan-perancangan/usecase_superadmin.png)
##### 3.2.1.2 Use Case Diagram Pendaftar Hibah
![my photo]({{ site.url }}images/desain-dan-perancangan/usecase_pelapor.png)
##### 3.2.1.3 Use Case Diagram Organisasi Perangkat Daerah (OPD)
![my photo]({{ site.url }}images/desain-dan-perancangan/usecase_opd.png)
##### 3.2.1.4 Use Case Diagram Inspektorat
![my photo]({{ site.url }}images/desain-dan-perancangan/usecase_inspektorat.png)
##### 3.2.1.5 Use Case Diagram TAPD
![my photo]({{ site.url }}images/desain-dan-perancangan/usecase_tapd.png)
##### 3.2.1.6 Use Case Diagram BPKAD
![my photo]({{ site.url }}images/desain-dan-perancangan/usecase_bpkad.png)

#### 3.2.2 Activity Diagram
##### 3.2.2.1 Activity Diagram Super Admin
![my photo]({{ site.url }}images/desain-dan-perancangan/activitydiagram_superadmin.png)
##### 3.2.2.2 Activity Diagram Kegiatan Belanja Hibah Bansos
![my photo]({{ site.url }}images/desain-dan-perancangan/activitydiagram_workflow-hibahbansos.png)

#### 3.2.3 Sequence Diagram
##### 3.2.3.1 Sequence Diagram Super Admin
![my photo]({{ site.url }}images/desain-dan-perancangan/sequencediagram_superadmin.png)
##### 3.2.3.2 Sequence Kegiatan Belanja Hibah Bansos
![my photo]({{ site.url }}images/desain-dan-perancangan/sequencediagram_workflow.png)

#### 3.2.4 State Chart Diagram
##### 3.2.4.1 State Chart Diagram Super Admin
![my photo]({{ site.url }}images/desain-dan-perancangan/statechart_superadmin.png)
##### 3.2.4.2 State Chart Diagram Pendaftar Hibah / Bansos
![my photo]({{ site.url }}images/desain-dan-perancangan/statechart_pendaftar.png)
##### 3.2.4.3 State Chart Diagram OPD
![my photo]({{ site.url }}images/desain-dan-perancangan/statechart_opd.png)
##### 3.2.4.4 State Chart Diagram Inspektorat
![my photo]({{ site.url }}images/desain-dan-perancangan/statechart_inspektorat.png)
##### 3.2.4.5 State Chart Diagram TAPD
![my photo]({{ site.url }}images/desain-dan-perancangan/statechart_tapd.png)
##### 3.2.4.6 State Chart Diagram BPKAD
![my photo]({{ site.url }}images/desain-dan-perancangan/statechart_bpkad.png)
#### 3.2.5 Deployment Diagram
![my photo]({{ site.url }}images/desain-dan-perancangan/deployment-diagram.jpg)
#### 3.2.6 Technology Stack Diagram
![my photo]({{ site.url }}images/desain-dan-perancangan/technology-stack-diagram.jpg)

### 3.3 Tahapan Pekerjaan :
Tahap-tahap atau langkah yang dilakukan dalam mengembangkan Sistem Informasi E-hibahbansos adalah sebagai berikut:
#### 3.3.1 Analisis dan Perancangan
1). Analisis
Tim pengembang aplikasi akan melakukan analisis jika diperlukan dapat dilakukan survey pendahuluan untuk melihat sejauh mana kebutuhan pengguna akan sistem yang akan dibangun, data-data yang dibutuhkan, dll. Dalam analisis ini dilakukana diskusi-diskusi baik dengan bagian terkait pada satuan kerja.

2). Perancangan Sistem
Perancangan sistem dilaksanakan setelah proses analisis dilaksanakan dan telah disepakati modul dan prosedur-prosedur yang akan diterapkan dalam sistem. Perancangan sistem meliputi kegiatan: penetapan alur data/dokumen, penetapan prosedur, perancangan database, perancangan form dan perancangan interface/dialog layar.
#### 3.3.2 Pembangunan Sistem
Setelah proses analisis dan perancangan sistem selesai dilakukan, tahapan selanjutnya adalah pembangunan sistem, yang meliputi kegiatan. Pembuatan struktur database, pembuatan kode program/koding, pembuatan laporan-laporan.
#### 3.3.3 Integrasi dan Pengujian
1). Integrasi
Setelah proses pengembangan sistem selasai dilakukan, tahap selanjutnya adalah Integrasi sistem, yang meliputi kegiatan: pembuatan struktur database terkait integrasi, pembuatan kode program/coding terkait integrasi, pembuatan laporan-laporan terkait integrasi.
Penggunaan webservices / API yang telah disiapkan oleh sistem informasi / aplikasi yang ada.
2). Pengujian
Sistem yang telah selesai dibuat akan diuji coba menggunakan data test sebelum sistem dijalankan. Dalam uji coba sistem ini akan diterapkan metode prototye, yaitu jika terjadi kesalahan/kekurangan baik proses maupuan output sistem, maka kesalahan/kekurangan tersebut akan diperbaiki/ditambahkan, sehingga memungkinkan pengembang untuk kembali ke tahapan pertama yaitu analisa (jika kekurangan sistem memang tidak terdefinisikan dalam dokumen perancangan sistem).

### 3.4 Hasil
Berikut ini adalah hasil eksekusi sistem informasi Dashboard
#### 3.4.1 Layout Tampilan Awal
![my photo]({{ site.url }}images/desain-dan-perancangan/tampilan-awal.png)
#### 3.4.2 Layout Tampilan Login
![my photo]({{ site.url }}images/desain-dan-perancangan/login.png)
#### 3.4.3 Layout Tampilan Registrasi
![my photo]({{ site.url }}images/desain-dan-perancangan/registrasi.png)
#### 3.4.4 Layout Tampilan Tentang
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_tentang.png)
#### 3.4.5 Layout Tampilan Proposal
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_proposal.png)
#### 3.4.6 Layout Tampilan Laporan
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_laporan.png)
#### 3.4.7 Layout Tampilan Superadmin
![my photo]({{ site.url }}images/desain-dan-perancangan/tampilan-awal_superadmin.png)
##### 3.4.7.1 Layout Tampilan Koreksi
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_koreksi.png)
##### 3.4.7.2 Layout Tampilan CMS
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_cms.png)
#### 3.4.8 Layout Tampilan Pendaftar Hibah Bansos
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_awal-pendaftar.png)
##### 3.4.8.1 Layout Tampilan Daftar
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_daftar.png)
##### 3.4.8.2 Layout Tampilan LPJ
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_lpj.png)
#### 3.4.9 Layout Tampilan OPD
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_awal-opd.png)
##### 3.4.9.1 Layout Tampilan Daftar OPD
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_daftar-opd.png)
##### 3.4.9.2 Layout Tampilan Cek Berkas
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_cek-berkas.png)
##### 3.4.9.3 Layout Tampilan Pemberian Rekomendasi
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_opd-rekomendasi.png)
#### 3.4.10 Layout Tampilan Inspektorat
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_awal-inspektorat.png)
##### 3.4.10.1 Layout Tampilan Rekomendasi dan Verifikasi
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_rekom-dan-verifikasi.png)
#### 3.4.11 Layout Dashboard TAPD
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_awal-tapd.png)
##### 3.4.9.1 Layout Tampilan Verifikasi
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_verifikasi-tapd.png)
##### 3.4.9.2 Layout Tampilan Generate
![my photo]({{ site.url }}images/desain-dan-perancangan/layuot_generate.png)
#### 3.4.12 Layout Dashboard BPKAD
![my photo]({{ site.url }}images/desain-dan-perancangan/layout_awal-bpkad.png)
##### 3.4.12.1 Layout Tampilan Upload SPPD dan SPJ
[![koreksi](../images/desain-dan-perancangan/layout_sppd-dan-spj.png)](/document/aplikasi/dashboard-pimpinan/images/desain-dan-perancangan/dashboard-admin.jpg)

## 4.PENUTUP

Dengan adanya pembuatan dari sistem aplikasi E-hibahbansos diharapkan dapat  terciptanya efisiensi proses, perbaikan prosedur, peningkatan transparansi dan akuntabilitas belanja hibah, bantuan sosial dan bantuan keuangan pada Pemerintah Provinsi Banten.

![my photo]({{ site.url }}images/cc_by_88x31.png)
