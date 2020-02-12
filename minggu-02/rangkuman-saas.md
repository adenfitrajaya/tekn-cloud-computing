# Apa perbedaan antara IaaS, SaaS, dan PaaS?

- Iaas: Infrastructure as a Service

Perangkat keras, perangkat lunak, dan kode aplikasi Anda harus dikelola. Anda memilih server untuk diaktifkan (baik fisik atau virtual), menginstal OS dan tumpukan perangkat lunak, lalu akhirnya menyebarkan aplikasi Anda. Beberapa penyedia menawarkan kontrol tingkat sangat rendah sehingga Anda dapat membangun pusat data Anda sendiri di cloud.

- SaaS: Software as a Service

Ini adalah level abstraksi tertinggi dan berarti Anda hanya menggunakan aplikasi web dan tidak pernah melihat tumpukan perangkat keras dan lunak yang membuatnya berjalan. Anda memasukkan data Anda sendiri ke dalam aplikasi yang disediakan namun beberapa aplikasi yang lebih besar memungkinkan untuk membangun aplikasi khusus di atas (mis. Facebook).

- PaaS: Platform as a service

Jenis layanan ini memisahkan semua keputusan perangkat keras. Hanya tumpukan perangkat lunak dan kode aplikasi Anda yang harus dikelola. Pilih penyedia yang sesuai tergantung pada tumpukan perangkat lunak yang Anda inginkan kemudian gunakan aplikasi Anda. Server, jaringan, dan penyimpanan yang sebenarnya semuanya diurus secara otomatis oleh platform.

# SaaS Platform Architecture

Dengan model ini, satu versi aplikasi, dengan satu konfigurasi digunakan untuk semua pelanggan. Aplikasi ini diinstal pada banyak mesin untuk mendukung skalabilitas (disebut penskalaan horizontal). Dalam beberapa kasus, versi kedua aplikasi diatur untuk menawarkan kelompok pelanggan tertentu dengan akses ke versi pra-rilis aplikasi untuk tujuan pengujian. Dalam model tradisional ini, setiap versi aplikasi didasarkan pada kode unik. Meskipun pengecualian, beberapa solusi SaaS tidak menggunakan multitenancy, untuk mengelola secara efektif sejumlah besar pelanggan di tempat. Apakah multitenancy merupakan komponen yang diperlukan untuk perangkat lunak-sebagai-layanan adalah topik kontroversi.

<h2>Ada dua varietas utama SaaS</h2>

- SaaS Vertikal
Perangkat Lunak yang menjawab kebutuhan industri tertentu (mis., Perangkat lunak untuk kesehatan, pertanian, real estat, industri keuangan)
- SaaS Horisontal
Produk-produk yang berfokus pada kategori perangkat lunak (pemasaran, penjualan, alat pengembang, SDM) tetapi agnostik industri.
