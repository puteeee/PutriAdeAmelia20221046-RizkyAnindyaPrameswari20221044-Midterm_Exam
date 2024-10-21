**Pendahuluan**

  Inflasi merupakan indikator ekonomi yang penting untuk menilai kestabilan harga dan daya beli masyarakat. Di Indonesia, inflasi digunakan sebagai acuan dalam merumuskan kebijakan ekonomi baik di tingkat nasional maupun daerah. Setiap provinsi di Indonesia memiliki kondisi ekonomiyang berbeda-beda, mulai dari sektor yang dominan hingga kebijakan lokal yang diterapkan, sehingga tingkat inflasi antarprovinsi sering kali bervariasi dari inflasi nasional yang merupakan rata-rata dari seluruh provinsi. Untuk memahami lebih dalam mengenai perbedaan ini, perlu dilakukan analisis inflasi di tingkat provinsi dan perbandingannya dengan inflasi nasional.


**Motivasi**

  Analisis inflasi di tingkat provinsi di Indonesia sangat penting karena memberikan gambaran mendalam mengenai kondisi ekonomi yang bervariasi di seluruh wilayah. Alasan pentingnya analisis ini antara lain, setiap provinsi memiliki kebijakan ekonomi yang berbeda, seperti insentif pajak atau subsidi, yang memengaruhi harga barang dan jasa di wilayah tersebut. Mengetahui variasi inflasi antarprovinsi dapat membantu pemerintah daerah merancang kebijakan yang lebih efektif untuk menjaga stabilitas harga.
Provinsi dengan sektor industri atau sumber daya alam yang dominan mungkin mengalami pola inflasi yang berbeda dibandingkan provinsi yang mengandalkan sektor pertanian. Analisis inflasi dapat memberikan pemahaman mengenai bagaimana pengelolaan sumber daya lokal memengaruhi inflasi.
  Mengetahui adanya perbedaan inflasi antarprovinsi membantu pemerintah pusat merancang kebijakan ekonomi nasional yang memperhitungkan disparitas antarwilayah, sehingga kebijakan tersebut dapat lebih tepat sasaran.
Analisis inflasi provinsi dapat membantu mengidentifikasi anomali atau ketidakwajaran dalam perekonomian daerah, seperti masalah pasokan atau gangguan pasar, yang mungkin memengaruhi harga secara tidak normal.
Analisis ini juga penting bagi masyarakat dan pelaku usaha agar lebih memahami faktor-faktor yang memengaruhi biaya hidup di wilayah mereka, sehingga dapat membuat keputusan ekonomi yang lebih baik.
Dengan melakukan analisis inflasi di tingkat provinsi, kita bisa lebih memahami interaksi antara faktor-faktor ekonomi lokal dan nasional serta merancang kebijakan yang lebih sesuai untuk mengurangi kesenjangan ekonomi antarwilayah di Indonesia.


**Metodologi Pengumpulan dan Pemrosesan Data**

  Data collection, menggunakan data inflasi nasional tahun 2024 yang menampilkan inflasi pada setiap provinsi untuk menganalisis laju inflasi pada tahun 2024.

  Data analysis, dengan menggunakan PySpark untuk melakukan analisis data inflasi nasional tahun 2024 yang diambil dari data collection tadi.

  Data cleaning, dengan memisahkan data inflasi provinsi dan data inflasi Indonesia (nasional).

  Compare mean inflation rates, untuk membuat perbandingan rata-rata dari data inflasi provinsi dengan data inflasi Indonesia.

  Calculation of difference, untuk melakukan perbandingan selisih absolute dari rata-rata inflasi provinsi dan inflasi Indonesia.

  Interpretation, untuk menginterpretasikan hasil dari data yang telah kami analisis (investigate discrepancies dan investigasi pola anomali).


**Hasil disertai Grafik dan Table Pendukung**

  Hasil setelah memasukan dan menganalisis data inflasi 2024 dengan menggunakan PySpark.

![image](https://github.com/user-attachments/assets/e19a80bd-ad1c-48a8-88f4-3301b6c5d2c0)

  Hasil setelah melakukan cleaning data dengan memisahkan data inflasi Indonesia dengan data inflasi provinsi.

![image](https://github.com/user-attachments/assets/2548107f-f19a-45f5-9fe9-9046ca25ec21)

  Hasil setelah dilakukan compare nilai rata-rata inflasi provinsi dan inflasi Indonesia.

![image](https://github.com/user-attachments/assets/10816583-aa6e-4c44-aa42-19cdac79cdf8)

  Hasil setelah dilakukan perbandingan selisih absolute dari rata-rata inflasi provinsi dan inflasi Indonesia pada setiap bulannya.
![image](https://github.com/user-attachments/assets/de94d361-1dc9-4bb7-b696-4294253446b8)

Berikut table perbandingan selisih absolute, investigate discrepancies, serta identifikasi anomali pada inflasi bulanan.

![image](https://github.com/user-attachments/assets/e79a360c-8baf-4258-903c-9d78dbedef2f)
Dari hasil di atas kita bisa melihat bahwa : 
- pada bulan januari selisih inflasi provinsi dengan Indonesia cukup tinggi, sekitar 0.3. Ini menunjukkan bahwa inflasi di tingkat provinsi pada bulan ini berbeda secara signifikan dari rata-rata Indonesia.
- Pada bulan februari terjadi penurunan selisih inflasi, dengan selisih absolut sekitar 0.15. Perbedaan inflasi provinsi dibandingkan Indonesia tidak terlalu besar dibandingkan bulan sebelumnya.
- Pada bulan maret selisih inflasi pada bulan ini adalah yang paling rendah, mendekati 0.1, yang menunjukkan bahwa inflasi di provinsi cenderung mendekati angka inflasi Indonesia.
- Pada bulan april selisih inflasi kembali meningkat menjadi sekitar 0.15, menunjukkan adanya sedikit perbedaan inflasi provinsi dengan Indonesia.
- Pada bulan Mei dan Juni pada bulan-bulan ini, selisih inflasi mencapai puncak kembali sekitar 0.3. Ini menunjukkan adanya variasi besar antara inflasi provinsi dan Indonesia pada bulan-bulan ini.
- Pada bulan Juli dan Agustus selisih inflasi menurun kembali, dengan selisih di sekitar 0.1 hingga 0.15, yang menunjukkan tingkat inflasi yang lebih seragam antara provinsi dan Indonesia.


![image](https://github.com/user-attachments/assets/2d7aea45-d255-4659-afae-2f06f4966de2)

Dari hasil gambar diatas kita bisa melihat bahwa : 
Garis Biru (Rata - Rata Provinsi ) : Inflasi provinsi terlihat bervariasi setiap bulan, dimulai dari sedikit lebih rendah di Januari, meningkat pada bulan Maret dan April, kemudian menurun mulai Mei hingga September.

Garis Orange (Inflasi Indonesia) :  Inflasi Indonesia juga memiliki pola serupa dengan rata-rata provinsi, tetapi secara keseluruhan berada sedikit di bawah garis biru, menunjukkan bahwa inflasi Indonesia cenderung lebih rendah dari rata-rata inflasi provinsi.

Selisih Absolut (Bar Abu - Abu) : Selisih tertinggi terjadi di bulan Januari, Mei, dan Juni, yang berarti inflasi provinsi lebih berbeda dibandingkan inflasi Indonesia pada bulan-bulan ini. Sebaliknya, di bulan-bulan seperti Maret, selisihnya kecil, menunjukkan inflasi provinsi lebih mendekati inflasi Indonesia.

![image](https://github.com/user-attachments/assets/49c92efc-8166-46b1-8d05-586798f1132e)

  Interpretasi terhadap inflasi nasional yang telah dilakukan bahwa dari hal tersebut dapat menciptakan ide bisnis baru seperti menciptakan platform berbasis teknologi yang dapat membantu memhami pola inflasi disetiap provinsi sehingga mereka bisa merencanakan strategi dalam pengelolaan biaya hidup, distribusi barang, atau pemasaran produk berdasarkan kondisi inflasi yang berbeda-beda di tiap daerah. Dengan adanya pemahaman yang lebih mendalam terkait inflasi di setiap daerah, perusahaan-perusahaan dapat menyesuaikan harga, memperbaiki distribusi barang, dan merancang strategi pemasaran yang relevan untuk setiap daerah, sehingga akan membantu dalam mengurangi kesenjangan ekonomi antar daerah dan mendorong pertumbuhan yang lebih merata. Namun, suksesnya bisnis ini bergantung pada akurasi dan ketersediaan data inflasi real-time dari setiap provinsi. Jika ada kesalahan atau keterlambatan data hal ini dapat mengakibatkan kesalahan pengambilan keputusan.


**Kesimpulan**

  Dari hasil analisis inflasi provinsi di Indonesia, terlihat adanya perbedaan yang cukup signifikan antara rata-rata inflasi provinsi dengan tingkat inflasi Indonesia. Meskipun tidak ditemukan kejanggalan besar dalam data, perbedaan inflasi antar provinsi mengungkapkan adanya ketidakseimbangan ekonomi antar daerah. Hal ini mungkin dipengaruhi oleh faktor-faktor seperti kondisi ekonomi setempat, distribusi barang dan jasa, serta variasi dalam metode pelaporan data di setiap wilayah.

  Analisis ini menyoroti pentingnya pemantauan inflasi di tingkat provinsi, karena inflasi Indonesia sering kali tidak menggambarkan situasi ekonomi di masing-masing provinsi. Untuk mengatasi ketimpangan ini, ada peluang untuk menciptakan solusi bisnis berbasis data yang membantu pelaku usaha dan pemerintah dalam merumuskan kebijakan dan strategi distribusi yang disesuaikan dengan kondisi inflasi lokal. Langkah ini dapat mendorong pemerataan ekonomi di seluruh wilayah dan meningkatkan efisiensi dalam berbagai sektor ekonomi.
