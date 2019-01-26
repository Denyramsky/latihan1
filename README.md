    Assalamualaikum wr wb

### **Membuat akun pada layanan github**
untuk menggunakan git, dibutuhkan sebuah layanan. Layanan yang tersedia sangat banyak namun saya menggunakan **github**, tidak masalah kalau nanti misalnya mau pindah ke layanan lain seperti **gitlab** seperti yang saya lakukan sekarang, karena saya tetap menggunakan keduanya.

Buka website [Github](https://github.com), buat akun baru terlebih dahulu**(maaf saya tidak perlu menjelaskan bagaimana membuat akun baru, karena saya yakin semua pasti pernah membuat akun di jejaring social, jadi saya rasa sudah sanggup untuk membuat akun github)**

![image](https://user-images.githubusercontent.com/47053617/51785322-ab9d6a80-2188-11e9-97b9-e96498532d9b.png)

Setelah terbuat akun-nya, login dengan akun baru(kalau langsung diarahkan ke halaman utama), setelah itu pada **pojok kanan atas terdapat tombol “+”**, klik button tersebut dan pilih **“new repository”**.

### **Membuat Repositori online**

![image](https://user-images.githubusercontent.com/47053617/51785350-1fd80e00-2189-11e9-9fe8-5855cdc46e14.png)

Lalu kalian akan diarahkan ke halaman pembuatan repository, pembuatan repositori ini tergantung dari project kalian yang mau kalian upload, jadi saya harapkan kalian sudah punya proyek yang ingin di upload ke repositori.

![image](https://user-images.githubusercontent.com/47053617/51785356-34b4a180-2189-11e9-8643-b153cee81331.png)

Untuk mengisi, ada beberapa hal yang perlu di perhatikan :

- Repository name : nama repository(isi saja dengan nama proyek), akan lebih rapi kalau misalnya nama repository juga di beri jenis pemogramannya juga contohnya “Android/test” atau “js/test”.

- Description : deskripsi repository (bisa kisah project dan siapa yang terlibat)

- Public/Private : kondisi repository mau di public (di buat umum) atau private(di buat pribadi atau tertutup)

- Intiallize the repository with README : ini adalah isi dokumentasi pada project yang dikerjakan, saya sarankan tidak usah di centang karena mempermudah praktek untuk mengelola git.

![image](https://user-images.githubusercontent.com/47053617/51785379-9248ee00-2189-11e9-9b35-eab02a2c27b1.png)

Setelah di isi sesuai dengan keinginan, klik saja tombol **“create repository”**, maka pada halaman selanjutnya akan menampilkan repositori yang sudah dibuat, dan tahap selanjutnya adalah upload project ke repository online.

![image](https://user-images.githubusercontent.com/47053617/51785401-c8866d80-2189-11e9-8595-5341dac9ea88.png)

Untuk membuat file ```README.md``` lakukan codding deperti _gambar berikut_ pada ```Gitbash``` yang sudah anda download dan instal.

![screenshot 1](https://user-images.githubusercontent.com/47053617/51785413-fff51a00-2189-11e9-8b80-4b9f1130f7e9.png)

![screenshot 3](https://user-images.githubusercontent.com/47053617/51785414-07b4be80-218a-11e9-92fa-81faec202acc.png)

### **Keterangan perintah diatas seperti ini :**

**git init**
untuk meng-set folder yang digunakan tersebut sebagai repo local git. bisa di bilang ini instalasi git pertama kali

**git add “.” atau nama file**
untuk menambah file project yang mau di upload sebelum di commit, tanda titik setelah kata “add” pada perintah tersebut adalah keseluruhan file dan folder project tersebut, saat awal upload kalian bisa menggunakan perintah tersebut. **Namun saat commit atau upload ke repository selanjutnya bisa menggunakan perintah add dengan “nama file” untuk memberikan status commit.**

**git commit -m “isi commit”**
untuk menambah keterangan/status perubahaan saat upload ke repo online, untuk memasukkan keterangan tersebut setelah “git commit -m” ditambah tanda petik lalu komentar(lihat di list perintah untuk contoh).

**git remote add origin “link repo online”**
untuk meng-setting remote origin dari repo online, repo online bisa dilihat pada link yang tersedia di bagian atas Project dengan format “.git”, diperlukan ini untuk mengakses ke repo tersebut sehingga kita bisa melakukan apapun di repo online tersebut.

**git push origin “nama branch”**
Perintah untuk mengupload file yang ada pada repo lokal ke repo online yang diletakkan pada branch yang sudah tersedia di repo online.

Setelah melakukan semua perintah silahkan cek di github, apakah file yg di upload sudah masuk atau tidak? jika iya maka anda berhasil mengelola git untuk tahap awal, jika ada kesalahan bisa menghubungi saya melalui Facebook atau kontak saya.

Tahap awal itu dulu, nanti tahap selanjutnya adalah mengelola branch untuk perkembangan proyek.

Sekian **Tutorial** dari saya, apa bila ada kekurangan mohon dimaafkan

    Wassalamualaikum wr wb
