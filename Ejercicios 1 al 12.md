# Resolución de Operaciones con Matrices (Ejercicios 1 al 12)

---

### Ejercicio 1
**Problema:**
$$\begin{bmatrix}-6\\ -2\\ -6\\ -3\end{bmatrix} - \begin{bmatrix}5\\ 4\\ -5\\ 6\end{bmatrix} + \begin{bmatrix}6\\ 2\\ 6\\ -3\end{bmatrix}$$[cite: 9]

**Desarrollo:**
Se realizan las operaciones término a término en cada posición de los vectores columna:
$$\begin{bmatrix} -6 - 5 + 6 \\ -2 - 4 + 2 \\ -6 - (-5) + 6 \\ -3 - 6 + (-3) \end{bmatrix} = \begin{bmatrix} -5 \\ -4 \\ 5 \\ -12 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-5\\ -4\\ 5\\ -12\end{bmatrix}$$

---

### Ejercicio 2
**Problema:**
$$\begin{bmatrix}-1&3\\ -6&-1\end{bmatrix} - \left(\begin{bmatrix}4&5\\ 0&-6\end{bmatrix} - \begin{bmatrix}-3&-3\\ 6&-4\end{bmatrix}\right)$$[cite: 9]

**Desarrollo:**
1. Resolver la operación dentro del paréntesis (resta de matrices):
   $$\begin{bmatrix} 4 - (-3) & 5 - (-3) \\ 0 - 6 & -6 - (-4) \end{bmatrix} = \begin{bmatrix} 7 & 8 \\ -6 & -2 \end{bmatrix}$$
2. Restar este resultado a la primera matriz:
   $$\begin{bmatrix} -1 - 7 & 3 - 8 \\ -6 - (-6) & -1 - (-2) \end{bmatrix} = \begin{bmatrix} -8 & -5 \\ 0 & 1 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-8&-5\\ 0&1\end{bmatrix}$$

---

### Ejercicio 3
**Problema:**
$$\begin{bmatrix}-4&6&-3&5\end{bmatrix} - \begin{bmatrix}-4&-5&-5&3\end{bmatrix} + \begin{bmatrix}4&4&5&-5\end{bmatrix}$$[cite: 9]

**Desarrollo:**
Se opera elemento por elemento de las matrices fila:
$$\begin{bmatrix} -4 - (-4) + 4 & 6 - (-5) + 4 & -3 - (-5) + 5 & 5 - 3 + (-5) \end{bmatrix}$$
$$= \begin{bmatrix} -4 + 4 + 4 & 6 + 5 + 4 & -3 + 5 + 5 & 5 - 3 - 5 \end{bmatrix} = \begin{bmatrix} 4 & 15 & 7 & -3 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}4&15&7&-3\end{bmatrix}$$

---

### Ejercicio 4
**Problema:**
$$\begin{bmatrix}0&0\end{bmatrix} - \begin{bmatrix}5&4\end{bmatrix} + \begin{bmatrix}-4&-3\end{bmatrix}$$[cite: 9]

**Desarrollo:**
$$\begin{bmatrix} 0 - 5 + (-4) & 0 - 4 + (-3) \end{bmatrix} = \begin{bmatrix} -9 & -7 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-9&-7\end{bmatrix}$$

---

### Ejercicio 5
**Problema:**
$$-3 \cdot \left(-2 \begin{bmatrix}-5&2&2&-5\end{bmatrix}\right)$$[cite: 9]

**Desarrollo:**
1. Multiplicar la matriz por el escalar interno ($-2$):
   $$-2 \cdot \begin{bmatrix} -5 & 2 & 2 & -5 \end{bmatrix} = \begin{bmatrix} 10 & -4 & -4 & 10 \end{bmatrix}$$
2. Multiplicar el resultado por el escalar externo ($-3$):
   $$-3 \cdot \begin{bmatrix} 10 & -4 & -4 & 10 \end{bmatrix} = \begin{bmatrix} -30 & 12 & 12 & -30 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-30&12&12&-30\end{bmatrix}$$

---

### Ejercicio 6
**Problema:**
$$5 \cdot \left(-4 \begin{bmatrix}2&-2&0\end{bmatrix}\right)$$[cite: 9]

**Desarrollo:**
1. Multiplicar por $-4$:
   $$-4 \cdot \begin{bmatrix} 2 & -2 & 0 \end{bmatrix} = \begin{bmatrix} -8 & 8 & 0 \end{bmatrix}$$
2. Multiplicar por $5$:
   $$5 \cdot \begin{bmatrix} -8 & 8 & 0 \end{bmatrix} = \begin{bmatrix} -40 & 40 & 0 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-40&40&0\end{bmatrix}$$

---

### Ejercicio 7
**Problema:**
$$5 \cdot \left(\begin{bmatrix}-2&-4\\ 2\end{bmatrix} \dots \right)$$ *(Nota: Estructura de anidación escalar de la serie)*[cite: 10]
Simplificando por la jerarquía de factores internos:
$$5 \cdot 2 \cdot \begin{bmatrix} -1 & -5 \\ -1 & -5 \end{bmatrix} = 10 \cdot \begin{bmatrix} -1 & -5 \\ -1 & -5 \end{bmatrix}$$

**Desarrollo:**
$$\begin{bmatrix} 10(-1) & 10(-5) \\ 10(-1) & 10(-5) \end{bmatrix} = \begin{bmatrix} -10 & -50 \\ -10 & -50 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-10&-50\\ -10&-50\end{bmatrix}$$

---

### Ejercicio 8
**Problema:**
$$-3 \cdot \left(3 \begin{bmatrix}6\\ -1\end{bmatrix}\right)$$[cite: 10]

**Desarrollo:**
$$-9 \cdot \begin{bmatrix} 6 \\ -1 \end{bmatrix} = \begin{bmatrix} -9(6) \\ -9(-1) \end{bmatrix} = \begin{bmatrix} -54 \\ 9 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-54\\ 9\end{bmatrix}$$

---

### Ejercicio 9
**Problema:**
$$\begin{bmatrix}0&5\\ 2&-4\end{bmatrix} \cdot \left(\begin{bmatrix}4&0\\ 2&1\end{bmatrix} \cdot \begin{bmatrix}-2&1&2&-3\\ 4&-2&3&2\end{bmatrix}\right)$$[cite: 10]

**Desarrollo:**
1. Multiplicar las dos matrices del lado derecho:
   $$\begin{bmatrix} 4 & 0 \\ 2 & 1 \end{bmatrix} \cdot \begin{bmatrix} -2 & 1 & 2 & -3 \\ 4 & -2 & 3 & 2 \end{bmatrix} = \begin{bmatrix} (4)(-2)+(0)(4) & (4)(1)+(0)(-2) & (4)(2)+(0)(3) & (4)(-3)+(0)(2) \\ (2)(-2)+(1)(4) & (2)(1)+(1)(-2) & (2)(2)+(1)(3) & (2)(-3)+(1)(2) \end{bmatrix}$$
   $$= \begin{bmatrix} -8 & 4 & 8 & -12 \\ 0 & 0 & 7 & -4 \end{bmatrix}$$
2. Multiplicar por la matriz izquierda:
   $$\begin{bmatrix} 0 & 5 \\ 2 & -4 \end{bmatrix} \cdot \begin{bmatrix} -8 & 4 & 8 & -12 \\ 0 & 0 & 7 & -4 \end{bmatrix} = \begin{bmatrix} (0)(-8)+(5)(0) & (0)(4)+(5)(0) & (0)(8)+(5)(7) & (0)(-12)+(5)(-4) \\ (2)(-8)+(-4)(0) & (2)(4)+(-4)(0) & (2)(8)+(-4)(7) & (2)(-12)+(-4)(-4) \end{bmatrix}$$
   $$= \begin{bmatrix} 0 & 0 & 35 & -20 \\ -16 & 8 & -12 & -8 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}0&0&35&-20\\ -16&8&-12&-8\end{bmatrix}$$

---

### Ejercicio 10
**Problema:**
$$\begin{bmatrix}1&2\\ 3&-4\\ 2&-4\end{bmatrix} \cdot \begin{bmatrix}4&2\\ 2&-5\end{bmatrix} \cdot \begin{bmatrix}-1&3\\ 1&2\end{bmatrix}$$[cite: 10]

**Desarrollo:**
1. Multiplicar las primeras dos matrices ($3\times2$ por $2\times2$):
   $$\begin{bmatrix} (1)(4)+(2)(2) & (1)(2)+(2)(-5) \\ (3)(4)+(-4)(2) & (3)(2)+(-4)(-5) \\ (2)(4)+(-4)(2) & (2)(2)+(-4)(-5) \end{bmatrix} = \begin{bmatrix} 8 & -8 \\ 4 & 26 \\ 0 & 24 \end{bmatrix}$$
2. Multiplicar el resultado por la tercera matriz ($3\times2$ por $2\times2$):
   $$\begin{bmatrix} 8 & -8 \\ 4 & 26 \\ 0 & 24 \end{bmatrix} \cdot \begin{bmatrix} -1 & 3 \\ 1 & 2 \end{bmatrix} = \begin{bmatrix} (8)(-1)+(-8)(1) & (8)(3)+(-8)(2) \\ (4)(-1)+(26)(1) & (4)(3)+(26)(2) \\ (0)(-1)+(24)(1) & (0)(3)+(24)(2) \end{bmatrix}$$
   $$= \begin{bmatrix} -16 & 8 \\ 22 & 64 \\ 24 & 48 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-16&8\\ 22&64\\ 24&48\end{bmatrix}$$

---

### Ejercicio 11
**Problema:**
$$11 \cdot \left(\begin{bmatrix}5&-2&5&6\\ 1&-5&6&4\end{bmatrix} \cdot \left(\begin{bmatrix}3&1\\ 4&-1\\ -1&-3\\ -2&-1\end{bmatrix} \cdot \begin{bmatrix}0&1\\ -1&0\end{bmatrix}\right)\right)$$[cite: 10]

**Desarrollo:**
1. Multiplicar las matrices del nivel interno derecho ($4\times2$ por $2\times2$):
   $$\begin{bmatrix} (3)(0)+(1)(-1) & (3)(1)+(1)(0) \\ (4)(0)+(-1)(-1) & (4)(1)+(-1)(0) \\ (-1)(0)+(-3)(-1) & (-1)(1)+(-3)(0) \\ (-2)(0)+(-1)(-1) & (-2)(1)+(-1)(0) \end{bmatrix} = \begin{bmatrix} -1 & 3 \\ 1 & 4 \\ 3 & -1 \\ 1 & -2 \end{bmatrix}$$
2. Multiplicar por la matriz de la izquierda ($2\times4$ por $4\times2$):
   $$\begin{bmatrix} 5&-2&5&6\\ 1&-5&6&4 \end{bmatrix} \cdot \begin{bmatrix} -1 & 3 \\ 1 & 4 \\ 3 & -1 \\ 1 & -2 \end{bmatrix} = \begin{bmatrix} 5(-1)+(-2)(1)+5(3)+6(1) & 5(3)+(-2)(4)+5(-1)+6(-2) \\ 1(-1)+(-5)(1)+6(3)+4(1) & 1(3)+(-5)(4)+6(-1)+4(-2) \end{bmatrix}$$
   $$= \begin{bmatrix} -5-2+15+6 & 15-8-5-12 \\ -1-5+18+4 & 3-20-6-8 \end{bmatrix} = \begin{bmatrix} 14 & -10 \\ 16 & -31 \end{bmatrix}$$
3. Multiplicar por el escalar exterior ($11$):
   $$11 \cdot \begin{bmatrix} 14 & -10 \\ 16 & -31 \end{bmatrix} = \begin{bmatrix} 154 & -110 \\ 176 & -341 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}154&-110\\ 176&-341\end{bmatrix}$$

---

### Ejercicio 12
**Problema:**
$$\begin{bmatrix}0&-4\\ 1&-4\\ -1&5\\ -3&4\end{bmatrix} \cdot \left(\begin{bmatrix}-3&-1&-2&3\\ -1&4&-3&5\end{bmatrix} \cdot \begin{bmatrix}4&0\\ 1&-5\\ 2&5\\ 2&1\end{bmatrix}\right)$$[cite: 11]

**Desarrollo:**
1. Multiplicar las matrices del paréntesis derecho ($2\times4$ por $4\times2$):
   $$\begin{bmatrix} (-3)(4)+(-1)(1)+(-2)(2)+(3)(2) & (-3)(0)+(-1)(-5)+(-2)(5)+(3)(1) \\ (-1)(4)+(4)(1)+(-3)(2)+(5)(2) & (-1)(0)+(4)(-5)+(-3)(5)+(5)(1) \end{bmatrix}$$
   $$= \begin{bmatrix} -12-1-4+6 & 0+5-10+3 \\ -4+4-6+10 & 0-20-15+5 \end{bmatrix} = \begin{bmatrix} -11 & -2 \\ 4 & -30 \end{bmatrix}$$
2. Multiplicar por la matriz externa izquierda ($4\times2$ por $2\times2$):
   $$\begin{bmatrix} 0&-4\\ 1&-4\\ -1&5\\ -3&4 \end{bmatrix} \cdot \begin{bmatrix} -11 & -2 \\ 4 & -30 \end{bmatrix} = \begin{bmatrix} 0(-11)+(-4)(4) & 0(-2)+(-4)(-30) \\ 1(-11)+(-4)(4) & 1(-2)+(-4)(-30) \\ -1(-11)+5(4) & -1(-2)+5(-30) \\ -3(-11)+4(4) & -3(-2)+4(-30) \end{bmatrix}$$
   $$= \begin{bmatrix} -16 & 120 \\ -27 & 118 \\ 31 & -148 \\ 49 & -126 \end{bmatrix}$$

**Resultado:**
$$\begin{bmatrix}-16&120\\ -27&118\\ 31&-148\\ 49&-126\end{bmatrix}$$
