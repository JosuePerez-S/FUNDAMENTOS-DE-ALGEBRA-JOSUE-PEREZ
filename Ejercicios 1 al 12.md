# Fundamentos de Álgebra – Unidad 3

## Realiza las siguientes operaciones

### Ejercicio 1
* **Problema:**

  ```math
  \begin{bmatrix}-6\\-2\\-6\\-3\end{bmatrix}+\begin{bmatrix}5\\-4\\-5\\6\end{bmatrix}+\begin{bmatrix}6\\2\\6\\-3\end{bmatrix}
  ```

* **Análisis:** Suma de matrices columna de dimensión $4 \times 1$. Las operaciones se realizan elemento a elemento en cada posición correspondiente.
* **Desarrollo:**

  ```math
  \begin{bmatrix}-6+5+6\\-2-4+2\\-6-5+6\\-3+6-3\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}5\\-4\\-5\\0\end{bmatrix}
  ```

### Ejercicio 2
* **Problema:**

  ```math
  \begin{bmatrix}-1&3\\-6&-1\end{bmatrix}-\left(\begin{bmatrix}4&5\\0&-6\end{bmatrix}-\begin{bmatrix}-3&-3\\6&-4\end{bmatrix}\right)
  ```

* **Análisis:** Suma y resta de matrices de dimensión $2 \times 2$. Se resuelve primero el paréntesis y después la resta restante, elemento a elemento.
* **Desarrollo:**

  ```math
  \begin{bmatrix}4+3&5+3\\0-6&-6+4\end{bmatrix}=\begin{bmatrix}7&8\\-6&-2\end{bmatrix}
  ```

  ```math
  \begin{bmatrix}-1-7&3-8\\-6+6&-1+2\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-8&-5\\0&1\end{bmatrix}
  ```

### Ejercicio 3
* **Problema:**

  ```math
  \begin{bmatrix}-4&6&-3&5\end{bmatrix}-\begin{bmatrix}-4&-5&-5&3\end{bmatrix}+\begin{bmatrix}4&4&5&-5\end{bmatrix}
  ```

* **Análisis:** Suma y resta de matrices fila de dimensión $1 \times 4$. Las operaciones se realizan elemento a elemento, de izquierda a derecha.
* **Desarrollo:**

  ```math
  \begin{bmatrix}-4+4+4&6+5+4&-3+5+5&5-3-5\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}4&15&7&-3\end{bmatrix}
  ```

### Ejercicio 4
* **Problema:**

  ```math
  \begin{bmatrix}0&0\end{bmatrix}-\begin{bmatrix}5&4\end{bmatrix}+\begin{bmatrix}-4&-3\end{bmatrix}
  ```

* **Análisis:** Suma y resta de matrices fila de dimensión $1 \times 2$. Las operaciones se realizan elemento a elemento.
* **Desarrollo:**

  ```math
  \begin{bmatrix}0-5-4&0-4-3\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-9&-7\end{bmatrix}
  ```

### Ejercicio 5
* **Problema:**

  ```math
  -3\cdot\left(-2\begin{bmatrix}-5&2&2&-5\end{bmatrix}\right)
  ```

* **Análisis:** Multiplicación de escalares por una matriz fila de dimensión $1 \times 4$. Se multiplican primero los escalares y después cada elemento de la matriz.
* **Desarrollo:**

  ```math
  (-3)(-2)=6
  ```

  ```math
  6\begin{bmatrix}-5&2&2&-5\end{bmatrix}=\begin{bmatrix}6(-5)&6(2)&6(2)&6(-5)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-30&12&12&-30\end{bmatrix}
  ```

### Ejercicio 6
* **Problema:**

  ```math
  5\cdot\left(-4\begin{bmatrix}2&-2&0\end{bmatrix}\right)
  ```

* **Análisis:** Multiplicación de escalares por una matriz fila de dimensión $1 \times 3$. Se multiplican primero los escalares y después cada elemento de la matriz.
* **Desarrollo:**

  ```math
  (5)(-4)=-20
  ```

  ```math
  -20\begin{bmatrix}2&-2&0\end{bmatrix}=\begin{bmatrix}-20(2)&-20(-2)&-20(0)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-40&40&0\end{bmatrix}
  ```

### Ejercicio 7
* **Problema:**

  ```math
  5\cdot\left(2\begin{bmatrix}-2&-4\\-1&-5\\-1&-5\end{bmatrix}\right)
  ```

* **Análisis:** Multiplicación de escalares por una matriz de dimensión $3 \times 2$. Se multiplican primero los escalares y después cada elemento de la matriz.
* **Desarrollo:**

  ```math
  (5)(2)=10
  ```

  ```math
  10\begin{bmatrix}-2&-4\\-1&-5\\-1&-5\end{bmatrix}=\begin{bmatrix}10(-2)&10(-4)\\10(-1)&10(-5)\\10(-1)&10(-5)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-20&-40\\-10&-50\\-10&-50\end{bmatrix}
  ```

### Ejercicio 8
* **Problema:**

  ```math
  -3\cdot\left(3\begin{bmatrix}6\\-1\end{bmatrix}\right)
  ```

* **Análisis:** Multiplicación de escalares por una matriz columna de dimensión $2 \times 1$. Se multiplican primero los escalares y después cada elemento de la matriz.
* **Desarrollo:**

  ```math
  (-3)(3)=-9
  ```

  ```math
  -9\begin{bmatrix}6\\-1\end{bmatrix}=\begin{bmatrix}-9(6)\\-9(-1)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-54\\9\end{bmatrix}
  ```

### Ejercicio 9
* **Problema:**

  ```math
  \begin{bmatrix}0&5\\2&-4\end{bmatrix}\cdot\left(\begin{bmatrix}4&0\\2&1\end{bmatrix}\cdot\begin{bmatrix}-2&1&2&-3\\4&-2&3&2\end{bmatrix}\right)
  ```

* **Análisis:** Producto de matrices. Se resuelve primero el paréntesis ($2 \times 2$ por $2 \times 4$ da $2 \times 4$) y luego se multiplica la primera matriz ($2 \times 2$) por ese resultado ($2 \times 4$).
* **Desarrollo:**

  ```math
  \begin{bmatrix}4(-2)+0(4)&4(1)+0(-2)&4(2)+0(3)&4(-3)+0(2)\\2(-2)+1(4)&2(1)+1(-2)&2(2)+1(3)&2(-3)+1(2)\end{bmatrix}=\begin{bmatrix}-8&4&8&-12\\0&0&7&-4\end{bmatrix}
  ```

  ```math
  \begin{bmatrix}0(-8)+5(0)&0(4)+5(0)&0(8)+5(7)&0(-12)+5(-4)\\2(-8)-4(0)&2(4)-4(0)&2(8)-4(7)&2(-12)-4(-4)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}0&0&35&-20\\-16&8&-12&-8\end{bmatrix}
  ```

### Ejercicio 10
* **Problema:**

  ```math
  \begin{bmatrix}1&2\\3&-4\\2&-4\end{bmatrix}\cdot\left(\begin{bmatrix}4&2\\2&-5\end{bmatrix}\cdot\begin{bmatrix}-1&3\\1&2\end{bmatrix}\right)
  ```

* **Análisis:** Producto de matrices. Se resuelve primero el paréntesis ($2 \times 2$ por $2 \times 2$) y luego se multiplica la matriz $3 \times 2$ por ese resultado.
* **Desarrollo:**

  ```math
  \begin{bmatrix}4(-1)+2(1)&4(3)+2(2)\\2(-1)-5(1)&2(3)-5(2)\end{bmatrix}=\begin{bmatrix}-2&16\\-7&-4\end{bmatrix}
  ```

  ```math
  \begin{bmatrix}1(-2)+2(-7)&1(16)+2(-4)\\3(-2)-4(-7)&3(16)-4(-4)\\2(-2)-4(-7)&2(16)-4(-4)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}-16&8\\22&64\\24&48\end{bmatrix}
  ```

### Ejercicio 11
* **Problema:**

  ```math
  \begin{bmatrix}5&-2&5&6\\1&-5&6&4\end{bmatrix}\cdot\left(\begin{bmatrix}3&1\\4&-1\\-1&-3\\-2&-1\end{bmatrix}\cdot\begin{bmatrix}0&1\\-1&0\end{bmatrix}\right)
  ```

* **Análisis:** Producto de matrices. Se resuelve primero el paréntesis ($4 \times 2$ por $2 \times 2$ da $4 \times 2$) y luego se multiplica la matriz $2 \times 4$ por ese resultado.
* **Desarrollo:**

  ```math
  \begin{bmatrix}3(0)+1(-1)&3(1)+1(0)\\4(0)-1(-1)&4(1)-1(0)\\-1(0)-3(-1)&-1(1)-3(0)\\-2(0)-1(-1)&-2(1)-1(0)\end{bmatrix}=\begin{bmatrix}-1&3\\1&4\\3&-1\\1&-2\end{bmatrix}
  ```

  ```math
  \begin{bmatrix}5(-1)-2(1)+5(3)+6(1)&5(3)-2(4)+5(-1)+6(-2)\\1(-1)-5(1)+6(3)+4(1)&1(3)-5(4)+6(-1)+4(-2)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}14&-10\\16&-31\end{bmatrix}
  ```

### Ejercicio 12
* **Problema:**

  ```math
  \begin{bmatrix}0&-4\\1&-4\\-1&5\\-3&4\end{bmatrix}\cdot\left(\begin{bmatrix}-3&-1&-2&3\\-1&-4&-3&5\end{bmatrix}\cdot\begin{bmatrix}4&0\\1&-5\\2&5\\2&1\end{bmatrix}\right)
  ```

* **Análisis:** Producto de matrices. Se resuelve primero el paréntesis ($2 \times 4$ por $4 \times 2$ da $2 \times 2$) y luego se multiplica la matriz $4 \times 2$ por ese resultado.
* **Desarrollo:**

  ```math
  \begin{bmatrix}-3(4)-1(1)-2(2)+3(2)&-3(0)-1(-5)-2(5)+3(1)\\-1(4)-4(1)-3(2)+5(2)&-1(0)-4(-5)-3(5)+5(1)\end{bmatrix}=\begin{bmatrix}-11&-2\\-4&10\end{bmatrix}
  ```

  ```math
  \begin{bmatrix}0(-11)-4(-4)&0(-2)-4(10)\\1(-11)-4(-4)&1(-2)-4(10)\\-1(-11)+5(-4)&-1(-2)+5(10)\\-3(-11)+4(-4)&-3(-2)+4(10)\end{bmatrix}
  ```

* **Resultado:**

  ```math
  \begin{bmatrix}16&-40\\5&-42\\-9&52\\17&46\end{bmatrix}
  ```
