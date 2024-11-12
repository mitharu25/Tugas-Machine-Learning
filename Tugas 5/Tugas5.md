Nama : Mochammad Fajar Maulana<br>
NPM  : 41155050210004<br>
Kelas : INF A1

Tugas 5

A.	K-Nearest Neighbours (KNN). Lakukan praktik dari https://youtu.be/4zARMcgc7hA?si=x6RoHQXFF4NY76X8 , buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini:<br>
1.	Persiapan sample dataset

![Capture1](https://github.com/user-attachments/assets/1a50a103-5dfa-40bc-9f0d-7aeb27b62879)

3.	Visualisasi dataset
 

4.	Pengantar classification dengan K-Nearest Neighbours | KNN
Algoritma K-Nearest Neighbor (KNN) adalah algoritma machine learning yang bersifat non-parametric dan lazy learning. Metode yang bersifat non-parametric memiliki makna bahwa metode tersebut tidak membuat asumsi apa pun tentang distribusi data yang mendasarinya. Dengan kata lain, tidak ada jumlah parameter atau estimasi parameter yang tetap dalam model, terlepas data tersebut berukuran kecil ataupun besar.
Algoritma non-parametric seperti KNN menggunakan sejumlah parameter yang fleksibel, dan jumlah parameter seringkali bertambah seiring data yang semakin banyak. Algoritma non-parametric secara komputasi lebih lambat, tetapi membuat lebih sedikit asumsi tentang data. Algoritma KNN juga bersifat lazy learning, yang artinya tidak menggunakan titik data training untuk membuat model. Singkatnya pada algoritma KNN tidak ada fase training, kalaupun ada juga sangat minim.

5.	Preprocessing dataset dengan Label Binarizer
 
 
 

6.	Training KNN Classification Model
 

7.	Prediksi dengan KNN Classification Model
 

8.	Visualisasi Nearest Neighbours
 

9.	Kalkulasi jarak dengan Euclidean Distance
 

10.	Evaluasi KNN Classification Model | Persiapan testing set
 

11.	Evaluasi model dengan accuracy score
 

12.	Evaluasi model dengan precision score
 

13.	Evaluasi model dengan recall score
 

14.	Evaluasi model dengan F1 score
 

15.	Evaluasi model dengan classification report
 

16.	Evaluasi model dengan Mathews Correlation Coefficient
 

B.	Support Vector Machine (SVM). Lakukan praktik dari https://youtu.be/z69XYXpvVrE?si=KR_hDSlwjGIMcT0w , buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini:
1.	Pengenalan Decision Boundary & Hyperplane
 
Decision boundary adalah garis yang membagi jalan atau margin menjadi 2 bagian yang sama besar. Hyperplane adalah bidang yang memisahkan kedua kelas, sedangkan margin adalah lebar 'jalan' yang membagi kedua kelas.

2.	Pengenalan Support Vector & Maximum Margin
 
Maximum margin adalah model linier yang memisahkan kelas dalam satu set data dengan jarak yang paling jauh dari cangkang cembung kelas. Pemisahan ini juga harus tegak lurus terhadap garis terpendek yang menghubungkan kelas tersebut.

3.	Pengenalan kondisi Linearly Inseparable dan Kernel Tricks
 
Dua set titik data dalam ruang dua dimensi dikatakan dapat dipisahkan secara linear jika keduanya dapat dipisahkan sepenuhnya oleh satu garis lurus . Secara umum, dua kelompok titik data dapat dipisahkan dalam ruang n-dimensi jika keduanya dapat dipisahkan oleh bidang hiper n-1 dimensi.
Trik kernel adalah teknik hebat yang memungkinkan SVM memecahkan masalah klasifikasi non-linier dengan memetakan data input secara implisit ke ruang fitur berdimensi lebih tinggi . Dengan demikian, kita dapat menemukan hiperbidang yang memisahkan kelas data yang berbeda.

4.	Pengenalan MNIST Handwritten Digits Dataset
 
 

5.	Klasifikasi dengan Support Vector Classifier | SVC
 

6.	Hyperparameter Tuning dengan Grid Search
 
 
 
 

7.	Evaluasi Model
 
 
