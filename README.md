# Actividad – Uso de Clases y Objetos en C++

**Asignatura:** Programación Orientada a Objetos  
**Profesor:** Gamalier Reyes del Carmen  

---

## 👨‍🎓 Datos del Estudiante
* **Nombre Completo:** Allen Alberth Disla Irizarry  
* **Matrícula:** 2026-1008  

---

## 📝 Descripción Breve del Programa
Este programa desarrollado en C++ gestiona el registro de 5 libros mediante los principios de la Programación Orientada a Objetos (POO). Define una clase llamada `Libro` con atributos encapsulados (privados) y un método público para mostrar la información en consola. El sistema solicita interactivamente los datos de los libros al usuario y al finalizar imprime el listado completo de las obras registradas.

---

## 📊 Flujo de Datos del Sistema

### 📥 Datos de Entrada
* **Título del libro:** Texto (`string`)
* **Autor:** Texto (`string`)
* **Año de publicación:** Número entero (`int`)
* **Edición:** Texto (`string`)
* **Cantidad de páginas:** Número entero (`int`)

### ⚙️ Datos que Procesa
* Instancia un arreglo de 5 objetos de la clase `Libro`.
* Asigna los valores capturados por teclado utilizando los métodos mutadores públicos (`setters`).
* Almacena temporalmente el estado de cada objeto en la memoria durante la ejecución.

### 📤 Datos de Salida
* Impresión formateada en consola de la ficha técnica de cada uno de los 5 libros a través del método público `mostrarInformacion()`.

---

## 🔒 Importancia de la Encapsulación en la POO
La encapsulación es un pilar esencial de la Programación Orientada a Objetos que consiste en ocultar el estado interno (atributos) de un objeto y restringir su acceso directo desde el exterior.

**Importancia:**
1. **Protección y Control de Datos:** Evita que el código externo modifique arbitrariamente las variables internas con datos no válidos o incoherentes (como un año negativo o una cantidad de páginas igual a cero).
2. **Mantenibilidad:** Permite cambiar la lógica o estructura interna de la clase en el futuro sin romper el funcionamiento del resto del programa.
3. **Abstracción y Seguridad:** Promueve una interfaz limpia, obligando al programa a interactuar únicamente a través de métodos autorizados (`getters` y `setters`).

---

## 🚀 Cómo Compilar y Ejecutar el Programa

### Requisitos Previos
* Un compilador de C++ (como GCC / MinGW) o un entorno de desarrollo (IDE) como VS Code, Dev-C++ o Code::Blocks.

Fotos
<img width="1471" height="747" alt="image" src="https://github.com/user-attachments/assets/4204c2d7-6213-4098-b281-6e9a02cb913e" />
<img width="1477" height="751" alt="image" src="https://github.com/user-attachments/assets/fae68454-80dd-4555-8b92-db12a104b8d5" />

### Pasos desde la Terminal / Consola:

1. **Compilar el archivo C++:**
   ```bash
   g++ -o programa libro.cpp


   

