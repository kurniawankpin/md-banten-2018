---
layout: item
title: "Integrasi dan Pengujian"
date: 2018-05-16 16:25:06 +0700
toc: true
comments: true
cat: Sop Online
---

## Daftar Isi
* will be replaced with the ToC, excluing the "Contents" header
{:toc}

### Integrasi dan Pengujian SOP Online
Pada laporan ini akan membahas tentang Integrasi dan Pengujian SOP Online, untuk pengujiannya menggunakan User Acceptance Test.

### Integrasi SOP Online

Salah satu sasaran Dinas Komunikasi, Informasi, Statistika dan Persandian adalah membuat sebuah sistem yang terkelola rapi dalam segala hal, baik dalam bidang IT maupun bidang yang lainnya agar mampu menyelenggarakan seluruh kegiatannya secara mandiri dan sesuai dengan ketentuan yang berlaku.

Untuk mencapai hal tersebut, diperlukan suatu prosedur operasional yang jelas dan standar bagi semua pihak yang terlibat dalam mencapai sasaran tersebut. Praktik-praktik baik yang telah berlangsung di KOMINFO Banten perlu distandarisasi dan didokumentasikan agar menjadi acuan bagi manejemen dalam menjalankan tugas dan fungsinya serta menjamin keberlangsungan implementasi praktik-praktik tersebut.

Terkait dengan sasaran tersebut kami bertujuan akan membangun standarisasi sistem pengembangan apliaksi yang dapat meningkatkan efisiensi dan efektifitas kinerja dinas terkait serta mampu mebagikan informasi yang dibutuhkan oleh berbagai pihak untuk kepentingan proses pengambilan keputusan. Untuk menuju kepada standarisasi dalam pengembangan aplikasi perlu diciptakan terlebih dahulu sistem manual  terstandar atau semacam *Standar Operating Procedur* (SOP) untuk seluruh pengembangan aplikasi yang ada sehingga dapat dipahami oleh semua pihak yang terlibat.

Integrasi aplikasi dilakukan dengan:

1. melalui antar muka aplikasi atau melalui method
2. focus method level
3. method dishare dengan meletakannnya pada sebuah server pusat / dengan mengakses method pada aplikasi.

Application Programming Interface mekanisme terdefinisi dibuat untuk berhubungan dengan sumber daya seperti server aplikasi, middleware, dan basis data.
Dibawah ini adalah contoh method, parameter dan response yang terdapat didalam SOP Online:

#### Tampilan Permission

[![Tampilan Get Permission](../images/sop-online/integrasi-dan-pengujian/sop-permission.png)](../images/sop-online/integrasi-dan-pengujian/sop-permission.png)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten get permission, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:

1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json

#### Tampilan Role

[![Tampilan Get Role](../images/sop-online/integrasi-dan-pengujian/sop-role.png)](../images/sop-online/integrasi-dan-pengujian/sop-role.png)

Pada page ini terdapat method yang berupa tombol **GET** dan link url untuk konten get role, method ini digunakan untuk menambahkan data baru aplikasi ke server. Parameter yang terdapat didalam konten ini berisi field, type dan description. Terdapat 2 response didalam page ini yaitu:

1. *Success Response* yang ditampilkan dalam "Success 200" dan hasilnya ditampilkan dalam bentuk Json.
2. *Error Response* yang ditampilkan dalam "Error 4xx" dan hasilnya akan ditampilkan dalam bentuk Json

#### Pengujian SOP Online
Sistem informasi saat ini semakin berkembang pesat membuat semua pekerjaan dikehidupan ini banyak yang sudah beralih dibantu oleh teknologi informasi. Teknologi yang dapat membantu lebih mudah, cepat, aman dan efektif jelas sangatlah membantu siapa saja yang memanfaatkannya, document dibuat untuk memberikan panduan penggunaan aplikasi SOP Online.

Untuk memulai akses aplikasi SOP Online. Buka web browser (IE, Mozila Firefox atau yang lainnya) dengan menulis alamat url http://http://sop.bantenprov.go.id/ kemudian tekan Enter pada tombol keyboard atau klik tombol Go pada browser.

##### Tampilan Login

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Login    | [![tampilan login](../images/sop-online/integrasi-dan-pengujian/01-tampilan-login.png)](../images/sop-online/integrasi-dan-pengujian/01-tampilan-login.png) |      |       |


Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan login sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Dashboard

| Tampilan  | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Dashboard | [![Tampilan Dashboard](../images/sop-online/integrasi-dan-pengujian/02-tampilan-dashboard.png)](../images/sop-online/integrasi-dan-pengujian/02-tampilan-dashboard.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan dashboard sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Opd

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Opd      | [![Tampilan Opd](../images/sop-online/integrasi-dan-pengujian/03-tampilan-opd.png)](../images/sop-online/integrasi-dan-pengujian/03-tampilan-opd.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan opd sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add New Opd

| Tampilan    | URL/ Image                               | Ada  | Tidak |
| ----------- | ---------------------------------------- | ---- | ----- |
| Add New Opd | [![Tampilan Add New Opd](../images/sop-online/integrasi-dan-pengujian/16-tampilan-tambah-opd.png)](../images/sop-online/integrasi-dan-pengujian/16-tampilan-tambah-opd.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new opd sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add New Child

| Tampilan      | URL/ Image                               | Ada  | Tidak |
| ------------- | ---------------------------------------- | ---- | ----- |
| Add New Child | [![Tampilan Add New Child](../images/sop-online/integrasi-dan-pengujian/17-tampilan-tambah-child.png)](../images/sop-online/integrasi-dan-pengujian/17-tampilan-tambah-child.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new child sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Sop Online

| Konten     | URL/ Image                               | Ada  | Tidak |
| ---------- | ---------------------------------------- | ---- | ----- |
| Sop Online | [![Tampilan Sop Online](../images/sop-online/integrasi-dan-pengujian/04-tampilan-sop-online.png)](../images/sop-online/integrasi-dan-pengujian/04-tampilan-sop-online.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan sop online sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".


##### Tampilan Add Sop Online

| Tampilan       | URL/ Image                               | Ada  | Tidak |
| -------------- | ---------------------------------------- | ---- | ----- |
| Add Sop Online | [![Tampilan Add Sop Online](../images/sop-online/integrasi-dan-pengujian/18-tampilan-add-sop-online.png)](../images/sop-online/integrasi-dan-pengujian/18-tampilan-add-sop-online.png) |      |       |


Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add sop online sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan View Sop Online

| Subkonten       | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| View Sop Online | [![Tampilan View Sop Online](../images/sop-online/integrasi-dan-pengujian/19-tampilan-view-sop-online.png)]((../images/sop-online/integrasi-dan-pengujian/19-tampilan-view-sop-online.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan view sop online sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Sop Online

| Tampilan        | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Edit Sop Online | [![Tampilan Edit Sop Online](../images/sop-online/integrasi-dan-pengujian/20-tampilan-edit-sop-online.png)](../images/sop-online/integrasi-dan-pengujian/20-tampilan-edit-sop-online.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit sop online sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".


##### Tampilan Workflows

| Subkonten | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Workflows | [![Tampilan Workflows](../images/sop-online/integrasi-dan-pengujian/05-tampilan-workflows.png)](../images/sop-online/integrasi-dan-pengujian/05-tampilan-workflows.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan workflows sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add New Workflows

| Tampilan         | URL/ Image                               | Ada  | Tidak |
| ---------------- | ---------------------------------------- | ---- | ----- |
| Add New Workflow | [![Tampilan Add New Workflow](../images/sop-online/integrasi-dan-pengujian/21-tampilan-add-workflows.png)](../images/sop-online/integrasi-dan-pengujian/21-tampilan-add-workflows.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new workflow sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Workflow

| Tampilan      | URL/ Image                               | Ada  | Tidak |
| ------------- | ---------------------------------------- | ---- | ----- |
| Edit Workflow | [![Tampilan Edit Workflow](../images/sop-online/integrasi-dan-pengujian/23-tampilan-edit-workflows.png)](../images/sop-online/integrasi-dan-pengujian/23-tampilan-edit-workflows.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit workflow sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan State List

| Tampilan   | URL/ Image                               | Ada  | Tidak |
| ---------- | ---------------------------------------- | ---- | ----- |
| State List | [![Tampilan State List](../images/sop-online/integrasi-dan-pengujian/06-tampilan-statelist.png)](../images/sop-online/integrasi-dan-pengujian/06-tampilan-statelist.png) |      |       |


Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan state list sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add new State

| Tampilan      | URL/ Image                               | Ada  | Tidak |
| ------------- | ---------------------------------------- | ---- | ----- |
| Add New State | [![Tampilan Add New State](../images/sop-online/integrasi-dan-pengujian/24-tampilan-add-state.png)](../images/sop-online/integrasi-dan-pengujian/24-tampilan-add-state.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new state sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit State

| Tampilan   | URL/ Image                               | Ada  | Tidak |
| ---------- | ---------------------------------------- | ---- | ----- |
| Edit State | [![Tampilan Edit State](../images/sop-online/integrasi-dan-pengujian/25-tampilan-edit-state.png)](../images/sop-online/integrasi-dan-pengujian/25-tampilan-edit-state.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit state sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Transition List

| Tampilan        | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Transition List | [![Tampilan Transition List](../images/sop-online/integrasi-dan-pengujian/07-tampilan-transition.png)](../images/sop-online/integrasi-dan-pengujian/07-tampilan-transition.png) |      |       |


Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan transition sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add New Transition

| Tampilan           | URL/ Image                               | Ada  | Tidak |
| ------------------ | ---------------------------------------- | ---- | ----- |
| Add New Transition | [![Tampilan Add New Transition](../images/sop-online/integrasi-dan-pengujian/26-tampilan-add-transition.png)](../images/sop-online/integrasi-dan-pengujian/26-tampilan-add-transition.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new transition sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Transition

| Tampilan        | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Edit Transition | [![Tampilan Edit Transition](../images/sop-online/integrasi-dan-pengujian/27-tampilan-edit-transition.png)](../images/sop-online/integrasi-dan-pengujian/27-tampilan-edit-transition.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit transition sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Workflow Guard
##### Tampilan Add New Guard


| Tampilan      | URL/ Image                               | Ada  | Tidak |
| ------------- | ---------------------------------------- | ---- | ----- |
| Add New Guard | [![Tampilan Add New Guard](../images/sop-online/integrasi-dan-pengujian/28-tampilan-add-guard.png)](../images/sop-online/integrasi-dan-pengujian/28-tampilan-add-guard.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new guard sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Guard

| Konten     | URL/ Image                               | Ada  | Tidak |
| ---------- | ---------------------------------------- | ---- | ----- |
| Edit Guard | [![Tampilan Edit Guard](../images/sop-online/integrasi-dan-pengujian/29-tampilan-edit-guard.png)](../images/sop-online/integrasi-dan-pengujian/29-tampilan-edit-guard.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit guard sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Workflow Attachment

| Tampilan            | URL/ Image                               | Ada  | Tidak |
| ------------------- | ---------------------------------------- | ---- | ----- |
| Workflow Attachment | [![Tampilan Workflow Attachment](../images/sop-online/integrasi-dan-pengujian/09-tampilan-workflow-attachment.png)](../images/sop-online/integrasi-dan-pengujian/09-tampilan-workflow-attachment.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan workflow attachment sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".


##### Tampilan Add New Attachment

| Tampilan           | URL/ Image                               | Ada  | Tidak |
| ------------------ | ---------------------------------------- | ---- | ----- |
| Add New Attachment | [![Tampilan Add New Attachment](../images/sop-online/integrasi-dan-pengujian/30-tampilan-add-attachment.png)](../images/sop-online/integrasi-dan-pengujian/30-tampilan-add-attachment.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new attachment sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Attachment

| Subkonten         | URL/ Image                               | Ada  | Tidak |
| ----------------- | ---------------------------------------- | ---- | ----- |
| Edit Attachment | [![Tampilan Edit Attachment](../images/sop-online/integrasi-dan-pengujian/31-tampilan-edit-attachment.png)](../images/sop-online/integrasi-dan-pengujian/31-tampilan-edit-attachment.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan Edit attachment sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Workflow Content


| Tampilan         | URL/ Image                               | Ada  | Tidak |
| ---------------- | ---------------------------------------- | ---- | ----- |
| Workflow Content | [![Tampilan Workflow Content](../images/sop-online/integrasi-dan-pengujian/10-tampilan-workflow-content.png)](../images/sop-online/integrasi-dan-pengujian/10-tampilan-workflow-content.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan workflow content sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add New Content

##### Konten Transition List

| Konten          | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Add New Content | [![Tampilan Add New Content](../images/sop-online/integrasi-dan-pengujian/32-tampilan-add-content.png)](../images/sop-online/integrasi-dan-pengujian/32-tampilan-add-content.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new content sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Workflow History

| Tampilan         | URL/ Image                               | Ada  | Tidak |
| ---------------- | ---------------------------------------- | ---- | ----- |
| Workflow History | [![Tampilan Workflow History](../images/sop-online/integrasi-dan-pengujian/11-tampilan-workflow-history.png)](../images/sop-online/integrasi-dan-pengujian/11-tampilan-workflow-history.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan workflow history sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan User

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| User     | [![Tampilan User](../images/sop-online/integrasi-dan-pengujian/12-tampilan-user.png)](../images/sop-online/integrasi-dan-pengujian/12-tampilan-user.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan user sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add User

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Add User | [![Tampilan Add User](../images/sop-online/integrasi-dan-pengujian/34-tampilan-add-user.png)](../images/sop-online/integrasi-dan-pengujian/34-tampilan-add-user.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add user sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit User

| Tampilan  | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Edit User | [![Tampilan Edit User](../images/sop-online/integrasi-dan-pengujian/35-tampilan-edit-user.png)](../images/sop-online/integrasi-dan-pengujian/35-tampilan-edit-user.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit user sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Permission

| Tampilan   | URL/ Image                               | Ada  | Tidak |
| ---------- | ---------------------------------------- | ---- | ----- |
| Permission | [![Tampilan Permission](../images/sop-online/integrasi-dan-pengujian/13-tampilan-permission.png)](../images/sop-online/integrasi-dan-pengujian/13-tampilan-permission.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan permission sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Add New Permission

| Tampilan           | URL/ Image                               | Ada  | Tidak |
| ------------------ | ---------------------------------------- | ---- | ----- |
| Add New Permission | [![Tampilan Add New Permission](../images/sop-online/integrasi-dan-pengujian/36-tampilan-add-permission.png)](../images/sop-online/integrasi-dan-pengujian/36-tampilan-add-permission.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan add new permission sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan View Permission

| Tampilan        | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| View Permission | [![Tampilan View Permission](../images/sop-online/integrasi-dan-pengujian/37-tampilan-view-permission.png)](../images/sop-online/integrasi-dan-pengujian/37-tampilan-view-permission.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan view permission sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Permission

| Tampilan        | URL/ Image                               | Ada  | Tidak |
| --------------- | ---------------------------------------- | ---- | ----- |
| Edit Permission | [![Tampilan Edit Permission](../images/sop-online/integrasi-dan-pengujian/38-tampilan-edit-permission.png)](../images/sop-online/integrasi-dan-pengujian/38-tampilan-edit-permission.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit permission sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Role

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| Role     | [![Tampilan Role](../images/sop-online/integrasi-dan-pengujian/14-tampilan-role.png)](../images/sop-online/integrasi-dan-pengujian/14-tampilan-role.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan role sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan New Role

| Tampilan | URL/ Image                               | Ada  | Tidak |
| -------- | ---------------------------------------- | ---- | ----- |
| New Role | [![Tampilan New Role](../images/sop-online/integrasi-dan-pengujian/39-tampilan-new-role.png)](../images/sop-online/integrasi-dan-pengujian/39-tampilan-new-role.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan new role sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan View Role

| Tampilan  | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| View Role | [![Tampilan View Role](../images/sop-online/integrasi-dan-pengujian/40-tampilan-view-role.png)](../images/sop-online/integrasi-dan-pengujian/40-tampilan-view-role.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan view role sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Edit Role

| Tampilan  | URL/ Image                               | Ada  | Tidak |
| --------- | ---------------------------------------- | ---- | ----- |
| Edit Role | [![Tampilan Edit Role](../images/sop-online/integrasi-dan-pengujian/41-tampilan-edit-role.png)](../images/sop-online/integrasi-dan-pengujian/41-tampilan-edit-role.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan edit role sudah dapat diakses oleh *user* atau tidak. Jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".

##### Tampilan Laporan Workflow

| Tampilan         | URL/ Image                               | Ada  | Tidak |
| ---------------- | ---------------------------------------- | ---- | ----- |
| Laporan Workflow | [![Tampilan Laporan](../images/sop-online/integrasi-dan-pengujian/15-tampilan-laporan.png)](../images/sop-online/integrasi-dan-pengujian/15-tampilan-laporan.png) |      |       |

Dalam tabel ini *user* dapat melakukan test kepada aplikasi apakah tampilan laporan workflow sudah dapat diakses oleh *user* atau tidak. jika sudah dapat diakses *user* dapat meceklis pada kolom "Ada" sedangkan jika belum dapat diakses maka *user* dapat menceklis pada kolom "tidak".
