# Array  
Array adalah tipe data list order yang dapat menyimpan tipe data apapun di dalamnya.  
Array dapat menyimpan tipe data String, Number, Boolean, dan lainnya.  

Contoh Array :  

</br>  

<img src="ar1.jpeg" width="200" height="100">  

</br>  

<img src="ar2.jpeg" width="200" height="100">  

</br>  

### Membuat Array  

<img src="ar3.jpeg" width="200" height="100">  

**Mengakses/Memanggil Array**  
Array pada javascript dihitung dari index data ke-0.  
Data pertama adalah index ke-0.  

<img src="arr4.jpeg" width="200" height="100">  

</br>

<img src="ar5.jpeg" width="200" height="100">  

<img src="ar6.jpeg" width="200" height="100">  

<img src="ar7.jpeg" width="200" height="100">  

<img src="ar8.jpeg" width="200" height="100">  

<img src="ar9.jpeg" width="200" height="100">  

</br>  

**Update Array**  

<img src="ar10.jpeg" width="200" height="100">  

**Const in Array**  
* Jika menggunakan let, kita dapat mengubah array  dengan array baru dan konten nilai yang ada di dalam array dengan nilai lain.  
* Const tidak bisa melakukan update data. Namun pada Array kita dapat melakukan update konten nilai di dalam array (mutable).  
* Yang tidak bisa adalah mengubah array dengan array yang baru jika menggunakan const.  

<img src="ar11.jpeg" width="200" height="100">  

<img src="ar12.jpeg" width="200" height="100">  

</br>

**Array Properties**  
Array memiliki 5 properti yang sering digunakan yaitu constructor, length, index, input, dan prototype.  
Properties adalah fitur yang sudah disediakan oleh Javascript untuk memudahkan developer.  

<img src="ar13.jpeg" width="200" height="100">  

>length akan mengembalikan nilai dari jumlah panjang data suatu array.  

</br>  

**Array Method**  
Array memiliki method atau biasa disebut built-in methods.  
Artinya Javascript sudah memudahkan kita dengan menyediakan function/method umum yang bisa kita gunakan.  

</br>

**Contoh Array Built-in Methods**  

<img src="ar14.jpeg" width="200" height="100">  

>.push() adalah method untuk menambahkan item  array pada urutan yang paling akhir.  

<img src="ar15.jpeg" width="200" height="100">  

>.pop() adalah method yang menghapus item array index terakhir.  

<img src="ar16.jpeg" width="200" height="100">  

>.shift() adalah method untuk menghapus item Array pada index pertama  

<img src="ar17.jpeg" width="200" height="100">  

>.unshift() adalah method untuk menambahkan item Array pada index pertama  

</br>

**Looping pada Array**  
Array memiliki built in methods untuk melakukan looping yaitu .map() dan .forEach()  

<img src="ar18.jpeg" width="200" height="100">  

>.forEach() adalah method untuk melakukan looping pada setiap elemen array.  

<img src="ar19.jpeg" width="200" height="100">  

>.map() melakukan perulangan/looping dengan membuat array baru.  

<img src="ar20.jpeg" width="200" height="100">  

<img src="ar21.jpeg" width="200" height="100">  

>Kita bisa lihat bahwa .map() dan forEach() sama-sama melakukan looping dan mengembalikan nilai baru dari operasi yang dilakukan.    

>Perbedaannya adalah .forEach tidak dapat membuat Array baru dari hasil operasi yang ada dalam looping  
>Lalu dari segi performance juga sangat jauh.  

<img src="ar22.jpeg" width="200" height="100">  

Jadi, gunakan .forEach() jika hanya memerlukan looping untuk menampilkan saja atau menyimpan ke database.  
Gunakan .map() jika akan melakukan operasi pada array seperti yang dapat mengubah nilai array sebelumnya.
