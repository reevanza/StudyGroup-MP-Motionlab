"Rangkuman Week 1"
"**Version Control**"
"Sistem yang mengelola perubahan pada kode atau dokumen, memungkinkan pelacakan versi dan pengembalian ke versi sebelumnya jika perlu" 

"**Git**"
"Salah satu Version Control System paling populer yang membantu developer mencatat dan mengelola perubahan kode, baik secara individu maupun kolaboratif. Git mendukung branching untuk pekerjaan paralel dan fleksibel."


"**Github**"
"Platform berbasis web yang menggunakan Git untuk kolaborasi tim dalam mengelola dan membagikan kode. GitHub menyediakan fitur seperti issue tracking, project board, dan code review untuk meningkatkan produktivitas."
"Platform lain: selain GitHub, ada juga GitLab dan Bitbucket yang memiliki fitur serupa."

"**Fitur**"
"Commit: Menyimpan perubahan sebagai snapshot dari kode pada waktu tertentu."
"Branching: Membuat cabang kode untuk mengembangkan fiturbaru tanpa mengganggu kode utama."
"Merging: Menggabungkan perubahan dari branch berbeda kedalam branch utama."
"Revert: Mengembalikan perubahan yang telah dibuat."
"Stash: Menyimpan perubahan sementara tanpa melakukan commit."


"**Alur Kerja**"
"Alur Kerja Git mengatur bagaimana proyek dikembangkan menggunakan branch (cabang)."
"Centralized Workflow: semua developer bekerja pada satu branch utama (main)."
"Feature Branch Workflow: setiap fitur dikembangkan pada branch terpisah untuk mengurangi risiko konflik."
"Gitflow: alur kerja terstruktur dengan branch khusus untuk pengembangan, pengujian, dan produksi."


"**Dasar Git**"
"git init: Membuat repositori baru."
"git status: Melihat perubahan yang terjadi."
"git add: Menambahkan file ke staging area."
"git commit: Menyimpan perubahan sebagai satu versi."
"git push: Mengunggah perubahan ke repositori jarak jauh."
"git pull: Mengambil pembaruan dari repositori jarak jauh."
"git reset: Mengembalikan commit tertentu (sebagai “undo”)."

"**Situasi Branching dan Merging**"
"Branching: Membuat cabang kode terpisah untuk fitur baru atau perbaikan bug tanpa mengganggu kode utama."
"Merging: Menggabungkan hasil kerja dari branch ke branch utama setelah perubahan selesai."

"**Situasi Branching dan Merging**"
"Konflik terjadi saat dua pengguna mengubah bagian kode yang sama."
"Git meminta pengguna untuk menyelesaikan konflik secara manual dengan memilih atau menggabungkan perubahan yang sesuai."

"**Situasi Branching dan Merging**"
"Fork: Menyalin repositori orang lain untuk pengembangan lebih lanjut."
"Pull Request: Meminta agar perubahan di repositori kita digabung ke repositori asal."
"Code Review: Memeriksa kode agar sesuai dengan standar kualitas."

"**Best Practice**"
"Lakukan commit secara teratur dan jelas."
"Hindari commit langsung ke branch utama."
"Perbarui branch sebelum melakukan merge untuk mencegah konflik."
"Gunakan .gitignore untuk mengabaikan file yang tidak perlu diunggah."