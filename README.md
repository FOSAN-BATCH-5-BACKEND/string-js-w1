# String

Soal latihan string ini memiliki 4 nomor. Simpan di file yang berbeda!

## 1. Let's Form a Sentence

### Problem

Pada tugas ini kamu diminta untuk melakukan penambahan string menggunakan simbol +. Disediakan variable word. Tambahkan nilai word satu per satu dengan nilai variable lain untuk membentuk sebuah kalimat. Jangan lupa menambahkan spasi di setiap kata, dan tampilkan di console hasil penggabungannya! **Kamu tidak perlu membuat variable baru!**

### Skeleton Code

```javascript
let word = 'JavaScript';
let second = 'is';
let third = 'awesome';
let fourth = 'and';
let fifth = 'I';
let sixth = 'love';
let seventh = 'it!';
```

### Output

```text
JavaScript is awesome and I love it!
```

## 2. Index Accessing - 1 by 1

### Problem

Pada tugas ini kamu diminta untuk "memecah" sebuah kalimat dan menampilkan setiap kata didalamnya. Untuk soal nomor ini, gunakan akses satu per satu karakter dari string untuk mengambil setiap huruf dalam kata. Terasa manual? Tidak apa-apa, kita coba ini dulu untuk saat ini.

### Hints

Saat kamu mendapatkan tiap huruf, untuk membentuk setiap kata kamu tinggal menggunakan simbol + untuk membentuk kata tersebut!

### Skeleton Code

```javascript
let word = 'wow JavaScript is so cool';
let exampleFirstWord = word[0] + word[1] + word[2];
let secondWord; // do your own!
let thirdWord; // do your own!
let fourthWord; // do your own!
let fifthWord; // do your own!

console.log('First Word: ' + exampleFirstWord);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

### Output

```text
First Word: wow
Second Word: JavaScript
Third Word: is
Fourth Word: so
Fifth Word: cool
```

## 3. Breaking Sentence (Again) using Substring

### Problem

Mirip seperti soal nomor 2, namun kali ini gunakan substring untuk mengambil potongan dari tiap kata!

### Skeleton Code

```javascript
let word3 = 'wow JavaScript is so cool';
let exampleFirstWord3 = word.substring(0, 3);
let secondWord3; // do your own!
let thirdWord3; // do your own!
let fourthWord3; // do your own!
let fifthWord3; // do your own!

console.log('First Word: ' + exampleFirstWord);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

### Output

```text
First Word: wow
Second Word: JavaScript
Third Word: is
Fourth Word: so
Fifth Word: cool
```

## 4. Breaking Sentence (yet Again) and Count Each Length

### Problem

Mirip seperti soal nomor 3, tapi tampilkan juga panjang kata masing-masingnya!

### Skeleton Code

Buatlah variable-variable baru untuk menyimpan panjang string, dan ubah console dibawah untuk menampilkan nya.

```javascript
let word4 = 'wow JavaScript is so cool';
let exampleFirstWord4 = word.substring(0, 3);
let secondWord4; // do your own!
let thirdWord4; // do your own!
let fourthWord4; // do your own!
let fifthWord4; // do your own!

let firstWordLength = exampleFirstWord4.length;
// create new variables around here

console.log('First Word: ' + exampleFirstWord + ', with length: ' + firstWordLength);
console.log('Second Word: ' + secondWord);
console.log('Third Word: ' + thirdWord);
console.log('Fourth Word: ' + fourthWord);
console.log('Fifth Word: ' + fifthWord);
```

### Output

```text
First Word: wow, with length: 3
Second Word: JavaScript, with length: 10
Third Word: is, with length: 2
Fourth Word: so, with length: 2
Fifth Word: cool, with length: 4
```