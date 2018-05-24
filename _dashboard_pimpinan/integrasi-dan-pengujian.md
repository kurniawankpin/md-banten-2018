---
layout: item
title: "Integrasi dan Pengujian"
date: 2018-05-16 16:25:06 +0700
comments: true
toc: true
cat: Dashboard Pimpinan
---

## Integrasi dan Pengujian Dashboard Pimpinan
Pada laporan ini akan membahas tentang Pengujian dan Integrasi Dashboard Pimpinan, untuk pengujiannya menggunakan *User Acceptance Test*.

## Daftar Isi
* Will be replaced with the ToC, excluding the "Contents" header
{:toc}

### 1. Integrasi
Dashboard Pimpinan adalah suatu aplikasi untuk memantau setiap OPD (Organisasi perangkat Daerah) di pemerintahan Banten.

Dalam kegiatannnya setiap kegiatan admin akan terdapat integrasi terhadap server yang bertujuan untuk melakukan integrasi aplikasi data sehingga mudah untuk di*share*, integrasi dilakukan tanpa membuat perubahan signifikan pada aplikasi dan sumber data.

Integrasi aplikasi dilakukan dengan:
1. melalui antar muka aplikasi atau melalui method
2. *focus method level*
3. method di*share* dengan meletakannnya pada sebuah server pusat / dengan mengakses *method* pada aplikasi.

*Application Programming Interface*
mekanisme terdefinisi dibuat untuk berhubungan dengan sumber daya seperti server aplikasi, *middleware*, dan basis data.

Dibawah ini adalah contoh method, parameter dan *response* yang terdapat didalam Dashboard Pimpinan:
#### 1.1 Kepegawaian
##### 1.1.1 Kenaikan Pangkat Otomatis Pegawai
###### 1.1.1.1 Save New Jumlah Kenaikan Pangkat Otomatis Pegawai
[![nambah data kenaikan pangkat](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-post1.png)
[![nambah data kenaikan pangkat](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten kenaikan pangkat otomatis pegawai, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.1.1.2 Update Jumlah Kenaikan Pangkat Otomatis Pegawai

[![update data kenaikan pangkat](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-put1.png)
[![update data kenaikan pangkat](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/kenaikan-pangkat-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten kenaikan pangkat otomatis pegawai, method ini digunakan untuk mengupdate data aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### 1.1.2 Pangkat Pegawai
###### 1.1.2.1 Save New Jumlah Pangkat Pegawai
[![nambah data pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-post1.png)
[![nambah data pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah pangkat pegawai, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.1.2.2 Update Jumlah Pangkat Pegawai
[![update pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-put1.png)
[![update pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pangkat-pegawai-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah pangkat pegawai, method ini digunakan untuk mengupdate data aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### 1.1.3 Pegawai
###### 1.1.3.1 Save New Jumlah Pegawai
[![nambah data jumlah pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-post1.png)
[![nambah data jumlah pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah pegawai, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.1.3.2 Update Jumlah Pegawai
[![update data jumlah pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-put1.png)
[![update data jumlah pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pegawai-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah pegawai, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### 1.1.4 Pegawai Esselon
###### 1.1.4.1 Save New Jumlah Pegawai Esselon
[![nambah data pegawai esselon](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-post1.png)
[![nambah data pegawai esselon](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah pegawai esselon, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.1.4.2 Update Jumlah Pegawai Esselon
[![update jumlah pegawai esselon](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-put1.png)
[![update jumlah pegawai esselon](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-esselon-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah pegawai esselon, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### 1.1.5 Pegawai yang akan pensiun
###### 1.1.5.1 Save New Jumlah Pegawai yang akan pensiun
[![jumlah pegawai pesiun](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-post1.png)
[![jumlah pegawai pesiun](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah pegawai yang akan pensiun, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.1.5.2 Update Jumlah Pegawai yang akan pensiun
[![update jumlah pegawai pesiun](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-put1.png)
[![update jumlah pegawai pesiun](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/pegawai-pensiun-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah pegawai yang akan pensiun, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

##### 1.1.6 Usia ASN
###### 1.1.6.1  Save New Jumlah Usia ASN
[![jumlah usia ASN](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-post1.png)
[![jumlah usia ASN](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah pegawai usia ASN, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.1.6.2 Update Jumlah Usia ASN
[![update jumlah pegawai ASN](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-put1.png)
[![update jumlah pegawai ASN](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/usia-asn-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah pegawai usian ASN, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

#### 1.2 Kependudukan
##### 1.2.1 jumlah Penduduk
###### 1.2.1.1 Save New Jumlah Penduduk
[![save jumlah penduduk](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-post1.png)
[![save jumlah penduduk](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah penduduk, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.2.1.2 Update Jumlah Penduduk
[![save jumlah penduduk](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-put1.png)
[![save jumlah penduduk](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-penduduk-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah penduduk, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

#### 1.3. Kesehatan
##### 1.3.1 Tim Medis
###### 1.3.1.1 Save New Jumlah Tim Medis
[![save jumlah tim medis](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-post1.png)
[![save jumlah tim medis](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah Tim medis, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.3.1.2  Update Jumlah Tim Medis
[![save jumlah tim medis](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-put1.png)
[![save jumlah tim medis](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-tim-medis-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah Tim medis, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

#### 1.4 Kependidikan
##### 1.4.1 Jumlah Pendidik
###### 1.4.1.1 Save New Jumlah Pendidik
[![save jumlah pendidik](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-post1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-post1.png)
[![save jumlah pendidik](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-post2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-post2.png)
Pada *page* ini terdapat *method* yang berupa tombol "POST" dan link url untuk konten jumlah Pendidik, method ini digunakan untuk menambah data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

###### 1.4.1.2 Update jumlah pendidik
[![update jumlah pendidik](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-put1.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-put1.png)
[![update jumlah pendidik](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-put2.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/jumlah-pendidik-put2.png)
Pada *page* ini terdapat *method* yang berupa tombol "PUT" dan link url untuk konten jumlah Pendidik, method ini digunakan untuk menngupdate data  aplikasi ke server. Parameter yang terdapat didalam konten ini berisi *field, type dan description*. Terdapat 2 *response* didalam *page* ini yaitu
1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json.

### 2. User Acceptance Test (UAT)

#### 2.1Dashboard Kepegawaian

##### 2.1.1 Subkonten Jumlah Pegawai

| Dashboard | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Pegawai   | [![Jumlah pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pegawai.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pegawai.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah pegawai sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kepegawaian , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### 2.1.2 Subkonten Jumlah Kenaikan Pangkat Pegawai Otomatis

| Dashboard                | URL/ Image                               | Ada  | Tidak |
| ------------------------ | ---------------------------------------- | ---- | ----- |
| Kenaikan Pangkat Pegawai | [![jumlah kenaikan pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pangkat-pegawai.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pangkat-pegawai.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah kenaikan pangkat pegawai otomatis sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kepegawaian , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### 2.1.3 Subkonten Jumlah Pegawai yang Akan pensiun

| Dashboard                 | URL/ Image                               | Ada  | Tidak |
| ------------------------- | ---------------------------------------- | ---- | ----- |
| Pegawai yang Akan pensiun | [![jumlah kenaikan pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pegawai-akan-pensiun.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pegawai-akan-pensiun.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah pegawai yang akan pensiun sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kepegawaian , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### 2.1.4 Subkonten Jumlah Pegawai Esselon

| Dashboard       | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Pegawai Esselon | [![jumlah pegawai esselon](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pegawai-esselon.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pegawai-esselon.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah pegawai esselon sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kepegawaian , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### 2.1.5 Subkonten Pangkat Pegawai

| Dashboard       | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Pangkat pegawai | [![jumlah pangkat pegawai](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pangkat-pegawai.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-pangkat-pegawai.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten pangkat pegawai sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kepegawaian , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### 2.1.6 Subkontem Usia Aparatur Sipil Negara (ASN)

| Dashboard                  | URL/ Image                               | Ada  | Tidak |
| -------------------------- | ---------------------------------------- | ---- | ----- |
| Usia Aparatur Sipil Negara | [![Usia aparatur sipil negara](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-usia-asn.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kepegawaian-usia-asn.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten usia aparatur sipi negara (ASN) sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kepegawaian , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.2 Dashboard Kependudukan

##### 2.2.1 Subkonten Jumlah Penduduk

| Dashboard | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Penduduk  | [![Jumlah penduduk](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kependudukan-penduduk.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kependudukan-penduduk.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah penduduk sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kependudukan , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.3 Dashboard Kesehatan

##### 2.3.1 Subkonten Jumlah Tim Medis

| Dashboard | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Tim Medis | [![Jumlah tim medis](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kesehatan-tim-medis.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kesehatan-tim-medis.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah tim medis sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kesehatan , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.4 Dashboard kependidikan

##### 2.4.1 Subkonten Jumlah Tenaga Pendidik

| Dashboard | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Pendidik  | [![Jumlah pendidik](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kependidikan-pendidik.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-kependidikan-pendidik.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah tenaga pendidik sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/kependidikan , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

#### 2.5 Dashboard Epormas

##### 2.5.1 Subkonten Jumlah Laporan

| Dashboard | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Laporan   | [![Jumlah laporan](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-epormas-jumlah-laporan.png)](../images/dashboard-pimpinan/integrasi-dan-pengujian/uat-epormas-jumlah-laporan.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah subkonten jumlah tenaga pendidik sudah dapat diakses oleh *user* atau tidak. Untuk mengecek dapat diakses tidaknya subkonten ini *user* dapat membuka link url http://dashboard-01.dev.bantenprov.go.id/#/dashboard/epormas , jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".
