Nama : Mochammad Fajar Maulana<br>
NPM  : 41155050210004<br>
Kelas : INF A1

Tugas 5

A.	K-Nearest Neighbours (KNN). Lakukan praktik dari https://youtu.be/4zARMcgc7hA?si=x6RoHQXFF4NY76X8 , buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini:<br>

1.	Persiapan sample dataset<br>
![Capture1](https://github.com/user-attachments/assets/1a50a103-5dfa-40bc-9f0d-7aeb27b62879)

2.	Visualisasi dataset<br>
![Capture2](https://github.com/user-attachments/assets/82ad0c6c-3621-4d0c-84d3-5b7de7e10d3d)

3.	Pengantar classification dengan K-Nearest Neighbours | KNN<br>
Algoritma K-Nearest Neighbor (KNN) adalah algoritma machine learning yang bersifat non-parametric dan lazy learning. Metode yang bersifat non-parametric memiliki makna bahwa metode tersebut tidak membuat asumsi apa pun tentang distribusi data yang mendasarinya. Dengan kata lain, tidak ada jumlah parameter atau estimasi parameter yang tetap dalam model, terlepas data tersebut berukuran kecil ataupun besar.
Algoritma non-parametric seperti KNN menggunakan sejumlah parameter yang fleksibel, dan jumlah parameter seringkali bertambah seiring data yang semakin banyak. Algoritma non-parametric secara komputasi lebih lambat, tetapi membuat lebih sedikit asumsi tentang data. Algoritma KNN juga bersifat lazy learning, yang artinya tidak menggunakan titik data training untuk membuat model. Singkatnya pada algoritma KNN tidak ada fase training, kalaupun ada juga sangat minim.

4.	Preprocessing dataset dengan Label Binarizer<br>
![Capture3](https://github.com/user-attachments/assets/4b25347f-171c-47ce-b562-34cd9f593aa9) <br>
![Capture4](https://github.com/user-attachments/assets/7a177355-cc55-4798-abca-2583757ec691)

5.	Training KNN Classification Model<br>
 

6.	Prediksi dengan KNN Classification Model
 

7.	Visualisasi Nearest Neighbours
 

8.	Kalkulasi jarak dengan Euclidean Distance
 

9.	Evaluasi KNN Classification Model | Persiapan testing set
 

10.	Evaluasi model dengan accuracy score
 

11.	Evaluasi model dengan precision score
 

12.	Evaluasi model dengan recall score
 

13.	Evaluasi model dengan F1 score
 

14.	Evaluasi model dengan classification report
 

15.	Evaluasi model dengan Mathews Correlation Coefficient
 

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
 
 
