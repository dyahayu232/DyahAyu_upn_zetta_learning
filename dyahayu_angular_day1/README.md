<h2>dyahayu_upn_zetta_learning</h2>
<h2>Task Angular Day 1</h2>
Angular adalah platform pengembangan, dibangun di atas TypeScript. Sebagai platform, Angular        mencakup:

<ul>
<li>Kerangka kerja berbasis komponen untuk membangun aplikasi web yang skalabel</li>
<li>Kumpulan perpustakaan yang terintegrasi dengan baik yang mencakup berbagai fitur, termasuk perutean, manajemen formulir, komunikasi klien-server, dan banyak lagi</li>
<li>Serangkaian alat pengembang untuk membantu Anda mengembangkan, membangun, menguji, dan memperbarui kode Anda</li>
</ul>

Dengan Angular, Anda memanfaatkan platform yang dapat menskalakan dari proyek pengembang tunggal hingga aplikasi tingkat perusahaan. Angular dirancang untuk membuat pembaruan semudah mungkin, jadi manfaatkan perkembangan terbaru dengan sedikit usaha. Yang terbaik dari semuanya, ekosistem Angular terdiri dari kelompok beragam lebih dari 1,7 juta pengembang, penulis perpustakaan, dan pembuat konten.

di Angular, modul adalah mekanisme untuk mengelompokkan components, directives, pipes, dan services yang terkait, sedemikian rupa sehingga dapat digabungkan dengan modul lain untuk membuat aplikasi. Aplikasi Angular dapat dianggap sebagai teka-teki di mana setiap bagian (atau setiap modul) diperlukan untuk dapat melihat gambaran lengkapnya.

Komponen adalah blok bangunan yang menyusun aplikasi. Komponen menyertakan kelas TypeScript dengan dekorator @Component(), template HTML, dan styles. Dekorator @Component() menentukan informasi khusus Angular berikut:

<ul>
<li>Sebuah pemilih CSS yang mendefinisikan bagaimana komponen digunakan dalam template. Elemen HTML di template Anda yang cocok dengan pemilih ini menjadi instance dari komponen tersebut.</li>
<li>Template HTML yang menginstruksikan Angular cara merender komponen</li>
<li>Satu set opsional gaya CSS yang menentukan tampilan elemen HTML template</li>
</ul>

Hubungan component dan module adalah, module berisikan component yang saling berhubungan satu sama lain dan component juga membutuhkan module untuk mingidentifikasi components lainnya

<h3>Quiz</h3>
<ol type = "1">
<li>Components yang merupakan isi dari module tersebut akan dibagi menjadi beberapa jenis file yaitu HTML untuk hasil tampilannya,Typescript untuk isi dari HTML tersebut dan juga SCSS untuk styling</li>
<li>Component akan dikelompokon berdasarkan modulenya seperti module subscriptions,module beranda yang akan menampilkan component component yang merupakan isi dari module tersebut</li>
<li>Struktur file proyek tersebyut bisa diperkirakan karena hasil akhir dari project angular merupakan satu file HTML saja</li>
</ol>