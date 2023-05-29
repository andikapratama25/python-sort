# python-sort


Pada Hari ini sedang membahas tentang Ascending dan Descending dan juga membahas Bubble Sort serta Selection Sort


**Ascending** adalah Pengurutan secara menaik (ascending) mengacu pada proses pengurutan elemen-elemen dalam urutan dari nilai terkecil ke terbesar. Dalam hal ini, elemen pertama dalam urutan akan memiliki nilai terkecil, dan elemen terakhir akan memiliki nilai terbesar. Dalam Python, Anda dapat menggunakan metode sort() untuk mengurutkan secara menaik.

**Descending** adalah Pengurutan secara menurun (descending) mengacu pada proses pengurutan elemen-elemen dalam urutan dari nilai terbesar ke terkecil. Dalam hal ini, elemen pertama dalam urutan akan memiliki nilai terbesar, dan elemen terakhir akan memiliki nilai terkecil. Dalam Python, Anda dapat menggunakan metode sort() dengan argumen reverse=True atau menggunakan fungsi sorted() dengan argumen reverse=True untuk mengurutkan secara menurun.

**Bubble sort** adalah salah satu algoritma pengurutan sederhana yang bekerja dengan membandingkan pasangan elemen secara berurutan dan menukar posisinya jika diperlukan. Algoritma ini mengulang proses ini sampai seluruh elemen diurutkan secara benar.  Perulangan pertama digunakan untuk mengontrol jumlah iterasi. Perulangan kedua membandingkan pasangan elemen bersebelahan dan menukar posisinya jika elemen sebelumnya lebih besar dari elemen setelahnya. Setelah setiap iterasi, elemen terbesar akan terdorong ke akhir array. Proses ini diulang hingga seluruh array terurut dengan benar.

**Selection sort** adalah salah satu algoritma pengurutan sederhana yang bekerja dengan memilih elemen terkecil dari sisa array yang belum diurutkan dan menukarnya dengan elemen pertama dari sisa array tersebut. Proses ini diulang untuk setiap elemen hingga seluruh array terurut dengan benar. Perulangan pertama digunakan untuk mengontrol iterasi dari elemen pertama hingga elemen sebelum terakhir. Di setiap iterasi, elemen terkecil dari sisa array yang belum diurutkan dicari dengan menggunakan perulangan kedua. Jika ditemukan elemen yang lebih kecil, maka indeksnya disimpan sebagai min_index. Setelah selesai mencari elemen terkecil, elemen terkecil tersebut ditukar dengan elemen pertama dari sisa array yang belum diurutkan. Proses ini diulang hingga seluruh array terurut dengan benar.
