# Perbandingan_Scaning_Networks
Nmap, Zenmap, dan Angry IP Scanner adalah alat yang digunakan untuk pemindaian jaringan, namun memiliki perbedaan signifikan dalam penggunaan dan fitur. Nmap adalah alat pemindaian jaringan berbasis command-line yang sangat kuat dan fleksibel, biasanya digunakan oleh pengguna tingkat lanjut yang memahami sintaksis terminal. Nmap memiliki kemampuan mendalam untuk pemetaan jaringan, deteksi layanan, dan identifikasi sistem operasi. Zenmap, di sisi lain, adalah antarmuka grafis (GUI) untuk Nmap, yang dirancang untuk memudahkan pengguna yang kurang nyaman dengan perintah terminal. Ini menawarkan hasil pemindaian yang ditampilkan secara visual, menjadikannya lebih ramah bagi pemula. Angry IP Scanner adalah alat GUI sederhana dan ringan yang lebih fokus pada pemindaian cepat IP address dan port. Meskipun tidak sekuat Nmap dalam hal fitur dan analisis mendalam, Angry IP Scanner sangat mudah digunakan dan cocok untuk pemindaian cepat tanpa kerumitan.

## Nmap:
Nmap (Network Mapper) adalah alat pemindaian jaringan berbasis command-line yang sangat kuat dan fleksibel, digunakan oleh administrator jaringan dan ahli keamanan untuk pemetaan jaringan, deteksi layanan, dan identifikasi sistem operasi. Nmap mampu melakukan pemindaian port, mendeteksi layanan yang berjalan di host, serta melakukan fingerprinting sistem operasi. Karena berbasis CLI, Nmap menawarkan fleksibilitas yang tinggi, tetapi membutuhkan pengetahuan yang baik tentang sintaksis perintah untuk memanfaatkan sepenuhnya kemampuannya. Alat ini sering digunakan dalam pengujian penetrasi, audit keamanan, dan troubleshooting jaringan.

![11](https://github.com/user-attachments/assets/76861e62-be9f-4a89-876f-b6c094df6cd5)

![2](https://github.com/user-attachments/assets/68bca916-8f16-462f-95ce-caae976403fd)


## zenmap:
Zenmap adalah versi GUI dari Nmap yang dirancang untuk memudahkan pengguna yang mungkin tidak terbiasa dengan perintah terminal atau ingin melihat hasil pemindaian dalam bentuk visual. Zenmap menawarkan fungsionalitas penuh Nmap tetapi dengan antarmuka yang lebih ramah pengguna, memungkinkan pengguna untuk menyimpan hasil pemindaian, membandingkan pemindaian sebelumnya, serta menampilkan peta topologi jaringan. Ini sangat membantu bagi pemula atau pengguna yang lebih menyukai antarmuka visual daripada mengetik perintah.

Fitur Utama Zenmap: Antarmuka Visual: Zenmap menyediakan antarmuka yang mudah digunakan dengan opsi-opsi yang intuitif, yang memungkinkan pengguna untuk mengonfigurasi pemindaian tanpa harus menulis perintah Nmap secara manual.

Profil Pemindaian: Zenmap memiliki fitur untuk menyimpan dan mengelola profil pemindaian. Pengguna bisa membuat profil dengan konfigurasi tertentu dan menggunakannya kembali di lain waktu, sehingga memudahkan pengulangan pemindaian jaringan.

Visualisasi Topologi Jaringan: Zenmap dapat menampilkan topologi jaringan secara visual setelah pemindaian selesai. Pengguna dapat melihat perangkat apa saja yang terhubung dalam jaringan, rute yang digunakan, dan status perangkat tersebut.

Penyimpanan Hasil Pemindaian: Zenmap memungkinkan pengguna untuk menyimpan hasil pemindaian dalam berbagai format, seperti XML, untuk analisis atau dibagikan dengan tim lain.

Support Multi-Platform: Zenmap tersedia untuk berbagai sistem operasi seperti Linux, Windows, dan macOS.

Menyederhanakan Perintah Nmap: Zenmap menampilkan perintah Nmap yang sesuai dengan konfigurasi pemindaian yang dipilih pengguna, sehingga membantu mempelajari perintah-perintah Nmap sambil menggunakan GUI.

![1](https://github.com/user-attachments/assets/7c42c3fd-2483-483d-9233-cac3829c81ed)


## Angry IP Scanner:
Angry IP Scanner adalah alat pemindaian jaringan berbasis GUI yang lebih sederhana dan ringan dibandingkan dengan Nmap atau Zenmap. Alat ini dirancang untuk pemindaian IP address dan port dengan cepat, tanpa terlalu banyak pengaturan atau opsi konfigurasi. Meskipun fiturnya tidak selengkap Nmap, Angry IP Scanner mudah digunakan bahkan oleh pengguna non-teknis. Ini ideal untuk tugas pemindaian dasar, seperti memeriksa host aktif dalam jaringan atau memeriksa port terbuka pada server, dan cocok untuk pengguna yang menginginkan pemindaian cepat tanpa kerumitan.     

Fitur Utama Angry IP Scanner:

Pemindaian Cepat dan Ringan: Angry IP Scanner terkenal karena kecepatannya dalam memindai jaringan, karena menggunakan teknik pemindaian multi-threading, yang memproses banyak alamat IP secara paralel.

Antarmuka yang Sederhana: Angry IP Scanner memiliki antarmuka grafis yang sederhana dan mudah digunakan, bahkan oleh pengguna yang tidak berpengalaman dalam administrasi jaringan. Pengguna hanya perlu memasukkan rentang IP atau alamat IP spesifik, dan pemindaian bisa langsung dimulai.

Fleksibilitas dalam Pemindaian: Pengguna dapat memilih untuk memindai alamat IP dalam rentang tertentu dan juga menentukan port mana saja yang ingin dipindai. Selain itu, alat ini bisa memindai perangkat di jaringan lokal (LAN) atau jaringan yang lebih besar.

Informasi yang Ditampilkan: Setelah pemindaian selesai, Angry IP Scanner menampilkan daftar perangkat yang aktif, bersama dengan informasi seperti alamat IP, hostname, status port, dan MAC address (jika tersedia). Hasil pemindaian bisa diekspor dalam format berbeda seperti CSV, TXT, XML, atau bahkan diekspor ke basis data SQL.

Plugin yang Dapat Diperluas: Angry IP Scanner mendukung plugin, sehingga pengguna dapat menambahkan fungsionalitas tambahan sesuai dengan kebutuhan mereka. Multi-Platform:

Alat ini tersedia untuk berbagai sistem operasi seperti Windows, Linux, dan macOS.

Penggunaan Angry IP Scanner

Pemindaian IP: Pengguna bisa memasukkan rentang alamat IP atau alamat tunggal yang ingin dipindai. Misalnya, memasukkan 192.168.1.1-254 akan memindai seluruh alamat di jaringan lokal tersebut.

Pemindaian Port: Pengguna bisa menentukan port tertentu yang ingin dipindai. Jika tidak ada port yang ditentukan, Angry IP Scanner akan memindai port standar seperti HTTP (port 80), SSH (port 22), dan lainnya.

Ekspor Hasil: Setelah pemindaian selesai, hasil bisa disimpan dan diolah lebih lanjut untuk analisis jaringan atau audit keamanan.

Deteksi Perangkat Aktif: Angry IP Scanner menandai perangkat mana saja yang aktif (online) berdasarkan respons dari ping atau koneksi ke port terbuka.

contoh hasil tampilan :

![1](https://github.com/user-attachments/assets/94461dbd-63b3-4f43-b7ff-00df98e4aa28)

