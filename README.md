Langkah-langkah dalam pemberian warna ataupun desain dengan menggunakan CSS

1. Membuat Dokumen HTML

    Buatlah dokumen HTML dengan menggunakan koodingan dasar pada HTML, Contohnya sebagai berikut: e1
![codlab2](https://user-images.githubusercontent.com/81575487/113584901-b059e500-9655-11eb-823c-99ae7504bfe0.PNG)

* Lalu jalankan VSCODE dengan mengklik menu terminal yang berada pada kiri atas pada VS CODE, dan pilih Run Active File. Otomatis langsung terhubung ke Web Browser. contohnya pada gambar: ![hcodlab2](https://user-images.githubusercontent.com/81575487/113585425-67eef700-9656-11eb-9cbe-59523a66364b.PNG)

2. Mendeklarasikan CSS Internal

    Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian Head dokumen.
![cod2lab2](https://user-images.githubusercontent.com/81575487/113585621-aedcec80-9656-11eb-87d7-e932fd55328e.PNG)

Selanjutnya Simpan Perubahan pada coodingan anda dengan mengklik CTRL+S, dan lakukan refresh pada browser yang tadi untuk melihat hasil perubahannya.
![hcod2lab2](https://user-images.githubusercontent.com/81575487/113585842-f794a580-9656-11eb-9224-d1862e51320e.PNG)

3. Menambahkan Inline CSS

    Kemudian tambahakan deklarasi Inline CSS pada tag

    seperti berikut. ![cod3lab2](https://user-images.githubusercontent.com/81575487/113585964-1eeb7280-9657-11eb-80cb-1e24b43df5ae.PNG)
Simpan hasil perubahan dengan CTRL+S, dan refresh kembali web Browser untuk melihat perubahannya.![hcod3lab1](https://user-images.githubusercontent.com/81575487/113586112-4e01e400-9657-11eb-92d4-8c1f13ff12ca.PNG)

4. Membuat CSS Eksternal.

    Buatlah File baru dengan nama style_eksternal.css dan kemudian buatlah deklarasi CSS berikut:
![cod5lab2](https://user-images.githubusercontent.com/81575487/113586214-6e31a300-9657-11eb-84ec-3d43d95b1184.PNG)
Kemudian tambahkan <link untuk merujuk File CSS yang telah dibuat pada bagian Head
![hcod5lab2](https://user-images.githubusercontent.com/81575487/113586320-8e616200-9657-11eb-8fcd-1c09a9b0fb29.PNG)

5. Menambahkan CSS Selector

    Selanjutnya menambahkan CSS Selector menggunakan Id dan Class Selector pada file style_eksternal.css, lalu tambahan Code berikut:
![cod6lab2](https://user-images.githubusercontent.com/81575487/113586421-b18c1180-9657-11eb-82b4-55e8eacdea38.PNG)
Kemudian simpan kembali dan refresh browser untuk melihat hasil perubannya.
![hcod6lab2](https://user-images.githubusercontent.com/81575487/113586518-cec0e000-9657-11eb-9ddb-773f0379496d.PNG)

6.Melaukan Validasi dokumen CSS dengan mengakses https://jigsaw.w3.org/css-validator/
![image](https://user-images.githubusercontent.com/81575487/113588053-de412880-9659-11eb-9a7b-d8e181f04763.png)


Tugas !

1.Perbedaan pendeklarasian CSS elemen h1 {...} dengan #intro h1{...} h1

* h1 {...}
Deklarasi ini akan merubah semua elemen "h1" 	

* #intro h1 {...}
deklarasi ini lebih spesifik, maksud nya adalah yang akan mendapat atribut adalah elemen "h1" dengan id "intro"

2. Apabila ada deklarasi CSS secara internal, lalu ditambahkan CSS eksternal dan inline CSS pada elemen yang sama. Deklarasi      manakah yang akan ditampilkan pada browser?
 jawaban : adalah deklarasi inline yang akan di tampilkan pada browser.

3.  Pada sebuah elemen HTML terdapat ID dan Class, apabila masing-masing selector tersebut terdapat deklarasi CSS, maka deklarasi manakah yang akan ditampilkan pada browser?
 jawaban : adalah class ID yang akan di tampilkan pada browser karena class id secara individu mewakili sebua atribut. Contoh nya bisa di lihat pada 2 gambar di bawah ini terdapat sebuah paragraf dengan class dan id, saat di running di browser yang di tampikan adalah atribut id: 
 ![image](https://user-images.githubusercontent.com/81575487/113593225-5f032300-9660-11eb-8c5f-f5980456c1d5.png)
![image](https://user-images.githubusercontent.com/81575487/113593318-83f79600-9660-11eb-80cb-b809b5cb7394.png)



