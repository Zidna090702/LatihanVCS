Nama : ZIDNA SOLEDA ZULFA
NIM  : 312210031

A.Install Git

B.	PENGGUNAAN GIT
1.	Konfirmasi global akun yaitu name dan email agar tidak eror Ketika git commit :

      git config --global user.name “name”
      
      git config --global user.email “email”
      ![image](https://user-images.githubusercontent.com/115474076/196129317-922fbe6a-ad02-4d35-ab74-03455627376d.png)

2.	Membuat folder baru di file explorer dengan judul “latihanVCS”
![image](https://user-images.githubusercontent.com/115474076/196129584-16acabaf-353c-4f65-8f0c-09ab2b954116.png)

3.	Untuk masuk repository tersebut dengan :
	
	Klik kanan di file "latihanVCS" pilih git bash here
![image](https://user-images.githubusercontent.com/115474076/196129640-ce930fa7-96a5-4bd2-9960-82c339cd4239.png)

Lalu masukan perintah berikut :

	mkdir latihanVCS

	cd latihanVCS
![image](https://user-images.githubusercontent.com/115474076/196129725-4359ada0-efe2-4b7b-ae28-7c7d28bdf05f.png)

4.	Membuat file baru Bernama README.md :

	Echo “# latihanVCS” >> README.md
 ![image](https://user-images.githubusercontent.com/115474076/196129782-f73755c5-6caa-4f70-8bc3-d90c12908361.png)

5.	Inisialisasi dengan perintah berikut :

	git init 
 ![image](https://user-images.githubusercontent.com/115474076/196129851-4566dba6-b2af-4563-ac41-564085a970c8.png)

6.	Melihat status dari file tersebut :

	git status
![image](https://user-images.githubusercontent.com/115474076/196129900-06b2696b-2286-4ce7-8968-c6c0c89a5f1b.png)
 
File README.md yang belum ditambahkan akan bertuliskan warna merah

7.	Untuk menambah file tersebut/perubahan pada file staging sebelum proses commit. Ketikan perintah berikut 

	git add “README.md”

	git status
![image](https://user-images.githubusercontent.com/115474076/196129982-cfbe37bd-0ed2-44d1-8ba8-eb16e4741480.png)
Lalu cek Kembali status file tersebut, jika sudah sukses ditambahkan maka akan berwarna hijau 

8.	Simpan perubahan/penambahan yang terjadi dengan mengetikan perintah berikut :

	git commit -m “first commit”

	git remote -v => untuk mengecek sudah terhubung dengan url server git
 ![image](https://user-images.githubusercontent.com/115474076/196130864-9816e41f-b96d-4b78-adf9-9bc798db01a8.png)

Perubahan/penambahan pada repository berhasil di simpan didatabase local, jika ingin menyimpannya di server repository silahkan kunjungi link berikut : https://github.com
9.	Lalu akan muncul tampilan berikut :
 ![image](https://user-images.githubusercontent.com/115474076/196130970-4e293d4c-7a00-4e64-841e-05cf1a75e7c1.png)

Silahkan login jika sudah memiliki akun namun jika memiliki akun silahkan daftar terlebih dahulu.

Dengan cara :	A. Masukan email
		B. Tulis Password
		C. Tulis username(menggunakan huruf dan angka). Ex. Zidna090702

10.	Membuat Repository baru di github, klik tombol create or new yang berwarna hijau
![image](https://user-images.githubusercontent.com/115474076/196131105-ff5b5d8f-1c36-46cc-8460-7b16466d03da.png)
 
11.	Lalu akan tampil halaman berikut silahkan di isi nama Repository sesuai keinginan :
![image](https://user-images.githubusercontent.com/115474076/196131178-3712bc13-f7b7-444a-b9e3-a7970bbf41a6.png)
 ![image](https://user-images.githubusercontent.com/115474076/196131217-50c09570-943c-4ee3-8a94-34664b430bfb.png)
 
	Public => Repository dapat dilihat oleh semua orang

	Privat => Repository dibatasi tidak semua orang bisa lihat

12.	Jika berhasil akan muncul tampilan sebagai berikut :
![image](https://user-images.githubusercontent.com/115474076/196131346-0bf011ef-d5c1-45e0-8ae1-c8f8d5c16545.png) 
	(1) Untuk menyimpan repository jika di computer local belum ada

	(2) Untuk membuat Repository jika di computer local sudah ada dan tersimpan kalian tinggal ikutin perintahnya

13.	Sekarang kita akan push repository local ke github pertama, dengan melakukan remote sebagai berikut :

	git remote add origin https://github.com/Zidna090702/LatihanVcs.git

Lalu cek status remote berhasil atau tidak :

	git remote -v
Lalu kita bisa atur branch repository dengan menjalankan perintah berikut :

	git branch -M main

 ![image](https://user-images.githubusercontent.com/115474076/196131426-3dd6af17-a8bc-4a1d-8549-c3d53ac58802.png)
14.	Selanjutnya push dengan menggunakan perintah di bawah ini :

	git push -u origin main

	origin adalah nama metode yang tadi di buat

	main adalah branch repository

 ![image](https://user-images.githubusercontent.com/115474076/196131487-2733e333-ed7e-41fb-b7fe-5e6917c8f36a.png)
	Sudah berhasil menyimpan repository di GITHUB

15.	Jika ingin menggunakan repository yang telah ada di Github, kitab isa mendownload atau mengclone pertama klik code berwarna hijau lalu copy url https repository
![image](https://user-images.githubusercontent.com/115474076/196131571-704ed5a5-1009-455f-b787-209f963e0b11.png)
 






 

 
