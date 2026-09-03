# Website Profil XI RPL  
Website ini merupakan proyek pembelajaran kolaborasi Git dan GitHub.  
## Anggota Tim  
1. Muhammad Arman Ramdhan - Project Manager  
2. Ahmad Saepul Anwar - Developer Profil  
3. Choralyan - Developer Anggota  
4. Muhammad Faiz W - Developer Kontak  

## Nama Branch
1. fitur-profil  
2. fitur-anggota  
3. fitur-kontak  

## URL GitHub  
https://github.com/marmanforum/website-profil-xi-rpl-01.git  

## Pertanyaan-pertanyaan
Apa perbedaan pesan commit berikut? git commit -m "update" dan: git commit -m "Menambahkan halaman profil kelas" Mana yang lebih baik? informasi yang di berikan apa yang di commit tentu berbeda, di update memunculkan update, dan di menambahkan halaman profil kelas, ya menampilkan itu, apa yang di tampilkan sesuai dengan apa yang di commit.

1. Apa fungsi git pull?  
git pull berfungsi untuk mengambil perubahan terbaru dari repository remote (GitHub) ke repository lokal. Jadi, kode di komputer kita diperbarui sesuai dengan versi terbaru yang ada di GitHub.  
2. Apa yang terjadi jika programmer tidak melakukan git pull?  
Programmer bisa menggunakan kode yang sudah tidak terbaru. Akibatnya, perubahan dari anggota tim lain tidak terlihat di komputer kita dan bisa menyebabkan konflik saat melakukan push atau menggabungkan kode.  
3. Mengapa main harus dijaga agar tetap stabil?  
Karena main biasanya menjadi versi utama proyek yang siap digunakan. Jika setiap programmer langsung memasukkan kode yang belum diuji ke main, bisa menyebabkan error dan mengganggu pekerjaan seluruh tim. Karena itu, fitur biasanya dikerjakan di branch masing-masing, diuji terlebih dahulu, baru digabungkan ke main.  

## CODE REVIEW  
Nama Developer: Muhammad Arman Ramdhan  
APPROVE  
  
  Struktur HTML sudah benar, penamaan file sesuai, kode rapi dan mudah dibaca. Informasi yang ditampilkan lengkap serta sesuai dengan ketentuan tugas. Tidak ditemukan kesalahan yang perlu diperbaiki.

## Pertanyaan Conflict  
1. Mengapa conflict terjadi?  
Conflict terjadi ketika dua programmer mengubah bagian/baris kode yang sama dengan perubahan yang berbeda, sehingga Git tidak bisa menentukan perubahan mana yang harus digunakan.  
2. Apakah conflict berarti Git rusak?  
Tidak. Conflict adalah hal normal dalam pengembangan software. Git justru memberi tahu bahwa ada perubahan yang perlu ditentukan secara manual.  
3. Siapa yang harus menentukan versi kode yang benar?  
Programmer atau tim yang bertanggung jawab terhadap kode tersebut yang menentukan versi mana yang benar, berdasarkan kebutuhan proyek dan hasil diskusi dengan anggota tim.  
4. Mengapa komunikasi antar programmer penting?  
Karena komunikasi membantu programmer menghindari perubahan yang bertabrakan, memahami pekerjaan anggota lain, dan menentukan solusi yang tepat ketika terjadi conflict.  

## URL Repository  
https://github.com/marmanforum/website-profil-xi-rpl-01.git  

## Refleksi Individu  

1. Apa perbedaan bekerja sendiri dengan bekerja menggunakan Git dan GitHub?  
Bekerja sendiri lebih sederhana karena tidak perlu menggabungkan hasil pekerjaan dengan orang lain. Sedangkan menggunakan Git dan GitHub memudahkan kerja sama dalam tim, menyimpan riwayat perubahan, dan mengelola versi proyek dengan lebih rapi.  

2. Apa manfaat branch?   
Branch memungkinkan setiap anggota tim mengerjakan fitur atau perbaikan secara terpisah tanpa mengganggu kode utama. Setelah selesai dan dipastikan benar, perubahan dapat digabungkan ke branch utama.  

3. Mengapa Pull Request diperlukan?  
Pull Request digunakan agar perubahan dapat diperiksa terlebih dahulu sebelum digabungkan ke branch utama Dengan begitu, kesalahan dapat ditemukan lebih awal dan kualitas kode tetap terjaga.  

4. Apa manfaat Code Review?  
Code Review membantu menemukan kesalahan, meningkatkan kualitas kode, memastikan hasil sesuai dengan tugas, serta menjadi sarana belajar dari masukan anggota tim.

5. Error apa yang paling sulit kalian selesaikan?  
Error yang paling sulit saya selesaikan adalah saat terjadi konflik saat menggabungkan perubahan (merge conflict) dan beberapa bagian kode tidak sesuai setelah digabungkan.  

6. Bagaimana kalian menemukan solusinya?  
Saya membaca pesan error, memeriksa perubahan pada Git, berdiskusi dengan anggota tim, dan mencoba memperbaiki konflik hingga proyek dapat berjalan dengan baik.  

7. Apa kontribusi terbesar kalian dalam kelompok?  
Kontribusi terbesar saya adalah mengerjakan bagian HTML, membantu memperbaiki kesalahan yang ditemukan saat review, serta memastikan hasil akhir sesuai dengan ketentuan tugas.  

8. Jika menjadi programmer profesional, kebiasaan apa dari kegiatan ini yang akan kalian pertahankan?  
Saya akan mempertahankan kebiasaan menggunakan Git untuk mencatat setiap perubahan, membuat commit yang jelas, melakukan code review sebelum menggabungkan kode, dan bekerja sama dengan tim secara teratur.  