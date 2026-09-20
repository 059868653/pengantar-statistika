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

#### Ukuran Pemusatan dan Penyebaran Data

1. Seorang mahasiswa melakukan survei terhadap 30 mahasiswa kos di sekitar kampus. Ia menanyakan terlebih dahulu mengenai jenis makanan favorit mahasiswa, dan hasilnya menunjukkan bahwa nasi goreng adalah makanan yang paling banyak dipilih, diikuti oleh mie instan, ayam geprek, pecel lele, dan beberapa makanan lain. Selain itu, ia juga mencatat waktu tidur mahasiswa per malam, yang sebagian besar berada pada kisaran 6 hingga 9 jam, dengan distribusi data yang relatif seimbang. Tidak hanya itu, mahasiswa tersebut juga mengumpulkan data mengenai pengeluaran bulanan mahasiswa yang ternyata sangat bervariasi, mulai dari Rp800.000 hingga Rp10.000.000, dengan beberapa mahasiswa memiliki pengeluaran yang jauh lebih tinggi dibandingkan mayoritas lainnya. Berdasarkan uraian kasus tersebut, tentukan ukuran pemusatan yang paling tepat digunakan untuk menggambarkan masing-masing data, serta jelaskan alasan pemilihan ukuran tersebut.

2. Sebuah perusahaan farmasi sedang melakukan uji klinis terhadap dua jenis obat penurun tekanan darah (Obat A dan Obat B). Penelitian melibatkan masing-masing 50 pasien dengan kondisi hipertensi ringan. Setelah 1 bulan konsumsi obat, rata-rata penurunan tekanan darah sistolik pada kedua kelompok pasien ternyata sama, yaitu 15 mmHg. Namun, ketika data dianalisis lebih detail, terlihat perbedaan dalam pola sebaran hasil:
   - Pada kelompok Obat A, sebagian besar pasien mengalami penurunan yang cukup konsisten, berkisar antara 12–18 mmHg.
   - Pada kelompok Obat B, terdapat pasien yang penurunannya sangat kecil (hanya 5 mmHg) dan ada juga yang sangat besar (hingga 30 mmHg).

   Kondisi ini menimbulkan pertanyaan: walaupun rata-rata efek kedua obat sama, apakah salah satu obat lebih “stabil” dalam memberikan efek penurunan tekanan darah? Untuk menjawab hal ini, peneliti perlu menghitung variansi/ragam dari hasil penurunan tekanan darah pada kedua kelompok.

   Pertanyaan:

   2a. Mengapa variansi diperlukan dalam kasus ini meskipun rata-rata hasil penurunan tekanan darah sama?

   2b. Bagaimana variansi dapat membantu peneliti dalam menentukan obat mana yang lebih baik digunakan secara klinis?

<div class="newpage"></div>

**1. Berdasarkan uraian kasus pada soal pertama, tentukan ukuran pemusatan yang paling tepat digunakan untuk menggambarkan masing-masing data, serta jelaskan alasan pemilihan ukuran tersebut.**

| Data                            | Ukuran Pemutusan | Penejelasan                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| ------------------------------- | :--------------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Jenis Makanan Favorit           |      Modus       | Menurut saya, ukuran pemusatan yang paling tepat digunakan adalah modus. Hal ini karena data jenis makanan favorit merupakan data kualitatif atau kategorikal dengan skala pengukuran nominal. Pada jenis data seperti ini, nilai rata-rata maupun nilai tengah tidak dapat dihitung, sehingga satu-satunya ukuran pemusatan yang relevan adalah modus.                                                                                                                                                                                           |
| Waktu Tidur Mahasiswa per Malam |       Mean       | Ukuran pemusatan yang paling tepat digunakan adalah rata-rata atau mean. Pada soal dijelaskan kalau data yang dikumpulkan bersifat kuantitatif kontinu dengan distribusi data yang relatif seimbang atau simetris tanpa adanya nilai ekstrem. Dalam kondisi distribusi data yang normal dan seimbang, rata-rata merupakan ukuran pemusatan terbaik karena memperhitungkan seluruh proporsi nilai data secara menyeluruh.                                                                                                                          |
| Pengeluaran Bulanan Mahasiswa   |      Median      | Untuk pengeluaran bulanan mahasasiswa ukuran pemusatan yang paling tepat menurut pada adalah median. Hal ini karena pada kasus diatas dijelaskan bahwa pengeluaran sangat bervariasi, dimana terdapat beberapa mahasiswa dengan pengeluaran yang jauh lebih tinggi dibanding mayoritas atau memiliki outlier. Jika kita menggunakan mean, nilainya akan terdistorsi oleh nilai outlier dan menjadi kurang mewakili. Oleh karena itu, median atau nilai tengah lebih tepat karena bersifat tahan terhadap keberadaan nilai-nilai ekstrem tersebut. |

<div class="newpage"></div>

**2a. Mengapa variansi diperlukan dalam kasus ini meskipun rata-rata hasil penurunan tekanan darah sama?**

Pada kasus diatas dijelaskan bahwa rata-rata penurunan tekanan darah pada pasien yang diberikan obat A dan B sama, namun ketika data dikumpulkan lebih detail, terlihat perbedaan dalam pola sebaran hasil

- Obat A memiliki sebaran yang sempit yaitu pada 12–18 mmHg, artinya hasil dari pemberian obat A kepada pasien di kelompok ini cenderung konsisten pada sebagian besar pasien.

- Obat B memiliki sebaran yang lebih kurang konsisten, artinya pada kelompok ini terdapat pasien yang penurunannya sangat kecil hanya 5 mmHg dan ada juga yang sangat besar hingga 30 mmHg.

> Jadi rata-rata hanya dapat memberikan gambaran umum titik pusat data, tetapi menyembunyikan tingkat keberagaman atau persebaran data itu sendiri, dengan melihat variansi atau ragam dari data kita dapat menentukan bagaimana persebaran data tersebut mempengaruhi hasil pengukuran.

**2. Bagaimana variansi dapat membantu peneliti dalam menentukan obat mana yang lebih baik digunakan secara klinis?**

Prediktabilitas didapatkan dari obat A yang memiliki variansi hasil yang kecil menunjukkan efek obat konsisten dan dapat diprediksi. Dokter dapat meyakini bahwa hampir setiap pasien akan mengalami penurunan tekanan darah yang cukup dan aman, pada pengujian mendapatkan hasil penurunan 12–18 mmHg.

Sedangkan risiko efek samping menjadi ancaman pada obat B karena variansi yang tinggi menunjukkan efektivitas yang tidak stabil. Pasien dengan penurunan hanya 5 mmHg berisiko gagal pengobatarn, sedangkan pasien dengan penurunan hingga 30 mmHg berisiko mengalami hipotensi berlebihan.

> Kesimpulan klinis dari studi kasus ini adalah obat A lebih disarankan karena memberikan hasil yang lebih stabil, dapat diprediksi, dan berisiko lebih rendah.

**Referensi**

- Materi Ukuran Pemusatan dan Penyebaran Data - SATS4121
- Sutikno, & Ratnaningsih, D. J. (2022). Metode Statistika 1. Universitas Terbuka
