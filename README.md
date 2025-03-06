# README - Actividades de Programación en Java

Este documento describe dos actividades de programación en Java: **Gestor de Contactos con Ficheros** y **Análisis de XML con XPath**. A continuación, encontrarás una explicación detallada de cada actividad, sus objetivos, requisitos y los pasos necesarios para ejecutar los programas.

---

## Requisitos Previos

Antes de ejecutar los programas, asegúrate de tener instalado:

- **Java Development Kit (JDK)**: Versión 8 o superior.
- **Entorno de Desarrollo Integrado (IDE)**: Opcional, pero recomendado (como Eclipse, IntelliJ IDEA o NetBeans).
- **Permisos de lectura/escritura**: Para los archivos generados por los programas (`contactos.txt` y `libros.xml`).

---

## Actividad 1: Gestor de Contactos con Ficheros

### Objetivo

Desarrollar una aplicación en Java que gestione una lista de contactos almacenados en un fichero de texto. La aplicación permitirá añadir, listar y buscar contactos mediante una interfaz gráfica basada en `JOptionPane`.

### Requisitos

- **ArrayList**: Para almacenar los contactos en memoria.
- **Ficheros**: Para guardar y cargar la lista de contactos en un archivo de texto (`contactos.txt`).
- **Flujos de entrada/salida**: Para leer y escribir datos en el fichero.
- **Manipulación de cadenas**: Para buscar contactos por nombre.
- **JOptionPane**: Para la interacción con el usuario a través de ventanas emergentes.

### Funcionalidades

1. **Carga de contactos**: Al iniciar, el programa lee los contactos desde `contactos.txt` y los almacena en un `ArrayList`.
2. **Guardar contactos**: Al cerrar el programa, todos los contactos se guardan en `contactos.txt`.
3. **Añadir contacto**: Pide al usuario un nombre y teléfono mediante `JOptionPane` y lo agrega al `ArrayList`.
4. **Listar contactos**: Muestra todos los contactos en una ventana emergente.
5. **Buscar contacto**: Solicita un nombre y muestra los contactos que coincidan con ese criterio.
6. **Menú interactivo**: Usa `JOptionPane.showOptionDialog` para ofrecer un menú con las opciones disponibles.

### Pasos para Ejecutar

1. **Compilar el programa**:
   - Abre una terminal o línea de comandos.
   - Navega al directorio donde está el archivo fuente (por ejemplo, `GestorContactos.java`).
   - Ejecuta:  
     ```bash
     javac GestorContactos.java
