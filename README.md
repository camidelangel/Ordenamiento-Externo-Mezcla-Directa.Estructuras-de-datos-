# Ordenamiento Externo: Mezcla Directa

## Descripción

Esta práctica consiste en completar la implementación del algoritmo de ordenamiento externo de Mezcla Directa (Straight Merge) utilizando Java.

El programa utiliza dos archivos auxiliares (`f1.txt` y `f2.txt`), compara los números almacenados en ellos y
escribe el resultado ordenado en un tercer archivo llamado `f3.txt`.

## Requisitos

- Tener instalado Java JDK.
- Contar con un IDE para programar en Java, como NetBeans, IntelliJ IDEA o Eclipse.
- Crear los archivos auxiliares `f1.txt` y `f2.txt` antes de ejecutar el programa.

## Estructura del proyecto

```text
Estructura_de_datos/
│
├── src/
    |
    └── OrdenamientoExterno/
           |___MezclaDirectaPractica.java
           |── f1.txt
           |── f2.txt
           |── f3.txt
           └── README.md
```

**Nota:** `f3.txt` se genera automáticamente al ejecutar el programa.

## Instalación y configuración

1. Descargar o clonar el repositorio desde GitHub.
2. Abrir el IDE de Java.
3. Seleccionar la opción para abrir un proyecto existente o importar el proyecto.
4. Ubicar el archivo `MezclaDirectaPractica.java` dentro de la carpeta de código fuente.
5. Crear los archivos `f1.txt` y `f2.txt` en la carpeta raíz del proyecto.
6. Escribir un número por renglón en cada archivo.

### Clonar el repositorio

Abrir una terminal y ejecutar el siguiente comando:

```bash
git clone https://github.com/camidelangel/Ordenamiento-Externo-Mezcla-Directa.Estructuras-de-datos-.git
```

Después, entrar a la carpeta del proyecto y abrirlo desde el IDE.

## Datos de prueba

**Archivo f1.txt**

```text
45
```

**Archivo f2.txt**

```text
12
```

El tamaño del bloque utilizado en el método principal es `L = 1`.

## Ejecución del programa

1. Abrir la clase `MezclaDirectaPractica.java`.
2. Verificar que los archivos `f1.txt` y `f2.txt` estén en la carpeta raíz del proyecto.
3. Ejecutar el método `main`.
4. Revisar el resultado mostrado en la consola.
5. Abrir el archivo `f3.txt` para comprobar que los números se escribieron ordenadamente.

## Salida obtenida en consola

```text
 Bloque intercalado con exito !
```

## Resultado del archivo f3.txt

```text
12
45
```
Mediante esta práctica se completó la lógica de intercalación de bloques del 
algoritmo de Mezcla Directa en Java. Se utilizaron dos archivos auxiliares para comparar sus elementos y 
generar un archivo de salida con los números ordenados. Esto permitió comprender cómo se realiza la lectura, 
comparación y escritura de datos mediante archivos de texto.

## Datos

Camila amor del angel cervantes 
Estructura de datos
Víctor Hugo Vásquez Herrera
sistemas computacionales 3ro"B"
