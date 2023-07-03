
# Modul 8







## Operasi Arikmatik

Operasi aritmatika adalah operasi matematika yang dilakukan pada bilangan untuk melakukan perhitungan matematika seperti penjumlahan, pengurangan, perkalian, pembagian, dan sebagainya. Di Java, operator aritmatika dapat digunakan untuk melakukan operasi aritmatika pada tipe data numerik seperti int, double, float, long, dan lainnya. Berikut adalah beberapa operator aritmatika yang umum digunakan dalam Java:

Penjumlahan (+): Operator penjumlahan digunakan untuk menjumlahkan dua bilangan atau ekspresi. Misalnya, int hasil = 5 + 3; akan menyimpan nilai 8 pada variabel hasil.

Pengurangan (-): Operator pengurangan digunakan untuk mengurangkan satu bilangan dari bilangan lainnya atau ekspresi. Misalnya, int hasil = 5 - 3; akan menyimpan nilai 2 pada variabel hasil.

Perkalian (*): Operator perkalian digunakan untuk mengalikan dua bilangan atau ekspresi. Misalnya, int hasil = 5 * 3; akan menyimpan nilai 15 pada variabel hasil.

Pembagian (/): Operator pembagian digunakan untuk membagi satu bilangan dengan bilangan lainnya atau ekspresi. Misalnya, int hasil = 10 / 2; akan menyimpan nilai 5 pada variabel hasil. Perlu diperhatikan bahwa jika hasil pembagian adalah pecahan, maka hasilnya akan dibulatkan ke bawah jika tipe datanya adalah integer.

Modulus (%): Operator modulus digunakan untuk mendapatkan sisa hasil pembagian dua bilangan atau ekspresi. Misalnya, int hasil = 10 % 3; akan menyimpan nilai 1 pada variabel hasil.

Selain operator aritmatika tersebut, terdapat juga operator lain seperti operator peningkatan (++), operator pengurangan (--), dan operator negasi (-) yang digunakan dalam konteks aritmatika.
## Mencetak Argumen

Untuk mencetak argumen atau nilai dari suatu variabel di Java, Anda dapat menggunakan metode System.out.println() atau metode-metode lainnya yang ada di kelas PrintStream seperti System.out.print() atau System.out.printf(). Metode println() digunakan untuk mencetak nilai dan menambahkan baris baru setelahnya. Misalnya, System.out.println("Hello, world!"); akan mencetak teks "Hello, world!" di layar dengan baris baru setelahnya. Anda juga dapat mencetak nilai variabel dengan menggunakan operator konkatenasi (+) atau menggunakan metode System.out.printf() untuk mencetak nilai dengan format tertentu.

Contoh penggunaan System.out.println() untuk mencetak argumen:

int angka = 10;
System.out.println("Nilai angka: " + angka);

double harga = 9.99;
System.out.println("Harga produk: " + harga);

Contoh penggunaan System.out.printf() untuk mencetak argumen dengan format tertentu:

int umur = 25;
System.out.printf("Umur: %d tahun%n", umur);

double tinggi = 165.5;
System.out.printf("Tinggi: %.1f cm%n", tinggi);

Dalam contoh-contoh di atas, nilai variabel angka, harga, umur,


