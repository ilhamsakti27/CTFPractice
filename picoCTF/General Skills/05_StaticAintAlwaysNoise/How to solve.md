# How to slove this

URL soal: https://play.picoctf.org/practice/challenge/163?category=5&page=1

## Cara 1
1. Download programnya *static*.
2. Coba lihat isi file dengan menggunakan command.
```bash
cat static
```
&emsp;&emsp;&emsp;Hasil:<br>
![HasilCara1_1](image/cara1_1.png)<br>
&emsp;&emsp;&emsp;Terlihat tidak bisa melihat isi file karena file *static* berjenis executable.<br>

3. Saya mencoba menggunakan code editor. Di sini saya menggunakan visual studio code dengan menggunakan command.
```bash
code static
```
&emsp;&emsp;&emsp;Hasil:<br>
![HasilCara1_2](image/cara1_2.png)

4. Flag berhasil didapat.
## Cara 2
1. Download program *static* dan *BASH script*.
2. Dikarenakan *static* file merupakan executable file, maka coba eksekusi dengan command.
```bash
./static
```
3. Berikut merupakan hasilnya.<br>
![cara2_1](image/cara2_1.png)<br>
4. Coba buka dan eksekusi file script *ltdis.sh*.
![cara2_2](image/cara2_2.png)
![cara2_3](image/cara2_3.png)
5. Dari langkah sebelumnya kita mendapatkan petunjuk pada bagaian *Usage*. Oleh karena itu, saya mencoba untuk mengeksekusi sesuai perintah.
![cara2_4](image/cara2_4.png)
Setelah menjalankan perintah di atas, kita mendapatkan beberapa file seperti berikut.
![cara2_5](image/cara2_5.png)
6. Di sini saya mencoba membuka file .txt.
![cara2_6](image/cara2_6.png)
7. Flag berhasil didapat.



### Flag
>picoCTF{d15a5m_t34s3r_ccb2b43e}