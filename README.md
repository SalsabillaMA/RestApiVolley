# RestApiVolley

- Hasil Aplikasi 

![alt text](DotaApi/app.gif)

![alt text](DotaApi/app.jpg)


# API

API atau Application Programming Interface adalah sebuah interface yang dapat menghubungkan aplikasi satu dengan aplikasi lainnya. Jadi, API berperan sebagai perantara antar berbagai aplikasi berbeda, baik dalam satu platform yang sama atau lintas platform.

- Manfaat API

1. Memudahkan Membangun Aplikasi yang Fungsional

2. Pengembangan Aplikasi Menjadi Lebih Efisien

3. Meringankan Beban Server

- Cara kerja API 

![alt text](MovieProject/api.jpg)

1. Aplikasi mengakses API

2. API Melakukan Request ke Server

3. Server Memberi Respon ke API

4. API Menyampaikan Respon ke Aplikasi

Penjelasan  lengkap dapat dilihat [disini.](https://www.niagahoster.co.id/blog/api-adalah/#:~:text=API%20atau%20Application%20Programming%20Interface,yang%20sama%20atau%20lintas%20platform.)


# Rest API

REST merupakan kependekan dari Representational State Transfer. REST ini merupakan web service yang bersifat stateless, jadi setiap kali request harus menyertakan semua data dan parameter dengan lengkap. REST ini bersifat client dan server. Client REST akan meminta sesuatu ke REST server, REST server kemudian akan memberikan response, client REST ini kemudian akan menampilkan hasilnya atau melakukan pemrosesan yang lain.

Prinsip kerja dari  REST API ini adalah client akan menganggap  server sebagai object yang dapat dibuat, diupdate, dihapus dan juga dibaca. Jadi pada pelaksanaannya akan ada create dengan request POST, update dengan request PUT atau PATCH, hapus dengan request DELETE, dan baca dengan request GET.

Penjelasan lebih lengkap dapat dilihat [disini.](https://www.proweb.co.id/articles/restful/restful-api.html)


# Retrofit

[Retrofit]( https://www.codepolitan.com/library-yang-wajib-kamu-coba-untuk-membuat-aplikasi-android-59b254b6d153c) merupakan library android yang dibuat oleh Square yang digunakan sebagai REST Client pada Android, yang pasti akan memudahkan kita. Karena kita tidak perlu lagi untuk membuat method-method sendiri untuk menggunakan REST Client API dari backend. Library ini menyediakan framework yang powerfull untuk authenticating dan berinteraksi dengan API dengan mengirimkan request menggunakan OkHTTP

# Volley 
[Volley]( https://www.codepolitan.com/library-yang-wajib-kamu-coba-untuk-membuat-aplikasi-android-59b254b6d153c) merupakan produk yang diperkenalkan oleh Google untuk mempermudah pertukaran data tanpa harus membuat deretan kode yang sangat panjang. Secara default volley menggunakan metode singkronisasi jadi tidak perlu membuat sebuah method atau fungsi yang menggunakan class asynctask.

Volley menawarkan manfaat-manfaat berikut:

-	Penjadwalan otomatis permintaan jaringan.

-	Beberapa koneksi jaringan serentak.

-	Caching respons disk dan memori transparan dengan koherensi cache HTTP standar.
-	Dukungan untuk pemrioritasan permintaan.
-	API permintaan pembatalan. Anda bisa membatalkan satu permintaan, atau menetapkan blok atau cakupan permintaan untuk dibatalkan.
-	Kemudahan kustomisasi, misalnya, untuk mencoba ulang dan backoff.
-	Pemesanan kuat yang memudahkan pengisian UI Anda dengan benar menggunakan data yang diambil secara asinkron dari jaringan.
-	Fitur proses debug dan penelusuran.

Penjelasan lebih lengkap dapat dilihat [disini.]( https://developer.android.com/training/volley?hl=id#:~:text=Volley%20adalah%20library%20HTTP%20yang,Penjadwalan%20otomatis%20permintaan%20jaringan.)

# Perbedaan Retrofit dan Volley
-	Mudah digunakan

Retrofit : Retrofit sangat mudah digunakan. Memungkinkan anda untuk memakai API ini dengan method sederhana dari java menggunakan interface.

Volley : Sedikit lebih rumit pada umumnya. Volley hanya mendukung beberapa response yaitu String,Image,JSONObject dan JSONArray.

-	Performan dan Caching

Retrofit : Caching harusnya bisa berjalan jika server anda menetapkan header control yang benar. Jika tidak ,atau anda melakukan sesuatu yang tidak biasa anda hanya bisa mengubah lapisan klien Http anda.

Volley: Volley memiliki mekasnisme chacing yang lebih rumit dan fleksibel, memanfaatkan untuk membuat caching bitmaps yang lebih besar.

•	POST requests + multipart uploads

Retrofit : memiliki dukungan penuh untuk permintaan POST dan upload file yang multi, dengan API Sweet untuk boot.

Volley : support POST request tetapi anda harus convert terlebih dahulu java objek yang kita buat menjadi JSONObject.

Sekian, Terimakasih:)

Salsabilla Maurettasya A




