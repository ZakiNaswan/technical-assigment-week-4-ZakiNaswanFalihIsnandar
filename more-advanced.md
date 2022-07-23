1. A. Git Reset
git reset merupakan perintah yang complex yang dapat digunakan untuk membatalkan perubahan yang dilakukan.
kita tidak dapat membatalkan git reset, semua perubahan yang telah di reset tidak dapat dikembalikan lagi.
B. Git Revert
Perintah git revert akan mengembalikan kondisi berkas yang ada dimasa lalu, selanjutnya akan digabungkan dengan commit -an terakhir dimasa sekarang.

git revert lebih aman digunakan daripada git reset. Karena perintah ini tidak akan menghapus catatan log git di masa yang lalu.

2. A. Git Merge
Ketika Kita punya 2 branch, develop dan master.
Saat kedua branch ini digabungkan maka akan menghasilkan satu commit baru.
Commit baru ini berisi catatan merge.

   B. Git Rebase
Dengan contoh kasus yang sama, kita akan menggabungkan branch develop dan master.
Jika diperhatikan, rebase hanya mengambil commit dari branch lain. Dalam hal ini branch master mengambil 2 commit dari branch develop. Perhatikan juga bahwa ketika menggunakan rebase maka tidak akan membuat commit baru.

Kapan harus menggunakan merge dan kapan menggunakan rebase?
- Jika kita bekerja dalam sebuah repository dengan sedikit branch, misal hanya ada 2–3 branch, sebaiknya gunakan merge.
- Sebaliknya, jika repositorinya punya banyak branch, sebaiknya menggunakan proses rebase.

3. git stash pop membuang simpanan (paling atas, secara default) setelah menerapkannya, sedangkan git stash apply menyimpannya di daftar simpanan untuk kemungkinan nanti digunakan kembali.
git stash pop menerapkan elemen simpanan teratas dan menghapusnya dari tumpukan. git stash apply melakukan hal yang sama, tetapi meninggalkannya di tumpukan simpanan.

Kapan harus menggunakan git stash pop dan kapan menggunakan git stash apply?
- Jika kamu ingin menerapkan perubahan simpanan teratas untuk perubahan yang tidak dipentaskan saat ini dan menghapus simpanan itu juga, maka kamu harus menggunakan git stash pop.
- Tetapi jika kamu ingin menerapkan perubahan simpanan teratas ke perubahan tidak dipentaskan saat ini tanpa menghapusnya, maka kamu harus menggunakan git stash apply.