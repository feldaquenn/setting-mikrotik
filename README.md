# setting-mikrotik
Sebelum memulai setting Mikrotik, ada beberapa persiapan yang perlu dilakukan. Pastikan kita telah mempersiapkan perangkat Mikrotik yang akan digunakan, kabel-kabel yang dibutuhkan, dan komputer untuk mengakses Mikrotik. Selain itu, pastikan juga kita memiliki akses ke internet untuk mendownload aplikasi Winbox yang akan digunakan untuk mengakses Mikrotik.

1. Hubungkan Router
Hal pertama yang kita lakukan adalah menghubungkan router Mikrotik ke komputer. Untuk melakukan ini, cukup sambungkan kabel Ethernet dari port LAN Mikrotik ke port Ethernet pada komputer. Pastikan kabel terhubung dengan baik dan tidak ada masalah pada koneksinya.

2. Unduh dan Instal Aplikasi Winbox
Winbox merupakan aplikasi yang akan digunakan untuk mengakses dan mengelola Mikrotik. Kita dapat mengunduh aplikasi ini dari situs resmi Mikrotik atau dari sumber terpercaya lainnya. Setelah mengunduh, instal aplikasi Winbox di komputer.

3. Konfigurasi Awal
Setelah menginstal Winbox, buka aplikasi tersebut dan cari Mikrotik yang terhubung ke komputer. Klik pada Mikrotik yang terdeteksi dan klik tombol ‘Connect’ untuk menghubungkan ke Mikrotik.

4. Setting Konfigurasi IP Address
Konfigurasi IP Address diperlukan untuk mengatur alamat IP pada perangkat Mikrotik. Untuk melakukan ini, buka jendela ‘Bridge’ pada aplikasi Winbox dan klik tab ‘Bridge’. Tekan tombol (+) untuk membuka dialog baru dan masukkan nama lokal bridge. Klik OK untuk menyimpan pengaturan.

Selanjutnya, klik tab ‘Ports’ dan klik tombol (+) untuk menambahkan interface Ether2. Pilih ‘Local’ di bagian Bridge dan tekan OK untuk menyimpan pengaturan. Terakhir, buka IP dan klik Addresses. Masukkan alamat IP (misalnya, 192.168.88.1/24) dan pilih ‘Local’ di bagian ‘Interface’. Tekan OK untuk menyimpan pengaturan.

5. Setting Konfigurasi DHCP Server
Konfigurasi DHCP Server diperlukan untuk mengatur alamat IP secara otomatis pada perangkat yang terhubung ke jaringan Mikrotik. Untuk melakukan ini, buka IP pada aplikasi Winbox dan klik ‘DHCP Server’. Tekan tombol DHCP Set up untuk membuka jendela baru. Klik ‘Local’ pada ‘DHCP Server Interface’ dan klik ‘Next’ untuk melanjutkan proses konfigurasi.

6. Setting Konfigurasi Jaringan Internet
Terakhir, setting konfigurasi jaringan internet diperlukan agar perangkat dapat mengakses internet. Untuk melakukan ini, buka kategori segmen PPP pada aplikasi Winbox dan klik tab Interfaces. Klik tombol (+) untuk menambahkan ‘PPPoE Client’. Pilih ‘Ether 1’ di bagian ‘Interfce’ dan klik OK untuk menyimpan pengaturan.

7. Verifikasi Konektivitas
Setelah semua konfigurasi selesai, verifikasi konektivitas IP dengan melakukan Ping ke Alamat IP yang diketahui server Google. Jika ping berhasil, berarti konfigurasi telah berhasil dan kita dapat mengakses internet dari perangkat Mikrotik.

Semoga ulasan tentang cara setting mikrotik ini bermanfaat dan dapat membantu dalam mengatur jaringan Mikrotik.
