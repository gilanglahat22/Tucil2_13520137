# Tugas Kecil 2: Implementasi Convex Hull untuk Visualisasi Tes Linear Separability Dataset dengan Algoritma Divide and Conquer
### Tugas Kecil 2 IF2211 Strategi Algoritma

## Convex Hull
Convex Hull merupakan permasalahan yang klasik dalam bidang geometri komputasional. Convex Hull sendiri didefinisikan sebagai himpunan titik terkecil yang mengandung set of titik (koordinat) yang sifatnya convex. Suatu set of titik dikatakan convex apabila untuk sembarang 2 buah titik yang berada pada set tersebut, semua segmen garis yang berakhir pada dua titik tersebut terdapat pada set tersebut.

Adapun repository ini berisi implementasi dari library Convex Hull yang dapat digunakan untuk mencari Convex Hull pada suatu set of point.

## Requirement
Berikut adalah requirement yang dipakai untuk mengimplementasikan program ini, pastikan anda telah mendownload dan menginstall semua package berikut dengan cara pip install "nama package" di Command Prompt dan telah terinstall Python 3 di PC Anda.
1. numpy==1.22.2
2. pandas==1.4.1
3. matplotlib==3.5.1
4. scikit-learn==1.0.2
5. random

# Cara Penggunaan

## Opening
<img src="photo_readme/pembuka.jpg" />

Pertama-tama clone repository ini di local repository Anda dengan cara menjalankan perintah berikut

`git clone https://github.com/gilanglahat22/Tucil2_13520137.git`

## Untuk mengimplementasikan programmnya Anda bisa menjalankan file MainProgram.py ataupun main.ipynb
1. Untuk menjalankan file MainProgram.py anda bisa memasukkan command berikut di terminal

    ```shell
    python src/MainProgram.py
    ```
    atau dengan mengerunnya langsung di vscode (pastikan anda juga menginstall exstentionnya terlebih dahulu di vscode). 
    Adapun cara untuk mengerun file python di vscode dapat anda ikuti seperti tutorial pada link berikut ini : https://code.visualstudio.com/docs/python/python-tutorial
 
Setelah itu, untuk visualisasi di MainProgram.py, Anda bisa memvisualisasikan 5 dataset, yaitu Iris, Wine, Breast_Cancer, Diabetes, dan Digits. Dimana untuk memvisualisasikannya akan disajikan pilihan menu awal sebagai berikut.

<img src="photo_readme/MenuAwal.jpg" />

Pada pilihan menu tersebut, user diminta untuk memilih dataset (input disesuaikan dengan angka yang tercantum pada menu dataset tersebut) yang ingin divisualisasikan. Setelah itu, pengguna diminta untuk memasukkan kolom sumbu-x dan sumbu-y (kolom tersebut diambil darim masing-masing kolom dari tabel dataset yang akan diuji, dimana kolom dimulai dari 0 sampai jumlah maksimum kolom - 1) yang akan diuji serta memasukkan nama file dari hasil visualisasi plot yang akan diuji (cukup berikan namanya saja tanpa ekstensi apapun seperti .png, .txt, dll. Karena akan otomatis tersimpan dengan format PNG), sebagaimana gambar dibawah ini.

<img src="photo_readme/menulanjutan.jpg" />

Setelah langkah tadi, maka di terminal akan disajikan vertex dari convex hull yang dihasilkan serta akan muncul hasil plot dari convex hull di luar terminal, seperti gambar di bawah ini.

<img src="photo_readme/visualisasi_data.jpg" />

Setelah itu, anda diminta memasukkan command yang sama dengan command pada menu memilih dataset dan mengulangi langkah-langkah sebelumnya atau mengakhiri program dengan memasukkan command 0, seperti gambar di bawah ini.
 
 <img src="photo_readme/commandlanjutan.jpg" />

2. Untuk memvisualisasikan di file main.ipynb, pastikan anda sudah menginstall ipynb (jupyter notebook). Untuk visualisasinya anda, dapat menggunakan IDE jupiter_notebook ataupun Visual Studio Code. Untuk memvisualisasikannya di file main.ipynb, telah tersedia source code masing-masing test dataset pada file tersebut. Jadi, Anda tinggal memilih untuk mengerun source code mana yang anda ingin visualisasikan. Seperti gambar yang ditunjukkan di bawah ini.
<img src="photo_readme/contoh_code_ipynb.jpg" />
<img src="photo_readme/contoh_output_ipynb.jpg" />

Adapun cara mengerun file ipynb di vscode dapat anda ikuti seperti di link berikut ini : https://code.visualstudio.com/docs/datascience/jupyter-notebooks

## Penutup
<img src="photo_readme/penutup.jpg" />

# Struktur Repository
Adapun struktur dari repository ini adalah sebagai berikut.
1. docs => isinya laporan
2. src => isinya source code dari program
3. output => isinya hasil output dari visualisasi plot dataset yang telah disave dari MainProgram.py
4. photo_readme => isinya gambar yang diperlukan untuk readme

# Strutur Source Code
1. myConvexHull.py => isinya fungsi-fungsi untuk library Convex Hull
2. Visualisasi.py => isinya fungsi-fungsi untuk visualisasi data
3. MainProgram.py => isinya program utama
4. main.ipynb => isinya beberapa visualisasi dataset dalam bentuk ipynb

# Identitas Author
## Nama  : Muhammad Gilang Ramadhan (13520137).
## Email : gilanglahat22@gmail.com.

## Copyright By Muhammad Gilang Ramadhan
