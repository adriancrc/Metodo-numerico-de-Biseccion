# Método Numérico Cerrado de Bisección

🌐 This README is also available in English 🇺🇸: [README.en.md](README.en.md)

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-numerico-de-Biseccion)  
[![View on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/180635-metodo-numerico-de-biseccion)

![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Metodo-numerico-de-Biseccion)
![Total Downloads](https://img.shields.io/github/downloads/adriancrc/Metodo-numerico-de-Biseccion/total)
![Tested with MATLAB](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadriancrc%2FMetodo-numerico-de-Biseccion%2Fmain%2Freport%2Fbadge%2Ftested_with.json)
![Made with MATLAB](https://img.shields.io/badge/Made%20with-MATLAB-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)
![Use Case](https://img.shields.io/badge/Use-Educational-success)
![Author](https://img.shields.io/badge/Author-Adrián%20Quesada%20Martínez-blueviolet)
![Developed at ITCR](https://img.shields.io/badge/Developed%20at-ITCR-blue)




---

## 👨‍💻 Autor
**Adrián José Quesada Martínez**  
*Instituto Tecnológico de Costa Rica*

---

## 📘 Descripción

Este repositorio contiene una implementación en MATLAB del **método numérico de bisección**, una técnica robusta y sencilla para encontrar raíces de funciones continuas. Está diseñado como un **Live Script interactivo**, ideal para propósitos educativos.

---

## 🧠 Resumen del algoritmo

El **método de bisección** divide un intervalo \[a, b\] en el que la función cambia de signo (f(a)·f(b) < 0), garantizando que existe al menos una raíz. En cada iteración:

1. Se calcula el punto medio: `c = (a + b) / 2`.
2. Se evalúa f(c).
3. Según el signo de f(c), se escoge el nuevo intervalo \[a, c\] o \[c, b\].
4. El proceso se repite hasta alcanzar la tolerancia deseada.

---

## ✨ Características del Live Script

- **Interactividad**: permite ingresar la función, el intervalo y la tolerancia.
- **Gráficos**: visualiza la convergencia del método y la evolución del intervalo.
- **Tablas**: presenta iteraciones con valores de a, b, c y f(c).
- **Documentación integrada**: incluye explicaciones, ecuaciones y comentarios.
- **Debugging**: se pueden pausar iteraciones y examinar variables.
- **Facilidad de uso**: ideal para estudiantes y docentes.

---

## 📚 Fundamentos de métodos numéricos

- **Aproximación numérica**: cuando no hay solución analítica exacta.
- **Iteración y convergencia**: se mejora una solución paso a paso.
- **Error y precisión**: control mediante tolerancia.
- **Raíces de ecuaciones**: se busca `f(x) = 0`.

---

## 🚀 Cómo usar el script interactivo

### 🔹 Opción 1: Descargar

1. Descargue y descomprima el repositorio.
2. Abra el archivo `.mlx` (Live Script) en MATLAB®.

### 🔹 Opción 2: [Abrir en MATLAB Online](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-numerico-de-Biseccion)

- Inicie sesión con su cuenta MathWorks.
- Si es estudiante/docente, use su correo institucional para acceder a la licencia.

---

## 💻 Producto requerido

- **MATLAB®**

---

## 📄 Licencia

Este proyecto está licenciado bajo los términos definidos en el archivo [`LICENSE`](LICENSE) incluido en este repositorio.

---

## 📬 Soporte

¿Consultas o sugerencias?  
📧 [adquesada@itcr.ac.cr](mailto:adquesada@itcr.ac.cr)

---

© 2024 Adrián José Quesada Martínez



