# Asycncronous  
Maksudnya adalah selama proses loading kita masih bisa scrolling.  

Bahasa pemograman Javascript :  
* JS single-thread  
* Non-Blocking  
* Asyncronous  

</br>  

### Single Thread  

Single thread hanya punya satu jalur proses sehingga setiap proses harus saling menunggu baru lanjut ke proses lain kayak dari console.log A ke B ke C harus saling menunggu.  
Lawannya adalah multi thread atau disebut juga banyak jalur.  

<img src="as1.jpeg" width="200" height="100">  

</br>

### Non Blocking  
artinya kalau proses memakan waktu lama, maka dia akan mempersilahkan proses yang lain berjalan.  
Kebalikannya blocking : menghalangi. 

<img src="as3.jpeg" width="200" height="100">  

</br>

### Asycncronous  
Syncronus : proses biasa.  
Proses yg dilakukan secara tidak berurutan.  
Semisal A panjang banget prosesnya, jd B diekseskusi, trus lanjut lagi si A nya.  

<img src="as2.jpeg" width="200" height="100">  

>Kalau proses kepanjangan maka diselak dulu  

>a=kayak dipecah-pecah  

</br>

**Sifat Proses JS**  

<img src="as5.jpeg" width="200" height="100">

</br> 

Proses js tersebut disebuat dengan proses yang concurent. Yang lawan katanya multitask.  
Proses yang panjang2 dipecah-pecah sama js  

<img src="as4.jpeg" width="200" height="100">  

</br> 

Syncronus konteknya urutan. Berarti dia dikerjakan berurutan.  
Sedangkan asyncronus konteksnya tidak terurut  

</br>

#### Cara menghandle asynchronus  
* callback  
* promises  
* async await  


<img src="as6.jpeg" width="200" height="100">   

<img src="as7.jpeg" width="200" height="100">  

>proses yg lama akan masuk ke callback queue  

Contoh :  

<img src="as8.jpeg" width="200" height="100">  

</br>

Set time out : untuk menjalankan proses selama 1 detik  

</br>  

<img src="as9.jpeg" width="200" height="100">  

>Dalam kasus ini meskipun B 0 set time nya tetapi dia akan masuk dlu call back queue, maka dia eksekusi C nya dulu.  

**Promises**  
Promises mempersentasekan dr kjadian, apakah kejadin berhasil atau gagal dr proses asyncronus.  

<img src="as10.jpeg" width="200" height="100">  

Contoh :  

<img src="as11.jpeg" width="200" height="100">  

<img src="as12.jpeg" width="200" height="100">  

>eksekusi proses  

<img src="as13.jpeg" width="200" height="100">  

>hasil di console  

</br>

Contoh lain tanpa set time  

<img src="as14.jpeg" width="200" height="100">    

<img src="as15.jpeg" width="200" height="100">  

>Teks  akan masuk ke then kemudian masuk ke result  

<img src="as16.jpeg" width="200" height="100">  

>reject kalau mau ditangkap menggunakan .catch

<img src="as17.jpeg" width="200" height="100">   

>hasil di console.log  

</br>

**Promise in Function**  
Membuat promise : new promise  
Ada resolve dan reject

<img src="as18.jpeg" width="200" height="100"> 