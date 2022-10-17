# Tutorial cara penggunaan git

Pertama kalian harus instal terlebih dahulu software Git Lalu kalian bisa buka software tersebut

1.Login Git
Langkah pertama kalian adalah memasukan username dengan menggunakan perintah

$ git config --global user.name "UsernameAnda"

lalu kalian tambahkan juga email dengan menggunakan perintah

$ git config --global user.email "email anda"


![Gambar](screenshot/ss1.png)


2.Login Github

Langkah kedua kalian bisa login ke dalam website github, Setelah kalian login akan muncul tampilan dashboard dari github tersebut


![SharedScreenshot2](https://user-images.githubusercontent.com/115879313/196106179-070139c5-4394-431c-a1e3-63a11a3c8658.png)




3.Buat Repository

Setelah berhasil login ke GitHub, Anda bisa mulai membuat repository. Klik tombol New pada menu Repositories untuk membuat repository baru.


![SharedScreenshot3](https://user-images.githubusercontent.com/115879313/196106343-005e36cf-b9e8-447e-84c3-43521400ee0a.png)


Kemudian kaliam akan diarahkan pada halaman untuk membuat repository baru seperti gambar di bawah ini


![SharedScreenshot4](https://user-images.githubusercontent.com/115879313/196106564-4e5ec664-cb46-4924-93cb-3ca57c614a8f.png)



4.Buat Folder

Lalu kalian buat folder di localdisk koomputer kalian


![SharedScreenshot13](https://user-images.githubusercontent.com/115879313/196110314-3f3b6d4b-6d08-44d5-aef9-e7184570cc27.png)


5.jika sudah kalian klik kanan pada folder tersebut lalu klik Git Bash


![SharedScreenshot14](https://user-images.githubusercontent.com/115879313/196110574-8a62671d-4582-4072-bf9f-ca6306d5c398.png)

7.Buat folder dengan menggunakan perintah dan buka folder tersebut

$mkdir latihan1

$cd latihan

![image](https://user-images.githubusercontent.com/115879313/196104995-9fa0dcfe-957d-4018-949b-e468a17692e8.png)



8.dan tambahkan file README.md dengan menggunakan perintah

$echo "#VCS1" >> README.md

![image](https://user-images.githubusercontent.com/115879313/196107103-7c4c44c7-74d2-4113-aa9a-d9f5cfc0e0fa.png)


9.kemudian buat repository lokal menggunakan perintah

$git init

![SharedScreenshot7](https://user-images.githubusercontent.com/115879313/196107520-1a15d678-19b8-4d7a-9417-956bf3c22c29.png)

10.Untuk menambahkan file yang baru saja dibuat tersebut menggunakan perintah

$git add README.md

![image](https://user-images.githubusercontent.com/115879313/196108007-91d770cd-81d9-4924-b0ad-fe5cdfc9e279.png)


12.Untuk menyimpan perubahan yang ada kedalam database repository local, gunakan perintah

$git commit -m "first commit"

![SharedScreenshot9](https://user-images.githubusercontent.com/115879313/196108440-e4b6a02d-9269-4070-892b-b5edddf6b075.png)

13.kemudian gunakan perintah

$git branch -M main

![SharedScreenshot10](https://user-images.githubusercontent.com/115879313/196108892-795cf612-08c6-4fbe-994f-d1bd916abd22.png)

14.Setelah itu menambahkan remote repository. remote Repository merupakan repository server yang akan digunakan untuk menyimpan setiap perubahan pada local repository, sehingga dapat diakses oleh banyak user. dengan menggunakan perintah

$git remote add origin https://github.com/Lans210504/VCS1.git

![SharedScreenshot11](https://user-images.githubusercontent.com/115879313/196109381-453c6f74-338a-447a-8bbd-95e6d8ce1549.png)

15.Dan untuk mengirim perubahan pada local repository ke server gunakan perintah

$git push -u origin main

Dan kita bisa cek di repository langsung pada website github image

![SharedScreenshot12](https://user-images.githubusercontent.com/115879313/196109935-33669bad-e85a-41c9-873f-a8d400abfbbb.png)




