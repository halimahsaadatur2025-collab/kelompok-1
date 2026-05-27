---
Judul: Koordinat Titik, Jarak, Vektor, dan Garis.
Kelompok: 1
Nama Anggota : ["Salma Fitri Bakhitoh
25030630032", "Halimah Sa'adatur Rahmah 25030630034", "Zuhrotul Jannatil Karimah 
25030630057", "Fawwaz Dhiya'ulhaq 25030630077"]
---
https://markdownviewer.pages.dev/

# Koordinat Titik, Jarak, Vektor, dan Garis. 
## 1. SISTEM KOORDINAT
a. Sistem Koordinat Kartesius 2D
b. Sistem Koordinat Kartesius 3D
c. Jarak Dua Titik (2D & 3D)
d. Titik Tengah (2D & 3D)
e. Perbandingan Ruas Giri (Titik Membagi Ruas)

## 2. JARAK
a. Jarak Dua Titik (2D & 3D)
b. Jarak Titik ke Garis (2D & 3D)
c. Jarak Titik ke Bidang (3D)
d. Jarak Dua Garis (3D)
   * Garis sejajar
   * Garis bersilangan (*skew lines*)

## 3. VEKTOR
a. Definisi dan Notasi Vektor
b. Besar (Panjang) Vektor
c. Vektor Satuan
d. Operasi Vektor
   * Penjumlahan & pengurangan
   * Perkalian skalar
e. Perkalian Vektor
   * *Dot product* (hasil kali titik)
   * *Cross product* (hasil kali silang / vektor)
f. Proyeksi Vektor
   * Proyeksi skala
   * Proyeksi vektor

## 4. GARIS
a. Persamaan Garis Lurus (2D)
   * Bentuk umum
   * Bentuk *slope*
   * Gradien/*slope*
   * Bentuk titik-*slope*
   * Bentuk dua titik
   * Bentuk *intercept*
b. Hubungan Dua Garis (2D)
   * Sejajar
   * Tegak lurus
   * Berpotongan: titik potong (sistem persamaan)
   * Sudut antara dua garis
c. Persamaan Garis di Ruang 3D
   * Bentuk parametrik
   * Bentuk simetri
   * Bentuk vektor
d. Hubungan Dua Garis (3D)
   * Sejajar (*parallel*)
   * Berpotongan (*intersecting*)
   * Bersilangan / tidak sebidang (*skew lines*)
   * Berimpit (*coincident*)
e. Sudut dan Posisi Relatif
   * Sudut antara dua garis
   * Sudut antara garis dan bidang
   * Sudut antara dua bidang
## 1. Koordinat Titik di Ruang
Untuk menentukan lokasi suatu titik pada bidang datar, diperlukan dua angka. Kita tahu bahwa setiap titik pada bidang datar dapat direpresentasikan sebagai pasangan terurut bilangan real $(a, b)$, $a$ adalah koordinat $x$ dan $b$ adalah koordinat $y$. Karena alasan ini, bidang datar disebut dua dimensi. Sedangkan, untuk menentukan lokasi suatu titik di ruang, diperlukan tiga angka. Kita merepresentasikan setiap titik di ruang dengan tiga bilangan real yang terurut $(a, b, c)$. 
* Bidang (2D): Memerlukan 2 angka $(x, y)$ untuk menentukan posisi.
* Bidang (3D): Memerlukan 3 angka $(x, y, z)$ untuk menentukan posisi.

Komponen dasar sistem koordinat:
* Titik asal $(O)$: Titik acuan $(0, 0, 0)$
* Sumbu koordinat: Tiga garis berarah $(x, y, z)$ yang saling tegak lurus
* Aturan tangan kanan: Cara menentukan arah sumbu $z$ positif (ibu jari menunjuk ke arah sumbu $z$ positif saat jari tangan kanan melengkung dari $x$ ke $y$)

Bidang dan Oktan:
* Tiga bidang koordinat:
 
   1. Bidang $xy$ (di mana $z = 0$)
   2. Bidang $yz$ (di mana $x = 0$)
   3. Bidang $xz$ (di mana $y = 0$)
* Oktan: Ruang dibagi menjadi 8 oktan oleh ketiga bidang tersebut

Menentukan titik $P(a, b, c)$:

* Mulai dari titik asal $(0, 0, 0)$
* Berjalan $a$ satuan sepanjang sumbu $x$
* Berjalan $b$ satuan sejajar sumbu $y$
* Berjalan $c$ satuan sejajar sumbu $z$

<div align="center">
  <img src="https://i.pinimg.com/736x/f3/06/89/f3068984ab873ffb897eebba5cbf399e.jpg" width="500">
   
</div>

Proyeksi titik

Setiap titik $P(a, b, c)$ membentuk "kotak persegi panjang" di ruang.
* Proyeksi adalah bayangan titik pada bidang:

  1. $Q(a, b, 0)$ → Proyeksi pada bidang $xy$.
  2. $R(0, b, c)$ → Proyeksi pada bidang $yz$.
  3. $S(a, 0, c)$ → Proyeksi pada bidang $xz$.

Contoh soal:

Misalkan posisi awal berada di titik asal $(0, 0, 0)$. Anda bergerak sejauh 4 satuan sepanjang sumbu $x$ positif, lalu bergerak sejauh 3 satuan ke arah bawah (sejajar sumbu $z$ negatif). Tentukan koordinat posisi akhir Anda.

Penyelesaian:

<div align="center">
  <img src="https://i.pinimg.com/736x/fa/00/5a/fa005a4d692a9d2f926fb8b3206934f3.jpg" width="500">
   
</div>

* Titik awal $(0, 0, 0)$

* Bergerak sejauh 4 satuan sepanjang sumbu $x$ positif $(4, 0, 0)$

* Bergerak sejauh 3 satuan ke arah bawah (sejajar sumbu $z$ negatif) $(4, 0, -3)$

* Jadi, titik akhir berada di $(4, 0, -3)$


## 2. Jarak Antara Dua Titik
Jarak antara dua titik dalam ruang adalah perluasan dari jarak pada bidang. Fondasi utamanya tetap menggunakan Teorema Phytagoras, namun diterapkan pada tiga sumbu koordinat yang saling tegak lurus. Dalam geometri ruang sebuah titik tidak lagi diwakili oleh $(x, y)$, tetapi diwakili oleh triple koordinat $(x, y,z)$. Dengan adanya penambahan dimensi ketiga (sumbu $z$) memungkinkan kita merepresentasikan posisi titik dalam ruang hampa, mencakup panjang, lebar, dan tinggi.

  a. Rumus Jarak dalam Ruang
    
  1. Bidang (3D): Jika terdapat dua titik dalam ruang $P_1(x_1, y_2, z_3)$ dan $P_2(x_1, y_2, z_3)$, maka jarak d diantara keduanya adalah: 
$d=\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$

  2. Sifat Non-negatif: Karena setiap komponen selisih koordinat dikuadratkan, hasil di bawah akar akan selalu positif atau nol, sehingga jarak tidak pernah bernilai negatif.

  b. Konsep Titik Tengah (Midpoint) dalam Ruang 

   Titik tengah $M$ yang menghubungkan $P_1(x_1, y_2, z_3)$ dan  $P_2(x_1, y_2, z_3)$ adalah 
   $M= (\frac{x_1+x_2}{2}, \frac{y_1+y_2}{2}, \frac{z_1+z_2}{2})$
  
  c. Aplikasi Geometris: Dari Lingkaran ke Bola

   Di dalam ruang, konsep lingkaran diperluas menjadi bola. Sebuah bola didefinisikan sebagai semua titik $(x, y, z)$ yang jaraknya dari titik pusat tertentu $(h,k,l)$ adalah konstan $(r)$.
   * Persamaan Bola
     
  Menggunakan rumus jarak, persamaan standar sebuah bola adalah:
  $(x-h)^2+(y-k)^2+(z-l)^2=r^2$

 Contoh soal:

   1. Tentukan jarak antara titik $P_1(1, 0, 2)$ dan  $P_2(3, 4, 6)$ dalam ruang koordinat tiga dimensi.
Penyelesaian:

      a. Identifikasi koordinat:

       * $P_1: x_1=1, y_1=0, z_1=2$

       * $P_2: x_2=3, y_2=4, z_2=6$

      b. Gunakan rumus jarak ruang:

         $d=\sqrt{(x^2-x^1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$

      c. Substitusikan nilai ke dalam rumus jarak:

         $\sqrt{d  =(3-1)^2+(4-0)^2+(6-2)^2}$
 
         $\sqrt{d  =(2)^2+(4)^2+(4)^2}$
   
         $\sqrt{d  =4+16+16}$

         $\sqrt{d  =36}$

         $d  =6$

         jadi, jarak antara kedua titik tersebut adalah 6 satuan.

   2. Tentukan nilai $x$ jika jarak antara titik $A(2,-1, 4)$ dan  $B(x, 3, 4)$ adalah 5 satuan.

       Penyelesaian: 

      d. Identifikasi koordinat:

         * $P_1:x_1=1, y_1=0, z_1=2$

         * $P_2:x_2=x, y_2=4, z_2=6$

      e. Gunakan rumus jarak ruang:
          $d =\sqrt{(x_2-x_1)^2+(y_2-y_1)^2+(z_2-z_1)^2}$

      f. Substitusikan nilai ke dalam rumus jarak:

         $5 =\sqrt{(x-2)^2+(3-(-1))^2+(4-4)^2}$
         $5  =\sqrt{(x-2)^2+(4)^2+(0)^2}$
         $5  =\sqrt{(x-2)^2+16}$
         $25 =(x-2)^2+16$
         $9   =(x-2)^2$
         $x-2=3$    atau    $x-2=-3$
         $x=5$      atau    $x=-1$
         jadi, nilai yang memenuhi $x adalah  antara 5 atau -1. 



## 3. Vektor dalam Ruang
  1 . Definisi Vektor dalam Ruang
      Vektor dalam ruang adalah besaran yang memiliki nilai dan arah yang terletak di dalam ruang tiga dimensi. Setiap vektor dapat dinyatakan dalam koordinat kartesius menggunakan tiga sumbu yang saling tegak lurus, yaitu sumbu $x$, sumbu $y$, dan sumbu $z$.

Notasi vektor:
  * Komponen:  $\overrightarrow{v} = (v_1, v_2, v_3)$
  * Vektor Satuan:  $\overrightarrow{v} =v_1\overrightarrow{i}+v_2\overrightarrow{j}+v_3\overrightarrow{k}$
  Dimana $\overrightarrow{i}$, $\overrightarrow{j}$, $\overrightarrow{k}$ adalah vektor basis pada sumbu $x$, $y$, $z$)

2. Operasi Dasar Vektor

  Jika diketahui $\overrightarrow{a} = (a_1, a_2, a_3)$ dan $\overrightarrow{b} = (b_1, b_2, b_3)$ , maka:
  * Penjumlahan dan Pengurangan
  Dilakukan dengan menjumlahkan atau mengurangkan komponen yang bersesuaian.
  $\overrightarrow{a} \pm \overrightarrow{b} = (a_1 \pm b_1,a_2 \pm b_2, a_3 \pm b_3)$

  * Perkalian Skalar
  Jika $k$ adalah sebuah skalar, maka:
   $k\overrightarrow{a} =(ka_1, ka_2, ka_3)$
  * Panjang Vektor
  Jarak dari titik pangkal ke titik ujung vektor:
  $|\overrightarrow{a}| =\sqrt{a_1^2+a_2^2+a_3^2}$

3. Perkalian Dua Vektor
  Ada dua jenis perkalian utama dalam $R^3$:

  * Dot Product (Perkalian Titik)

     Hasil dari perkalian titik adalah sebuah skalar. Digunakan untuk mencari sudut atau proyeksi.
    Rumus Komponen: $\overrightarrow{a}\overrightarrow{b} =a_1 b_1+a_2 b_2+a_3 b_3$
    Rumus Sudut: $\overrightarrow{a} \overrightarrow{b} =|\overrightarrow{a}| |\overrightarrow{b}| cos \theta$

     Sifat: $\overrightarrow{a} \overrightarrow{b} =|\overrightarrow{a}| |\overrightarrow{b}| sin \theta$  (Luas jajar genjang yang dibentuk kedua vektor).


  * Cross Product (Perkalian Silang)
    Hasil dari perkalian silang adalah sebuah vektor yang tegak lurus terhadap bidang yang dibentuk $\overrightarrow{a}$ dan $\overrightarrow{b}=$
    



 
4. Aplikasi Vektor dalam Ruang

  * Vektor Posisi: Menentukan letak titik $P(x,y,z)$ relatif terhadap titik asal $O(0,0,0)$.
  * Proyeksi Ortogonal: Mencari bayangan satu vektor pada arah vektor lainnya.
  * Persamaan Garis dan Bidang: Digunakan dalam kalkulus peubah banyak untuk menentukan geometri ruang.

5. Contoh Soal dan Penyelesaiannya:

    Diketahui dua buah vektor a dan b  sebagai berikut:

      $\overrightarrow{a} =2\overrightarrow{i}-\overrightarrow{j}+3\overrightarrow{k}$

      $\overrightarrow{b} =\overrightarrow{i}+2\overrightarrow{j}-2\overrightarrow{k}$

   Tentukanlah:
   
      1. Hasil perkalian titik $(a .b )$
         
      2. Panjang masing-masing vektor $\overrightarrow{a}$ dan $\overrightarrow{b}$
         
      3. Besar sudut yang dibentuk oleh kedua vektor

     Penyelesaian:
   
      1. $\overrightarrow{a}.\overrightarrow{b} =(a_x.b_x) + (a_y.b_y) + (a_z.b_z)$

         $\overrightarrow{a}.\overrightarrow{b} =(2.1)+(-1.2)+(3.-2)$

         $\overrightarrow{a}.\overrightarrow{b} =2-2-6$

         $\overrightarrow{a}.\overrightarrow{b} =-6$

      2. Menggunakan rumus Pythagoras ruang: v =x2+y2+z2
         * Panjang $\overrightarrow{a}$ :

           $|\overrightarrow{a}| =\sqrt{2^2+(-1)^2+3^2}$

           $|\overrightarrow{a}| =\sqrt{4+1+9}$
 
           $|\overrightarrow{a}| =\sqrt{14}$

         * Panjang $overrightarrow{b}$ :

             $|\overrightarrow{b}| =\sqrt{1^2+2^2+(-2)^2}$

             $|\overrightarrow{b}|=\sqrt{1+4+4}$
 
             $|\overrightarrow{b}| =\sqrt{9}$

             $|\overrightarrow{b}| =3$

      3. Menggunakan definisi perkalian titik
         $\overrightarrow{a}.\overrightarrow{b} =|\overrightarrow{a}|\overrightarrow{b}| cos \theta$

         $cos\theta=\frac{\overrightarrow{a}.\overrightarrow{b}}{|\overrightarrow{a}| |\overrightarrow{b}|}$

            $cos \theta=\frac{-61}{\sqrt{14}.3}$

            $cos \theta=\frac{-2}{\sqrt{14}}$
          
            $cos \theta=-\frac{1}{7}\sqrt{14}$

            $\theta=arccos(-\frac{\sqrt{14}}{7})=122,3 derajat$




## 4. Garis dalam Ruang
  a. Persamaan garis dalam ruang
  
  Untuk menentukan sebuah garis dalam ruang, kita membutuhkan dua informasi utama:
  
   * Satu titik tetap yang dilalui garis tersebut, misal $P_1(x_1,y_1,z_1)$

  * Vektor arah yang sejajar dengan garis tersebut, misal
    $\overrightarrow{v}=a$\overrightarrow{i}+b$\overrightarrow{j}+c$\overrightarrow{k} atau $\overrightarrow{v}=(a,b,c)$
    
    1. Persamaan Vektor
       
       Jika $r$ adalah posisi titik sembarang $(x,y,z)$ pada garis, maka:
        $r=r_0+t$\overrightarrow{v}$
        Di mana:
        * $r_0$ adalah vektor posisi titik $P_1$

        * $t$ adalah skalar(parameter)
    2. Persamaan Parametrik

        Dengan menguraikan komponen di atas, kita mendapatkan

        #x=x_1+at$

        $y=y_1+bt$
  
       $z=z_1+c$

    3. Persamaan Simetrik

       Jika kita mengeliminasi parameter $t$ (dengan syarat $a,b,c \ne 0$), maka diperoleh
       $x-x_1 a=y-y_1 b=z-z_1 c$

b. Kedudukan dua garis dalam ruang

Dua garis dalam ruang memiliki empat kemungkinan hubungan:

  1. Berpotongan: Memiliki satu titik persekutuan

  2. Sejajar: Memiliki arah yang sama dan tidak memiliki titk persekutuan.

  3. Berimpit: Memiliki arah yang sama dan semua titiknya sama.

  4. Bersilangan: Tidak sejajar dan tidak berpotongan (berada di bidang yang berbeda)


c. Sudut Antara Dua Garis

   Sudut antara dua garis ditentukan oleh sudut antara kedua vektor arahnya $(\overrightarrow{v_1}$ dan $\overrightarrow{v_2})$:
   $cos \theta = $\overrightarrow{v_1}.$\overrightarrow{v2}$\overrightarrow{v_1}$\overrightarrow{v_2}$

<div align="center">
  <img src="https://id.pinterest.com/40cec2ee-55de-4e54-b266-857b6ce5371d" width="500">     
</div>

 Persamaan Garis dalam Ruang 2D vs 3D

Dalam geometri analitik dua dimensi ($\mathbb{R}^2$), grafik dari sebuah persamaan yang melibatkan $x$ dan $y$ adalah sebuah kurva atau garis.  

Sebagai contoh, persamaan $y=5$ dalam $\mathbb{R}^2$ merepresentasikan sebuah garis, namun dalam $\mathbb{R}^3$ persamaan yang sama merepresentasikan sebuah bidang.  

Persamaan $y=x$ dalam $\mathbb{R}^3$ adalah bidang vertikal yang memotong bidang $xy$ pada sebuah garis dengan persamaan $y=x, z=0$.


