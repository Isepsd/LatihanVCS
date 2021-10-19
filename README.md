1. Buka website ini dan download installer GIT untuk Windows.
2. Setelah download, buka file tersebut untuk menjalankan proses instalasi. Ikuti semua instruksi, klik Next dan Finish hingga semua proses instalasi selesai.

Installing GIT on Windows
3. Jalankan perintah berikut ini di terminal:

git config --global user.name "John Smith"
git config --global user.email "example@email.com"
Catatan: Jangan lupa mengganti John Smith dan example@email.com dengan detail login Anda sendiri.

Setelah itu, GIT di Windows Anda siap digunakan.

Opsi 2 – Menginstall GIT di MacOS
Ada banyak cara meng-install GIT di perangkat Mac. Bisa jadi GIT sudah terinstall di komputer Anda jika Anda telah memiliki aplikasi XCode sebelumnya. Jalankan perintah berikut ini di terminal untuk memastikan:

git --version
Jika Anda mendapatkan output seperti git version 2.7.0 (Apple Git-66), Anda beruntung. Namun jika tidak, ikuti langkah berikut ini:

1. Buka website ini dan download installer terbaru untuk Mac.
2. Ikuti instruksi di layar dan selesaikan proses instalasi.

Install GIT MacOS
3. Sekali lagi, ketikkan perintah git --version
untuk memastikan bahwa instalasi telah berhasil.
4. Jalankan perintah berikut ini di terminal Anda untuk mengkonfigurasi email Anda dan username yang digunakan untuk akun GIT:

git config --global user.name "John Smith"
git config --global user.email "example@email.com"
Catatan: Jangan lupa mengganti John Smith dan example@email.com dengan detail login Anda sendiri.

Opsi 3 – Install GIT di Linux
Jika Anda adalah pengguna Linux, mungkin Anda telah terbiasa meng-install software dan paket di komputer Anda menggunakan perintah apt-get atau yum install. Begitu juga dengan instalasi GIT:

Untuk pengguna Debian/Ubuntu (apt-get):
1. Buka terminal dan jalankan perintah berikut ini:

Sudo apt-get update
Sudo apt-get install git
2. Cek apakah instalasi sudah berhasil dengan menggunakan git --version

3. Jalankan perintah berikut di terminal untuk mengkonfigurasikan email Anda dan username yang digunakan dengan akun GIT Anda:

git config --global user.name "John Smith"
git config --global user.email "example@email.com"
