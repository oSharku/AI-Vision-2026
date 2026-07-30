# WEEK 04 - AI Code Assistants & Python Engineering

## 1. Tugasan Utama: Penjanaan & Perbandingan Kod Python menggunakan AI (ChatGPT vs Gemini)

Membandingkan keupayaan dua AI Code Assistant (ChatGPT vs Gemini) dalam membina fungsi pengaturcaraan Python bagi:
1. **Kalkulator BMI (Body Mass Index)** dengan *Input Validation* & *Exception Handling*.
2. **Debugging & Penyahpijatan Kod**.
3. **Unit Testing (Ujian Perisian)**.
4. **Refactoring Kod (Pythonic Practices)**.

---

## 2. Hasil Perbandingan Kod AI

### 📌 Modul 1: Kalkulator BMI (`bmi_calculator.py`)
* **Prompt**: "Bina program Python untuk mengira BMI pengguna. Minta input berat (kg) dan tinggi (m). Sertakan validation try-except dan pengelasan status BMI."
* **Perbandingan Output**:
  - **ChatGPT**: Menjana kod yang bersih dengan kawalan ralat `ValueError` yang teliti.
  - **Gemini**: Memberikan penerangan docstring yang lengkap dan contoh penggunaan kelas/fungsi yang teratur.

### 📌 Modul 2: Debugging & Refactoring (`contoh1_debugging.py` & `contoh3_refactoring.py`)
* Menukarkan gelung `for` tradisional kepada *List Comprehension* yang lebih Pythonic:
  ```python
  # Kod Asal
  hasil = []
  for x in nombor:
      hasil.append(x * x)

  # Kod Di-Refactor (Pythonic)
  hasil = [x**2 for x in nombor]
