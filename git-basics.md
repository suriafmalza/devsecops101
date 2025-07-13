Git Branching

🔹 1. commit
Aspek
Penjelasan
Maksud & Kegunaan
Simpan snapshot projek semasa — seperti “save” dalam permainan.
Bila nak guna
Setiap kali siap satu perubahan bermakna (tambah fungsi, betulkan bug).
Analogi
Ambil gambar kerja harian supaya boleh rujuk balik.
Real-world case
Anda tambah fungsi “login” dan simpan kemajuan dengan git commit -m "Tambah fungsi login"


🔹 2. branch
Aspek
Penjelasan
Maksud & Kegunaan
Cipta laluan kerja baru tanpa ganggu kod utama.
Bila nak guna
Bila nak uji idea, tambah ciri baru, atau kerja dalam pasukan.
Analogi
Macam buat salinan kertas kerja dan tulis versi lain tanpa rosakkan salinan asal.
Real-world case
Anda buat git branch ciri-profile, ubah suai, dan merge semula ke main.


🔹 3. merge
Aspek
Penjelasan
Maksud & Kegunaan
Gabungkan kerja dari dua branch ke dalam satu.
Bila nak guna
Bila branch baru dah siap dan mahu digabung semula ke main.
Analogi
Satukan dua versi karangan jadi satu cerita lengkap.
Real-world case
Selepas siap ubah suai dalam feature-a, anda git merge feature-a ke main.


🔹 4. rebase
Aspek
Penjelasan
Maksud & Kegunaan
Susun semula commit supaya sejarah kelihatan kemas dan linear.
Bila nak guna
Bila nak elakkan sejarah bercabang; atau sebelum push ke GitHub.
Analogi
Salin semula nota lama atas kertas versi terkini.
Real-world case
Anda git rebase main semasa kerja dalam feature-b, supaya kerja anda ada di atas commit terkini dari main.


🔹 5. checkout
Aspek
Penjelasan
Maksud & Kegunaan
Berpindah ke branch atau commit tertentu.
Bila nak guna
Bila nak semak kod lama, pindah ke branch lain, atau cipta branch baru.
Analogi
Lompat ke bab tertentu dalam buku — anda lihat isi pada bab itu saja.
Real-world case
git checkout bugFix untuk ubah suai kod dalam branch tersebut.


🔹 6. HEAD
Aspek
Penjelasan
Maksud & Kegunaan
Penunjuk commit yang anda sedang berada sekarang.
Bila nak guna
Faham di mana anda berada dalam sejarah Git — penting bila buat merge/rebase.
Analogi
Penanda buku — tunjuk bab mana anda sedang baca/tulis.
Real-world case
Bila anda git checkout main, HEAD akan berada pada branch main. Bila git checkout C1, HEAD jadi "detached".

