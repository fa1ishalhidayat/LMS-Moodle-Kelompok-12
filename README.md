# LMS Moodle Kelompok 12
ADAPTLOOP: Pengembangan Challenge Loop Progress Tracking dan Adaptive Task Reminder Berbasis Moodle

<img width="1919" height="912" alt="Screenshot 2026-05-19 151204" src="https://github.com/user-attachments/assets/65da1a0c-eaa7-4e99-a8ee-4a8314223b0c" />


Project Akhir E-Learning Pembuatan LMS berbasis Moodle

Oleh :
MUHAMMAD FAISHAL HIDAYAT (25050974075)

MUHAMMAD NUR RAFI (25050974108)


## File dalam Repository

1. backup-moodle2-course-8-xxx.mbz
   → Untuk file backup course Moodle

2. moodle_database.sql
   → File database export dari phpMyAdmin

3. Plugin Moodle/
   → Plugin tambahan yang digunakan (Completion Progress)



## Cara Menjalankan LMS Moodle 

1.  Pastikan sudah terinstall Moodle pada perangkat anda
2. Install plugin tambahan:
   - Pada moodle klik Site Administration > Plugins > Install plugin > masukkan file plugin yang sudah didownload >
      tunggu proses hingga selesai > done
     
   - Plugin block_completion_progress
    
    Jika versi moodle nya berbeda dengan yang saya gunakan saat ini boleh mendownload dan menyesuaikan versi moodle  yang digunakan
    untuk pluginnya pada link yang tertera:
    https://moodle.org/plugins/block_completion_progress/version-for-moodle-4.1-onwards/38217?lang=en_us&utm_source=

4. Import database moodle_database.sql ke phpMyAdmin XAMPP
5. Restore file backup .mbz melalui:

   Site Administration > Courses > Restore > Tunggu proses > Selesai
7. Selesai
8. LMS Moodle bisa digunakan dengan fitur yang sudah ada pada plugin block completion progress yang sudah di install tadi






Versi Moodle yang digunakan:
Moodle 5.0.6
