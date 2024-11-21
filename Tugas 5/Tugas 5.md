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
![Capture5](https://github.com/user-attachments/assets/473e11f6-70e0-4f98-964d-2e1a4665c284)
 
6.	Prediksi dengan KNN Classification Model<br>
![Capture6](https://github.com/user-attachments/assets/051a4347-126c-45f6-857b-c4b97f51951f)

7.	Visualisasi Nearest Neighbours<br>
![Capture7](https://github.com/user-attachments/assets/e703affb-d9e6-488d-aa45-49f371674877)

8.	Kalkulasi jarak dengan Euclidean Distance<br>
![Capture8](https://github.com/user-attachments/assets/70f9ad6c-0a8b-404a-9ac7-f89856f879b6)

9.	Evaluasi KNN Classification Model | Persiapan testing set<br>
![Capture9](https://github.com/user-attachments/assets/0cc51bbc-d338-4874-914d-a7cca164c817)

10.	Evaluasi model dengan accuracy score<br>
![Capture10](https://github.com/user-attachments/assets/84e65db5-2e58-4568-917b-8694054a49f8)

11.	Evaluasi model dengan precision score<br>
![Capture11](https://github.com/user-attachments/assets/2d4952c0-b373-4993-b9f2-e45070a59795)

12.	Evaluasi model dengan recall score<br>
![Capture12](https://github.com/user-attachments/assets/2adad14c-f0b9-4c7f-ae4b-075f71006a11)

13.	Evaluasi model dengan F1 score<br>
![image](https://github.com/user-attachments/assets/3ab07ca8-9bd1-4b4e-b216-0ab3d6326f7d)

14.	Evaluasi model dengan classification report<br>
![Capture14](https://github.com/user-attachments/assets/5fc0faa7-7e1f-47de-80d0-602a241b22f6)

15.	Evaluasi model dengan Mathews Correlation Coefficient<br>
![Capture15](https://github.com/user-attachments/assets/d563c7bb-081d-4b2f-9476-e4c13249498b)

B.	Support Vector Machine (SVM). Lakukan praktik dari https://youtu.be/z69XYXpvVrE?si=KR_hDSlwjGIMcT0w , buat screenshot dengan nama kalian pada coding, kumpulkan dalam bentuk pdf, dari kegiatan ini:
1.	Pengenalan Decision Boundary & Hyperplane<br>
![Capture16](https://github.com/user-attachments/assets/7aafd092-971f-452b-b326-986794e5b4f0) <br>
Decision boundary adalah garis yang membagi jalan atau margin menjadi 2 bagian yang sama besar. Hyperplane adalah bidang yang memisahkan kedua kelas, sedangkan margin adalah lebar 'jalan' yang membagi kedua kelas.

2.	Pengenalan Support Vector & Maximum Margin<br>
![Capture17](https://github.com/user-attachments/assets/f35cf4a8-65bb-4544-a764-095de6ba0078) <br>
Maximum margin adalah model linier yang memisahkan kelas dalam satu set data dengan jarak yang paling jauh dari cangkang cembung kelas. Pemisahan ini juga harus tegak lurus terhadap garis terpendek yang menghubungkan kelas tersebut.

3.	Pengenalan kondisi Linearly Inseparable dan Kernel Tricks<br>
![Capture18](https://github.com/user-attachments/assets/6a9a00a5-4adc-42c5-8256-01e71e16a0cd) <br>
Dua set titik data dalam ruang dua dimensi dikatakan dapat dipisahkan secara linear jika keduanya dapat dipisahkan sepenuhnya oleh satu garis lurus . Secara umum, dua kelompok titik data dapat dipisahkan dalam ruang n-dimensi jika keduanya dapat dipisahkan oleh bidang hiper n-1 dimensi.
Trik kernel adalah teknik hebat yang memungkinkan SVM memecahkan masalah klasifikasi non-linier dengan memetakan data input secara implisit ke ruang fitur berdimensi lebih tinggi . Dengan demikian, kita dapat menemukan hiperbidang yang memisahkan kelas data yang berbeda.

4.	Pengenalan MNIST Handwritten Digits Dataset<br>
![Capture19](https://github.com/user-attachments/assets/c9b86907-1ce3-456b-92cb-48cdd8320a24) <br>
![Capture20](https://github.com/user-attachments/assets/beb661c5-cb38-4fed-a18a-bebdbb017865) <br>
 
5.	Klasifikasi dengan Support Vector Classifier | SVC<br>
![Capture21](https://github.com/user-attachments/assets/1e3cc9af-a530-4a0e-841c-e32a1ae79a4e)

6.	Hyperparameter Tuning dengan Grid Search<br>
![Capture22](https://github.com/user-attachments/assets/d432ec3a-74f1-43cc-ba27-0a1adaff2130) <br>
![Capture23](https://github.com/user-attachments/assets/4a6bb7b6-2227-4166-b494-1efee6411544) <br>
 
7.	Evaluasi Model<br>
![Capture24](https://github.com/user-attachments/assets/67686fd8-03e7-4feb-b1ad-8cbdc497dc07)
 
 
