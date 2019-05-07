# belajarC
Situs ini menampung file-file yang berguna dalam belajar bahasa C.
Khususnya untuk menunjang Buku "Pemrograman C untuk penyelesaian kasus"
oleh I Wayan Sudiarta dan Raja F. Akmaludin.

![image buku C](https://github.com/wayansudiarta/belajarC/blob/master/buku-cs.jpg)

bisa dibeli di Penerbit Periuk: https://penerbitperiuk.com/product/pemrograman-c-untuk-penyelesaian-kasus/

## Errata
Walaupun Kami telah berusaha mengurangi kesalahan dengan berbagai cara, kesalahan cetak (errata) pada Buku C tersebut di atas masih ada. Kesalahan kesalahan cetak adalah sebagai berikut.

1) Hal. 37, Tabel 5.3: pada operator kurangi satu, seharusnya a = a - 1
2) Hal. 57, Soal 4. seharusnya s=(x+y+z)/3
3) Hal. 93, Pada kode: seharusnya float g[2][3] = {{0, 1.3, 2}, { 3.1, 4, 5.2}};  
4) Hal. 96, Pada kode: seharusnya int g[2][3] = {{{1,2},{3,2}},{{3,4},{4,5}},{{5,6},{6,7}}};  
5) Hal. 111, pada ilustrasi pointer pada gambar v menunjuk d, seharusnya v = &d
6) Hal. 195- 
   ada kesalahan ketik pada semua makro IDX:
> #define IDX(i1,i2,n1,n2) ((i1)*(n2)+(i2))
   
> #define IDX(i1,i2,i3,n1,n2,n3) (((i1)*(n2)+(i2))*(n3) + (i3))
   
> #define IDX(a1,a2,a3,a4,a5,a6,n1,n2,n3,n4,n5,n6) ((((((a1)*(n2)+(a2))*(n3)+(a3))*(n4)+(a4))*(n5)+(a5))*(n6)+(a6))
   
## Instalasi MinGW
Silahkan mengunjungi situs ini: https://github.com/wayansudiarta/minGW
