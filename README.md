|Nama|NIM|Kelas|Matkul|
|----|---|-----|------|
|M Tegar Hermawanto|312310404|TI.23.A4|Pemograman Web 1|

1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.

![image](https://github.com/user-attachments/assets/4c2dfca9-e969-4f1d-b6d8-bfc42f6fc662)

3. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
   
 semua elemen h1 di halaman HTML jika ada beberapa h1, semuanya akan mendapatkan gaya yang sama.
![image](https://github.com/user-attachments/assets/afaa6065-365f-4901-ba80-4db8e47c5959)

h1 yang ada di dalam elemen dengan id intro artinya jika ada h1 lain di luar elemen dengan id intro gaya ini tidak akan di terapkan pada elemen tersebut

![image](https://github.com/user-attachments/assets/1639103b-e111-4ef4-ab30-c2552a83aeab)

h1 yang ada di dalam elemen dengan id intro artinya jika ada h1 lain di luar elemen dengan id intro gaya ini tidak akan di terapkan pada elemen tersebut

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi berikut yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!.

CSS Internal: Gaya yang ditetapkan dalam tag <style> akan diterapkan jika tidak ada inline CSS. Dalam contoh ini, color: blue; tidak akan terlihat.

contohnya

            h1{

                color: green; /* CSS Eksternal */

CSS Eksternal: Gaya yang ditetapkan dalam file eksternal akan diterapkan terakhir dan hanya jika tidak ada inline CSS atau CSS internal yang lebih spesifik. Dalam contoh ini, color: green; tidak akan terlihat.

contohnya  

            h1{

                color: blue; /* CSS Internal */
              
4. Pada sebuah elemen HTML ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka terdapat deklarasi yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!.

Ketika menggunakan CSS, elemen HTML dapat memiliki beberapa deklarasi gaya yang diterapkan padanya. Dalam hal ini, jika sebuah elemen memiliki ID dan class, dan masing-masing memiliki deklarasi CSS, prioritas atau spesifisitas dari selector akan menentukan gaya mana yang diterapkan.

contohnya

![image](https://github.com/user-attachments/assets/28b3acde-fd29-4d75-a941-c3867748c3e8)

ini yang akan di tampikan id selector

![image](https://github.com/user-attachments/assets/048bf428-6633-4365-9b4a-950ccdec3655)

ini yang akan di tampilkan class


