# FizzBuzz
Sebuah program sederhana untuk menampilkan angka 1 hingga 100 dengan aturan:
- Jika habis dibagi 3 dan 5, tampilkan "FizzBuzz"
- Jika hanya habis dibagi 3, tampilkan "Fizz"
- Jika hanya habis dibagi 5, tampilkan "Buzz"
- Untuk angka lainnya, tampilkan angka itu sendiri

## Panduan Untuk Menjalankan

### Pre-requisites
- Bun

### Bun Installation (Linux / MacOS)
```bash
curl -fsSL https://bun.sh/install | bash
```
### Bun Installation (Windows)
```bash
powershell -c "irm bun.sh/install.ps1|iex"
```
### Cek ketersediaan bun
```bash
bun -v
```
### Clone Repository
```bash
git clone https://github.com/vennius/fizz-buzz.git
cd fizz-buzz
```
### Install dependency
```bash
bun i
```
### Running
```bash
bun index.ts
```
### Output yang diharapkan
```text
1
2
Fizz
4
Buzz
Fizz
7
8
Fizz
Buzz
11
Fizz
13
14
FizzBuzz
16
17
Fizz
19
...
```
