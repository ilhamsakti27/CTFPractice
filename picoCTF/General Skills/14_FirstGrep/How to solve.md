# How to slove this

URL soal: https://play.picoctf.org/practice/challenge/67?category=5&page=2

1. Lakukan comman berikut untuk mencari *flag* pada file.
```bash
egrep picoCTF file
```
atau
```bash

cat file | egrep picoCTF
```
atau
```bash
strings file | egrep picoCTF
```

### Flag
>picoCTF{grep_is_good_to_find_things_dba08a45}