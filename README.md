# PCD_Assignment3
Penugasan Pengantar Citra Digital dengan membuat K means clustering untuk proses segmentasi gambar yang dilanjutkan dengan proses morphological simpel berupa Erosi (Erosi digunakan untuk menghilangkan piksel dari batas citra masukan dan mengecilkan / shrinking objek), Dilasi (digunakan untuk memperbesar atau memperluas batas / enlarging objek dalam sebuah citra, Closing (proses dilasi yang diikuti dengan proses erosi), dan Opening (proses erosi yang diikuti dengan proses dilasi)

Morphological proses sendiri diterapkan setelah segmentasi dan sebelum ekstraksi. Proses ini umumnya menggunakan memiliki banyak fungsi, dan bisa dibagikan menjadi morphological proses yang simple dan yang advanced. Pada penugasan kali ini kita akan fokus ke yang simple saja. 

Klasifikasi Morphological Process : 
a. Simple 
1. Erosi
2. Dilasi
3. Opening
4. Clossing

b. Advanced 
1. hit / miss transform
2. thickening
3. thining
4. skeletonisation

Erosi dan Opening memiliki fungsi untuk : 
1. memperkecil area region
2. region seperation
3. noise removal dan segmentasi (Asalkan ukuran noise tidak sama dengan ukuran kernel)
4. Selecting / removing bentuk tertentu
5. Edge detection dan boundary

Dilasi dan Clossing memiliki fungsi untuk : 
1. memperluas area region
2. region merging (menyatukan region)
3. Filling the hole
4. Edge detection / boundary

Di repository ini akan disediakan kode python yang sudah dibuat dan juga gambar source
