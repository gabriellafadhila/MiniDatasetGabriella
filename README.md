# Mini Dataset Gabriella
Tugas Penyusunan Mini Dataset Natural Language Processing

Nama: Gabriella Fadhilatus Awanda
NIM : 2446000025

Deskripsi Data
Dataset ini berisi 213 entri dengan 7 kolom, yaitu:

1. type_of_reference - Jenis referensi (misalnya jurnal, konferensi, dll.), tidak ada nilai yang hilang.
2. authors - Nama penulis dari setiap referensi, tidak ada nilai yang hilang.
3. primary_title - Judul utama referensi, memiliki banyak nilai kosong (hanya 91 dari 213 entri yang memiliki data).
4. title - Alternatif dari judul utama, juga memiliki banyak nilai kosong (hanya 122 dari 213 entri yang memiliki data).
5. publication_year - Tahun publikasi dalam format objek (string), dengan 122 nilai non-kosong.
6. year - Tahun publikasi dalam format numerik (integer), tidak ada nilai yang hilang.
7. abstract - Abstrak dari referensi, tidak ada nilai yang hilang.

Kemudian pada tugas ini saya hanya berfokus pada primary_title yang merupakan kolom berisi judul artikel. Pada kolum tersebut saya lakukan pre prosesing data yang dilanjutkan dengan proses cleaning, parsing, proses tokenisasi, stopword, lemmatization, Perhitungan frekuensi kata yang sering muncul, bobot TF IDF, dan NER.

Kemudian didapatkan hasil analisis akhir seperti berikut:
![image](https://github.com/user-attachments/assets/86373cd3-ba0f-42bb-865e-3974471415a7)

