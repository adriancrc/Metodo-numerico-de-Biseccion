# Closed Numerical Bisection Method

🌐 Este README también está disponible en Español 🇪🇸: [README.md](README.md)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-numerico-de-Biseccion)  
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/180635-metodo-numerico-de-biseccion)

![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Metodo-numerico-de-Biseccion)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/Metodo-numerico-de-Biseccion/total)
![Tested with MATLAB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadriancrc%2FMetodo-numerico-de-Biseccion%2Fmain%2Freport%2Fbadge%2Ftested_with.json)
![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue)
![Top language](https://img.shields.io/github/languages/top/adriancrc/Metodo-numerico-de-Biseccion?label=Top%20Language&color=blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)


---

## 👨‍💻 Author
**Adrián José Quesada Martínez**  
*Tecnológico de Costa Rica*

---

## 📘 Description

This repository contains a MATLAB implementation of the **bisection numerical method**, a robust and simple technique to find roots of continuous functions. It is designed as an **interactive Live Script**, ideal for educational purposes.

---

## 🧠 Algorithm Overview

The **bisection method** divides an interval \[a, b\] where the function changes sign (f(a)·f(b) < 0), ensuring at least one root exists. At each iteration:

1. Compute the midpoint: `c = (a + b) / 2`.
2. Evaluate f(c).
3. Depending on the sign of f(c), select the new interval \[a, c\] or \[c, b\].
4. Repeat until the desired tolerance is reached.

---

## ✨ Live Script Features

- **Interactivity**: allows input of function, interval, and tolerance.
- **Graphs**: visualize the convergence of the method and interval updates.
- **Tables**: show iterations with values of a, b, c, and f(c).
- **Integrated documentation**: includes explanations, equations, and comments.
- **Debugging**: pause iterations and inspect variables.
- **Ease of use**: ideal for students and educators.

---

## 📚 Numerical Methods Fundamentals

- **Numerical approximation**: when no exact analytical solution exists.
- **Iteration and convergence**: refining a solution step by step.
- **Error and precision**: controlled via a tolerance.
- **Equation roots**: solving `f(x) = 0`.

---

## 🚀 How to Use the Interactive Script

### 🔹 Option 1: Download

1. Download and unzip the repository.
2. Open the `.mlx` (Live Script) file in MATLAB®.

### 🔹 Option 2: [Open in MATLAB Online](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-numerico-de-Biseccion)

- Log in with your MathWorks account.
- If you are a student or faculty, use your institutional email to access the license.

---

## 💻 Required Product

- **MATLAB®**

---

## 📄 License

This project is licensed under the terms defined in the [`LICENSE`](LICENSE) file included in this repository.

---

## 📬 Support

Questions or suggestions?  
📧 [adquesada@itcr.ac.cr](mailto:adquesada@itcr.ac.cr)

---

## ⭐ Don't forget to rate!

If you found this material useful, please support it by leaving a ⭐⭐⭐⭐⭐ rating on the project page.  
Your feedback helps improve and keep sharing resources!

[![Rate this project](https://img.shields.io/badge/★★★★★-Rate%20on%20File%20Exchange-blueviolet?style=for-the-badge)](https://la.mathworks.com/matlabcentral/fileexchange/180635-metodo-numerico-de-biseccion)

---


© 2024 Adrián José Quesada Martínez
