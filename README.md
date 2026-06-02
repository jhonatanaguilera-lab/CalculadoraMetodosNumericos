# Calculadora de Métodos Numéricos
### Proyecto Final — Programación Orientada a Objetos 2026
### Facultad de Ingeniería — Universidad Nacional de Asunción

---

##  Descripción

La **CalculadoraMetodosNumericos** es una herramienta de escritorio desarrollada en Java que busca solucionar un problema concreto en la materia de Métodos Numéricos: a la hora de estudiar es complicado dar con el resultado exacto de los ejercicios y verificar si se llegó a la respuesta correcta.

Al empezar a estudiar la materia, los alumnos deben recordar y aprender la implementación del lenguaje Python junto con los algoritmos numéricos al mismo tiempo, lo que complica el proceso. La **CalculadoraMetodosNumericos** busca resolver esto con una interfaz intuitiva y fácil de utilizar, sin necesidad de ser experto en Python.

Implementando cada una de las rutinas proporcionadas por la cátedra, la calculadora traduce fielmente los algoritmos originales a Java, de manera a que los alumnos puedan verificar con total seguridad las respuestas a las que deben llegar en sus ejercicios. Se utilizó la herramienta de IA como apoyo para reducir errores y llevar a cabo un proyecto satisfactorio.

---

##  Módulos disponibles

La calculadora cuenta con 3 unidades importantes de Métodos Numéricos:

### Raíces de ecuaciones
Bisección, Falsa Posición, Newton-Raphson, Punto Fijo, Secante

### Integración numérica
Trapecio, Simpson 1/3, Simpson 3/8 — con soporte para funciones ingresadas como expresión o datos tabulados cargados desde un archivo `.txt`

### Sistemas lineales
Gauss-Jordan, Jacobi, Gauss-Seidel

---

##  Diagrama UML

<img width="1301" height="921" alt="01_vista_general" src="https://github.com/user-attachments/assets/127f05ea-4d0f-4f04-bb48-8e64dbc419ad" />
<img width="982" height="331" alt="01_vista_general (2)" src="https://github.com/user-attachments/assets/05b6cae2-a206-41b9-b8f2-148c928339de" />
<img width="1201" height="586" alt="01_vista_general (3)" src="https://github.com/user-attachments/assets/e4c5b730-d170-4dde-a7fd-c80af2c98a80" />
<img width="1082" height="606" alt="01_vista_general (4)" src="https://github.com/user-attachments/assets/bd168ce7-cdd9-45e8-bc4f-f5a9b7400793" />
<img width="1071" height="616" alt="01_vista_general (5)" src="https://github.com/user-attachments/assets/316c9c55-a722-4e3c-b45e-a66bd45a261f" />
<img width="1101" height="651" alt="01_vista_general (6)" src="https://github.com/user-attachments/assets/689be715-6c9d-438d-aeea-321887c8ef76" />

---

##  Capturas de la interfaz

<img width="1365" height="720" alt="1000476144" src="https://github.com/user-attachments/assets/362b5321-8aab-4094-9305-54ca8b4aa611" />
<img width="1365" height="712" alt="1000476147" src="https://github.com/user-attachments/assets/bb1e38ad-846e-4866-b9df-888f83719cff" />
<img width="1365" height="717" alt="1000476145" src="https://github.com/user-attachments/assets/5862a6eb-fb04-4e9e-b435-d88b6e1f717f" />
<img width="1365" height="724" alt="1000476146" src="https://github.com/user-attachments/assets/87e68c79-091c-403d-95d0-e870b4856c17" />
<img width="1365" height="716" alt="1000476150" src="https://github.com/user-attachments/assets/6020c263-4f6c-4170-9c26-e41b52f0583c" />
<img width="1364" height="721" alt="1000476143" src="https://github.com/user-attachments/assets/51ffc99d-809c-43bd-963c-c3d356817583" />
<img width="1365" height="715" alt="1000476148" src="https://github.com/user-attachments/assets/8ad8a3ba-6fd5-4cb6-b7bf-3d8d6cc5e753" />
<img width="1364" height="718" alt="1000476149" src="https://github.com/user-attachments/assets/4eb2f98c-3044-4952-9588-5021da38a8f2" />

---

##  Instrucciones de uso

1. Ejecutar el programa desde NetBeans con **F6**
2. En el menú principal, seleccionar el tipo de cálculo: **Raíces**, **Integración** o **Sistemas Lineales**
3. Seleccionar el método deseado
4. Ingresar los parámetros solicitados (función, intervalo, tolerancia, etc.)
5. Presionar el botón **Calcular**
6. El resultado aparece en el panel derecho de la pantalla

** Gráfica de funciones:** En los módulos de Raíces e Integración, una vez ejecutado el cálculo, el programa muestra una gráfica de la función ingresada. En Raíces se visualiza el punto donde la función corta el eje x, y en Integración se resalta el área calculada bajo la curva.

** Historial de resultados:** El programa guarda automáticamente cada cálculo realizado en un archivo local. Desde el apartado de Historial se pueden consultar todos los resultados anteriores, incluyendo el método utilizado, los parámetros ingresados y el resultado obtenido, permitiendo hacer un seguimiento de los ejercicios resueltos.

> **Nota:** Las funciones deben ingresarse en formato matemático estándar, por ejemplo: `x^2 - 2`, `sin(x)`, `x^3 + 2*x - 1`

---

##  Ejecución desde el código fuente

**Requisitos:** Java 21, Maven 3.8, NetBeans 21 (recomendado)

Clonar el repositorio, abrir el proyecto en NetBeans y presionar **F6**.

---

##  Formato del archivo de datos tabulados

Para integración numérica con datos tabulados, el archivo `.txt` debe tener una línea por punto con `x` y `f(x)` separados por coma. Las líneas que empiezan con `#` se ignoran.

```
# x, f(x)
0.0,  0.0
0.25, 0.0625
0.5,  0.25
0.75, 0.5625
1.0,  1.0
```

---

##  Dependencias

| Librería | Versión | Uso |
|---|---|---|
| exp4j | 0.4.8 | Evaluación de expresiones matemáticas |
| JFreeChart | 1.5.4 | Gráficas de funciones |

---

##  Autor

**Jhonatan Thiago Aguilera Salcedo**  
Facultad de Ingeniería — UNA — POO 2026
