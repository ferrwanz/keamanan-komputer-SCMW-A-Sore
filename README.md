## Setup
1. Buka git bash
2. CD ke directory folder yang anda inginkan
3. Git clone dengan command ```git clone https://github.com/ferrwanz/keamanan-komputer-SCMW-A-Sore.git ```
4. cd ke dalam folder ```cd keamanan-komputer-SCMW-A-Sore```
5. Edit file README.md dengan editor anda. Copy text dari Nama - NIM sampai "- - - -" kemudian paste kan dibawahnya (Ingat untuk enter 1 line sebelum "- - - -". 1 line kosong adalah enter dalam file .md ini). Cukup edit pada bagian Nama - NIM, Nama Layer, dan kata - kata setelah 'titik-dua' (: )
6. Siap edit, git add dengan command ```git add README.md```
7. Commit sesuai dengan deskripsi anda ```git commit -m "Deskripsi yang sesuai kerjaan anda"```
8. Silahkan push ```git push origin master```. Masukkan username dan password anda.
9. Bila ada conflict ketika push. Silahkan git pull dulu dengan command ```git pull origin master```
10. Bila ada conflict dalam pull, silahkan git merge ```git merge```
11. Apabila bingung dengan git merge, maka pakai branch baru saja dengan command ```git checkout -b new-branch-name```. Nanti akan saya merge-kan.
12. Git susah? Tidak. Hanya kurang pengalaman memakai saja.

- - - -

## Name - NIM Here

### 1. Layer Name Here

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Finger Of Death
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: C atau I atau A (Terserah)
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Memberikan magic damage terhadap lawan sebesar 800 damage
* Counter Measure/Prevent &nbsp;: Memakai BKB, Pipe of Insight

### 2. Layer Name Here

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Kuota Habis
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: C atau I atau A (Terserah)
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Tidak bisa menghubungkan client ke server untuk bermain DotA
* Counter Measure/Prevent &nbsp;: Connect WiFi / Hotspot teman or tempat publik, Beli Kuota Bung !

- - - - 

## Denny Ho - 14.111.0191

### 1. Application Layer

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Cross-Site_Request_Forgery
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: C
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Sebuah penyerangan yang memaksa user untuk submit data ke website yang user sedang login misalnya ketika login pada website perbankan user dipaksa untuk transfer uang. Cross site request forgery dapat dipadukan dengan XSS (cross site scripting) yang melakukan submit data otomatis dengan script yang diberi.
* Counter Measure/Prevent &nbsp;: Menggunakan CSRF Token

### 2. Layer Name Here

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Kuota Habis
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: C atau I atau A (Terserah)
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Tidak bisa menghubungkan client ke server untuk bermain DotA
* Counter Measure/Prevent &nbsp;: Connect WiFi / Hotspot teman or tempat publik, Beli Kuota Bung !

- - - - 

## Willy - 14.111.0311

### 1. Transport Layer

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Session Hijacking 
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: C
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Salah satu metode dalam session hijacking adalah  : Session fixation , dimana penyerang ini menempatkan suatu session-id yang diketahui si target lalu si penyerang hanya menunggu target untuk melakukan akses login sehingga penyerang ini mengetahui segala info yang dimiliki oleh si target saat login.
* Counter Measure/Prevent &nbsp;:
    1. Menggunakan Enskripsi pada jalur data diantara kedua pihak yang berkomunikasi dengan menggunakan SSL/TLS. 
    2. Menggunakan sebuah angka random string pada session.


### 2. Layer Name Here

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : Kuota Habis
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: C atau I atau A (Terserah)
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Tidak bisa menghubungkan client ke server untuk bermain DotA
* Counter Measure/Prevent &nbsp;: Connect WiFi / Hotspot teman or tempat publik, Beli Kuota Bung !

- - - - 

## Kenedy Lukito - 14.111.0043

### 1. Data Link Layer

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : MAC Address alteration and MAC Flooding attacks
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: Availability
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Perangkat jaringan yang terkena serangan MAC flooding, semua resource CPU akan seperti tersedot. Dengan MAC Address alteration, laju lalu lintas jaringan dapat diubah dengan mudah. Serangan MAC Flooding menyebabkan terjadinya overflow pada MAC table di switch. Switch akan melambat dan bisa menyebabkan crash
* Counter Measure/Prevent &nbsp;: Dengan mengunakan fungsi dari por-security yang disediakan oleh Cisco ISO

### 2. Transport Layer

* Nama Penyerangan &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; : TCP,UDP flooding attacks
* Penyerangan Terhadap &nbsp; &nbsp; &nbsp;: Availability
* Deskripsi Penyerangan &nbsp; &nbsp; &nbsp;: Ancaman ini menyerang dengan mengirimkan traffic UDP yang sangat banyak ke target tertentu atau melakukan request TCP 3 way handshaking setelah mengganti IP addressnya. Akibatnya akan menyebabkan kerusakan pada perangkat networking dan server akan mengalami kelebihan muatan.
* Counter Measure/Prevent &nbsp;: Dengan menggunakan SYN cookies

- - - - 