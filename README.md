# **DotAutomationTest**

![Automation](https://img.shields.io/badge/Automation-Testing-blue?style=flat-square)
![Katalon](https://img.shields.io/badge/Framework-Katalon%20Studio-green?style=flat-square)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)

---

## 📌 **Deskripsi Project**

**DotAutomationTest** adalah project **automation testing** yang dikembangkan menggunakan **Katalon Studio** untuk membantu proses pengujian aplikasi secara otomatis, cepat, dan konsisten.
Dengan project ini, proses pengujian dapat dilakukan lebih efisien, meminimalkan human error, serta menghasilkan **laporan pengujian otomatis** untuk analisis kualitas aplikasi.

---

## 🧩 **Fitur Utama**

* ✅ **Automated Test Cases** → Menjalankan pengujian aplikasi secara otomatis.
* ✅ **Test Suites Management** → Mengelompokkan beberapa test cases sekaligus.
* ✅ **Reusable Object Repository** → Semua locator UI tersimpan dalam satu tempat.
* ✅ **Environment Profiles** → Mendukung pengujian multi-environment (Dev, QA, Production).
* ✅ **Reporting System** → Menghasilkan laporan otomatis dalam bentuk **HTML/PDF**.
* ✅ **Scalable & Maintainable** → Struktur project yang rapi dan mudah dikelola.

---

## 🏗️ **Struktur Project**

```bash
DotAutomationTest/
├── Include/                # Konfigurasi tambahan dan libraries kustom
├── Object Repository/      # Penyimpanan locator elemen aplikasi
├── Profiles/               # Variabel global & konfigurasi environment
├── Reports/                # Hasil eksekusi testing (HTML/PDF/Log)
├── Scripts/                # Source code automation test cases
├── Test Cases/             # Skenario pengujian individual
├── Test Suites/            # Kumpulan test cases dalam satu suite
├── Drivers/                # WebDriver & dependencies tambahan
├── settings/               # Konfigurasi project Katalon
└── README.md               # Dokumentasi project
```

---

## 🛠️ **Teknologi yang Digunakan**

| **Teknologi**                    | **Fungsi**                         |
| -------------------------------- | ---------------------------------- |
| **Katalon Studio**               | Framework utama automation testing |
| **Groovy/Java**                  | Bahasa scripting untuk test cases  |
| **Selenium WebDriver**           | Automasi pengujian web             |
| **Appium** *(opsional)*          | Automasi pengujian aplikasi mobile |
| **Jenkins / CI/CD** *(opsional)* | Integrasi pipeline otomatis        |

---

## ⚡ **Instalasi & Setup**

### **1. Clone Repository**

```bash
git clone https://github.com/agilwidianto/DotAutomationTest.git
```

### **2. Buka Project**

* Download dan install **[Katalon Studio](https://katalon.com/download)**
* Buka **Katalon Studio** → klik **Open Project** → arahkan ke folder **DotAutomationTest**.

### **3. Setup WebDriver**

* Pastikan browser (Chrome/Firefox) sesuai dengan **WebDriver**.
* Jika perlu, update driver di menu:
  `Tools > Update WebDrivers > Pilih Browser`.

---

## ▶️ **Cara Menjalankan Test**

### **1. Menjalankan Test Case**

1. Buka folder **Test Cases**.
2. Pilih salah satu test case.
3. Klik tombol **Run** (pilih browser atau device target).

### **2. Menjalankan Test Suite**

1. Buka folder **Test Suites**.
2. Pilih salah satu suite.
3. Klik **Run** untuk menjalankan seluruh test case dalam suite tersebut.

### **3. Melihat Laporan Hasil Testing**

* Setelah eksekusi selesai, buka folder:

  ```
  Reports/
  ```
* Laporan tersedia dalam format:

  * **HTML**
  * **PDF**
  * **Log Execution**

---
