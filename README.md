[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-numerico-de-Biseccion) or [![View Velocity and pressure profile in pipes on File Exchange](https://www.mathworks.com/matlabcentral/images/matlab-file-exchange.svg)](https://la.mathworks.com/matlabcentral/fileexchange/180635-metodo-numerico-de-biseccion)

![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/adriancrc/Velocity-and-pressure-profile-in-pipes/total) ![Endpoint Badge](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fadriancrc%2FVelocity-and-pressure-profile-in-pipes%2Fmain%2Freport%2Fbadge%2Ftested_with.json) ![GitHub Release](https://img.shields.io/github/v/release/adriancrc/Metodo-numerico-de-Biseccion)




# Método Numérico cerrado de Bisección

## Autor
Adrián José Quesada Martínez

Instituto Tecnológico de Costa Rica

## Descripción: ##
Este repositorio contiene una implementación en Matlab del método numérico de bisección para encontrar las raíces de una función. El método de bisección es un algoritmo de búsqueda de raíces que divide repetidamente un intervalo a la mitad y selecciona el subintervalo que contiene una raíz.

### Resumen: Método Numérico cerrado de Bisección Live Script

#### Descripción general

El método de bisección es un algoritmo numérico simple y robusto utilizado para encontrar las raíces de una función continua. En otras palabras, se usa para hallar los valores de "x" donde una función f(x) es igual a cero.

¿Cómo funciona?

Intervalo inicial: Se comienza con un intervalo [a, b] donde la función cambia de signo, es decir, f(a) y f(b) tienen signos opuestos. Esto asegura que haya al menos una raíz dentro del intervalo.
Punto medio: Se calcula el punto medio del intervalo: c = (a + b) / 2.
Evaluación: Se evalúa la función en el punto medio, f(c).
Nuevo intervalo:
Si f(c) es igual a cero, entonces "c" es la raíz.
Si f(c) tiene el mismo signo que f(a), la raíz está en el intervalo [c, b].
Si f(c) tiene el mismo signo que f(b), la raíz está en el intervalo [a, c].
Repetición: Se repiten los pasos 2-4 con el nuevo intervalo, reduciendo gradualmente el tamaño del intervalo hasta que se alcanza la precisión deseada.

#### Características principales

Interactividad:
Los Live Scripts permiten combinar código, texto formateado, ecuaciones y visualizaciones en un solo documento interactivo.
Esto facilita la exploración y comprensión del método de bisección al permitir la modificación de parámetros y la visualización inmediata de los resultados.
Visualización integrada:
El Live Script puede incluir gráficos que muestran el proceso de convergencia del método de bisección, lo que ayuda a visualizar cómo se reduce el intervalo y se aproxima a la raíz.
Se pueden incluir tablas que muestren las iteraciones del método, incluyendo los valores de los extremos del intervalo, el punto medio y el valor de la función en el punto medio.
Documentación clara:
El Live Script permite incluir texto explicativo, ecuaciones y comentarios que describen el algoritmo del método de bisección y su implementación en Matlab.
Esto facilita la comprensión del código y la documentación del proceso de resolución.
Flexibilidad:
El Live Script puede ser diseñado para permitir al usuario ingresar la función objetivo, el intervalo inicial y la tolerancia como parámetros, lo que lo hace flexible para diferentes problemas.
Se pueden incluir controles interactivos, como controles deslizantes y menús desplegables, para modificar los parámetros del método y observar cómo cambian los resultados.
Facilidad de uso:
Los Live Scripts son fáciles de crear y compartir, lo que los convierte en una herramienta ideal para la enseñanza y el aprendizaje del método de bisección.
La combinación de código y resultados en un solo documento facilita la comprensión del proceso de resolución.
Capacidad de "Debugging"
Es posible pausar la ejecución del código, y examinar los valores de las variables en cada iteración, lo que facilita la detección de errores.


## Conceptos Fundamentales de Métodos Numéricos ##

Aproximación Numérica:
Los métodos numéricos se utilizan cuando no se puede obtener una solución analítica exacta a un problema matemático. En su lugar, se generan soluciones aproximadas.
Es crucial entender que estas soluciones tienen un grado de error, y el objetivo es minimizar ese error.
Iteración:
Muchos métodos numéricos, incluido el de bisección, son iterativos. Esto significa que repiten un proceso varias veces para acercarse a la solución.
Cada repetición se llama iteración, y el resultado de una iteración se utiliza como entrada para la siguiente.
Convergencia:
La convergencia se refiere a si un método numérico se acerca a la solución correcta a medida que se realizan más iteraciones.
No todos los métodos numéricos convergen, y algunos convergen más rápido que otros.
El método de bisección, bajo ciertas condiciones, garantiza la convergencia.
Error y Precisión:
Es fundamental comprender los diferentes tipos de error, como el error de truncamiento y el error de redondeo.
La precisión se refiere a qué tan cerca está la solución aproximada de la solución exacta.
La tolerancia es un valor que define el nivel de precisión deseado.
Raíces de Ecuaciones:
El método de bisección se utiliza para encontrar las raíces de ecuaciones no lineales, es decir, los valores de "x" que hacen que f(x) = 0.
Es importante comprender el concepto de una raíz y cómo se relaciona con la gráfica de una función.


## Comience a utilizar la aplicación interactiva Método Numérico cerrado de Bisección ##

**Opción 1: Descargar al escritorio** Descargue y descomprima el repositorio. Luego, haga doble clic en el live script para abrir la aplicación MATLAB&reg;. 

**Option 2: [Open in MATLAB Online](https://matlab.mathworks.com/open/github/v1?repo=adriancrc/Metodo-numerico-de-Biseccion)** Log in to your MathWorks account to access your license. If you are associated with a university, use your university email to access a license and install the app. 

## Products ##
MATLAB&reg;

## License ##
The license for this module is available in the [license](LICENSE) file in this GitHub repository.

## Support ##
Please contact <a href="mailto:adquesada@itcr.ac.cr">Adrián José Quesada Martínez.</a>

# #
_Copyright 2024 Adrián José Quesada Martínez._
