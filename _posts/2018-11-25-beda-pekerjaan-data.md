---
title: "Apa beda Data Scientist, Data Engineer, dan Data Analyst?"
date: 2018-11-25 09:00:00
excerpt: "Apa beda Data Scientist, Data Engineer, dan Data Analyst?"
tags:
  - Data Scientist
  - Data Engineer
  - Data Analyst
---
Dalam bacaan kali ini, saya akan membahas bagaimana perbedaan dari 3 pekerjaan **terseksi** abad ini, yaitu Data Scientist, Data Engineer, dan Data Analyst.

Banyak sekali pertanyaan yang timbul ketika mendengar ketiga pekerjaan ini. `Apa bedanya, apa kesamaannya? Kok menurut saya sama.` Ya, ketiga pekerjaan ini memang pada dasarnya sama karena semua memiliki kata `Data` di depan nama pekerjaan-nya. Tetapi secara pekerjaan mereka sehari-hari, perbedaan pekerjaan mereka cukup signifikan.

![differencesdata_1]({{ site.url }}{{ site.baseurl }}/assets/images/differences_data.png)

Mari kita analogikan ketiga pekerjaan ini sebagai pekerjaan di dalam sebuah restoran ternama yang mempunyai _Michelin Star_.

### 1. _Data Engineer_

Dalam sebuah restoran ternama ini, **Data Engineer** adalah orang-orang yang memilih, menyiapkan, dan mengolah bahan-bahan terbaik untuk diberikan kepada para Chef terhebat. Selain bahan-bahan terbaik, bahan ini harus fresh dan dapat diambil kapan saja oleh para Chef.

Untuk mendapatkan bahan fresh dan terbaik, **Data Engineer** harus mempunyai koneksi penjual bahan (ter-fresh dan terbaik) tersebut dan harus mengatur bagaimana _flow_ pengantaran bahan dan bahan tersebut harus dalam kondisi yang paling fresh.

Dari analogi ini, setiap individu **Data Engineer** adalah penyedia data yang nantinya akan diberikan kepada Data Scientist (DS) dan Data Analyst (DA). Data yang diberikan kepada mereka harus data yang sesuai dengan kebtuhan mereka. Data tersebut harus `100% benar dan bersih`.

**Data Engineer (DE)** erat kaitannya dengan istilah `Big Data` dan `Pipeline`. Mereka adalah pembuat infrastruktur bagaimana data akan didapatkan dan diolah sesuai dengan kebutuhan para DS dan DA. Dari data ini harus disimpan dimana dan bagaimana bentuknya, DE harus memikirkan semuanya.

DE juga harus memikirkan bagaimana data yang mereka ambil adalah data yang balik fresh dan bersih. Mereka juga harus memikirkan bagaimana jika data (bahan) yang akan dikirim gagal sampai tujuan. Semua ini adalah proses dari `pipeline` yang dibuat oleh DE.

Yang harus dikuasai oleh DE adalah `SQL`, `Databases` (RDBMS,NoSQL, Data Warehouse, Data Lake, etc), `ETL Tools` (Pentaho, Ab Initio, etc), `Pipeline` (Airflow, Kafka, Luigi, Azkaban, etc), dan tentunya basic pemrograman dan shell script.


### 2. _Data Scientist_

**Data Scientist** adalah Chef yang berinovasi, setelah menerima bahan dari DE langsung bekerja untuk membuat menu-menu terbaik untuk disajikan kepada para penikmat makanan yang sudah menunggu di luar. Tugas Chef ini adalah membuat inovasi dari setiap bahan yang sudah diterima, entah bahan itu direbus lalu dioven dan diasap. Semua ide konyol harus dilakukan oleh **Data Scientist** untuk menciptakan sebuah inovasi terbaru.

_Chef_ ini tidak jauh dari kegagalan membuat menu baru tidaklah semudah mengambil upil di hidung. Data Scientist harus menguasai semua metode memasak dan mengetahui semua inovasi terkini. Tanpa adanya Chef yang berionvasi, _Michelin Star_ dari restoran ini sudah pasti dicabut. Intinya tanpa inovasi, bisnis restoran pasti tidak akan bertahan.

DS dalam analogi ini adalah Chef dengan semua alat dan ilmu pengetahuan yang dikuasainya, harus membuat inovasi dalam memecahkan masalah yang ada di dalam sebuah restoran. Inovasi tersebut tak kadang menaikkan revenue restoran hingga berkali-kali lipat.

Yang harus dikuasai oleh DS adalah `Statistika`, `Matematika`, `Algoritma` terkini, Bahasa pemrograman untuk membuat model (Inovasi Masakan Baru) yang biasa `Python atau R`, dan tools-tools lainnya untuk mengolah dan membuat model.

### 3. _Data Analyst_

**Data Analyst** adalah Business Chef restoran yang berhubungan langsung dengan orang yang akan menikmati makanan. Chef ini tahu betul menu-menu apa yang sering dipesan, menu-menu yang akhir-akhir ini jarang dipesan, dsb. Chef ini pintar dan tahu tips dan trik bisnis terbaik untuk meningkatkan penjualan dan memberikan ide kepada DS dan DE.

Karena Chef ini berhubungan langsung dengan bisnis, tentunya mereka paham betul bagaimana permainan pasar dan naik turunnya sebuah penjualan. Chef ini secara langsung juga menggunakan bahan bahan yang disediakan oleh DE untuk diolah menjadi sebuah prototipe makanan yang nantinya digunakan untuk melakukan eksperimen.

DA biasanya melakukan eksperimen untuk menentukkan makanan apa yang disukai orang belakangan ini, tipe ruangan seperti apa yang disukai mereka, dsb. Hasil dari eksperimen ini biasanya diserahkan kepada DS dan DE untuk digunakan sebagai insights.

Dari analogi ini **Data Analyst** adalah orang mencari insights untuk memajukan bisnis dari segi apapun. Mengolah bahan yang diberikan untuk melakukan eksperimen dan menentukkan langkah selanjutnya.

Yang harus dikuasai oleh DA adalah `istilah bisnis`, `SQL`, `Excel`, dan tools pembuat infografik/ grafik yang menarik.


### Conclusion
Dari ketiga pekerjaan ini, semuanya saling melengkapi dan susah berdiri sendiri. Nama pekerjaan mereka mungkin mirip, tapi pekerjaan sehari-hari mereka berbeda.

 If you have any question as of how awesome is it, feel free to contact me :)
{: .notice}
