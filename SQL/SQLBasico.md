# **SQL Básico**
## Autor: Ángel Hernández


### **Crear una tabla**
#### Sintaxis
<code>CREATE TABLE <nombre_tabla> (atributo1 tipo,atributo2  tipo);  </code>

#### Ejemplo
<code>CREATE TABLE GRAB
(CAT CHAR(6),
OBRA CHAR(25),
INTERPRETE VARCHAR(30),
DURAC DECIMAL(6)); </code>

### **Consulta básica**
#### Sintaxis
<code>SELECT * FROM <nombre_tabla>; </code>
#### Clausulas adicionales
<code>WHERE - GROUP BY - OREDER BY</code>
#### Ejemplo
<code>SELECT NOMNBRE,RFC,SALDO FROM EMPLEADOS 
WHERE NOMBRE='LUIS' AND SALDO > 1000
ORDER BY NOMBRE;</code>

### **Buscar en por un rango de valores**
#### Sintaxis
<code>WHERE <nombre_columna> BETWEEN X AND Y</code> 
#### Ejemplo
<code>WHERE año BETWEEN 1970 AND 2000</code>

### **Excluir un rango de valores**
#### Sintaxis
<code>WHERE <nombre_columna> NOT BETWEEN X AND Y</code> 
#### Ejemplo
<code>WHERE año NOT BETWEEN 1970 AND 2000</code>

### **Buscar en una lista de valores**
#### Sintaxis
<code>WHERE <nombre_columna> IN (X,Y,Z)</code> 
#### Ejemplo
<code>WHERE AÑO IN (1999,1997,1995)</code>


### **Excluir una lista de valores**
#### Sintaxis
<code>WHERE <nombre_columna> NOT IN (X,Y,Z)</code> 
#### Ejemplo
<code>WHERE AÑO NOT IN (1999,1997,1995)</code>


### **Busqueda mediante patrones alfanuméricos**
#### Sintaxis
<code>WHERE <nombre_columna> LIKE 'patron_de_busqueda'</code> 
#### Caráteres especiales: 
- % sustituye 0 a N número de posiciones dentro de la cadena
- _ sustituye un solo carácter dentro de la cadena 
#### Ejemplo
En este caso se busca una palabra que inicie con C tenga una N en cualquier posición y termine con O

<code>WHERE NOMBRE LIKE 'C%n%o' </code>


### ****
#### Sintaxis
<code></code> 
#### Ejemplo
<code></code>


### ****
#### Sintaxis
<code></code> 
#### Ejemplo
<code></code>


### ****
#### Sintaxis
<code></code> 
#### Ejemplo
<code></code>


### ****
#### Sintaxis
<code></code> 
#### Ejemplo
<code></code>


### ****
#### Sintaxis
<code></code> 
#### Ejemplo
<code></code>


### ****
#### Sintaxis
<code></code> 
#### Ejemplo
<code></code>