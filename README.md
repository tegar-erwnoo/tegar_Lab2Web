|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|M Tegar Hermawanto|312310404|TI.23.A4|Pemograman Web 1|

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![image](https://github.com/user-attachments/assets/1c3d9fec-483b-4b62-a1be-3094ed2d5dee)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!

![image](https://github.com/user-attachments/assets/e6eb3a57-2358-4ca5-8e33-2beb2caaf687)

semua elemen h1 di halaman HTML jika ada beberapa h1, semuanya akan mendapatkan gaya yang sama.

![image](https://github.com/user-attachments/assets/cf5f9d24-761a-4bd0-bb3f-a6e192f971b3)

h1 yang ada di dalam elemen dengan id intro artinya jika ada h1 lain di luar elemen dengan id intro gaya ini tidak akan di terapkan pada elemen tersebut

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi berikut yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!.

CSS Internal: Gaya yang ditetapkan dalam tag <style> akan diterapkan jika tidak ada inline CSS. Dalam contoh ini, color: blue; tidak akan terlihat.

contohnya

            h1{

                color: #green; /* CSS Eksternal */

CSS Eksternal: Gaya yang ditetapkan dalam file eksternal akan diterapkan terakhir dan hanya jika tidak ada inline CSS atau CSS internal yang lebih spesifik. Dalam contoh ini, color: green; tidak akan terlihat.

contohnya  

            h1{

                color: blue; /* CSS Internal */
              
4. Pada sebuah elemen HTML ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka terdapat deklarasi yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!.

Ketika menggunakan CSS, elemen HTML dapat memiliki beberapa deklarasi gaya yang diterapkan padanya. Dalam hal ini, jika sebuah elemen memiliki ID dan class, dan masing-masing memiliki deklarasi CSS, prioritas atau spesifisitas dari selector akan menentukan gaya mana yang diterapkan.

contohnya

ini yang akan di tampikan id selector

![image](https://github.com/user-attachments/assets/007fd373-dc6c-4e2e-b688-db1b1e84a930)

ini yang akan di tampilkan class

![image](https://github.com/user-attachments/assets/afc7d7b2-ae61-492c-892c-c21f845eac6e)
