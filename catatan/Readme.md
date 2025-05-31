# Tanggal 31 MEI 2025

## Introduction PHP
Hello World
Latihan dasar untuk membuat fungsi yang mengembalikan "Hello, World!".
## Catatan
- Fungsi harus bernama `helloWorld`.
- Pastikan file bisa dijalankan dengan `php HelloWorld.php`.


## Basic PHP Syntax

📌 Dasar-Dasar PHP (Introduction & Basics)
1. Sintaks Umum
Kode PHP dibuka dengan tag <?php

Setiap pernyataan harus diakhiri dengan ;
```php
$message = "Hello"; // benar
$message = "Hello"  // salah - tidak ada ;
```

2. Komentar
Komentar satu baris menggunakan //
```php
// Ini adalah komentar
```

3. Nilai dan Variabel
Variabel diawali dengan tanda $ dan diisi dengan operator =
```php
$count = 1;
$message = "Success!";
```

String bisa memakai ' atau ":
```php
$str1 = 'Hai';
$str2 = "Halo";
```

4. Fungsi
Fungsi didefinisikan dengan function, menerima argumen dan mengembalikan nilai pakai return
```php
function tambah($a, $b) {
    return $a + $b;
}
tambah(3, 2); // => 5
```

5. Class dan Method
Method adalah fungsi dalam class
$this digunakan untuk merujuk pada instance saat ini
```php
class Calculator {
    public function add($x, $y) {
        return $x + $y;
    }
    public function sub($x, $y) {
        return $this->add($x, -$y);
    }
}
$calc = new Calculator();
$calc->sub(3, 1); // => 2
```
