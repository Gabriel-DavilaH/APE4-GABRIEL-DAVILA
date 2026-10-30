<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=180&color=0:263A29,50:4B5320,100:789262&text=GU%C3%8DA%20APE&fontColor=A3B18A&fontSize=50&fontAlignY=38&desc=Proyecto%20Java&descAlignY=60&descSize=20" width="100%" alt="Encabezado GUÍA APE"/>

<br>

<img src="https://github.com/user-attachments/assets/e0f2bb8b-2840-421f-8f8b-3ae0511d4453" alt="Logo del proyecto" width="50"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=22&pause=1200&color=A3B18A&center=true&vCenter=true&width=650&lines=Programaci%C3%B3n+Orientada+a+Objetos;Cinco+ejercicios+en+Java;Aprendiendo+a+programar" alt="Texto animado"/>

</div>

---

# 📚 Proyecto Examen — Programación Java

## 👥 Integrante
- Dávila Hernández Gabriel Marcelo

## 🎓 Curso

**Software "B" — Nivel 1**

## 📝 Descripción del proyecto

Este repositorio contiene cinco ejercicios desarrollados en Java para poner en práctica los fundamentos de la programación orientada a objetos (POO).

Cada ejercicio se encuentra organizado en una carpeta independiente y cuenta con una clase principal `Ejercicio#.java`, encargada de ejecutar el programa, además de las clases auxiliares necesarias.

Los ejercicios abarcan el manejo de clases y objetos, atributos, métodos, constructores, arreglos de objetos, estructuras condicionales y ciclos repetitivos.

## 📂 Organización del repositorio

```text
APE4-GABRIEL-DAVILA/
│
├── Ej1_LibroAutor/
│   ├── Autor.java
│   ├── Libro.java
│   └── Main1.java
│
├── Ej2_Rectangulo/
│   ├── Rectangulo.java
│   └── Main2.java
│
├── Ej3_ProductoVenta/
│   ├── Producto.java
│   ├── Venta.java
│   └── Main3.java
│
├── Ej4_Transferencias/
│   ├── Cuenta.java
│   └── Main4.java
│
├── Ej5_Biblioteca/
│   ├── Usuario.java
│   ├── LibroBib.java
│   ├── Prestamo.java
│   └── Main5.java
│
└── README.md
```

### 💻 Descripción de los ejercicios

### 🟢 Ejercicio 1: Libro y Autor
El programa permite representar la relación entre un libro y su autor mediante dos clases: Autor y Libro. La clase Autor almacena el nombre y la nacionalidad, mientras que la clase Libro contiene el título, el año de publicación y un objeto de tipo Autor.

Mediante el método mostrarInformacion(), se presentan los datos de cada libro junto con la información de su autor. Se crean dos libros para demostrar cómo un objeto puede formar parte de los atributos de otro objeto.

Conceptos aplicados:
- Creación de clases y objetos.
- Atributos y constructores.
- Objetos como atributos de otras clases.
- Relación entre clases.
- Métodos para mostrar información.
Resultados: muestra el título, el año de publicación y el nombre del autor de los dos libros registrados.

### 🟢 Ejercicio 2: Rectángulo
El programa permite calcular las propiedades de un rectángulo mediante la clase Rectangulo, que contiene los atributos base y altura.

A través de diferentes métodos, calcula el área, el perímetro y determina si el rectángulo tiene las mismas medidas en sus lados, es decir, si es un cuadrado. También genera una descripción de sus dimensiones y muestra todos los resultados.

Conceptos aplicados:
- Creación de clases y objetos.
- Atributos y constructores.
- Métodos con diferentes tipos de retorno.
- Tipo de dato double.
- Tipo de dato boolean.
- Operaciones aritméticas.
- Métodos que devuelven cadenas de texto (String).
Resultados: muestra el área, el perímetro, las dimensiones y determina si la figura es un cuadrado.

### 🟢 Ejercicio 3: Producto y Venta
El programa simula la venta de productos mediante las clases Producto y Venta. La clase Producto almacena el nombre, el precio y la cantidad disponible en stock, mientras que la clase Venta registra la cantidad de unidades que se desean comprar.

Mediante el método aplicar(Producto producto), se envía un objeto como parámetro para realizar la venta, reducir el stock disponible y calcular el total a pagar. Si no existen suficientes unidades, el programa muestra un mensaje de stock insuficiente.

Conceptos aplicados:
- Creación de clases y objetos.
- Atributos y constructores.
- Objetos como parámetros de métodos.
- Métodos para modificar atributos.
- Estructuras condicionales if y else.
- Operaciones aritméticas.
- Control de stock.
Resultados: muestra la información del producto, verifica si existe stock suficiente, actualiza las unidades disponibles y calcula el total de la venta.

### 🟢 Ejercicio 4: Transferencias
El programa simula transferencias de dinero entre dos cuentas bancarias utilizando la clase Cuenta, que contiene los atributos titular y saldo.

Mediante el método transferir(Cuenta destino, double monto), se envía otra cuenta como parámetro para realizar una transferencia. El sistema verifica que exista suficiente saldo antes de retirar el dinero de la cuenta de origen y depositarlo en la cuenta de destino.

Se realizan dos pruebas: una transferencia válida y otra que falla por falta de fondos.

Conceptos aplicados:
- Creación de clases y objetos.
- Atributos y constructores.
- Objetos como parámetros de métodos.
- Métodos para modificar atributos.
- Estructuras condicionales.
- Operaciones aritméticas.
- Validación de saldos.
Resultados: muestra los saldos de las dos cuentas, realiza una transferencia válida y demuestra cómo el sistema rechaza una operación cuando no existen fondos suficientes.

###🟢 Ejercicio 5: Biblioteca
El programa simula un sistema básico de préstamos de libros mediante tres clases: Usuario, Libro y Prestamo. La clase Usuario almacena el nombre y la cédula, mientras que la clase Libro contiene el título y su disponibilidad.

La clase Prestamo relaciona un objeto de tipo Usuario con un objeto de tipo Libro. Mediante el método registrar(), se intenta realizar el préstamo y se muestra un mensaje dependiendo de si el libro está disponible.

Se realizan pruebas con dos usuarios que intentan solicitar el mismo libro, demostrando que no puede prestarse nuevamente mientras se encuentre ocupado.

Conceptos aplicados:
- Creación de varias clases relacionadas.
- Clases y objetos.
- Objetos como atributos de otras clases.
- Colaboración entre clases.
- Objetos como parámetros de métodos.
- Métodos con retorno boolean.
- Estructuras condicionales.
- Control de disponibilidad.
Resultados: muestra los datos de los usuarios, registra los intentos de préstamo y verifica la disponibilidad del libro, evitando que dos usuarios puedan obtener el mismo libro al mismo tiempo.
---

## ⚙️ Requisitos para ejecutar los programas

- Tener instalado el JDK de Java.
- Disponer de un entorno de desarrollo compatible, como NetBeans, Eclipse o IntelliJ IDEA.
- Descargar o clonar el repositorio de GitHub.
- Mantener los archivos de cada ejercicio en su carpeta correspondiente.

## ▶️ Instrucciones de uso

1. Descargue o clone el repositorio en su computadora.
2. Abra el proyecto en su entorno de desarrollo Java.
3. Seleccione la carpeta del ejercicio que desea ejecutar.
4. Abra el archivo `Main#.java`.
5. Ejecute el método `Main#`.
6. Observe los resultados que aparecen en la consola.
7. Repita el procedimiento con los demás ejercicios.

**Nota:** cada carpeta contiene su propia clase principal `Main#.java`. Por eso, los ejercicios se ejecutan de manera independiente.

## 📖 Aprendizajes obtenidos

Durante el desarrollo del proyecto se reforzaron los conocimientos sobre programación orientada a objetos, creación de clases, instanciación de objetos, constructores, atributos y métodos.

También se practicó el uso de arreglos de objetos, estructuras condicionales, ciclos repetitivos y referencias a objetos. La organización por carpetas facilita la comprensión, el mantenimiento y la ejecución independiente de cada programa.

## 🛠️ Tecnologías utilizadas

- **Lenguaje de programación:** Java.
- **Paradigma:** Programación orientada a objetos.
- **Control de versiones:** Git.
- **Plataforma de alojamiento:** GitHub.
- **Entornos de desarrollo:** NetBeans, Eclipse e IntelliJ IDEA.

---

<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=rect&color=0:263A29,100:4B5320&height=3&section=footer" alt="Separador verde militar" width="100%"/>

  **Desarrollado por estudiantes de Software "B" — Nivel 1**

  *Si lo puedes imaginar, lo puedes programar.* 🌿

</div>

