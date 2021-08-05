# Glosarium
Berfungsi agar bila kita ingin mencari suatu topik khusus, gak perlu buka semua resourcenya satu per satu. Berisi deskripsi singkat mengenai resource yang ada di folder ini. Bila ingin menkontribusi bacaan jangan lupa di buat ringkasannya dan di tambahkan di sini.

1) Understanding Learning Rate in Machine Learning
\
Banyak di antara kita yang sedang belajar machine learning mendapatkan miskonsepsi tentang learning rate. Yang kita tau cuman semakin kecil semakin presisi belajarnya, which is training semakin lama, cuman hasil (harusnya/biasanya) semakin bagus. Ya berarti logikanya kita mau pake learning rate terkecil dong? Gak gitu.. Maka dari itu pengertian matematis dari learning rate juga diperlukan, dan ada di PDF ini. (Peringatan: math inside)


2) Why is my validation loss is lower than my training loss
\
Seringkali dalam kasus pembuatan model ML/DL kita tranining lalu di ukur hasil training per iterasi dengan data validasi. Logikanya validation loss lebih tinggi dari training loss karena data validasi dia baru lihat pertama kali jadi kemungkinan salahnya lebih tinggi... tapi ada lho kasus sebaliknya. Ini merupakan gejala kalau model kita perlu di tune ulang untuk menghindari underfitting, osilasi, dan bahkan overfitting di iterasi-iterasi selanjutnya. Nah PDF ini membahas mengapa hal itu bisa terjadi dan apa yang harus dilakukan.


3) An overview of gradient descent (based) optimization 
\
Kita mungkin tau berbagai fungsi optimisasi yang ada seperti Stochastic Gradient Descend (SGD), atau variasinya seperti Adam dan Momentum. Tapi apa sih sebenarnya itu dan bagaimana perumusannya? Di PDF ini kita akan mendapatkan semuanya termasuk rumus yang di jalankan di tiap iterasi sehingga membuat model lebih baik lagi bercermin dari kesalahan yang di tampilkan loss function. (Peringatan: intensive math inside)
