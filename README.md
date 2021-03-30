# Jawab Pertanyaan Berikut
# (1) Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah yang berubah
# jawaban : perubahan kode ada pada langkah-langkah dibawah ini.

# (2) Apa perbedaan dari tag < p > dengan tag < br >, berikan penjelasannya!
  # Tag < p > Tag ini berfungsi untuk memberi perintah paragraf baru pada halaman html, antara baris atau paragraf terbentuk jarak. Tag ini merupakan tag yang berpasangan, dimulai dengan tag pembuka < p > dan diakhiri dengan tag penutup< /p > . 
  # Tag < br > bisa dibilang sebagai tag sendiri, kenapa saya katakan sendiri , karena tag ini adalah tag tunggal tanpa diawali tag pembuka dan diakhiri tag penutup. Ia berdiri sendiri. Tag < br >  dituliskan pada kerangka html untuk memberikan perintah "break line", artinya meng intruksikan baris baru.
# Jadi perbedaan yang mencolok dari kedua tag ini adalah pada jarak yang terbentuk. Kesimpulannya jika hanya ingin membuat baris baru tanpa jarak gunakan tag < br > , tapi jika sobat ingin membuat baris baru namun memiliki jarak dengan paragraf diatasnya maka bungkuslah paragraf baru tersebut dengan sepasang tag < p >  dan < /p >


# Langkah - langkah :
 # Persiapan Membuka VScode dan Browser

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(65).png)

# File Baru

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(63).png)

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(66).png)

# Kemudian buat file baru dengan nama lab1_tag_dasar.html dan tambahkan tag dasar dokumen HTML.

# Kemudian selanjutnya, buka file tersebut pada web browser misalnya Mozilla Firefox atau Google Chrome.

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(68).png)

# 1.) Membuat Paragraf Pertama dan Paragraf Kedua
  # Membuat Judul : < h1 >Belajar Dasar HTML< /h1 >

# < p > < /p >

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(64).png)

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(70).png)

# 2.) Membuat Paragraf Baru <br> </br>

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(69).png)

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(70).png)

# < pre > < /pre >

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(70).png)

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(72).png)

# 3.) Memformat Text

  # < mark > < /mark > Yamg Warnah Kuning
  ![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(75).png)
  
  # < u > < /u > Yang Bergaris Bawah
  ![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(77).png)
  
 # 4.) Menyisipkan Gambar
  
   # < !-- menambahkan gambar pada dokumen -- >
# < h1 >Me nambahkan Gambar< /h1 >
# < h3 >Logo Universitas Pelita Bangsa< /h3 >
# Dengan Cara :

   # <img src=" Capture.jpg " width="200" title=" Logo Univeritas Pelita Bangsa">

# Gambar Pada Bagian Bawah

![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(78).png)

# 5.) Menambahkan Hyperlink

   # < !-- menambahkan link navigasi -- >
   # < nav >
   # < a href="lab1_tag_dasar.html">Dasar HTML< /a >
   # < a href="lab1_halaman2.html">Halaman 2< /a >
   # < a href="http://www.google.com">Halaman Web Eksternal Google< /a >
   # < /nav >
    
   ![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(78).png)
     
# (3) Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
# Jwb :
  # Mereka digunakan untuk berbagai hal. The altatribut digunakan bukan gambar. Jika gambar tidak dapat ditampilkan, dan di pembaca layar.
  # The titleatribut ditampilkan bersama dengan gambar, biasanya sebagai tooltip melayang-layang.
  # Yang satu tidak boleh digunakan "sebagai pengganti" dari yang lain. Masing-masing harus digunakan dengan benar , untuk melakukan hal-hal yang dirancang untuk mereka lakukan.

# (4) Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
# proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
# Jwb :
  # Atribut Width pada tabel digunakan untuk menentukan lebar tabel : <table width="pixel atau %">
  # Atribut Height pada tabel digunakan untyk menetuka tinggi tabel : <table height="pixel atau %">
  
  # Menurut saya di isi semua, karena Atribut keduaanya berfungsi untuk menjelaskan bagaimana data isian form akan dikirim oleh web browser. Penerapan kedua atribut tersebut tidak hanya terbatas di table HTML saja, tetapi juga digunakan untuk mengatur ukuran konten.

# (5) Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top, _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
# Jwb :
  # Ini karena targetatribut dapat digunakan untuk lebih dari sekadar membuka jendela baru. Ini memiliki empat nilai bawaan tetapi juga memungkinkan Anda menentukan target Anda   # sendiri. Jika Anda melihat halaman Sekolah W3 yang relevan itu menunjukkan opsi berikut:

# _blank Buka dokumen yang ditautkan di jendela atau tab baru
# _self Buka dokumen yang ditautkan dalam bingkai yang sama seperti yang diklik (ini adalah default)
# _parent Buka dokumen yang ditautkan dalam bingkai induk
# _top Buka dokumen yang ditautkan di seluruh jendela
# < framename> Buka dokumen yang ditautkan dalam bingkai bernama
# Banyak dari ini tidak masuk akal kecuali Anda mengerti sedikit tentang bingkai HTML. Menggunakan <frameset>tag HTML memungkinkan Anda untuk membagi jendela browser menjadi 
  # Beberapa bagian (bingkai) masing-masing dengan halaman mereka sendiri. Dengan memberi bingkai nama dan menggunakan targetatribut di tautan Anda, Anda dapat mengontrol frame  mana yang harus menampilkan konten yang relevan.
     
   # Tampilan pada tampilan Handphone :
   
   ![imag](https://github.com/fdlhrauf/Lab1Web/blob/main/images/Screenshot%20(80).png)
