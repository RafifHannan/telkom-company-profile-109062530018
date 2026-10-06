# Telkom University Company Profile - Praktikum
Project simulasi HTML, CSS, PHP native, MySQL/MariaDB, dan Git.

## Menjalankan secara lokal
1. Salin folder proyek ke `htdocs` XAMPP.
2. Start Apache dan MySQL.
3. Import `database/telkom_profile.sql` melalui phpMyAdmin.
4. Buka `http://localhost/telkom-company-profile-final/`.

## Dokumentasi penyelesaian merge conflict
1. Membuat branch dengan nama `conflict-navbar` dan switch langsung ke branch `conflict-navbar`.
2. Edit pada baris dengan mengubah "Profil" menjadi "Tentang Kami".
3. Commit pada branch `conflict-navbar`.
4. Kembali switch menuju `main` branch.
5. "Tentang Kami" akan berubah kembali, karena pada `main` branch "Profil" tidak diubah.
6. Edit pada baris dengan mengubah "Profil" menjadi "Tentang Kampus".
7. Commit pada `main` branch. 
8. Merge `main` branch dengan `conflict-navbar`.
9. Tampilan akan otomatis memunculkan marker conflict.
10. Ubah menjadi final, pada kasus ini, mengubah kembali menjadi "Profil".
11. Commit untuk menyelesaikan merge.
12. Memastikan navbar tetap valid.

> Catatan: seluruh konten institusi bersifat simulasi untuk pembelajaran.