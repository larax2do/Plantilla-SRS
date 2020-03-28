# Especificación de Requerimientos de Software
## Para <project name>

  

Tabla de Contenidos
=================
* [Historial de Cambios](#historial-de-cambios)
* 1 [Introducción](#1-introducción)
  * 1.1 [Propósito del Sistema](#11-proposito-del-sistema)
  * 1.2 [Alcance del Sistema](#12-alcance-del-Sistema)
  * 1.3 [Descripción del producto](#13-descripción-del-producto)
  * 1.3.1 [Perspectiva del producto](#131-perspectiva-del-producto)
  * 1.3.2 [Funciones del Producto](#132-funciones-del-producto)
  * 1.3.3 [Características de los Usuarios](#133-caracteristicas-de-los-usuarios)
  * 1.3.4 [Limitaciones](#134-limitaciones)
  * 1.4 [Definiciones](#14-definiciones)
* 2 [Referencias](#2-referencias)
* 3 [Requisitos específicos](#3-requisitos-especificos)
  * 3.1 [Interfaces externas](#31-interfaces-externas)
  * 3.2 [Requisitos Funcionales](#32-requisitos-funcionales)
  * 3.3 [Requisitos de usabilidad](#33-requisitos-de-usabilidad)
  * 3.4 [Requisitos de desempeño](#34-requisitos-de-desempeño)
  * 3.5 [Requisitos de Bases de Datos lógicas](#35-requisitos-de-bases-de-datos-logicas)
  * 3.6 [Restricciones de Diseño](#36-restricciones-de-diseño)
  * 3.7 [Atributos del Sistema](#37-atributos-del-sistema)
  * 3.8 [Información de Soporte](#38-informacion-de-soporte)
* 4 [Verificación](#4-verificacion)
* 5 [Apéndices](#5-apendices)
  * 5.1 [Suposiciones y Dependencias](#51-suposiciones-y-dependencias)
  * 5.2 [Siglas y Abreviaturas](#52-siglas-y-abreviaturas)

## Historial de Cambios
| Versión | Fecha | Secciones Modificadas | Descripción | Responsable |
| ------- | ----- | --------------------- | ----------- | ----------- |
|         |       |                       |             |             |
|         |       |                       |             |             |
|         |       |                       |             |             |
## 1. Introducción

### 1.1 Propósito del Sistema
Definir el propósito del software que se especificará.

### 1.2 Alcance del Sistema
Describir el alcance del software considerando:
* La identificación del producto de software que se producirán por su nombre (por ejemplo, Host DBMS, generador de informes, etc.)
* Explicar lo que el producto de software va a hacer
* Describir la aplicación de software que se está especificado, incluyendo los beneficios relevantes, objetivos y metas.
* Ser coherente con las declaraciones similares en las especificaciones de nivel superior (por ejemplo, la especificación de requisitos del sistema), si es que existen.


### 1.3 Descripción del producto
#### 1.3.1 Perspectiva del producto
Definir la relación del sistema con otros productos.
Si el producto es un elemento de un sistema más grande, a continuación, identificar las interfaces entre el producto regulado por las SRS y el sistema mayor del cual el producto es un elemento.
Un diagrama de bloques que muestra los principales elementos del sistema más grande, interconexiones, y las interfaces externas puede ser útil.
Describir cómo el software funciona dentro de las siguientes limitaciones:
* Interfaces del sistema.
* Interfaces de usuario.
* Interfaces de hardware.
* Interfaces de software.
* Interfaces de comunicaciones.
* Memoria.
* Operaciones.
* Requisitos de adaptación del sitio.

#### 1.3.2 Funciones del Producto
Proporcionar un resumen de las principales funciones que llevará a cabo el software.
A veces el resumen función que es necesario para esta parte puede ser tomado directamente de la sección de la especificación de alto nivel (si existe) que asigna funciones particulares al producto de software.
Tenga en cuenta que en aras de la claridad
* Las funciones del producto deben organizarse de una manera que hace que la lista de funciones comprensibles para el adquirente o para cualquier otra persona que lee el documento por primera vez.
* Pruebas o métodos gráficos se pueden utilizar para mostrar las diferentes funciones y sus relaciones. Tal diagrama no pretende mostrar un diseño de un producto, sino que simplemente muestra las relaciones lógicas entre las variables.

#### 1.3.3 Características de los Usuarios
Describir las características generales de los grupos de usuarios previstas para el producto, incluyendo características que pueden influir en la facilidad de uso, como el nivel educativo, experiencia, discapacidad, y los conocimientos técnicos.
#### 1.3.4 Limitaciones
Proporcionar una descripción general de cualquier otro articulo que va limitar las opciones del proveedor.
* Politicas de Regulacion
* Limitaciones de Hardware
* Interfaces con otras aplicaciones
* Operación en paralelo
* Funciones de auditoría
* Funciones de Control
* Requisitos de idioma
* Protocolos de Handshake
* Requisitos de Calidad
* Criticidad de la solicitud
* Seguridad y Protecciones
* Consideraciones Físicas/mentales

### 1.4 Definiciones

## 2 Referencias

## 3 Requisitos Especificos
Especificar todos los requisitos de software detalladamente, como minimo describir cada entrada(estimulo) en el sistema y cada salida(respuesta) desde el sistema.
* Referencia a documentos anteriores
* Identificación unica

### 3.1 Interfaces Externas
Definir todas las entradas y salidas del sistema
* Nombre
* Propósito
* Fuente de entrada/salida
* Rango válido, exactitud y/o tolerancia
* Unidad de medida
* Sincronización
* Relación con otras entradas/salidas
* Formato/Organización de Pantalla
* Formato/Organización de ventana
* Formato de datos
* Formatos de Comandos
* Mensajes finales

### 3.2 Requisitos Funcionales
Definir las acciones fundamentales que tienen que llevarse a cabo en el software para aceptar y procesar entradas, en el proceso y en la generación de salidas.
* Validación de entradas
* Secuencia de operaciones
* Respuestas a situaciones anormales(desbordamiento, nuevas conexiones, errores y recuperación)
* Resultado de parámetros
* Relación de las salidas a las entradas

### 3.3 Requisitos de usabilidad
Definir los requisitos de usabilidad (calidad de uso). Los requisitos y objetivos de usabilidad para el sistema de software incluyen criterios de efectividad, eficiencia y satisfacción medibles en contextos específicos de uso.

### 3.4 Requisitos de desempeño
Especifique los requisitos numéricos estáticos y dinámicos colocados en el software o en la interacción humana con el software.
* Número de terminales para ser soportadas
* Número de usuarios simultáneos
* Cantidad y tipo de información a ser manejada

### 3.5 Requisitos de Bases de Datos lógicas
Especificar los requisitos lógicos  para cualquier información que se va colocar en una base de datos.
* Tipos de Información
* Frecuencia de uso
* Acceso a las capacidades
* Entidades de Datos y Relaciones
* Restricciones de integridad
* Requisitos de retención de Datos

### 3.6 Restricciones de Diseño
Especificar restricciones en el diseño del sistema impuesto por normas externas, los requisitos reglamentarios, o limitaciones del proyecto.

### 3.7 Atributos del Sistema
Especificar los atributos necesarios del producto de software.
* Fiabilidad
* Disponibilidad
* Seguridad, especificar los requisitos para proteger el software desde el acceso accidental o malintencionada, modificación uso, destrucción o divulgación.
* Mantenibilidad, especificar atributos de software que relaciona a la facilidad de mantenimiento del software en sí.
* Portabilidad, Para especificar atributos de software que relaciona a la facilidad de portar el software a otros equipos host y / o sistemas operativos.

### 3.8 Información de Soporte
> Información Adicional
* Ejemplo de entrada / formatos de salida, descripciones de estudios de análisis de costos, o resultados de encuestas a los usuarios.
* Información de fondo que puede ayudar a los lectores de los SRS.
* Una descripción de los problemas a resolver por el software.
* Instrucciones especiales de empaque para el código y los medios para cumplir con los requisitos de seguridad, exportación, carga inicial u otros requisitos.

## 4 Verificación
Proporcione los métodos y métodos de verificación planeados para calificar el software.

## 5 Apéndices
### 5.1 Suposiciones y Dependencias
Enumerar cada uno de los factores que afectan a los requisitos establecidos en los SRS. Estos factores no son restricciones de diseño en el software, pero cualquier cambio en estos factores pueden afectar los requisitos de las SRS.
Sistema operativo específico que se supone que está instalado.
### 5.2 Siglas y Abreviaturas

