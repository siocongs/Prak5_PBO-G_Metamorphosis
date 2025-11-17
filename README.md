---
# **Praktikum PBO (Tugas 5) - Kelompok Metamorphosis 🦋**

Proyek ini dibuat untuk memenuhi **Tugas Praktikum ke-5** mata kuliah *Pemrograman Berorientasi Objek* dengan topik **Rental PlayStation**.
Tugas dilakukan oleh **3 anggota**, masing-masing dengan jobdesk berbeda.

---

## **👥 Pembagian Tugas Anggota**

### **Anggota 1 – Struktur & Abstract Class**

* Membuat *abstract class* `RentalPS`
* Menambahkan atribut dasar: `namaPenyewa`, `lamaSewa`, `hargaPerJam`
* Membuat constructor
* Membuat 2 method abstract:

  * `hitungBiayaSewa()`
  * `tampilkanInfo()`

### **Anggota 2 – Interface & Fitur Bonus**

* Membuat interface `BonusMember`
* Menambahkan method `beriBonus()`
* Digunakan untuk pelanggan yang sering menyewa

### **Anggota 3 – Subclass & Output Program**

* Membuat class `RentalPS5` (extends `RentalPS`, implements `BonusMember`)
* Mengimplementasikan seluruh method
* Menampilkan hasil perhitungan biaya sewa
* Menjalankan program di `MainProgram.java`

---

## **📂 Struktur Folder**

```
src/
 └── rentalps/
      ├── RentalPS.java
      ├── BonusMember.java
      ├── RentalPS5.java
      └── MainProgram.java
```

---

## **📌 Cara Menjalankan Program**

1. Clone repository
2. Masuk ke folder proyek
3. Compile semua file:

   ```
   javac src/rentalps/*.java
   ```
4. Jalankan program:

   ```
   java rentalps.MainProgram
   ```

---

## **📊 Diagram**

Terdapat hubungan:

* `RentalPS` → abstract class
* `RentalPS5` → subclass (extends)
* `BonusMember` → interface (implements)

---
