<style>
  table {
    border-collapse: collapse;
    border: 1px solid black;
  }

  th {
    font-weight: 500;
  }

  th,
  td {
    border: 1px solid black;
  }

  th,
  td:nth-child(1) {
    white-space: nowrap;
  }

  .newpage {
    page-break-before: always;
  }
</style>

#### Peluang dan Unsur-unsur Peluang

1. Seorang mahasiswa sedang mempertimbangkan apakah akan ikut ujian tanpa belajar sama sekali atau meluangkan waktu belajar semalaman. Mahasiswa sadar bahwa keputusannya penuh dengan ketidakpastian, karena hasil ujiannya bisa lulus atau tidak lulus. Dari contoh tersebut, tentukan:
   a. Ruang Sampel ($S$), yaitu semua kemungkinan hasil yang dapat terjadi.
   b. Kejadian ($A$), yaitu peristiwa khusus yang ingin dihitung peluangnya.
   c. Buatlah satu contoh nyata penerapan peluang dalam kehidupan sehari-hari yang berbeda dari soal tersebut.

2. Sebuah keluarga memiliki 4 orang anak dan yang diamati adalah jenis kelamin anak berdasarkan urutan kelahirannya. Misalkan $A$ adalah kejadian bahwa keluarga tersebut memiliki anak laki-laki paling sedikit 2 orang dan $B$ adalah kejadian bahwa anak kedua laki-laki dan anak ketiga perempuan. Hitunglah:
   a. $P(A)$
   b. $P(B)$
   c. $P(A \cap B)$
   d. Peluang bahwa anak laki-laki paling sedikit dua orang jika diketahui bahwa anak kedua berjenis kelamin laki-laki dan anak ketiga perempuan.

**1. Dari contoh mahasiswa yang menghadapi ujian, tentukan ruang sampel, kejadian yang ingin dihitung peluangnya, dan satu contoh penerapan peluang lain dalam kehidupan sehari-hari.**

Pada soal pertama, hasil ujian yang mungkin terjadi ada dua, yaitu mahasiswa lulus atau tidak lulus.

a. Ruang sampel adalah kumpulan semua hasil yang mungkin terjadi. Dengan demikian:

$$
S = \{\text{lulus},\ \text{tidak lulus}\}
$$

b. Kejadian $A$ yang ingin diamati adalah mahasiswa lulus ujian. Jadi:

$$
A = \{\text{lulus}\}
$$

c. Contoh lain adalah memperkirakan kemungkinan koneksi internet terputus saat mengikuti kelas daring. Hasil yang mungkin adalah koneksi tetap tersambung atau terputus. Jika koneksi di rumah sering bermasalah pada jam tertentu, mahasiswa dapat memperkirakan risiko gangguan lebih tinggi pada waktu tersebut dan menyiapkan jaringan internet cadangan agar tetap bisa mengikuti kelas.

<div class="newpage"></div>

**2. Berdasarkan jenis kelamin empat anak dalam sebuah keluarga, hitung $P(A)$, $P(B)$, $P(A \cap B)$, dan peluang bersyarat $P(A \mid B)$.**

Untuk soal kedua, diasumsikan setiap anak memiliki peluang yang sama untuk berjenis kelamin laki-laki atau perempuan, dan jenis kelamin setiap anak tidak bergantung pada anak lainnya. L = laki-laki dan P = perempuan. Karena urutan kelahiran diperhatikan, ruang sampelnya terdiri dari seluruh susunan jenis kelamin untuk empat anak, yaitu:

$$
S = \{L, P\}^4, \qquad |S| = 2^4 = 16
$$

Notasi tersebut berarti setiap dari empat posisi kelahiran dapat diisi L (laki-laki) atau P (perempuan), sehingga ada 16 susunan yang mungkin. Setiap susunan memiliki peluang yang sama, yaitu $\frac{1}{16}$.

a. Kejadian $A$ adalah keluarga memiliki paling sedikit dua anak laki-laki. Artinya, jumlah anak laki-laki yang mungkin adalah tepat dua, tepat tiga, atau tepat empat orang. Peluang suatu kejadian dihitung dengan membagi banyaknya hasil yang memenuhi kejadian tersebut dengan banyaknya seluruh hasil yang mungkin:

$$
P(A) = \frac{n(A)}{n(S)}
$$

Dalam rumus tersebut, $n(A)$ adalah banyak susunan yang memenuhi kejadian $A$, sedangkan $n(S)$ adalah banyak seluruh susunan dalam ruang sampel. Untuk mencari $n(A)$, kita kelompokkan susunan berdasarkan jumlah anak laki-laki. Setiap rangkaian terdiri dari empat huruf yang menunjukkan jenis kelamin anak pertama sampai anak keempat. Huruf L berarti laki-laki, sedangkan huruf P berarti perempuan.

Untuk menghitung banyak susunan tanpa menuliskannya satu per satu, kita dapat menggunakan kombinasi. Kombinasi digunakan untuk menghitung banyak cara memilih sejumlah posisi dari seluruh posisi yang tersedia, tanpa memperhatikan urutan pemilihannya. Notasi kombinasi juga disebut koefisien binomial, dan rumusnya adalah:

$$
\binom{n}{r} = \frac{n!}{r!(n-r)!}
$$

Dalam soal ini, $n$ adalah jumlah posisi kelahiran, yaitu 4, sedangkan $r$ adalah jumlah posisi yang ditempati anak laki-laki. Untuk tepat 2 anak laki-laki, kita memilih 2 dari 4 posisi:

$$
\binom{4}{2} = \frac{4!}{2!(4-2)!}
$$

$$
\binom{4}{2} = \frac{4!}{2!2!}
$$

$$
\binom{4}{2} = 6
$$

Jadi, terdapat 6 susunan yang memenuhi. Perhitungan jumlah susunan dan kemungkinan L/P ditampilkan berdampingan:

$$
\begin{aligned}
\binom{4}{2}=6 &\quad \{\text{LLPP},\ \text{LPLP},\ \text{LPPL},\ \text{PLLP},\ \text{PLPL},\ \text{PPLL}\}
\end{aligned}
$$

Jika terdapat tepat 3 anak laki-laki, kita memilih 3 dari 4 posisi. Di sisi kiri ditunjukkan perhitungan kombinasinya, sedangkan di sisi kanan ditunjukkan susunan L/P yang mungkin:

$$
\begin{aligned}
\binom{4}{3}=4 &\quad \{\text{LLLP},\ \text{LLPL},\ \text{LPLL},\ \text{PLLL}\}
\end{aligned}
$$

Jika terdapat tepat 4 anak laki-laki, keempat posisi menjadi anak laki-laki. Perhitungan dan susunan yang mungkin adalah:

$$
\begin{aligned}
\binom{4}{4}=1 &\quad \{\text{LLLL}\}
\end{aligned}
$$

Ketiga kelompok tersebut tidak memiliki susunan yang sama. Jumlahkan banyak susunan dari setiap kelompok untuk memperoleh banyak hasil yang memenuhi kejadian $A$:

$$
n(A) = 6 + 4 + 1 = 11
$$

Jadi, banyak susunan yang memenuhi kejadian $A$ adalah $n(A)=11$, sedangkan banyak seluruh susunan adalah $n(S)=16$. Dengan menggunakan rumus peluang di atas:

$$
P(A) = \frac{11}{16}
$$

b. Kejadian $B$ menyatakan anak kedua laki-laki dan anak ketiga perempuan. Jenis kelamin anak pertama dan keempat bebas laki-laki atau perempuan, sehingga ada $2 \times 2 = 4$ susunan yang memenuhi dari 16 susunan yang mungkin. Maka:

$$
P(B) = \frac{4}{16} = \frac{1}{4}
$$

c. Pada kejadian $A \cap B$, anak kedua harus laki-laki, anak ketiga perempuan, dan jumlah anak laki-laki paling sedikit dua orang. Karena anak kedua sudah laki-laki, sedikitnya salah satu dari anak pertama atau anak keempat juga harus laki-laki. Susunan yang memenuhi adalah:

$$
\{\text{LLPL},\ \text{LLPP},\ \text{PLPL}\}
$$

Jadi, terdapat 3 susunan yang termasuk dalam kejadian $A \cap B$. Dengan demikian:

$$
P(A \cap B) = \frac{3}{16}
$$

d. Peluang yang ditanyakan adalah peluang kejadian $A$ jika kejadian $B$ sudah diketahui. Peluang bersyarat dihitung dengan membagi peluang irisan $A$ dan $B$ dengan peluang $B$:

$$
P(A \mid B) = \frac{P(A \cap B)}{P(B)}
$$

$$
P(A \mid B) = \frac{3}{16} \div \frac{4}{16}
$$

Karena kedua pecahan memiliki penyebut yang sama, perhitungannya dapat disederhanakan dengan membagi pembilangnya:

$$
P(A \mid B) = \frac{3}{4}
$$

Jadi, jika diketahui anak kedua laki-laki dan anak ketiga perempuan, peluang bahwa keluarga tersebut memiliki paling sedikit dua anak laki-laki adalah 75%.

**Referensi**

- Materi Menjelaskan Konsep Dasar Peluang, SATS4121. Universitas Terbuka.
