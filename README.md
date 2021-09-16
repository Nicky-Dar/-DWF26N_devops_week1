# DWF26N_devops_week1
# DevOps
DevOps adalah gabungan dari Development dan Operations. DevOps adalah sebuah prinsip developer untuk mengkoordinasikan antar tim yaitu tim development dengan tim operations dengan efektif dan efisien.



# Pipeline
![pipeline-devops](https://user-images.githubusercontent.com/88620315/133464745-4af9262c-0471-4035-b7c5-acdf5711ea7a.png)
Pipeline DevOps adalah sekumpulan proses yang memungkinkan tim developer dan tim operations dapat bekerja sama untuk membangun dan menerapkan kode ke production environment. Pipeline DevOps sendiri terdiri dari 2 bagian yaitu development dan opration, namun secara garis besar mereka akan mengikuti fase DevOps pipeline berikut:
 Devlopment :
1. Plan
Fase ini melibatkan perencanaan untuk seluruh alur kerja yang dibutuhkan sebelum tim pengembang mulai menulis kode. Dalam tahap ini, manajer produk dan manajer proyek akan memainkan peran penting. Mereka akan bekerjasama untuk mengumpulkan requirements dan feedback dari klien ataupun stakeholders. Informasi tersebut kemudian akan dikumpulkan untuk membangun roadmap produk untuk memandu proses pengembangan yang akan dilakukan.

2. Code
Setelah rencana dibuat, tim developer dapat mulai menulis kode yang dibutuhkan untuk mengembangkan produk. Tim developer biasanya akan menggunakan seperangkat plugin standar yang dipasang di lingkungan pengembangan mereka untuk membantu proses pengembangan, membantu menerapkan gaya kode yang konsisten, serta menghindari kelemahan keamanan umum dan anti-pattern.

3. Build
Setelah tim developer selesai menulis kode yang dibutuhkan, mereka akan memasukan kode tersebut ke dalam shared code repository. Developer akan mengirimkan pull request, setelah developer yang lain akan mereview perubahan yang telah dilakukan. Jika kode tidak memiliki masalah, maka developer tersebut akan menyetujui pull request yang telah dikirim sebelumnya.

4. Test
Langkah selanjutnya adalah melakukan pengujian.  Jika ada masalah yang ditemukan pada fase ini, maka masalah tersebut akan dikirim kembali ke tim developer untuk diselesaikan.

Opration:
5. Release
Fase release menjadi tonggak penting dalam DevOps pipeline. Pada tahap ini, setiap perubahan kode telah melewati serangkaian pengujian dan tim IT operations telah memastikan bahwa masalah yang merusak dan regresi sudah teratasi dengan baik.

6. Deploy
Tahap selanjutnya adalah deployment. Setelah production environment dibuat dan dikonfigurasi maka versi terakhir dari pengembangan yang telah dilakukan akan diterapkan.

7. Monitor
Pada tahap terakhir ini, tim IT operations akan terus bekerja keras untuk memantau infrastruktur, sistem, dan aplikasi. Hal ini dilakukan untuk memastikan bahwa produk atau aplikasi yang dikembangkan dapat berjalan dengan lancar. Mereka juga mengumpulkan data-data penting dari log, analitik, sistem monitoring, serta melihat feedback dari pengguna untuk mengetahui jika ada masalah pada kinerja aplikasi. 

# Tools yang Digunakan DevOps
Tools DevOps
![tools-devops](https://user-images.githubusercontent.com/88620315/133465203-bd4d970f-7859-4e4c-8d2b-6aaf0d455c16.png)
Melalui berbagai referensi, ternyata ada banyak alat bantu untuk menerapkan DevOps yang harus kamu tahu.

1 Source Code Management
Dengan membuat repository pada source code management, antar developer dapat memeriksa dan mengubah kode tanpa perlu saling menulis satu sama lainnya. Source control ini merupakan komponen utama dari Continuous Integration atau CI.

Beberapa contoh produk yang digunakan sebagai SCM yaitu Git, GitHub, Mercurial, Subversion, Cloudforce, Bitbucket, dan TFS.

2 Build Server
Build server adalah alat otomatisasi yang mengkompilasi kode dalam SCR (Source Code Repository) ke dalam basis kode yang dapat dieksekusi. Alat ini bisa kamu temukan seperti Jenkins, SonarQube, dan Artifactory.

3 Configuration Management
Manajemen konfigurasi berguna untuk menetapkan konfigurasi pada server atau lingkungannya. Alat yang populer biasa kamu temukan seperti Puppet dan Chef.

4 Virtual Infrastructure
Amazon Web Services dan Microsoft Azure adalah contoh infrastruktur virtual. Virtual Infrastructure ini disediakan oleh vendor cloud yang menjual insrastruktur atau Platform as a Service (PaaS). Infrastruktur ini memiliki API yang memungkinkan kamu membuat mesin baru yang terprogram dengan alat manajemen konfigurasi.

Ada juga private cloud di mana private infrastructure virtual memungkinkan kamu menjalankan cloud di hardware sebagai data terpusat.

Alat ini dikombinasikan dengan alat otomatisasi untuk memberdayakan organisasi yang melatih DevOps dengan kemampuan konfigurasi server tanpa jari di atas keyboard. Jika ingin menguji kode baru, cukup mengirimkan kode ke infrastruktur cloud untuk membangun lingkungan. Kemudian tes dijalankan tanpa adanya campur tangan manusia.

5 Test Automation
Test automation sebenarnya sudah ada sejak lama. Pengujian yang diadopsi oleh DevOps berfokus pada pengujian otomatis melalui pipeline build untuk memastikan bahwa build deployable sudah dilakukan. Tools populer untuk tahapan ini adalah Selenium dan Air.
