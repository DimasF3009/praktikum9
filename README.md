# praktikum9
## Exception Handling
1. Eksepsi (exception) merupakan suatu kesalahan (error) yang terjadi saat proses eksekusi program sedang berjalan.
2. Kesalahan ini akan menyebabkan program berakhir dengan tidak normal. 
3. Kesalahan-kesalahan ini dapat diidentifikasikan dengan nama tertentu dan direpresentasikan sebagai objek di dalam python

## Assertions Exception
Assertions Exception adalah sebuah peristiwa, yang terjadi selama pelaksanaan program yang mengganggu aliran normal instruksi program. Secara umum, ketika skrip Python menemukan situasi yang tidak dapat diatasi, hal itu menimbulkan pengecualian. Exception adalah objek Python yang mewakili kesalahan.

## The assert Statement
Saat menemukan pernyataan, Python mengevaluasi ekspresi yang menyertainya, yaitu satu berharap itu benar Jika ekspresi salah, Python memunculkan pengecualian AssertionError.
#### Sintaks untuk pernyataan yaitu :
```
assert Expression[, Arguments]
```
#### Contoh
1. Berikut adalah fungsi yang mengubah mengubah suhu dari derajat Kelvin ke derajat Fahrenheit.
2. Ketika kode di atas dijalankan, menghasilkan hasil sebagai berikut.

![pct1](https://user-images.githubusercontent.com/115356128/208431343-15325338-ea09-41f4-a981-7a337ca2d573.png)

![pct2](https://user-images.githubusercontent.com/115356128/208431421-80dd4de4-d821-4320-aad9-46162b637311.png)

#### Apa itu Pengecualian?
Pengecualian adalah peristiwa yang terjadi selama eksekusi program yang mengganggu aliran normal dari instruksi program instruksi. Secara umum, ketika Python bertemu situasi yang tidak dapat diatasi, itu menimbulkan pengecualian. Pengecualian adalah objek Python yang mewakili kesalahan ketika Python memunculkan pengecualian, harus segera menangani pengecualian segera jika tidak, itu berakhir dan berhenti.

#### Menangani pengecualian
Jika Anda memiliki beberapa kode mencurigakan yang dapat memunculkan pengecualian, pengecualian dapat mempertahankan program dengan menempatkan menempatkan kode mencurigakan yang mencurigakan di try: block. Setelah coba: blokir, sertakan sertakan pernyataan kecuali: diikuti oleh blok kode yang menangani masalah seanggun mungkin.

#### Syntax
```
try:
You do your operations here;
......................
except:
If there is any exception, then execute this block.
......................
else:
If there is no exception then execute this block.
```

#### Contoh 
![pct3](https://user-images.githubusercontent.com/115356128/208433108-af9c7276-f872-4997-a3bb-d12204321d8f.png)

![pct4](https://user-images.githubusercontent.com/115356128/208433413-07d9a545-32ff-4b8e-a0a4-b65b7158a9cf.png)

  Contoh yang sama dapat ditulis lebih bersih sebagai berikut: 

![pct5](https://user-images.githubusercontent.com/115356128/208433836-66651c20-432a-4ffb-aac8-aae357c53b18.png)

![pct6](https://user-images.githubusercontent.com/115356128/208433851-89648a7a-043a-408f-8566-4091fad0cb20.png)

#### Klausul kecuali dengan Tanpa Pengecualian

  Anda juga dapat menggunakan pernyataan exception yang sama untuk menangani beberapa exception sebagai berikut:
```
try:
You do your operations here;
......................
except(Exception1[, Exception2[,...ExceptionN]]]):
If there is any exception from the given exception list,
then execute this block.
......................
else:
If there is no exception then execute this block.
```
#### Contoh
![pct7](https://user-images.githubusercontent.com/115356128/208434582-59c72b35-a5f5-4b7e-a68a-dcb02498d858.png)

![pct8](https://user-images.githubusercontent.com/115356128/208434603-9e3660a0-a044-437d-aff1-e805c271051b.png)





















