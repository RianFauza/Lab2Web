# Lab2Web
# 1. Membuat dokumen HTML
![image](https://github.com/RianFauza/Lab2Web/assets/115771479/5f5b5694-7644-4cb0-af8b-b7adde4bec44)

# 2. Mendeklarasikan CSS Internal
![image](https://github.com/RianFauza/Lab2Web/assets/115771479/c71ef6fd-6b5a-4163-b68a-eff55cb072ea)

# 3. Menambahkan Inline CSS
![image](https://github.com/RianFauza/Lab2Web/assets/115771479/ad105254-c50b-400b-8fa5-a33dad1a9e10)

# 4. Membuat CSS Eksternal
![image](https://github.com/RianFauza/Lab2Web/assets/115771479/32825abb-ba20-4a12-aa5f-e9bb3f2ed3e0)

# 5. Menambahkan CSS Selector
![image](https://github.com/RianFauza/Lab2Web/assets/115771479/84730ea1-ecaa-4db3-a268-790f32eba55f)

# Berikut Hasil percobaan Pengujian Validator pada Css Eksternal
![Screenshot (39)](https://github.com/RianFauza/Lab2Web/assets/115771479/81530a98-24dd-4840-9ef0-4670e2b29a3b)
![Screenshot (40)](https://github.com/RianFauza/Lab2Web/assets/115771479/0c1f93af-d494-4529-b813-b20900350571)

# Pertanyaan dan Tugas
1. Lakukan eksperimen dengan mengubah dan menambah properti dan nilai pada kode CSS dengan mengacu pada CSS Cheat Sheet yang diberikan pada file terpisah dari modul ini.
 
     ![image](https://github.com/RianFauza/Lab2Web/assets/115771479/7682ab64-5151-412a-856c-39dd337e3f19)

2. Apa perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1 {...}? berikan penjelasannya!
  - Kalau h1 menggunakan internal dan inline pada penggunaan style nya sedangkan intro menggunakan eksternal css style nya

3. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya!

  - Ketika ada deklarasi CSS secara internal, CSS eksternal, dan inline CSS pada elemen yang sama, maka urutan keutamaan (specificity) akan menentukan deklarasi mana yang akan ditampilkan pada browser. Urutan prioritas biasanya adalah sebagai berikut, dari yang paling tinggi hingga yang paling rendah:

  - a. Inline CSS memiliki prioritas tertinggi.
  
  - b. Kemudian, deklarasi CSS yang ada dalam elemen `<style>` secara internal (internal CSS) akan digunakan jika ada konflik antara inline dan internal CSS.
  
  - c. Terakhir, deklarasi dari file CSS eksternal akan digunakan jika ada konflik dengan inline dan internal CSS.

4. Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser? Berikan penjelasan dan contohnya! `( <p id="paragraf-1" class="text-paragraf"> )`
   

  - Ketika sebuah elemen HTML memiliki ID dan class, dan keduanya memiliki deklarasi CSS, maka deklarasi yang akan digunakan akan bergantung pada spesifikitas (specificity) dari selector tersebut. Secara umum, ID selector memiliki spesifikitas yang lebih tinggi daripada class selector. Oleh karena itu, jika ada konflik antara deklarasi CSS ID dan class, deklarasi dari ID akan digunakan.


