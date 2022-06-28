# How to slove this

URL soal: https://play.picoctf.org/practice/challenge/186?category=4&page=1

1. Download file gambar yang ada pada deskripsi soal dengan menggunakan command berikut.
```bash
wget https://mercury.picoctf.net/static/7cf6a33f90deeeac5c73407a1bdc99b6/cat.jpg
```
2. Cek deskripsi file menggunakan command berikut.
```bash
exiftool cat.jpg
```
![gambar01](images/Screenshot%20from%202022-06-28%2020-33-00.png) <br>

3. Isi dari *License* terlihat seperti output karakter base64.
4. Lakukan decode menggunakan decoder online. <br>
![gambar02](images/Screenshot%20from%202022-06-28%2020-33-09.png) <br>
5. Flag berhasil didapatkan

>flag : picoCTF{the_m3tadata_1s_modified}