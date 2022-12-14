## **(08) Javascript Refreshment**

### A. Pengertian Javascript

Javascript adalah sebuah bahasa pemrograman script tingkat tinggi yang sifatnya dinamis

### B. Variable dalam Javascript

> - Var, merupakan variable yang bisa dideklarasi tanpa value, redeclaration, dan reassignment.
> - Let, merupakan variable yang bisa dideklarasi tanpa value, tidak bisa redeclaration, dan bisa reassignment.
> - Const, merupakan variable yang harus dideklarasi dengan value, tidak bisa redeclaration, dan tidak bisa reassignment.

Scoop berguna untuk menentukan dimana variable yang telah dibuat dapat diakses. Terdapat 3 jenis Scoop, yaitu :

> - Global Scoop, variable dapat diakses dimana saja
> - Function Scoop, variable dapat diakses di sebuah function
> - Block Scoop, variable dapat diakses di sebuah block {}

Hoisting merupakan variable yang dapat diakses sebelum dideklarasi, contohnya adalah variable Var selain Var tidak bisa hoisting.
Var saat ini jarang digunakan karena bisa saja menimbulkan suatu masalah hoisting ini.

### C. Destructuring & Method dalam Javascript

Destructuring adalah suatu cara untuk menyalin array atau object ke dalam variable baru.
Method adalah fungsi yang dibuat sesederhana mungkin untuk menjalankan program sesuai kegunaan.
Contoh Method :

> - Concat
> - Map
> - Foreach
> - Slice
> - Filter
> - Reduce

### D. Control Flow & Function dalam Javascript

Control flow merupakan alur dalam pengeksekusian suatu kode program, terdapat 2 Control Flow, yaitu :
Perulangan, perulangan ini dibagi menjadi 3 For, While, dan Do While.
Percabangan, percabangan ini dibagi menjadi beberapa yaitu, If Else, Switch, Block, Try Catch, Break, Continue, dan Throw

Function merupakan suatu kode program yang telah diatur sedemikian rupa yang menjalakan sebuah aksi dan dapat digunakan berulang kali.
Terdapat 2 Function yaitu :

> - Expression Function
> - Arrow Function

### E. Async Await & Document Object Model (DOM)

Async - Await

1.  Synchronous, yaitu suatu kode program yang dijalankan satu persatu sesuai urutan kode yang ditulis.
2.  Asynchronous, kode program yang dijalankan tidak selalu berdasarkan urutan kode, melainkan waktu proses.
3.  Callback merupakan fungsi yang dijalankan setelah fungsi lain selesai jalan.
4.  Promise, memberikan suatu representasi dari berhasil dan tidaknya suatu event yang asynchronous.
5.  Async Function, merupakan suatu function yang dijalankan sesuai waktu prosesnya dan memberikan suatu promise return valuenya, tapi ditulis secara synchronous.
6.  Await, suatu keyword dalam async func yang menghentikan jalan program sambil menunggu promise selesai.

Document Object Model

DOM atau Document Object Model adalah suatu API untuk HTML yang merepresentasikan halaman web menjadi suatu object.
DOM Selection Model dibagi menjadi :

1.  getElementByID(), untuk Element
2.  getElementByTagName(), untuk HTMLCollection
3.  getElementByClassName(), untuk HTMLCollection
4.  querySelector(), untuk Element
5.  querySelectorAll(), nodeList

DOM Manipulation dibagi menjadi :

1.  element.innerHTML, untuk merubah isi tag yang diseleksi
2.  element.style.propertCSS, untuk merubah style tag yang diseleksi
3.  element.setAttribute(), untuk memanipulasi attribute yang diseleksi
4.  element.classList.Add(), untuk memanipulasi class yang diseleksi

DOM Event dibagi menjadi :

1.  onCLick
2.  onChange
3.  onBlur
4.  onMouseOver
5.  onMouseOut
6.  onCopy
