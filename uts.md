## 1.1 Latar Belakang
    TastyTown Adalah salah satu layanan online yang menyediakan berbagai macam makanan siap saji yang siap antar kerumah..solusi terbaik untuk temen-temen yang malas masak dirumah.TastyTown menyediakan informasi yang lebih rinci tentang setiap menu nya,termasuk gambar,deskripsi,bahan dan harga.TastyTown juga dilengkapi dengan fitur penilaian dan ulasan dari pelanggan.Seiring dengan gaya hidup yang semakin sibuk, kini kita mencari makanan yang praktis, dapat diakses dengan cepat, dan sesuai dengan mobilitas kita yang tinggi. Kemajuan teknologi informasi, terutama melalui aplikasi seluler dan situs web, memberikan kita kenyamanan untuk menjelajahi berbagai opsi makanan dan memesan secara online.Dengan adanya aplikasi di ponsel atau situs web, sekarang kita bisa pesan makanan secara online. Praktis banget, kan? Makanan yang kita suka bisa kita pesan tanpa harus keluar rumah.
## 1.2. Deskripsi Teknologi Informasi

    Selamat Datang di TastyTown!
    Kami menyediakan solusi praktis dan nyaman untuk anda menikmati makanan favorit langsung dari keyamanan rumah anda.dalam olshop makanan kami,anda dapat menemukan berbagai pilihan hidangan lezat yang siap untuk memanjakan lidah anda.
    Kami menyediakan beragam menu yang menggugah selera,mada aneka masakan soto ayam kuninng,empal gentong,ayam bakar,dan bebek ungkep.Setiap hidangan kami dipersiapkan dengan bahan-bahan segar dan berkualitas tinggi.
    Jadi,jangan ragu lagi untuk mengunjungi olshop kami dan nikmati makanan lezat dalam sekejap.

## 1.3.Branding
    Merk         :Tasty Town    
    Campaign     :Siapa nih yang sukaa makan Tasty Town? Kabar gembiraa sekarang Tasty Town ada layanan Deliverynya lho, cocok banget buat temen-temen yang mau pesen makan di rumah aja nihhh… Menu makanannya ada banyak, ada aneka masakan soto ayam kuning,empal gentong, ayam bakar,sate maranggi,  bebek ungkep & cah kangkung! Asliii menunya enak-enak 👍🏻👍🏻 Harganya juga terjangkau mulai dari 35.000 bisa untuk rame rame.. Asikkknya lagi ada free ongkir lho, s&k :
                  Minimal order 1 pcs
                  Bisa order dari jam 12.00-19.00
                  Free ongkir maks 3 KM ( lebih dari itu 3.000/KM)
    Target User  :Dibuka untuk semua kalangan
                            - cocok untuk user yang bingung memilih makanan
                            - sangat memudahkan bagi orang-orang yang malas masak dirumah
## 2. User Story


    Sebagai|Saya ingin|Sehingga|Level Prioritas
    ---|---|---|---
    Customer|memudahkan semua orang yang malas masak dirumah|sehingga customer bisa memesan makanan di tasty town|⭐⭐⭐⭐⭐
    Customer|membantu orang-orang yang ingin memesan makanan via online dapatmemudahkannya memesan makanan siap saji|⭐⭐⭐⭐⭐
    Customer|saya ingin dapat melihat daftar menu yang tersedia di olshop makanan,beserta deskripsi dan harga masing-masing menu|⭐⭐⭐⭐
    Customer|saya ingin dapat memperbarui informasi akun saya, termasuk alamat pengiriman dan detail pembayaran|⭐⭐⭐⭐
    Customer|saya ingin dapat menghubungi layanan pelanggan secara langsung jika mengalami masalah atau memiliki pertanyaan tentang pesanan|⭐⭐⭐
    Customer|saya ingin dapat menambahkan menu-menu ke dalam keranjang belanja,sehingga saya dapat memesan beberapa hidangan sekaligus|⭐⭐⭐⭐
    Customer|saya ingin dapat melakukan pembayaran secara online melalui metode yang aman,seperti debit atau Qris|⭐⭐⭐
    Customer|saya ingin bisa menyimpan beberapa metode pembayaran yang berbeda untuk fleksibilitas saat membayar|⭐⭐⭐
    Customer|saya ingin saya ingin mendapatkan konfirmasi pembayaran dan nomor pesanan setelah selesai melakukan transaksi|⭐⭐⭐⭐
    Customer|saya ingin saya menerima notifikasi tentang status pesanan saya ,seperti konfirmasi pesanan,pemrosesan,pengiriman,dan pengiriman selesai|⭐⭐⭐
    Customer|saya ingin mendapatkan notifikasi ketika pesanan saya sedang diproses atau dalam perjalanan untuk pengiriman|⭐⭐⭐⭐
    Customer|saya ingin mendapatkan poin atau diskon sebagai bentuk loyalitas setiap kali melakukan pemesanan|⭐⭐⭐⭐⭐
    Customer|saya ingin dapat mengakses menu makanan dalam bahasa yang saya pilih untuk kenyamanan saat melakukan pemesanan|⭐⭐⭐
    Customer|saya ingin dapat melacak pengiriman pesanan saya secara real-time,untuk mengetahui perkiraan waktu tiba|⭐⭐⭐
    Customer|saya ingin dapat melihat pesanan-pesanan yang masuk,dengan detail tentang menu yang dipesan,jumlah,dan informasi pelanggan|⭐⭐⭐⭐⭐
    Customer|saya ingin dapat melihat riwayat pemesanan saya untuk melacak transaksi sebelumnya|⭐⭐⭐⭐
    Customer|saya ingin memberikan ulasan dan feedback tenntang pengalaman saya menggunakan olshop makanan ini,sehingga toko dapat memberbaiki kualitas pelayanan|⭐⭐⭐⭐⭐
    Customer|saya ingin mendapatkan diskon khusus sebagai pelanggan yang sering menggunakan olshop makanan ini|⭐⭐⭐
    Customer| saya ingin dapat menyimpan pesanan favorit saya untuk memesan dengan cepat tanpa harus memilih kembali dari menu|⭐⭐⭐⭐
    

## 3. Struktur Data
    ```mermaid
    erDiagram
        Program ||--o{MEMESAN MAKANAN : MEMESAN ONLINE
        PENGGUNA
            string username
            string password
            }

            PENGGUNA_LAIN ||--|{   :
            PENGGUNA_LAIN {
                string username

                
            }

            DELIVERY ONLINE {
                memesan makanan 
                string username_pengguna
                int jumlahpesanan
                }
                PENGGUNA ||--|{PENGGUNA_LAIN : MEMESAN MAKANAN
            ```
            

## 4. Arsitektur Sistem
    
## 5. Teknologi , Library , dan Framework
    Teknologi  :Figma-Android Studio
    Library    :       
    Framework  :
## 6. Desain User Eksperience dan User Interface
    https://ibb.co/9ngTfRf
    https://ibb.co/ZLMgg5W
    https://ibb.co/syxHZQ2
    https://ibb.co/3S9rBdD
    https://ibb.co/HCxzHNY
## 7. Demontrasi Video

    Link yuotube nya
    
## 8. Bagaimana mesin komputasi dan sistem operasi berperan dalam produk teknologi informasi?

    Lik youtube nya di detik jawaban ini 

    
## 9. Jelaskan bagaimana algoritma,struktur data,dan bahasa pemrograman berperan dalam produk teknologi informasimu!
Algoritma:

Penanganan Pesanan: Algoritma dapat digunakan untuk mengelola pesanan makanan, dari pemesanan oleh pelanggan hingga pemrosesan di dapur. Algoritma ini harus efisien, meminimalkan waktu antara pemesanan dan pengantaran, dan memastikan bahwa pesanan diproses dengan benar.
Rekomendasi Makanan: Algoritma dapat digunakan untuk memberikan rekomendasi makanan kepada pelanggan berdasarkan preferensi sebelumnya atau tren populer. Ini dapat meningkatkan pengalaman pengguna dan meningkatkan penjualan.
Struktur Data:

Manajemen Inventori: Struktur data dapat digunakan untuk mengelola inventori bahan makanan. Informasi tentang stok, tanggal kedaluwarsa, dan perubahan harga dapat disimpan dalam struktur data seperti basis data, memungkinkan pemantauan inventori yang efisien.
Profil Pelanggan: Data pelanggan, seperti riwayat pesanan, preferensi makanan, dan informasi kontak, dapat disimpan dalam struktur data untuk personalisasi layanan dan meningkatkan retensi pelanggan.
Bahasa Pemrograman:

Front-end Development: Pemilihan bahasa pemrograman seperti HTML, CSS, dan JavaScript dapat digunakan untuk mengembangkan antarmuka pengguna yang menarik dan responsif pada aplikasi web atau aplikasi seluler untuk pemesanan makanan.
Back-end Development: Bahasa pemrograman seperti Python, Java, atau Ruby dapat digunakan untuk mengelola logika bisnis, seperti pemrosesan pesanan, manajemen inventori, dan interaksi dengan database.
Database Management: Bahasa SQL digunakan untuk mengelola dan mengakses data dalam basis data, sementara NoSQL dapat menjadi pilihan untuk skenario di mana fleksibilitas struktur data diperlukan.
Penggunaan algoritma, struktur data, dan bahasa pemrograman yang tepat dapat meningkatkan kinerja dan kehandalan produk teknologi informasi terkait produk makanan. Pemilihan teknologi yang sesuai akan memastikan bahwa sistem dapat beradaptasi dengan skala bisnis, menjaga keamanan data pelanggan, dan memberikan pengalaman pengguna yang optimal.

## 10.Jelaskan bagaimana metode pengembangan perangkat lunak/software Development life Cycle berperan dalam produk teknologi informasimu!
## 11.Jelaskan bagaimana Database/sistem basis data berperan dalam produk teknologi informasimu!
 Berikut adalah beberapa cara bagaimana database berkontribusi dalam operasional dan pengelolaan toko online makanan:

Penyimpanan Informasi Produk:

Database menyimpan informasi lengkap tentang produk makanan, termasuk deskripsi, harga, ketersediaan, dan gambar produk. Hal ini memungkinkan toko online untuk menampilkan katalog produk secara akurat kepada pelanggan.
Manajemen Stok:

Basis data membantu dalam melacak stok produk makanan yang tersedia. Dengan informasi stok yang terkini, toko online dapat mengelola persediaan dengan lebih efisien dan menghindari kesalahan seperti penjualan produk yang sudah habis.
Proses Pemesanan dan Pembayaran:

Data pelanggan, termasuk informasi kontak dan alamat pengiriman, disimpan dalam basis data. Ini memfasilitasi proses pemesanan, pengaturan pengiriman, dan pengelolaan transaksi pembayaran.
Riwayat Pemesanan Pelanggan:

Informasi pemesanan pelanggan disimpan dalam basis data, memungkinkan pembuat keputusan untuk melihat riwayat pembelian pelanggan. Hal ini dapat digunakan untuk menyusun program loyalitas, memberikan diskon berdasarkan sejarah pembelian, dan menganalisis tren konsumen.
Sistem Pengelolaan Pengiriman:

Basis data dapat digunakan untuk mengintegrasikan sistem pengelolaan pengiriman, memungkinkan pelacakan pengiriman secara real-time. Informasi ini juga membantu dalam menyusun rute pengiriman yang efisien.
Keamanan Data Pelanggan:

Database menyimpan data pelanggan dengan aman dan mengelolanya sesuai dengan kebijakan privasi. Ini penting untuk menjaga kepercayaan pelanggan dan mematuhi regulasi privasi data.
Analisis dan Pelaporan:

Data penjualan, preferensi pelanggan, dan performa produk dapat dianalisis melalui basis data. Hal ini membantu dalam menyusun laporan penjualan, memahami tren pasar, dan membuat keputusan strategis.
Manajemen Promosi dan Diskon:

Database memungkinkan toko online menyimpan informasi tentang program promosi, diskon, atau kode kupon. Sistem ini dapat diintegrasikan untuk memberikan diskon otomatis atau mengelola kode kupon selama proses pembayaran.
Fleksibilitas dalam Penyesuaian Produk:

Basis data dapat dengan mudah diperbarui untuk menyesuaikan menu atau katalog produk. Ini memungkinkan pemilik toko online untuk menambahkan atau menghapus produk tanpa harus melakukan perubahan besar dalam infrastruktur sistem.
Interaksi Pelanggan dan Umpan Balik:

Informasi umpan balik pelanggan, ulasan produk, dan pertanyaan yang diajukan dapat disimpan dalam basis data. Hal ini membantu dalam memahami tingkat kepuasan pelanggan dan memungkinkan interaksi yang lebih baik.
Dengan semua peran ini, database dalam sistem basis data menjadi tulang punggung untuk operasional yang efisien dan pengelolaan yang baik dalam produk olshop makanan.
