# Customer Segmentation with Python
## Deskripsi Proyek
Perusahaan sedang berusaha untuk mengenal lebih baik pelanggannya. Tujuannya agar perusahaan dapat membuat strategi pemasaran yang lebih tepat dan juga efisien bagi tiap tiap pelanggan. Saya diberikan tugas agar dapat memberikan rekomendasi untuk menyelesaikan permasalahan tersebut.
Salah satu teknik yang bisa dilakukan untuk mengenal lebih baik pelanggan adalah dengan melakukan segmentasi pelanggan. Yaitu dengan mengelompokkan pelanggan-pelanggan yang ada berdasarkan kesamaan karakter dari pelanggan tersebut. Saya akan menggunakan algoritma K-Prototypes dalam segmentasi ini.
## Penentuan Banyaknya Cluster
Dalam menentukan banyaknya cluster itu tidak sembarangan. Harus dicari nilai optimalnya dengan melihat kedalam inertia plot. Gambar berikut merupakan inertia plot yang sudah dibuat di proyek ini.\
<img src="Customer Segmentation with Python/1.png?raw=true"/>\
Inertia plot menunjukkan bahwa banyaknya cluster yang terletak pada “elbow” adalah 5 sehingga banyak cluster yang optimal untuk proyek ini adalah 5.
## Pembuatan Model
Selanjutnya melakukan pembuatan model berdasarkan banyak cluster yang sudah ditentukan yakni 5. Model disimpan dalam variabel bernama “kproto”.
