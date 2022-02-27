# Tugas Kecil 2: Implementasi Convex Hull untuk Visualisasi Tes Linear Separability Dataset dengan Algoritma Divide and Conquer
### Tugas Kecil 2 IF2211 Strategi Algoritma

## Convex Hull
Convex Hull merupakan permasalahan yang klasik dalam bidang geometri komputasional. Convex Hull sendiri didefinisikan sebagai himpunan titik terkecil yang mengandung set of titik (koordinat) yang sifatnya convex. Suatu set of titik dikatakan convex apabila untuk sembarang 2 buah titik yang berada pada set tersebut, semua segmen garis yang berakhir pada dua titik tersebut terdapat pada set tersebut.

Adapun repository ini berisi implementasi dari library Convex Hull yang dapat digunakan untuk mencari Convex Hull pada suatu set of point.

## Requirement
Berikut adalah requirement yang dipakai untuk mengimplementasikan program ini, pastikan anda telah mendownload dan menginstall semua package berikut.
1. Numpy Versi 1.22.2
2. Pandas Versi 1.4.1
3. Matplotlib Versi 3.5.1
4. scikit-learn Versi 1.0.2

# Cara Penggunaan
[image](https://user-images.githubusercontent.com/80266785/155902168-ab6271d3-7676-4613-80a6-c8a593dd9bdb.png)

## Untuk file ConvexHull.py berisi fungsi-fungsi untuk library Convex Hull dan fungsi-fungsi untuk visualisasi data
## Untuk mengimplementasikan programmnya Anda bisa menjalankan file MainProgram.py ataupun main.ipynb
1. Untuk visualisasi di MainProgram.py anda bisa memvisualisasikan 5 dataset, yaitu Iris, Wine, Breast_Cancer, Diabetes, dan Digit. Dimana untuk memvisualisasikannya akan disajikan pilihan menu sebagai berikut.
 [image](https://user-images.githubusercontent.com/80266785/155901503-eb055d57-b6a9-4f48-8c21-74d1aba3d96c.png)
 Pada pilihan menu tersebut, user diminta untuk memilih dataset yang ingin divisualisasikan. Setelah itu, pengguna disuruh untuk memasukkan kolom sumbu-x dan sumbu-y yang akan diuji serta memasukkan namafile dari hasil visualisasi plot yang akan diuji (cukup berikan namanya saja tanpa ekstensi apapun seperti .png, .txt, dll. Karena akan otomatis tersimpan dengan format PNG), sebagaimana gambar dibawah ini.
 [image](https://user-images.githubusercontent.com/80266785/155901629-6d5b31af-90a1-4e91-810d-869a3a0445f1.png)
 Setelah langkah tadi, maka di terminal akan disajikan vertex dari convex hull yang dihasilkan serta akan muncul hasil plot dari convex hull di luar terminal.
 Setelah itu, anda diminta memasukkan command yang sama dengan command pada menu memilih dataset dan mengulangi langkah-langkah sebelumnya atau mengakhiri program dengan memasukkan command 0.
2. Untuk memvisualisasikan di file main.ipynb, pastikan anda sudah menginstall ipynb (jupyter notebook). Untuk visualisasinya anda, dapat menggunakan IDE jupiter_notebook ataupun Visual Studio Code. Untuk memvisualisasikannya di file main.ipynb, telah tersedia source code masing-masing test dataset pada file tersebut. Jadi, Anda tinggal memilih untuk mengerun source code mana yang anda ingin visualisasikan. Seperti gambar yang ditunjukkan di bawah ini.
[image](https://user-images.githubusercontent.com/80266785/155901927-5ef90ca5-e959-47bb-9ccb-c534d325adba.png)
[image](https://user-images.githubusercontent.com/80266785/155901938-74ceb373-a8e1-4a22-829b-c1a12a406949.png)

[image](https://user-images.githubusercontent.com/80266785/155902200-4e8089e4-2f04-4104-a5b7-2cee09791e84.png)

## Identitas Author :
Nama  : Muhammad Gilang Ramadhan (13520137)
Email : gilanglahat22@gmail.com 

## Copyright By Muhammad Gilang Ramadhan
