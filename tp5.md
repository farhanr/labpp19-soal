# Tugas Pendahuluan 5
## Prosedur, Fungsi, dan Method
> Hari / Tanggal : Jumat , 11 Oktober 2019

> Jam : 07:30 - 09:30

> Kelas : A

![alt text](https://media.geeksforgeeks.org/wp-content/uploads/methods-in-java.png "Method Composition")

## Soal
##### 1. Apa yang membedakan antara `Prosedur`, `Method`, dan `Fungsi`? Jelaskan apakah ketika ketiganya diimplementasikan, program dapat berjalan atau sebaliknya?
##### 2. Jelaskan apa itu `return type` dalam method, dan mengapa nilai dari `return value` harus bertipe data yang sama dengan `return type`?
##### 3. Bagaimana *method overloading* bekerja? Apa *output* dari program dibawah, dan mengapa *output*nya demikian?
```java
public class Overloading {
    public static void main(String[] args){
        //harga barang 2000
        System.out.println(beli(5000.0));
        System.out.println(beli(5000));
    }
    public static int beli(int uang){
        return uang-2000;
    }
    public static double beli(double uang){
        return uang-1000;
    }
}
```
##### 4. Apa yang dimaksud `recursion` dalam java dan *error* apa yang akan terjadi jika *method* `recursive` tidak diberikan kondisi penghentian?
###### contoh:
```java
public static void jump(){
    System.out.println("im jumping!");
    jump();
}
```
##### 5. Buatlah program dengan isi minimal satu *method* (selain *main method*) dengan ketentuan sebagai berikut
```
- method menerima dua parameter bertipe integer; a, b.
- method mengembalikan jumlah a+b.
- program mencetak hasil contoh pemanggilan method yang dibuat.
```

##### 6. Dari materi  `Prosedur`, `Method`, dan `Fungsi`,  Apa yang tidak kalian pahami?
###### .
> **Note**: Pelajari soal maupun materinya! 

> Lubangi lembar jawaban dengan pelubang kertas!

##### Bonus untuk respon
```java
String a = "//nama kalian";
a = String.valueOf(a.toLowerCase().charAt(0)) + String.valueOf(a.length());
System.out.println(a);
```
> *Bunda Ella menenyengamati ta*.
