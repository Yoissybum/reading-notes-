# 📌 READ 09 - Introducción al Javascript

## Preguntas y Respuestas

### **1. ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?**
1. **Number**: Representa números, tanto enteros como decimales.
2. **String**: Representa texto o caracteres.
3. **Boolean**: Representa valores de verdadero (`true`) o falso (`false`). (Lo usamos para controlar el flujo de programa, por ejemplo, en condiciones)
4. **Undefined**: Indica que una variable ha sido declarada pero no se le ha asignado un valor.
5. **Null**: Representa un valor vacio o nulo.
6. **Symbol**: Es un tipo de dato único e inmutable. (Lo usamos para identificar propiedades de objetos de manera exclusiva)
7. **BigInt**: Representa números grander, más grandes que los que puede manejar el tipo `Number`.
8. **Object**: Es un tipo de dato complejo que puede contener muchos valores de diferentes tipos. (Usado para colecciones de datos)


### **2. ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?**: 

#### Declaraciones Condicionales
- **if**: Especifica un bloque de código que se ejecutará si una condición especificada es verdadera.
- **else**: Especifica un bloque de código que se ejecutará si la misma condición es falsa.
- **else if**: Especifica una nueva condición para probar si la primera condición es falsa.

#### Ejemplos:

1. **La Declaración if:** Usamos la declaración if para especificar un bloque de código de JavaScript que se ejecutará si una condición es verdadera. **Nota: if debe estar en minúsculas. Las letras mayúsculas (If o IF) generan un error en JavaScript.**

*Si la edad es menor que 18, se imprime "Eres menor de edad":*
```
let edad = 10;
if (edad < 18) {
  console.log("Eres menor de edad");
}
```

2. **La Declaración else:** Usamos la declaración else para especificar un bloque de código que se ejecutará si la condición es falsa.

*Si la edad es menor que 18, se imprime "Eres menor de edad", de lo contrario se imprime "Eres mayor de edad":*
```
let edad = 20;
if (edad < 18) {
  console.log("Eres menor de edad");
} else {
  console.log("Eres mayor de edad");
}
```

3. **La Declaración else if:** Usamos la declaración else if para especificar una nueva condición si la primera condición es falsa.

*Si la edad es menor que 13, se imprime "Eres un niño"; si no, pero la edad es menor que 18, se imprime "Eres un adolescente"; de lo contrario, se imprime "Eres un adulto":*
```
let edad = 25;
if (edad < 13) {
  console.log("Eres un niño");
} else if (edad < 18) {
  console.log("Eres un adolescente");
} else {
  console.log("Eres un adulto");
}
```

### **3. ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?**

#### Tenemos los siguientes tipos de operadores:

1. **Operadores Aritméticos:** Se utilizan para realizar cálculos matemáticos.

   - `+`: Suma
   - `-`: Resta
   - `*`: Multiplicación
   - `/`: División
   - `%`: Resto (calcula el resto de la  división)
   - `**`: Potencia (eleva un número a la potencia de otro)
   - `++`: Aumenta el valor de la variable en 1
   - `--`: Disminuye el valor de la variable en 1

2. **Operadores de Asignación:** Se utilizan para asignar valores a variables.

   - **Asignación simple (`=`)**: Asigna un valor a una variable. (Ejemplo: `let x = 10;`)
   - **Asignación con suma (`+=`)**: Suma y asigna. (Ejemplo: `x += 5; // x es ahora 15`)

3. **Operadores de Comparación:** Se utilizan para comparar dos valores.

   - **Igualdad (`==`)**: Compara dos valores para ver si son iguales (sin considerar el tipo).
   - **Estrictamente igual (`===`)**: Compara dos valores y su tipo.
   - **Desigualdad (`!=`)**: Compara dos valores para ver si son diferentes.
   - **Estrictamente desigual (`!==`)**: Compara dos valores y su tipo para ver si son diferentes.
   - **Mayor que (`>`)** y **Menor que (`<`)**: Compara si un valor es mayor o menor que otro.

4. **Operadores Lógicos:** Se utilizan para combinar condiciones.

   - **AND (`&&`)**: Devuelve `true` si ambas condiciones son verdaderas.
   - **OR (`||`)**: Devuelve `true` si al menos una de las condiciones es verdadera.
   - **NOT (`!`)**: Invierte el valor de verdad de una condición.

5. **Operadores de Tipo:** Se utilizan para obtener el tipo de un valor.

   - **`typeof`**: Devuelve el tipo de un valor. (Ejemplo: `typeof "Hola"; // "string"`)

### **4. ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?**

   - **`var`**: Se declara con `var`, tiene un alcance global o de función y es reasignable.  
   - **`let`**: Se declara con `let`, tiene un alcance de bloque y es reasignable.  
   - **`const`**: Se declara con `const`, tiene un alcance de bloque y no es reasignable (aunque puedes modificar propiedades de objetos).  
  - **`const`**: Se declara con `const`, tiene un alcance de bloque y no es reasignable. 
  
**Nota**: Aunque no se puede cambiar el valor de una variable declarada con `const`, si es un objeto o un arreglo, se puede modificar sus propiedades o elementos.
