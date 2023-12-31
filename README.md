# webstatis2

Penerapan dan penjelasan properti css3 

1. Border-Radius.

Properti CSS3 border-radius digunakan untuk membuat sudut atau ujung dari elemen HTML menjadi bulat atau melengkung. Ini membuat elemen Anda terlihat lebih estetis dan lebih lembut daripada sudut-sudut yang tajam.

Anda dapat mengatur border-radius dengan beberapa cara:

1.Jika Anda ingin semua sudut elemen menjadi bulat, Anda cukup menentukan satu angka untuk meratakan semua sudut. Contoh: border-radius: 10px;

2.Jika Anda ingin mengatur sudut-sudut individu, Anda bisa menggunakan empat angka. Misalnya, border-radius: 10px 20px 30px 40px; akan membuat sudut-sudut elemen menjadi bulat secara berurutan dari sudut atas kiri, sudut atas kanan, sudut bawah kanan, dan sudut bawah kiri.

Anda juga dapat menggunakan dua angka, seperti border-radius: 10px 20px;, yang akan mengatur sudut horizontal (kiri dan kanan) dan sudut vertikal (atas dan bawah) secara terpisah.

3.Jika Anda ingin membuat sudut elemen menjadi sepenuhnya bulat, gunakan 50% seperti ini: border-radius: 50%;.

Jadi, border-radius adalah cara sederhana untuk membuat elemen Anda menjadi lebih berbentuk bulat atau melengkung di sudut-sudutnya dalam desain web Anda.

----------------------------------------------------------------------------------------------------------------

2. Opacity.


  Kegunaan: Properti opacity digunakan untuk mengatur sejauh mana elemen HTML dapat terlihat oleh mata manusia, dengan nilai antara 0 (sepenuhnya transparan) hingga 1 (sepenuhnya terlihat).
Contoh: Jika Anda ingin membuat elemen dengan latar belakang berwarna menjadi setengah transparan, Anda dapat menggunakan opacity: 0.5;.

-----------------------------------------------------------------------------------------------------

3. RGBA (Red, Green, Blue, Alpha) Color (Warna dengan Tingkat Transparansi):

Penggunaan: Properti rgba digunakan untuk mengatur warna elemen HTML dengan tambahan tingkat transparansi (alpha). Nilai merah (R), hijau (G), dan biru (B) adalah angka antara 0 hingga 255, dan nilai alpha adalah angka antara 0 hingga 1.
Contoh: background-color: rgba(255, 0, 0, 0.5); akan menghasilkan latar belakang merah setengah transparan.

noted : jika anda ingin mengatur tranparasi satu elemen saja, disarankan menggunakan rgba.

------------------------------------------------------------------------------------------------------

4. HSLA (Hue, Saturation, Lightness, Alpha) Color (Warna dengan Hue, Saturation, Lightness, dan Tingkat Transparansi):

Penggunaan: Properti hsla digunakan untuk mengatur warna elemen HTML dengan model warna HSL dan tambahan tingkat transparansi (alpha). Hue (H) adalah sudut dalam derajat, Saturation (S) dan Lightness (L) adalah persentase antara 0 hingga 100, dan alpha adalah angka antara 0 hingga 1.
Contoh: color: hsla(120, 100%, 50%, 0.7); akan memberikan warna teks hijau dengan tingkat transparansi 70%.

------------------------------------------------------------------------------------------------------------

5. Box-Shadow (Bayangan Kotak):

Penggunaan: Properti box-shadow digunakan untuk menambahkan bayangan pada elemen HTML. Nilai-nilainya adalah offset-x, offset-y, blur-radius, spread-radius, warna bayangan.
Contoh: box-shadow: 2px 2px 5px 1px rgba(0, 0, 0, 0.5); akan menambahkan bayangan dengan 2 piksel ke arah kanan dan 2 piksel ke bawah, dengan radius blur 5 piksel, radius penyebaran 1 piksel, dan warna bayangan setengah transparan.

----------------------------------------------------------------------------------------------------------------

6. Text Shadow (Bayangan Teks):

Penggunaan: Properti text-shadow digunakan untuk menambahkan bayangan pada teks dalam elemen HTML. Nilai-nilainya adalah offset-x, offset-y, blur-radius, dan warna bayangan.
Contoh: text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5); akan menambahkan bayangan teks dengan 1 piksel ke arah kanan dan 1 piksel ke bawah, radius blur 2 piksel, dan warna bayangan setengah transparan.

-----------------------------------------------------------------------------------------------------------------------

7. Linear-gradient

 CSS3 properti "linear gradient" digunakan untuk membuat latar belakang elemen HTML dengan gradien warna yang bergerak sepanjang garis lurus. Ini adalah cara yang bagus untuk memberi elemen tampilan visual yang menarik. Mari kita bahas dengan lebih detail:

Properti: background-image

Nilai: linear-gradient

background-image: linear-gradient(to right, red, yellow);

Penjelasan:

background-image: Ini adalah properti CSS yang digunakan untuk mengatur gambar latar belakang elemen HTML.

linear-gradient: Ini adalah nilai dari properti background-image yang digunakan untuk menciptakan gradien linear. Ini mengindikasikan bahwa Anda akan membuat latar belakang dengan gradien yang bergerak sepanjang garis lurus.

to right: Ini adalah arah gradien, yang menunjukkan bahwa gradiennya akan bergerak dari kiri ke kanan. Anda dapat mengganti ini dengan arah lain seperti to left, to top, atau to bottom sesuai kebutuhan.

red dan yellow: Ini adalah warna-warna yang akan digunakan dalam gradien. Di sini, gradiennya akan dimulai dengan warna merah (di sisi kiri) dan berubah menjadi warna kuning (di sisi kanan).

Jadi, dalam contoh di atas, elemen dengan properti ini akan memiliki latar belakang gradien linear yang berubah dari merah ke kuning dari kiri ke kanan. Anda dapat mengganti warna dan arah sesuai dengan preferensi desain Anda.

---------------------------------------------------------------------------------------------------------------

8. Radial-gradient

Properti CSS3 Radial Gradient digunakan untuk membuat latar belakang elemen HTML dengan gradasi berbentuk lingkaran atau elips. Ini memberikan efek visual yang menarik dan sering digunakan dalam desain web modern.

Anda dapat mendefinisikan gradasi radial dengan menggunakan properti background-image dan nilai radial-gradient(). Berikut contoh sintaksnya:
background-image: radial-gradient(shape size at position, color-stops);

Mari kita bahas nilai-nilai yang digunakan dalam properti ini:

shape: Ini mengacu pada bentuk gradasi radial. Biasanya, Anda dapat menggunakan nilai circle untuk gradasi lingkaran, atau ellipse untuk gradasi elips. Anda juga dapat mengatur bentuk kustom jika diperlukan.

size: Menentukan ukuran gradasi radial. Anda dapat menggunakan nilai-nilai seperti closest-side, closest-corner, farthest-side, atau farthest-corner. Ini mempengaruhi seberapa besar atau kecil gradasi tersebut.

at position: Menentukan posisi pusat gradasi radial. Ini dapat berupa nilai dalam satuan seperti piksel atau persentase, atau bahkan kata kunci seperti center untuk tengah elemen.

color-stops: Ini adalah daftar warna yang menggambarkan cara warna akan beralih dalam gradasi. Anda dapat menentukan dua atau lebih warna dengan nilai-nilai persentase yang memisahkan mereka. Misalnya, red 0%, blue 50%, green 100% akan memberikan gradasi dari merah ke biru hingga hijau.

Contoh penggunaan properti CSS3 radial gradient:
background-image: radial-gradient(circle at 50% 50%, #FF0000, #0000FF);
Dalam contoh ini, kita membuat gradasi lingkaran dengan pusat di tengah elemen dan beralih dari merah ke biru.

------------------------------------------------------------------------------------------------------------------

9.  @font-face

berikut penjelasan yang jelas dan mudah dimengerti mengenai properti CSS3 @font-face dan nilai-nilainya:

@font-face adalah aturan CSS yang digunakan untuk memuat jenis huruf (font) khusus pada halaman web. Ini memungkinkan Anda menggunakan jenis huruf yang tidak umum atau tidak tersedia secara default di perangkat pengguna.

Nilai-nilai utama yang digunakan dalam properti @font-face adalah:

font-family: Ini adalah nama yang Anda berikan pada font yang akan Anda gunakan. Ini adalah nilai yang Anda akan gunakan saat mengatur font-family di elemen-elemen HTML. Misalnya, font-family: 'NamaFont';.

src: Ini menentukan sumber atau lokasi dari file font yang akan digunakan. Anda dapat menggunakan URL untuk merujuk ke file font, baik itu di server Anda sendiri atau di luar sumber daya seperti Google Fonts. Contoh: src: url('path/ke/font.woff2') format('woff2');.

font-weight: Ini mengatur ketebalan font. Nilainya bisa berupa angka (100 hingga 900) atau kata-kata kunci seperti normal atau bold.

font-style: Ini mengatur gaya font seperti miring (italic) atau normal. Nilainya bisa berupa kata kunci seperti normal, italic, atau oblique.

font-display: Ini mengontrol perilaku tampilan font jika font tidak dapat diunduh dengan cepat. Nilainya bisa berupa auto (perilaku default), swap (font akan diganti dengan font alternatif jika tidak dapat diunduh), fallback (menampilkan font alternatif jika font utama tidak ada), atau optional (font adalah opsional dan tidak mempengaruhi tampilan sampai diminta).

Contoh penggunaan @font-face dalam CSS:

@font-face {
  font-family: 'NamaFont';
  src: url('path/ke/font.woff2') format('woff2');
  font-weight: normal;
  font-style: italic;
  font-display: swap;
}
Dalam contoh di atas, kita mendefinisikan @font-face dengan nama font 'NamaFont', mengarahkan ke file font dengan format WOFF2, dan mengatur berat dan gaya font. Selain itu, kami menggunakan font-display: swap sehingga jika font tidak dapat diunduh dengan cepat, itu akan digantikan dengan font alternatif sampai font utama diunduh.

Setelah mendefinisikan @font-face, Anda dapat menggunakannya dengan font-family pada elemen-elemen HTML seperti ini:

body {
  font-family: 'NamaFont', sans-serif;
}
Ini akan mengatur font 'NamaFont' untuk digunakan pada seluruh teks dalam elemen <body>, dan jika font tidak tersedia, akan menggunakan jenis huruf sans-serif sebagai alternatif.


------------------------------------------------------------------------------------------------------------------------


10. Filter 

CSS3 filter adalah properti yang digunakan untuk menerapkan efek visual pada elemen, seperti blur, brightness, contrast, dan lainnya. Efek filter ini biasanya digunakan untuk menyesuaikan tampilan gambar, latar belakang, dan border.

Value dari properti CSS3 filter adalah fungsi filter yang dapat digunakan untuk menghasilkan efek visual tertentu. Berikut adalah beberapa fungsi filter yang tersedia:

blur() : Mengaplikasikan efek blur pada elemen. Nilainya adalah angka yang menunjukkan ukuran blur, dalam piksel.
brightness() : Mengatur kecerahan elemen. Nilainya adalah angka dari 0 hingga 100, di mana 0 adalah hitam dan 100 adalah putih.
contrast() : Mengatur kontras elemen. Nilainya adalah angka dari 0 hingga 100, di mana 0 adalah kontras rendah dan 100 adalah kontras tinggi.
drop-shadow() : Menambahkan bayangan pada elemen. Nilainya adalah objek yang menentukan posisi, ukuran, warna, dan transparasi bayangan.
grayscale() : Mengubah elemen menjadi hitam putih. Nilainya adalah angka dari 0 hingga 100, di mana 0 adalah hitam putih sepenuhnya dan 100 adalah warna asli.
hue-rotate() : Mengubah hue elemen. Nilainya adalah angka dalam derajat.
invert() : Mengembalikan warna elemen.
opacity() : Mengatur transparansi elemen. Nilainya adalah angka dari 0 hingga 1, di mana 0 adalah transparan sepenuhnya dan 1 adalah tidak transparan.
saturate() : Mengatur saturasi elemen. Nilainya adalah angka dari 0 hingga 100, di mana 0 adalah tidak berwarna dan 100 adalah warna asli.
sepia() : Mengubah elemen menjadi warna sepia.
Fungsi filter dapat digabungkan untuk menghasilkan efek visual yang lebih kompleks. Misalnya, kita dapat menggunakan fungsi blur() dan contrast() secara bersamaan untuk membuat gambar menjadi blur dan kontras.

Berikut adalah contoh penerapan properti CSS3 filter:

HTML
<img src="image.jpg" style="filter: blur(5px) contrast(1.5)">
Use code with caution. Learn more
Kode di atas akan menerapkan efek blur sebesar 5 piksel dan meningkatkan kontras gambar sebesar 50%.

CSS3 filter adalah fitur yang powerful yang dapat digunakan untuk membuat tampilan web menjadi lebih menarik dan interaktif.

------------------------------------------------------------------------------------------------------------------

11. Transform 

Properti transform CSS3 memiliki beberapa properti yang dapat digunakan untuk mengubah posisi, ukuran, dan orientasi elemen. Properti-properti tersebut adalah:

translate(): Menggeser elemen ke arah tertentu. Value-nya adalah jumlah pergeseran dalam satuan piksel atau persentase.
rotate(): Memutar elemen dengan sudut tertentu. Value-nya adalah sudut rotasi dalam derajat atau radian.
scale(): Menskala elemen dengan faktor tertentu. Value-nya adalah faktor skala untuk lebar dan tinggi elemen.
skew(): Memiringkan elemen dengan sudut tertentu. Value-nya adalah sudut kemiringan untuk sumbu X dan sumbu Y.
matrix(): Mengubah posisi, ukuran, dan orientasi elemen dengan menggunakan matriks 4x4.
matrix3d(): Mengubah posisi, ukuran, dan orientasi elemen dengan menggunakan matriks 4x4 dalam ruang 3D.
perspective(): Menentukan perspektif untuk elemen 3D.
Berikut adalah penjelasan singkat dari masing-masing properti tersebut:

translate()
Properti translate() digunakan untuk menggeser elemen ke arah tertentu. Value-nya adalah jumlah pergeseran dalam satuan piksel atau persentase.

Contoh:

CSS
div {
  transform: translate(100px, 50px);
}
Use code with caution. Learn more
Kode CSS di atas akan menggeser elemen 100px ke kanan dan 50px ke bawah.

rotate()
Properti rotate() digunakan untuk memutar elemen dengan sudut tertentu. Value-nya adalah sudut rotasi dalam derajat atau radian.

Contoh:

CSS
div {
  transform: rotate(90deg);
}
Use code with caution. Learn more
Kode CSS di atas akan memutar elemen 90 derajat searah jarum jam.

scale()
Properti scale() digunakan untuk menskala elemen dengan faktor tertentu. Value-nya adalah faktor skala untuk lebar dan tinggi elemen.

Contoh:

CSS
div {
  transform: scale(2);
}
Use code with caution. Learn more
Kode CSS di atas akan menskala elemen dua kali ukuran aslinya.

skew()
Properti skew() digunakan untuk memiringkan elemen dengan sudut tertentu. Value-nya adalah sudut kemiringan untuk sumbu X dan sumbu Y.

Contoh:

CSS
div {
  transform: skew(30deg, 0deg);
}
Use code with caution. Learn more
Kode CSS di atas akan memiringkan elemen 30 derajat ke kiri.

matrix()
Properti matrix() digunakan untuk mengubah posisi, ukuran, dan orientasi elemen dengan menggunakan matriks 4x4.

Contoh:

CSS
div {
  transform: matrix(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0);
}
Use code with caution. Learn more
Kode CSS di atas akan menggeser elemen ke tengah layar.

matrix3d()
Properti matrix3d() digunakan untuk mengubah posisi, ukuran, dan orientasi elemen dengan menggunakan matriks 4x4 dalam ruang 3D.

Contoh:

CSS
div {
  transform: matrix3d(1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1, 0, 0, 0, 0, 1);
}
Use code with caution. Learn more
Kode CSS di atas akan menggeser elemen ke tengah layar dalam ruang 3D.

perspective()
Properti perspective() digunakan untuk menentukan perspektif untuk elemen 3D.

Contoh:

CSS
div {
  transform: perspective(1000px);
}
Use code with caution. Learn more
Kode CSS di atas akan membuat elemen 3D tampak lebih jauh.

Dengan memahami properti-properti transform CSS3, Anda dapat membuat berbagai macam efek transformasi untuk halaman web Anda.

-----------------------------------------------------------------------------------------------------------------

12. Transition

CSS3 Transition adalah properti CSS yang digunakan untuk mengatur perubahan transisi antara dua keadaan atau nilai yang berbeda pada elemen HTML. Dengan menggunakan properti ini, Anda dapat menciptakan efek perubahan yang halus, seperti perpindahan warna, ukuran, atau posisi elemen saat mouse mengarahkan ke atas elemen atau saat elemen mengalami perubahan dalam keadaan lainnya. Berikut penjelasan lengkap tentang properti CSS3 Transition beserta beberapa nilai (value) yang umum digunakan:

transition-property:

Ini adalah properti yang menentukan jenis properti CSS mana yang akan mengalami transisi. Anda dapat mengatur properti ini untuk "all" (semua properti), atau spesifik seperti "width", "color", "transform", dsb.
transition-duration:

Menentukan berapa lama transisi akan berlangsung. Anda bisa menggunakan unit waktu seperti "s" (detik), "ms" (milidetik), atau nilai seperti "0.5s" atau "1000ms".
transition-timing-function:

Ini mengontrol bagaimana perubahan dalam properti berlangsung selama periode transisi. Beberapa nilai yang umum digunakan adalah:
linear: Transisi berlangsung dengan kecepatan konstan.
ease: Transisi dimulai perlahan, mendekati kecepatan tengah, dan berakhir perlahan.
ease-in: Transisi dimulai perlahan.
ease-out: Transisi berakhir perlahan.
ease-in-out: Transisi dimulai perlahan, mencapai kecepatan tengah, dan berakhir perlahan.
cubic-bezier(x1, y1, x2, y2): Anda dapat menentukan kurva perubahan kustom dengan menggunakan fungsi bezier. Nilai x1, y1, x2, dan y2 mengontrol bentuk kurva.
transition-delay:

Menentukan berapa lama sebelum transisi dimulai setelah perubahan nilai properti. Ini berguna untuk mengatur penundaan sebelum efek transisi dimulai.
Contoh penggunaan properti CSS3 Transition:

/* Contoh 1: Transisi warna dan lebar selama 1 detik dengan penundaan 0.2 detik */
.element {
  transition-property: color, width;
  transition-duration: 1s;
  transition-delay: 0.2s;
}

/* Contoh 2: Transisi transformasi dengan fungsi ease-in-out */
.element:hover {
  transform: scale(1.2);
  transition-property: transform;
  transition-duration: 0.5s;
  transition-timing-function: ease-in-out;
}
Dalam contoh-contoh di atas, elemen dengan class "element" akan mengalami transisi ketika ada perubahan nilai properti yang sesuai. Anda dapat mengkombinasikan berbagai nilai properti transition untuk menciptakan efek transisi yang beragam pada elemen HTML Anda. Transisi adalah alat yang sangat berguna dalam menciptakan pengalaman interaktif yang lebih menarik dan halus di halaman web Anda.

Berikut adalah beberapa tips untuk menggunakan properti CSS3 transition:

Gunakan nilai duration yang cukup lama untuk membuat animasi terlihat halus.
Gunakan fungsi waktu yang sesuai untuk menciptakan efek yang diinginkan.
Gunakan nilai delay untuk membuat animasi lebih menarik.

----------------------------------------------------------------------------------------------------------



13. <h3>Animation</h3>


CSS3 Animation adalah salah satu fitur dalam Cascading Style Sheets (CSS) yang memungkinkan Anda untuk membuat efek animasi pada elemen-elemen HTML tanpa menggunakan JavaScript atau teknologi animasi lainnya. Animasi ini dapat digunakan untuk menambahkan pergerakan, perubahan warna, dan transisi visual lainnya pada elemen-elemen halaman web Anda. Properti CSS3 Animation adalah kunci dalam mengendalikan animasi, dan ada beberapa nilai yang dapat digunakan dalam properti ini. Berikut adalah penjelasan singkat tentang properti CSS3 Animation beserta valuenya:

1. `animation-name`: Menentukan nama dari animasi yang akan digunakan. Anda perlu mendefinisikan animasi dengan nama ini terlebih dahulu menggunakan aturan `@keyframes`.

2. `animation-duration`: Menentukan berapa lama animasi akan berlangsung dalam satuan detik (s atau ms).

3. `animation-timing-function`: Menentukan bagaimana perubahan properti animasi akan terjadi selama animasi. Beberapa nilai yang umum digunakan adalah `ease` (perubahan lambat di awal dan akhir animasi), `linear` (perubahan konstan sepanjang animasi), `ease-in` (perubahan lambat di awal), `ease-out` (perubahan lambat di akhir), dan lainnya.

4. `animation-delay`: Menentukan waktu tunda sebelum animasi dimulai dalam satuan detik (s atau ms).

5. `animation-iteration-count`: Menentukan berapa kali animasi akan diulang. Nilai yang umum adalah `infinite` untuk animasi berulang tanpa henti atau angka untuk jumlah iterasi tertentu.

6. `animation-direction`: Menentukan arah perubahan properti animasi. Beberapa nilai umum adalah `normal` (dari awal ke akhir), `reverse` (dari akhir ke awal), `alternate` (bolak-balik antara awal dan akhir), dan `alternate-reverse` (bolak-balik dari akhir ke awal).

7. `animation-fill-mode`: Menentukan bagaimana elemen akan tampil sebelum dan setelah animasi. Nilai yang umum adalah `none` (tanpa perubahan sebelum atau setelah animasi), `forwards` (elemen akan tetap dalam keadaan akhir animasi setelah animasi selesai), `backwards` (elemen akan berada dalam keadaan awal animasi sebelum animasi dimulai), dan `both` (kombinasi dari `forwards` dan `backwards`).

8. `animation-play-state`: Menentukan apakah animasi sedang berjalan (`running`) atau dijeda (`paused`).

Contoh penggunaan properti CSS3 Animation:

```css
.element {
  animation-name: myanimation;
  animation-duration: 2s;
  animation-timing-function: ease-in-out;
  animation-delay: 0.5s;
  animation-iteration-count: infinite;
  animation-direction: alternate;
  animation-fill-mode: forwards;
  animation-play-state: running;
}
```

Dalam contoh di atas, animasi dengan nama "myanimation" akan berjalan selama 2 detik, menggunakan efek perubahan `ease-in-out`, dimulai setelah 0.5 detik tunda, berulang tanpa henti dengan arah bolak-balik, dan elemen akan tetap dalam keadaan akhir animasi setelah selesai berkat `animation-fill-mode` yang diatur ke `forwards`.


--------------------------------------------------------------------------------------------------------











