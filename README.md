Repository = Database yang menyimpan history/ riwayat perubahan

Snapshot = Potret kondisi file dan folder pada saat tertentu

Commit = Snapshot yang disimpan di repository

Branch = Serangkaian commit yang berkaitan sehingga kalau digambar seperti garis lurus berisi banyak commit. Satu repository bisa berisi banyak branch.

Master = Nama branch default yang diberikan git pada waktu kita membuat repository. Branch master ini tidak istimewa. Dia bisa dihapus dan direname sesuka hati.

Head = Ujung branch, commit terbaru di dalam branch

HEAD = Head yang sedang aktif. Walaupun satu repository bisa memiliki banyak branch, tapi cuma satu yang aktif.
Working Folder = Folder berisi file dan folder tempat kita bekerja. Biasanya working folder berisi banyak file source code untuk aplikasi yang sedang kita buat. Git memantau working folder ini, dan bisa mengetahui file dan folder mana yang sudah berbeda dari posisi commit terakhir. Perbedaan atau perubahan ini bisa disimpan menjadi commit baru, atau dikembalikan ke kondisi sebelum diubah.

Staging Area = Snapshot dari working folder yang akan kita simpan pada saat commit. Ini adalah fitur unik Git yang tidak dimiliki version control lain. Dengan adanya staging area, kita bisa memilih perubahan mana yang akan di-commit dan mana yang tidak.

Object Store = ini adalah database tempat semua commit disimpan.
