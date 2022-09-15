# **HTML & CSS - Final Project**

## Objectives
* Membuat portofolio dalam bentuk HTML dan CSS
* Mampu membuat _website_ statis dengan HTML dan CSS
* Mampu menggunakan Tailwind CSS sebagai alat bantu desain
* Mampu melakukan _deployment_ ke PaaS seperti Netlify

## Restrictions
* Tidak boleh mengerjakan pada repositori ini.

## Acceptance criteria
* Wajib menggunakan Git sebagai repositori kerja
* Wajib menggunakan Tailwind CSS
* Wajib melakukan _deployment_ ke Netlify
* Wajib memiliki 3 section
  * Section personal info, berisi nama dan deskripsi singkat.
  * Section pendidikan, berisi latar belakang pendidikan, minimal 2 latar pendidikan.
  * Section portofolio, berisi gambar, judul dan deskripsi portofolio.
* Responsive, ketika layar dikecilkan atau dibesarkan, layout akan mengikuti dan tidak berantakan, seperti contoh gambar di akhir README, ketika layar dikecilkan dari 3 kolom berubah menjadi 1 kolom.

## Prerequisite
Buatlah sebuah *private repository* baru untuk menyimpan _file_ pengerjaannya dengan format penamaan **student_name-final_project** (contoh: dito_bagus-final_project).

## Directions:
Buatlah sebuah _private repository_ di Github dan gunakan sebagai repositori kerja. Bagilah proyek menjadi beberapa _task_ dan _commit_ secara berkala sesuai dengan _task_-nya dan berikan _commit message_ yang sesuai.

Buatlah sebuah _website_ yang memiliki konten mirip dengan CV yang terdiri dari 3 bagian:
  - Nama, dan deskripsi singkat. Jadikan nama sebagai **h1** dan deskripsi sebagai **p**
  - Latar belakang pendidikan (minimal 2 latar belakang pendidikan, maksimal 4 latar belakang pendidikan), disertai dengan tahun mulai dan tahun selesai (atau tulis "Sekarang" jika pendidikannya masih berjalan). Tambahkan teks Latar Belakang Pendidikan sebagai **h1** , dan jadikan masing-masing latar belakang pendidikan sebagai **h2** , dengan tahun dari masing-masing latar belakang pendidikan sebagai **p** .
  - 12 portofolio _dummy_, beserta gambar _dummy_ untuk masing-masing portofolio. Tambahkan teks Portofolio sebagai **h1** , judul dari masing-masing judul portofolio sebagai **h2** , dan deskripsi dari portofolionya sebagai **p** .

Tambahkan _styling_ agar _website_ lebih menarik dengan menggunakan CSS:
  - Flex bisa digunakan untuk 
    - Membagi latar belakang edukasi ke beberapa kolom, mirip dengan yang umum kita jumpai di surat kabar.
    - Membagi portofolio menjadi beberapa kolom agar terlihat rapih.
  Terapkan konsep responsive
    - Untuk layar kecil (small dan medium), sebaiknya "latar belakang edukasi" berada di satu kolom saja
    - Demikian juga seluruh portofolio sebaiknya menggunakan satu kolom saja, khusus layar kecil
  - Tambahkan konsep _design website_ untuk membuat halamannya lebih menarik:
    - Contoh bisa menggunakan _shadow_, _background color_, bahkan _background-color_ ber-_gradient_ ( contoh: https://uigradients.com/#SublimeLight)

Gunakan Tailwind CSS untuk mempercantik website:
  - Ubahlah _font_ dari _heading_ agar lebih cantik. Gunakan _font_ untuk _heading_ lebih besar dari _font_ teks normal, dan besarnya disesuaikan dengan _level_ dari _heading_-nya (h2 lebih kecil dari h1, tapi lebih besar dari normal teks)
  - Seluruh _heading_ wajib memiliki ketebalan minimal _bold_

_Deploy/hosting_ _website_ ke Netlify:
  - Peserta wajib menggunakan Git untuk _deployment_ ke Netlify

## Referensi website:

![](assets/demo.gif)

## Tips

- Gunakan background-image untuk membuat gambar dengan bentuk yang lebih fleksibel: Buat _container_-nya terlebih dahulu sesuai dengan keperluan (berikan _rounded_, _shadow_, dan lain sebagainya), baru berikan `background-image`

## Output:
* Sebuah _website_ statis dalam bentuk HTML dan CSS
* _Website_ statis yang dibuat bisa dilihat dengan menggunakan _hosting/deployment_ di Netlify

## Output yang harus disubmit ke LMS:
* *Link* URL _deployment_ Netlify
* *Link* Repository private
