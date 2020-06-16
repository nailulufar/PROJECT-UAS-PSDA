# PROJECT-UAS-PSDA
Nama  : Lulu Nailufar

NIM   : 1910512013

Kelas : A

Mata Kuliah: Praktikum Struktur Data dan Algoritma

Dosen Pengampu: Dr. Achmad Solichin, S.Kom, M.T.I

E-mail: nailulufar@gmail.com

# DESKRIPSI UMUM PROJECT
Project ini dibuat sebagai pengganti UAS pada mata kuliah Praktikum Struktur Data dan Algoritma. Program ini merupakan Penerapan dari Binary Search Tree (BST) yang ditulis menggunakan bahasa C++ dengan spesifikasi sebagai berikut:      
  1. Program dapat berupa tampilan GUI atau menu berbasis console / terminal.
  2. Data berupa bilangan bulat positif (integer).
  3. Program minimal terdiri dari sub-modul (menu/fungsi) untuk:
      
       a. Menginsert bilangan baru (penempatan bilangan dalam Tree dilakukan secara otomatis sesuai dengan aturan sebuah BST)
      
       b. Menampilkan seluruh isi BST, baik secara preorder, postorder maupun inorder.
       
       c. Menginput suatu bilangan dan mencarinya ke dalam BST. Jika bilangan ditemukan, tampilkan perkataan “DITEMUKAN” dan tampilkan 
         juga simpul-simpul yang dilewati untuk menemukan bilangan tersebut. Jika tidak ditemukan, tampilkan perkataan “TIDAK DITEMUKAN”
      
       d. Menghapus suatu bilangan dari BST. Bilangan diinput oleh user. Jika ditemukan, maka bilangan dihapus dari BST (jangan sampai
         proses penghapusan memutus/merusak struktur BST). Jika tidak ditemukan, tampilkan bahwa bilangan tidak ada dalam BST.
      
       e. Menampilkan nilai terbesar dan terkecil dari BST yang terbentuk.
      
       f. Menghapus seluruh isi BST (reset BST).
  4. Fungsi main berfungsi untuk mengatur menu yang memanggil sub-modul / menu yang disediakan program.

# FITUR-FITUR PROGRAM
Program ini terdiri dari beberapa sub-modul (menu/fungsi):
  
  Pilihan 1 berfungsi untuk insert bilangan baru ke dalam BST.
  
  Pilihan 2 berfungsi untuk mencetak atau menampilkan BST secara Pre-Order.
  
  Pilihan 3 berfungsi untuk mencetak atau menampilkan BST secara In-Order.
  
  Pilihan 4 berfungsi untuk mencetak atau menampilkan BST secara Post-Order.
  
  Pilihan 5 berfungsi untuk menghapus node atau bilangan dari BST. Bilangan diinput oleh user. Jika ditemukan, maka 
  bilangan dihapus dari BST (jangan sampai proses penghapusan memutus/merusak struktur BST). Jika tidak ditemukan, tampilkan bahwa 
  bilangan tidak ada dalam BST.
  
  Pilihan 6 berfungsi untuk Menghapus seluruh isi BST (reset BST).
  
  Pilihan 7 berfungsi untuk menginput suatu bilangan dan mencarinya ke dalam BST. Jika bilangan ditemukan, tampilkan perkataan 
  “DITEMUKAN”   dan tampilkan juga simpul-simpul yang dilewati untuk menemukan bilangan tersebut. Jika tidak ditemukan, tampilkan 
  perkataan “TIDAK DITEMUKAN".
  
  Pilihan 8 berfungsi untuk menghitung Node pada BST.
  
  Pilihan 9 berfungsi untuk menghitung Kedalaman BST.
  
  Pilihan A berfungsi untuk menampilkan nilai terbesar dan terkecil dari BST yang terbentuk.
  
  Pilihan x berfungsi untuk Keluar dari program
  
# CARA PENGGUNAAN PROGRAM (INPUT/OUTPUT)
Program ini berbentuk menu yang bisa dipilih, terdapat 11 pilihan pada program yang sudah dijelaskan pada bagian fitur program. 

Cara menggunakan program ini hanya cukup memasukkan angka menu yang ingin dipilih.
![0Tampilan Awal Program](https://user-images.githubusercontent.com/66952269/84756152-a1ce0e80-afec-11ea-8eb7-8685a6630ae1.png)


Pilih 1 untuk insert bilangan baru. Misalnya jika ingin menambahkan bilangan/node baru, masukkan angka 50 lalu tekan enter. Yang terjadi 
adalah bilangan/node bernilai 50 dijadikan sebagai root dari pohon.
![1  Tampilan Insert Bilangan](https://user-images.githubusercontent.com/66952269/84756459-05f0d280-afed-11ea-834a-94d834456bc9.png)

Pilih 2 untuk menampilkan/mencetak BST secara Pre-Order
![2  Tampilan Pre-Order](https://user-images.githubusercontent.com/66952269/84756467-07ba9600-afed-11ea-92fe-3f417ca46391.png)

Pilih 3 untuk menampilkan/mencetak BST secara In-Order
![3  Tampilan In-Order](https://user-images.githubusercontent.com/66952269/84756469-08ebc300-afed-11ea-8962-35951975ef6b.png)

Pilih 4 untuk menampilkan/mencetak BST secara Post-Order
![4  Tampilan Post-Order](https://user-images.githubusercontent.com/66952269/84756475-0a1cf000-afed-11ea-8173-a9c4992c7613.png)

Pilih 5 untuk menghapus bilangan/node dari BST. Misalnya jika ingin menghapus bilangan 28, maka masukkan angka 28 terlebih dahulu lalu tekan enter. Maka yang terjadi adalah bilangan 28 telah dihapus dari BST.

  Apabila Node Ditemukan
  ![5  Tampilan Menghapus Node Bila Node Ditemukan](https://user-images.githubusercontent.com/66952269/84758223-5ec16a80-afef-11ea-8962-9af37613f62a.png)
  
  Apabila Node Tidak Ditemukan
 ![5  Tampilan Menghapus Node Bila Node Tidak Ditemukan](https://user-images.githubusercontent.com/66952269/84758233-6123c480-afef-11ea-8b8e-55adbe7239b1.png)

Pilihan 6 untuk Menghapus seluruh isi BST (reset BST).
![6  Tampilan Reset (Menghapus Seluruh Isi BST)](https://user-images.githubusercontent.com/66952269/84756482-0be6b380-afed-11ea-8ca2-d360eacc0084.png)

Pilihan 7 berfungsi untuk menginput suatu bilangan dan mencarinya ke dalam BST. Jika bilangan ditemukan, tampilkan perkataan 
“DITEMUKAN”   dan tampilkan juga simpul-simpul yang dilewati untuk menemukan bilangan tersebut. Jika tidak ditemukan, tampilkan 
perkataan “TIDAK DITEMUKAN".

Apabila Node Ditemukan
  ![7  Tampilan Pencarian Node yang Ditemukan](https://user-images.githubusercontent.com/66952269/84756486-0d17e080-afed-11ea-80a2-b443c25849eb.png)
  
  Apabila Node Tidak Ditemukan
  ![7  Tampilan Pencarian Node yang Tidak Ditemukan](https://user-images.githubusercontent.com/66952269/84756492-1012d100-afed-11ea-9639-8e4528c125fc.png)

Pilihan 8 untuk menghitung Node pada BST. Misalnya node yang terdapat pada BST ada 7 node.
![8  Tampilan Menghitung Jumlah Node](https://user-images.githubusercontent.com/66952269/84756494-1143fe00-afed-11ea-9ea1-5e67f6bf21d9.png)

Pilihan 9 untuk menghitung Kedalaman BST. Misalnya kedalaman BST adalah 2
![9  Tampilan Kedalaman Node](https://user-images.githubusercontent.com/66952269/84756496-12752b00-afed-11ea-80bf-1605e2d7f7be.png)

Pilihan A  untuk menampilkan nilai terbesar dan terkecil dari BST yang terbentuk. Misalnya node yang terdapat dalam BST ada 50, 22, 80, 34,66, 90, 17. Saat memilih pilihan A maka muncul bahwa nilai tertinggi adalah 90 dan nilai terendah adalah 17.
![A  Tampilan Nilai Terbesar dan Terkecil](https://user-images.githubusercontent.com/66952269/84756499-13a65800-afed-11ea-8238-d6a1e1e48d66.png)

Pilihan x untuk Keluar dari program
![x  Tampilan Keluar](https://user-images.githubusercontent.com/66952269/84756515-1608b200-afed-11ea-88e7-68e47d895c7a.png)
