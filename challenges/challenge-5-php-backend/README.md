# PHP Backend

Oke, sebelumnya kalian telah mempelajari tentang SQL dan sudah mengetahui bagaimana cara untuk mendapatkan data tertentu yang ada pada sebuah database. Selama minggu kemarin, kemungkinan besar kalian menggunakan cara tradisional, manual, simple, tidak elit (tidak 1337) wkwkw, makadari itu kali ini kalian harus melakukan semua hal itu dengan otomatis yaitu kalian memproses semua hal dalam kodingan dan dalam hal ini menggunakan PHP untuk membuat backend yang akan melakukan semua proses operasi SQL untuk mendapatkan data yang diinginkan (dalam hal ini flagnya).

Kalian seharusnya sudah memahami konsep frontend, dan api, maka selanjutnya sekarang saatnya memahami konsep backend yaitu sebagai sebuah hal yang memproses data dibelakang layar, sesuai dengan permintaan yang didapat melalui pemanggilan api nya.

Baca pada resource yang telah diberikan untuk selanjutnya.

# Challenge

Untuk minggu ini challenge nya adalah kalian harus membuat sebuah backend yang memproses database `sadlysadcorporate` pada challenge minggu sebelumnya, dan dapatkan flag untuk seluruh challenge SQL dari minggu sebelumnya (serta 2 challenge tambahan yang akan di announce selanjutnya di server discord) akan tetapi kali ini semuanya dilakukan otomatis pada backend.

Prosesnya kurang lebih seperti berikut ini:

```
User/Client ->
    Masuk ke endpoint (ex: /challenge1.php) ->
        Backend PHP memproses data dari database sesuai dengan endpoint yang diakses ->
            Kirim balik response berupa flag
```

# Hint(s)

Resource untuk bahasan ini bisa kalian akses di folder [resources/backend-web](https://github.com/Daskom-Lab/2021-Academy/tree/main/resources/backend-web).