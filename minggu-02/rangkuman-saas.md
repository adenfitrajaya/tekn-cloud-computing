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

# Arsitektur Platform SAAS (Perangkat Lunak sebagai Layanan)

<h4>Apa itu Platform SaaS?</h4>

Sebelum kita masuk ke beberapa poin yang lebih terlibat, ada baiknya menyebutkan apa itu platform SaaS. SaaS adalah cara untuk mengirimkan perangkat lunak, penyedia perangkat lunak ini secara sentral menampung satu atau lebih aplikasi dan membuatnya tersedia bagi pelanggan melalui internet.

SaaS juga merupakan salah satu pilar utama komputasi awan. Sebuah ledakan dalam komputasi Cloud, didorong oleh penyedia cloud seperti Microsoft dengan Azure atau Amazon dengan AWS, telah melihat pertumbuhan produk dan layanan lain yang disampaikan melalui internet seperti:

- Infrastruktur sebagai Layanan
- Platform sebagai Layanan
- Pembelajaran Mesin sebagai Layanan
- …dan banyak lagi!

Setiap pembaruan atau tambalan untuk aplikasi SaaS semuanya ditangani oleh penyedia. Pelanggan tidak perlu mengunduh pemutakhiran atau menginstal ulang versi baru suatu produk saat perangkat lunak dikirimkan melalui internet.

<h4>Mengapa Menggunakan Arsitektur SaaS?</h4>

Seperti yang disebutkan dalam pendahuluan, perangkat lunak telah didistribusikan kepada pelanggan dalam berbagai saluran selama beberapa dekade terakhir. Saluran distribusi yang lebih baru dalam Perangkat Lunak sebagai Layanan (atau SaaS).

# Cara membangun aplikasi SaaS berbasis cloud

<h5>bagaimana memulai?</h5>
Bahasa pemrograman mana, basis data apa, alat perangkat lunak apa yang harus Anda pilih? Ada banyak pertanyaan yang perlu dijawab. Karenanya saya mencoba fokus pada hal-hal terpenting.

Jadi, hal pertama yang pertama.

<h4>Bahasa pemrograman mana?</h4>

Selain kemampuan dan keterampilan pribadi, pilihan bahasa pemrograman Anda akan dipengaruhi oleh kemungkinan masing-masing bahasa. Ada berbagai bahasa pemrograman (modern) di luar sana sehingga sulit untuk memilih yang benar.

<h4>Basis data yang sempurna</h4>

Jadi, salah satu hal pertama dalam daftar Anda akan mencakup pemasangan basis data. Kami merekomendasikan penggunaan basis data berorientasi dokumen. Database dokumen sangat berbeda dengan konsep tradisional database relasional.

