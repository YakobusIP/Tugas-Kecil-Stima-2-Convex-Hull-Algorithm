# Convex Hull Algorithm
## General Information
Program untuk mencari convex hull dari datasets menggunakan algoritma divide and conquer.
Program akan menerima dataset kemudian menjalankan fungsi **myConvexHull**.
Di dalam fungsi ini, program akan mencari titik ekstrem dari array dataset, kemudian akan ditarik garis diantara kedua titik.
Program kemudian akan mencari titik terjauh yang masih berada di atas atau di bawah garis tersebut.
Setelah menemukan titik tersebut, program kemudian membentuk sebuah garis baru yang menghubungkan titik tersebut ke titik awal, kemudian dilakukan rekursi untuk mencari titik yang masih berada di luar garis tersebut.
Program akan mengembalikan array of indexes yang dapat digunakan untuk memvisualisasi convex hull yang terbentuk.
Dataset yang dipakai di dalam program ini adalah **Iris** dan **Wine**

## Setup
1. Buka file **main.ipynb** menggunakan Visual Studio Code
2. Lakukan Run All di dalam file tersebut
3. Program akan memberikan output berupa grafik di bagian bawah file
4. Apabila ingin menggunakan dataset yang lain, pastikan dataset tersebut berisi array of points (array di dalam sebuah array)

## Created by:
Yakobus Iryanto Prasethio (13520104)