A.	Install Git

B.	PENGGUNAAN GIT
1.	Konfirmasi global akun yaitu name dan email agar tidak eror Ketika git commit :
      git config --global user.name “name”
      git config --global user.email “email”
2.	Membuat folder baru di file explorer dengan judul “latihanVCS”
3.	Untuk masuk repository tersebut dengan :
	Klik kanan di file "latihanVCS" pilih git bash here
Lalu masukan perintah berikut :
	mkdir latihanVCS
	cd latihanVCS
4.	Membuat file baru Bernama README.md :
	Echo “# latihanVCS” >> README.md
 
5.	Inisialisasi dengan perintah berikut :
	git init 
 


6.	Melihat status dari file tersebut :
	git status
 
File README.md yang belum ditambahkan akan bertuliskan warna merah
7.	Untuk menambah file tersebut/perubahan pada file staging sebelum proses commit. Ketikan perintah berikut 
	git add “README.md”
	git status
Lalu cek Kembali status file tersebut, jika sudah sukses ditambahkan maka akan berwarna hijau
 
8.	Simpan perubahan/penambahan yang terjadi dengan mengetikan perintah berikut :
	git commit -m “first commit”
	git remote -v => untuk mengecek sudah terhubung dengan url server git
 
Perubahan/penambahan pada repository berhasil di simpan didatabase local, jika ingin menyimpannya di server repository silahkan kunjungi link berikut : https://github.com
9.	Lalu akan muncul tampilan berikut :
 


Silahkan login jika sudah memiliki akun namun jika memiliki akun silahkan daftar terlebih dahulu.
Dengan cara : A. Masukan email
		    B. Tulis Password
		    C. Tulis username(menggunakan huruf dan angka). Ex. Zidna090702

10.	Membuat Repository baru di github, klik tombol create or new yang berwarna hijau
 
11.	Lalu akan tampil halaman berikut silahkan di isi nama Repository sesuai keinginan :
 
 
	Public => Repository dapat dilihat oleh semua orang
	Privat => Repository dibatasi tidak semua orang bisa lihat
12.	Jika berhasil akan muncul tampilan sebagai berikut :
 
	(1) Untuk menyimpan repository jika di computer local belum ada
	(2) Untuk membuat Repository jika di computer local sudah ada dan tersimpan kalian tinggal ikutin perintahnya
13.	Sekarang kita akan push repository local ke github pertama, dengan melakukan remote sebagai berikut :
	git remote add origin https://github.com/Zidna090702/LatihanVcs.git
Lalu cek status remote berhasil atau tidak :
	git remote -v
Lalu kita bisa atur branch repository dengan menjalankan perintah berikut :
	git branch -M main
 
14.	Selanjutnya push dengan menggunakan perintah di bawah ini :
	git push -u origin main
	origin adalah nama metode yang tadi di buat
	main adalah branch repository
 

	Sudah berhasil menyimpan repository di GITHUB


15.	Jika ingin menggunakan repository yang telah ada di Github, kitab isa mendownload atau mengclone pertama klik code berwarna hijau lalu copy url https repository
 





3.	Masuk repository tersebut dengan :
	Klik kanan pilih git bash here
Lalu masukan perintah berikut :
	mkdir latihanVCS
	cd latihanVCS
 

 
4.	Membuat file baru Bernama README.md :
	Echo “# latihanVCS” >> README.md
 
5.	Inisialisasi dengan perintah berikut :
	git init 
 


6.	Melihat status dari file tersebut :
	git status
 
Terlihat file README.md yang belum ditambahkan  yang bertuliskan warna merah
7.	Untuk menambah file tersebut/perubahan pada file staging sebelum proses commit. Ketikan perintah berikut 
	git add “README.md”
	git status
Lalu cek Kembali status file tersebut, jika sudah sukses ditambahkan maka akan berwarna hijau
 
8.	Simpan perubahan/penambahan yang terjadi dengan mengetikan perintah berikut :
	git commit -m “first commit”
	git remote -v => untuk mengecek sudah terhubung dengan url server git
 
Perubahan/penambahan pada repository berhasil di simpan didatabase local, jika ingin menyimpannya di server repository silahkan kunjungi link berikut : https://github.com
9.	Lalu akan muncul tampilan berikut :
 


Silahkan login jika sudah memiliki akun namun jika memiliki akun silahkan daftar terlebih dahulu.
Dengan cara : A. Masukan email
		    B. Tulis Password
		    C. Tulis username(menggunakan huruf dan angka). Ex. Zidna090702

10.	Membuat Repository baru di github, klik tombol create or new yang berwarna hijau
 
11.	Lalu akan tampil halaman berikut silahkan di isi nama Repository sesuai keinginan :
 
 
	Public => Repository dapat dilihat oleh semua orang
	Privat => Repository dibatasi tidak semua orang bisa lihat
12.	Jika berhasil akan muncul tampilan sebagai berikut :
 
	(1) Untuk menyimpan repository jika di computer local belum ada
	(2) Untuk membuat Repository jika di computer local sudah ada dan tersimpan kalian tinggal ikutin perintahnya
13.	Sekarang kita akan push repository local ke github pertama, dengan melakukan remote sebagai berikut :
	git remote add origin https://github.com/Zidna090702/LatihanVcs.git
Lalu cek status remote berhasil atau tidak :
	git remote -v
Lalu kita bisa atur branch repository dengan menjalankan perintah berikut :
	git branch -M main
 
14.	Selanjutnya push dengan menggunakan perintah di bawah ini :
	git push -u origin main
	origin adalah nama metode yang tadi di buat
	main adalah branch repository
 

	Sudah berhasil menyimpan repository di GITHUB


15.	Jika ingin menggunakan repository yang telah ada di Github, kitab isa mendownload atau mengclone pertama klik code berwarna hijau lalu copy url https repository
 

