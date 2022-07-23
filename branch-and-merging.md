1. Untuk menghapus file dan direktori yang diabaikan.
2. a) flag -d
Biasanya, ketika tidak ada <path> yang ditentukan, git clean tidak akan muncul kembali ke direktori yang tidak terlacak untuk menghindari penghapusan terlalu banyak. Tentukan -d untuk membuatnya berulang ke direktori seperti itu juga. Jika ada jalur yang ditentukan, -d tidak relevan; semua file yang tidak terlacak yang cocok dengan jalur yang ditentukan (dengan pengecualian untuk direktori git bersarang yang disebutkan di bawah --force) akan dihapus.
b) flag -f
Jika variabel konfigurasi Git clean.requireForce tidak disetel ke false, git clean akan menolak untuk menghapus file atau direktori kecuali diberi -f atau -i. Git akan menolak untuk mengubah repositori git bersarang yang tidak terlacak (direktori dengan .git subdirectory) kecuali jika -f kedua diberikan.
3. git branch.
4. a) Iteratif merupakan perulangan yang melakukan proses perulangan terhadap sekelompok instruksi.
   b) Rekursif adalah suatu proses atau prosedur dari fungsi yang memanggil dirinya sendiri secara berulang-ulang. 
5. Git checkout.
6. Untuk menghapus file yang dimodifikasi atau dihapus dari direktori kerja, gunakan perintah del. Ketikkan -> nama file untuk menghapus file tertentu.
7. Cara menghapus cabang, gunakan perintah git branch dengan argumen -d.
8. Perintah git diff akan membandingkan perubahan yang baru saja dilakukan dengan revisi/commit terakhir.
9. Untuk menghapus file dari area pementasan gunakan git reset. Perintah git reset, akan mengembalikan file ke kondisi sebelumnya, kemudian menghapus catatan sejarah commit beikutnya. 
10. Menggunakan perintah git merge, Merge adalah suatu command yang berguna untuk penggabungan conflict dalam git dengan membuat branch yang bercabang menjadi satu kembali atau dengan kata lain mengintegrasikan kembali branch tersebut menjadi satu.