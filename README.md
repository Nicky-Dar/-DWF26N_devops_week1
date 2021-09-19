# DWF26N_devops_week1
# DevOps
DevOps adalah gabungan dari Development dan Operations. DevOps adalah sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien. DevOps tumbuh sebagai reaksi terhadap beberapa masalah umum yang dihadapi industri teknologi informasi, termasuk pembungkaman anggota tim dan pekerjaan yang mereka lakukan, ketidak pastian memperkenalkan fitur baru atau menerapkan perubahan, kesulitan menemukan dan mengatasi cacat dan munculnya kemacetan dalam software development lifecycle (SDLC). 
DevOps bertujuan untuk mengatasi tantangan ini dengan meningkatkan seberapa baik operasi TI dan tim pengembangan berkolaborasi untuk menciptakan lingkungan yang dicirikan oleh tim terpadu dengan keahlian

# Pipeline
![pipeline-devops](https://user-images.githubusercontent.com/88620315/133464745-4af9262c-0471-4035-b7c5-acdf5711ea7a.png)
Pipeline DevOps adalah sekumpulan proses yang memungkinkan tim developer dan tim operations dapat bekerja sama untuk membangun dan menerapkan kode ke production environment. Pipeline DevOps sendiri terdiri dari 2 bagian yaitu development dan opration, namun secara garis besar mereka akan mengikuti fase DevOps pipeline berikut:


#### Devlopment :
 
1. Plan

    Fase ini melibatkan perencanaan untuk seluruh alur kerja yang dibutuhkan sebelum tim pengembang mulai menulis kode. Dalam tahap ini, manajer produk dan manajer proyek akan memainkan peran penting. Mereka akan bekerjasama untuk mengumpulkan requirements dan feedback dari klien ataupun stakeholders. Informasi tersebut kemudian akan dikumpulkan untuk membangun roadmap produk untuk memandu proses pengembangan yang akan dilakukan.

2. Code

    Setelah rencana dibuat, tim developer dapat mulai menulis kode yang dibutuhkan untuk mengembangkan produk. Tim developer biasanya akan menggunakan seperangkat plugin standar yang dipasang di lingkungan pengembangan mereka untuk membantu proses pengembangan, membantu menerapkan gaya kode yang konsisten, serta menghindari kelemahan keamanan umum dan anti-pattern.

3. Build

    Setelah tim developer selesai menulis kode yang dibutuhkan, mereka akan memasukan kode tersebut ke dalam shared code repository. Developer akan mengirimkan pull request, setelah developer yang lain akan mereview perubahan yang telah dilakukan. Jika kode tidak memiliki masalah, maka developer tersebut akan menyetujui pull request yang telah dikirim sebelumnya.

4. Test

    Langkah selanjutnya adalah melakukan pengujian.  Jika ada masalah yang ditemukan pada fase ini, maka masalah tersebut akan dikirim kembali ke tim developer untuk diselesaikan.


#### Opration:

5. Release

    Fase release menjadi tonggak penting dalam DevOps pipeline. Pada tahap ini, setiap perubahan kode telah melewati serangkaian pengujian dan tim IT operations telah memastikan bahwa masalah yang merusak dan regresi sudah teratasi dengan baik.

6. Deploy

    Tahap selanjutnya adalah deployment. Setelah production environment dibuat dan dikonfigurasi maka versi terakhir dari pengembangan yang telah dilakukan akan diterapkan.

7. Monitor

    Pada tahap terakhir ini, tim IT operations akan terus bekerja keras untuk memantau infrastruktur, sistem, dan aplikasi. Hal ini dilakukan untuk memastikan bahwa produk atau aplikasi yang dikembangkan dapat berjalan dengan lancar. Mereka juga mengumpulkan data-data penting dari log, analitik, sistem monitoring, serta melihat feedback dari pengguna untuk mengetahui jika ada masalah pada kinerja aplikasi. 

# Tools yang Digunakan DevOps
Tools DevOps
![tools-devops](https://user-images.githubusercontent.com/88620315/133465203-bd4d970f-7859-4e4c-8d2b-6aaf0d455c16.png)
Melalui berbagai referensi, ada banyak alat bantu atau tools untuk DevOps yang diperlukan. Berikut beberapa tools yang umumnya digunakan dalam proses development dan opration:

1. **Source Code Management**

    Dengan membuat repository pada source code management, antar developer dapat memeriksa dan mengubah kode tanpa perlu saling menulis satu sama lainnya. digunakan untuk melacak modifikasi ke repositori kode sumber. SCM melacak riwayat perubahan yang berjalan ke basis kode dan membantu menyelesaikan konflik saat menggabungkan pembaruan dari beberapa kontributor. SCM juga identik dengan Version control. Ketika beberapa pengembang bekerja dalam basis kode bersama, adalah hal yang biasa terjadi untuk mengedit bagian kode yang dibagikan. Pada pengembangan terpisah mungkin sedang mengerjakan fitur yang tampaknya terisolasi, namun fitur ini mungkin menggunakan modul kode bersama.Oleh karena itu pengembang 1 yang mengerjakan Fitur 1 dapat melakukan beberapa pengeditan dan kemudian mengetahui bahwa Pengembang 2 yang mengerjakan Fitur 2 memiliki pengeditan yang berbeda. SCM membawa version control untuk mencegah hilangnya pekerjaan karena penimpaan konflik. Perlindungan ini bekerja dengan melacak perubahan dari setiap pengembang individu dan mengidentifikasi area konflik dan mencegah penimpaan. SCM kemudian akan mengomunikasikan titik konflik ini kembali ke pengembang sehingga mereka dapat meninjau dan menangani dengan aman. Source control ini sendiri merupakan komponen utama dari Continuous Integration atau CI.

    Beberapa contoh produk yang digunakan sebagai SCM yaitu Git, GitHub, Gitlab, Mercurial, Subversion, Cloudforce, Bitbucket, dan TFS.

![image](https://user-images.githubusercontent.com/88620315/133928373-b2a3181b-5654-4665-aa89-6e4cf57db17f.png)


2. **Container Management tools**
    
    Manajemen kontainer mengacu pada serangkaian praktik yang mengatur dan memelihara perangkat lunak kontainerisasi. Alat manajemen kontainer mengotomatiskan pembuatan, penyebaran, penghancuran, dan penskalaan kontainer aplikasi atau sistem.
    Kontainerisasi adalah pendekatan untuk pengembangan perangkat lunak yang mengisolasi proses yang berbagi kernel OS dan mengikat pustaka aplikasi dan dependensi ke dalam satu unit yang dapat diterapkan. Hal ini membuat container ringan untuk dijalankan, karena hanya memerlukan informasi konfigurasi aplikasi dan kode dari OS host.
    
    ![image](https://user-images.githubusercontent.com/88620315/133932647-e2e1f42a-8ac5-4e13-815b-8149a3ecb000.png)
    
    **Docker**: Docker adalah alat ringan yang bertujuan untuk menyederhanakan dan mempercepat berbagai alur kerja di SDLC Anda dengan pendekatan terintegrasi. Docker kontainer adalah paket mandiri yang dapat dieksekusi yang mencakup semua yang Anda butuhkan untuk menjalankan aplikasi. Beberapa fitur utama docker yang sangat diperlukan diantara alat DevOps adalah:
    
    * Packaging format standart untuk berbagai aplikasi.
    * Runtime kontainer yang berjalan di berbagai OS Linux dan Windows Server.
    * Pengembang menggunakan Docker untuk membangun, menguji, dan berkolaborasi.
    *Docker Hub untuk menjelajahi jutaan gambar dari komunitas dan penerbit terverifikasi.
    *Kemas, Jalankan, dan Kelola aplikasi terdistribusi dengan Aplikasi Docker.
    
    ![image](https://user-images.githubusercontent.com/88620315/133932741-b45b6847-ba17-49f5-baa2-eecbe70368de.png)
    
    **Kubernetes**: Kubernetes adalah alat DevOps open-source yang digunakan untuk mengotomatisasi penerapan dan pengelolaan aplikasi dalam container & mungkin salah satu alat orkestrasi container paling populer. Fitur yang membedakannya dari Alat DevOps lainnya meliputi:
    * Membuat perubahan pada aplikasi Anda, mengkonfigurasinya dan monitoring kesehatan aplikasi otomatis secara bersamaan - rollouts & rollbacks.
    * Menawarkan alamat IP sendiri dan single name DNS untuk satu set Pod – Service Delivery and load balancing.
    * Pemasang storage system pilihan Anda secara otomatis.
    * Dapat melakukan Self-healing
    
    ![image](https://user-images.githubusercontent.com/88620315/133933974-dfc78729-4cee-4a79-b996-33ca23c42bb6.png)
    
    **Mesos**: Apache Mesos adalah alat DevOps untuk mengelola cluster komputer. Ini adalah kernel sistem terdistribusi untuk manajemen sumber daya dan penjadwalan di seluruh pusat data dan lingkungan cloud. Fitur-fiturnya meliputi:
    * Mendukung aplikasi cloud-native dan lama untuk berjalan di cluster yang sama dengan kebijakan penjadwalan yang dapat dipasangkan.
    * Berjalan di lintas platform seperti Linux, OSX dan Windows.
    * Dapat menscale hingga 10.000 node dengan mudah.
    


3. **Application Performance Monitoring tools**

    Dengan menggunakan APM, perusahaan dapat memantau seluruh lingkungan aplikasi untuk memastikan kinerjanya sudah sesuai standar, mengidentifikasi bugs dan masalah dalam aplikasi sebelum masalah tersebut berdampak pada end user.
    Tanpa APM, tim IT perusahaan akan sulit menemukan masalah yang terjadi pada aplikasi. Ini artinya, perlu ada dampak langsung terlebih dahulu pada end user untuk mengetahui masalah yang terjadi pada aplikasi. Pastinya, jika sering terjadi kendala dalam aplikasi yang berdampak langsung pada end user, akan berpengaruh negatif terhadap kepuasan pelanggan dan kualitas experiencenya.
    Dengan menggunakan APM, tim IT dapat mengetahui masalah yang terjadi sebelum masalah tersebut berdampak langsung pada end user. Dengan begitu, perusahaan dapat selalu memberikan digital experience yang prima dan berkualitas untuk pelanggannya.
    
    ![image](https://user-images.githubusercontent.com/88620315/133936498-ae0023bb-9737-4bbb-868f-220938600b8f.png)
    
    **Prometheus**: Prometheus adalah solusi pemantauan kinerja open-source dan berbasis komunitas. Ini juga mendukung pemantauan kontainer dan membuat peringatan berdasarkan data deret waktu. Solusi mencakup fitur-fitur berikut:
    * Penskalaan dengan bantuan sharding dan federasi fungsional.
    * Banyak perpustakaan klien memungkinkan instrumentasi layanan yang mudah.
    * Kemampuan pelaporan yang kuat melalui PromQL.
    
    


4. **Build Server**

    Build server adalah alat otomatisasi yang mengkompilasi kode dalam SCR (Source Code Repository) ke dalam basis kode yang dapat dieksekusi. Server build adalah alat yang digunakan juga pada Continuous Integration (CI). Ada sejumlah opsi open source dan komersial yang tersedia dalam kategori tools ini, dan Anda dapat menulis server build sederhana Anda sendiri hanya sebagai skrip yang dapat mendeteksi saat pembaruan telah dilakukan pada Kontrol Versi, dan memicu build sebagai hasilnya. Versi paling baru dari tools ini akan mendukung berbagai sistem kontrol versi yang berbeda dan banyak opsi berbeda untuk kapan dan bagaimana memicu pembangunan, apa yang harus dilakukan sebagai bagian dari pembangunan (misalnya menjalankan tes, menyebarkan ke staging server), dan bagaimana untuk memberi tahu anggota tim tentang hasil pembangunan. Di luar Continuous Integration (CI) server build dapat mengaktifkan Continuous Deployment, menerapkan pembaruan ke produksi saat build berhasil dan lulus semua pengujian.
    Bahkan jika sebuah proyek hanya memiliki satu pengembang yang mengerjakannya, server build menambahkan nilai dalam beberapa cara. Ini menghilangkan sindrom "It works on my machine", di mana perangkat lunak hanya berfungsi ketika berada di lingkungan tertentu, dan dependensi tersembunyi ini tidak selalu jelas, bahkan bagi pengembang perangkat lunak (pada mesin yang berbeda semuanya dapat berjalan dengan baik). 
    Jika proyek memiliki pengujian otomatis, beberapa di antaranya mungkin memerlukan lebih dari beberapa detik untuk dijalankan, server build dapat memindahkan tugas ini dari alur kerja developer dan menjalankannya secara paralel. Jika tidak, gesekan dari menjalankan tes ini dapat mengakibatkan pengembang memilih untuk tidak menjalankannya terlalu sering, mengurangi nilainya dan meningkatkan siklus umpan balik antara bug yang diperkenalkan dan terdeteksi (dengan tes atau sebaliknya).

    Beberapa contoh produk yang digunakan sebagai server builder seperti Jenkins, SonarQube, JetBrains TeamCity, Team Foundation Server Build Server dan Artifactory.
    

5. **Configuration Management**

    Manajemen konfigurasi adalah sumber daya adalah metode otomatis untuk memelihara sistem komputer dan perangkat lunak dalam keadaan yang diketahui dan konsisten. configuration management berguna untuk menetapkan konfigurasi pada server atau lingkungannya. 
Alat yang populer biasa kamu temukan seperti Red Hat Ansible, Puppet, dan Chef.

6. **Virtual Infrastructure**

    Amazon Web Services dan Microsoft Azure adalah contoh infrastruktur virtual. Virtual Infrastructure ini disediakan oleh vendor cloud yang menjual insrastruktur atau Platform as a Service (PaaS). Infrastruktur ini memiliki API yang memungkinkan kamu membuat mesin baru yang terprogram dengan alat manajemen konfigurasi.

    Ada juga private cloud di mana private infrastructure virtual memungkinkan kamu menjalankan cloud di hardware sebagai data terpusat.

    Alat ini dikombinasikan dengan alat otomatisasi untuk memberdayakan organisasi yang melatih DevOps dengan kemampuan konfigurasi server tanpa jari di atas keyboard. Jika ingin menguji kode baru, cukup mengirimkan kode ke infrastruktur cloud untuk membangun lingkungan. Kemudian tes dijalankan tanpa adanya campur tangan manusia.

6. **Test Automation**

    Test automation sebenarnya sudah ada sejak lama. Pengujian yang diadopsi oleh DevOps berfokus pada pengujian otomatis melalui pipeline build untuk memastikan bahwa build deployable sudah dilakukan. Tools populer untuk tahapan ini adalah Selenium dan Air.
