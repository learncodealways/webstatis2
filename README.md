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

2. Opacity.

  Kegunaan: Properti opacity digunakan untuk mengatur sejauh mana elemen HTML dapat terlihat oleh mata manusia, dengan nilai antara 0 (sepenuhnya transparan) hingga 1 (sepenuhnya terlihat).
Contoh: Jika Anda ingin membuat elemen dengan latar belakang berwarna menjadi setengah transparan, Anda dapat menggunakan opacity: 0.5;.

3. RGBA (Red, Green, Blue, Alpha) Color (Warna dengan Tingkat Transparansi):

Penggunaan: Properti rgba digunakan untuk mengatur warna elemen HTML dengan tambahan tingkat transparansi (alpha). Nilai merah (R), hijau (G), dan biru (B) adalah angka antara 0 hingga 255, dan nilai alpha adalah angka antara 0 hingga 1.
Contoh: background-color: rgba(255, 0, 0, 0.5); akan menghasilkan latar belakang merah setengah transparan.

noted : jika anda ingin mengatur tranparasi satu elemen saja, disarankan menggunakan rgba.

4. HSLA (Hue, Saturation, Lightness, Alpha) Color (Warna dengan Hue, Saturation, Lightness, dan Tingkat Transparansi):

Penggunaan: Properti hsla digunakan untuk mengatur warna elemen HTML dengan model warna HSL dan tambahan tingkat transparansi (alpha). Hue (H) adalah sudut dalam derajat, Saturation (S) dan Lightness (L) adalah persentase antara 0 hingga 100, dan alpha adalah angka antara 0 hingga 1.
Contoh: color: hsla(120, 100%, 50%, 0.7); akan memberikan warna teks hijau dengan tingkat transparansi 70%.

5. Box-Shadow (Bayangan Kotak):

Penggunaan: Properti box-shadow digunakan untuk menambahkan bayangan pada elemen HTML. Nilai-nilainya adalah offset-x, offset-y, blur-radius, spread-radius, warna bayangan.
Contoh: box-shadow: 2px 2px 5px 1px rgba(0, 0, 0, 0.5); akan menambahkan bayangan dengan 2 piksel ke arah kanan dan 2 piksel ke bawah, dengan radius blur 5 piksel, radius penyebaran 1 piksel, dan warna bayangan setengah transparan.

6. Text Shadow (Bayangan Teks):

Penggunaan: Properti text-shadow digunakan untuk menambahkan bayangan pada teks dalam elemen HTML. Nilai-nilainya adalah offset-x, offset-y, blur-radius, dan warna bayangan.
Contoh: text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.5); akan menambahkan bayangan teks dengan 1 piksel ke arah kanan dan 1 piksel ke bawah, radius blur 2 piksel, dan warna bayangan setengah transparan.


