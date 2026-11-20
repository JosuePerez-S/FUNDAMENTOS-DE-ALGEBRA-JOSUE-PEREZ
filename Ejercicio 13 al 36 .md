# Fundamentos de Álgebra – Unidad 3

## Encuentra la inversa de las siguientes matrices

### Ejercicio 13

**Problema:**

```math
\begin{bmatrix} 3 & -4 & -1 \\ -1 & 2 & 2 \\ -3 & -1 & 2 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [3\cdot 2\cdot 2+(-4)\cdot 2\cdot (-3)+(-1)\cdot (-1)\cdot (-1)]-[(-1)\cdot 2\cdot (-3)+3\cdot 2\cdot (-1)+(-4)\cdot (-1)\cdot 2] = [12+24+(-1)]-[6+(-6)+8]=[35]-[8] = 27
```

```math
\text{Cof}(A) = \begin{bmatrix} 6 & -4 & 7 \\ 9 & 3 & 15 \\ -6 & -5 & 2 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} 6 & 9 & -6 \\ -4 & 3 & -5 \\ 7 & 15 & 2 \end{bmatrix}
```

```math
A^{-1} = \frac{1}{27} \begin{bmatrix} 6 & 9 & -6 \\ -4 & 3 & -5 \\ 7 & 15 & 2 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} \frac{2}{9} & \frac{1}{3} & -\frac{2}{9} \\ -\frac{4}{27} & \frac{1}{9} & -\frac{5}{27} \\ \frac{7}{27} & \frac{5}{9} & \frac{2}{27} \end{bmatrix}
```

### Ejercicio 14

**Problema:**

```math
\begin{bmatrix} 3 & 0 & 2 \\ 4 & 5 & -2 \\ -1 & -3 & -4 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [3\cdot 5\cdot (-4)+0\cdot (-2)\cdot (-1)+2\cdot 4\cdot (-3)]-[2\cdot 5\cdot (-1)+3\cdot (-2)\cdot (-3)+0\cdot 4\cdot (-4)] = [(-60)+0+(-24)]-[(-10)+18+0]=[-84]-[8] = -92
```

```math
\text{Cof}(A) = \begin{bmatrix} -26 & 18 & -7 \\ -6 & -10 & 9 \\ -10 & 14 & 15 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} -26 & -6 & -10 \\ 18 & -10 & 14 \\ -7 & 9 & 15 \end{bmatrix}
```

```math
A^{-1} = -\frac{1}{92} \begin{bmatrix} -26 & -6 & -10 \\ 18 & -10 & 14 \\ -7 & 9 & 15 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} \frac{13}{46} & \frac{3}{46} & \frac{5}{46} \\ -\frac{9}{46} & \frac{5}{46} & -\frac{7}{46} \\ \frac{7}{92} & -\frac{9}{92} & -\frac{15}{92} \end{bmatrix}
```

### Ejercicio 15

**Problema:**

```math
\begin{bmatrix} -1 & 4 & -4 \\ 0 & -3 & 4 \\ 0 & 0 & 0 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [(-1)\cdot (-3)\cdot 0+4\cdot 4\cdot 0+(-4)\cdot 0\cdot 0]-[(-4)\cdot (-3)\cdot 0+(-1)\cdot 4\cdot 0+4\cdot 0\cdot 0] = [0+0+0]-[0+0+0]=[0]-[0] = 0
```

**Resultado:** $\det(A) = 0$, por lo tanto la matriz **no tiene inversa**.

### Ejercicio 16

**Problema:**

```math
\begin{bmatrix} 6 & -5 & 1 \\ -4 & 6 & -3 \\ 2 & 6 & -2 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [6\cdot 6\cdot (-2)+(-5)\cdot (-3)\cdot 2+1\cdot (-4)\cdot 6]-[1\cdot 6\cdot 2+6\cdot (-3)\cdot 6+(-5)\cdot (-4)\cdot (-2)] = [(-72)+30+(-24)]-[12+(-108)+(-40)]=[-66]-[-136] = 70
```

```math
\text{Cof}(A) = \begin{bmatrix} 6 & -14 & -36 \\ -4 & -14 & -46 \\ 9 & 14 & 16 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} 6 & -4 & 9 \\ -14 & -14 & 14 \\ -36 & -46 & 16 \end{bmatrix}
```

```math
A^{-1} = \frac{1}{70} \begin{bmatrix} 6 & -4 & 9 \\ -14 & -14 & 14 \\ -36 & -46 & 16 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} \frac{3}{35} & -\frac{2}{35} & \frac{9}{70} \\ -\frac{1}{5} & -\frac{1}{5} & \frac{1}{5} \\ -\frac{18}{35} & -\frac{23}{35} & \frac{8}{35} \end{bmatrix}
```

### Ejercicio 17

**Problema:**

```math
\begin{bmatrix} 1 & -5 & -5 \\ 7 & -3 & -1 \\ -2 & -6 & 0 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [1\cdot (-3)\cdot 0+(-5)\cdot (-1)\cdot (-2)+(-5)\cdot 7\cdot (-6)]-[(-5)\cdot (-3)\cdot (-2)+1\cdot (-1)\cdot (-6)+(-5)\cdot 7\cdot 0] = [0+(-10)+210]-[(-30)+6+0]=[200]-[-24] = 224
```

```math
\text{Cof}(A) = \begin{bmatrix} -6 & 2 & -48 \\ 30 & -10 & 16 \\ -10 & -34 & 32 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} -6 & 30 & -10 \\ 2 & -10 & -34 \\ -48 & 16 & 32 \end{bmatrix}
```

```math
A^{-1} = \frac{1}{224} \begin{bmatrix} -6 & 30 & -10 \\ 2 & -10 & -34 \\ -48 & 16 & 32 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} -\frac{3}{112} & \frac{15}{112} & -\frac{5}{112} \\ \frac{1}{112} & -\frac{5}{112} & -\frac{17}{112} \\ -\frac{3}{14} & \frac{1}{14} & \frac{1}{7} \end{bmatrix}
```

### Ejercicio 18

**Problema:**

```math
\begin{bmatrix} -5 & 1 & -4 \\ -3 & -6 & -4 \\ -1 & -1 & -4 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [(-5)\cdot (-6)\cdot (-4)+1\cdot (-4)\cdot (-1)+(-4)\cdot (-3)\cdot (-1)]-[(-4)\cdot (-6)\cdot (-1)+(-5)\cdot (-4)\cdot (-1)+1\cdot (-3)\cdot (-4)] = [(-120)+4+(-12)]-[(-24)+(-20)+12]=[-128]-[-32] = -96
```

```math
\text{Cof}(A) = \begin{bmatrix} 20 & -8 & -3 \\ 8 & 16 & -6 \\ -28 & -8 & 33 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} 20 & 8 & -28 \\ -8 & 16 & -8 \\ -3 & -6 & 33 \end{bmatrix}
```

```math
A^{-1} = -\frac{1}{96} \begin{bmatrix} 20 & 8 & -28 \\ -8 & 16 & -8 \\ -3 & -6 & 33 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} -\frac{5}{24} & -\frac{1}{12} & \frac{7}{24} \\ \frac{1}{12} & -\frac{1}{6} & \frac{1}{12} \\ \frac{1}{32} & \frac{1}{16} & -\frac{11}{32} \end{bmatrix}
```

### Ejercicio 19

**Problema:**

```math
\begin{bmatrix} -1 & -1 & -3 \\ -6 & -6 & -3 \\ 3 & 6 & -2 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [(-1)\cdot (-6)\cdot (-2)+(-1)\cdot (-3)\cdot 3+(-3)\cdot (-6)\cdot 6]-[(-3)\cdot (-6)\cdot 3+(-1)\cdot (-3)\cdot 6+(-1)\cdot (-6)\cdot (-2)] = [(-12)+9+108]-[54+18+(-12)]=[105]-[60] = 45
```

```math
\text{Cof}(A) = \begin{bmatrix} 30 & -21 & -18 \\ -20 & 11 & 3 \\ -15 & 15 & 0 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} 30 & -20 & -15 \\ -21 & 11 & 15 \\ -18 & 3 & 0 \end{bmatrix}
```

```math
A^{-1} = \frac{1}{45} \begin{bmatrix} 30 & -20 & -15 \\ -21 & 11 & 15 \\ -18 & 3 & 0 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} \frac{2}{3} & -\frac{4}{9} & -\frac{1}{3} \\ -\frac{7}{15} & \frac{11}{45} & \frac{1}{3} \\ -\frac{2}{5} & \frac{1}{15} & 0 \end{bmatrix}
```

### Ejercicio 20

**Problema:**

```math
\begin{bmatrix} -2 & 2 & -2 \\ 5 & -2 & 1 \\ -1 & 5 & 3 \end{bmatrix}
```

**Análisis:** Inversa de una matriz $3 \times 3$ con $A^{-1} = \frac{1}{\det(A)} \text{adj}(A)$. Primero se calcula $\det(A)$ por Sarrus; si es $0$ no existe la inversa.

**Desarrollo:**

```math
\det(A) = [(-2)\cdot (-2)\cdot 3+2\cdot 1\cdot (-1)+(-2)\cdot 5\cdot 5]-[(-2)\cdot (-2)\cdot (-1)+(-2)\cdot 1\cdot 5+2\cdot 5\cdot 3] = [12+(-2)+(-50)]-[(-4)+(-10)+30]=[-40]-[16] = -56
```

```math
\text{Cof}(A) = \begin{bmatrix} -11 & -16 & 23 \\ -16 & -8 & 8 \\ -2 & -8 & -6 \end{bmatrix}
```

```math
\text{adj}(A) = \text{Cof}(A)^{T} = \begin{bmatrix} -11 & -16 & -2 \\ -16 & -8 & -8 \\ 23 & 8 & -6 \end{bmatrix}
```

```math
A^{-1} = -\frac{1}{56} \begin{bmatrix} -11 & -16 & -2 \\ -16 & -8 & -8 \\ 23 & 8 & -6 \end{bmatrix}
```

**Resultado:**

```math
A^{-1} = \begin{bmatrix} \frac{11}{56} & \frac{2}{7} & \frac{1}{28} \\ \frac{2}{7} & \frac{1}{7} & \frac{1}{7} \\ -\frac{23}{56} & -\frac{1}{7} & \frac{3}{28} \end{bmatrix}
```

## Calcula el determinante usando la regla de Sarrus

### Ejercicio 21

**Problema:**

```math
\begin{vmatrix} -6 & 0 & -3 \\ 3 & 4 & -8 \\ 10 & 7 & 11 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [(-6)\cdot 4\cdot 11+0\cdot (-8)\cdot 10+(-3)\cdot 3\cdot 7]-[(-3)\cdot 4\cdot 10+(-6)\cdot (-8)\cdot 7+0\cdot 3\cdot 11] = [(-264)+0+(-63)]-[(-120)+336+0]=[-327]-[216] = -543
```

**Resultado:**

```math
\det(A) = -543
```

### Ejercicio 22

**Problema:**

```math
\begin{vmatrix} 10 & -5 & 0 \\ 7 & -2 & -1 \\ 5 & -3 & 1 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [10\cdot (-2)\cdot 1+(-5)\cdot (-1)\cdot 5+0\cdot 7\cdot (-3)]-[0\cdot (-2)\cdot 5+10\cdot (-1)\cdot (-3)+(-5)\cdot 7\cdot 1] = [(-20)+25+0]-[0+30+(-35)]=[5]-[-5] = 10
```

**Resultado:**

```math
\det(A) = 10
```

### Ejercicio 23

**Problema:**

```math
\begin{vmatrix} -9 & 11 & 5 \\ 9 & 10 & 0 \\ -2 & 9 & 10 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [(-9)\cdot 10\cdot 10+11\cdot 0\cdot (-2)+5\cdot 9\cdot 9]-[5\cdot 10\cdot (-2)+(-9)\cdot 0\cdot 9+11\cdot 9\cdot 10] = [(-900)+0+405]-[(-100)+0+990]=[-495]-[890] = -1385
```

**Resultado:**

```math
\det(A) = -1385
```

### Ejercicio 24

**Problema:**

```math
\begin{vmatrix} 5 & -7 & 12 \\ -11 & -5 & 7 \\ 1 & 10 & 11 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [5\cdot (-5)\cdot 11+(-7)\cdot 7\cdot 1+12\cdot (-11)\cdot 10]-[12\cdot (-5)\cdot 1+5\cdot 7\cdot 10+(-7)\cdot (-11)\cdot 11] = [(-275)+(-49)+(-1320)]-[(-60)+350+847]=[-1644]-[1137] = -2781
```

**Resultado:**

```math
\det(A) = -2781
```

### Ejercicio 25

**Problema:**

```math
\begin{vmatrix} -8 & 5 & 11 \\ 2 & 1 & 10 \\ 2 & 12 & 4 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [(-8)\cdot 1\cdot 4+5\cdot 10\cdot 2+11\cdot 2\cdot 12]-[11\cdot 1\cdot 2+(-8)\cdot 10\cdot 12+5\cdot 2\cdot 4] = [(-32)+100+264]-[22+(-960)+40]=[332]-[-898] = 1230
```

**Resultado:**

```math
\det(A) = 1230
```

### Ejercicio 26

**Problema:**

```math
\begin{vmatrix} -7 & 8 & 2 \\ 1 & -3 & 2 \\ 0 & 4 & 1 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [(-7)\cdot (-3)\cdot 1+8\cdot 2\cdot 0+2\cdot 1\cdot 4]-[2\cdot (-3)\cdot 0+(-7)\cdot 2\cdot 4+8\cdot 1\cdot 1] = [21+0+8]-[0+(-56)+8]=[29]-[-48] = 77
```

**Resultado:**

```math
\det(A) = 77
```

### Ejercicio 27

**Problema:**

```math
\begin{vmatrix} -6 & -4 & -11 \\ 3 & -9 & 6 \\ -12 & 1 & -11 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [(-6)\cdot (-9)\cdot (-11)+(-4)\cdot 6\cdot (-12)+(-11)\cdot 3\cdot 1]-[(-11)\cdot (-9)\cdot (-12)+(-6)\cdot 6\cdot 1+(-4)\cdot 3\cdot (-11)] = [(-594)+288+(-33)]-[(-1188)+(-36)+132]=[-339]-[-1092] = 753
```

**Resultado:**

```math
\det(A) = 753
```

### Ejercicio 28

**Problema:**

```math
\begin{vmatrix} 0 & 12 & 3 \\ 6 & 6 & -4 \\ -7 & -3 & -8 \end{vmatrix}
```

**Análisis:** Determinante $3 \times 3$ por Sarrus: suma de las diagonales principales menos suma de las diagonales secundarias.

**Desarrollo:**

```math
\det(A) = [0\cdot 6\cdot (-8)+12\cdot (-4)\cdot (-7)+3\cdot 6\cdot (-3)]-[3\cdot 6\cdot (-7)+0\cdot (-4)\cdot (-3)+12\cdot 6\cdot (-8)] = [0+336+(-54)]-[(-126)+0+(-576)]=[282]-[-702] = 984
```

**Resultado:**

```math
\det(A) = 984
```

## Calcula el determinante usando el método de cofactores

### Ejercicio 29

**Problema:**

```math
\begin{vmatrix} -6 & 1 & 5 & 8 & -7 \\ 3 & 9 & 9 & -3 & -6 \\ 6 & 5 & 0 & -10 & -5 \\ 4 & 0 & -1 & -3 & -7 \\ 9 & 10 & 2 & -10 & -4 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 3 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{31} = (+1) \begin{vmatrix} 1 & 5 & 8 & -7 \\ 9 & 9 & -3 & -6 \\ 0 & -1 & -3 & -7 \\ 10 & 2 & -10 & -4 \end{vmatrix} = -3420
```

```math
C_{32} = (-1) \begin{vmatrix} -6 & 5 & 8 & -7 \\ 3 & 9 & -3 & -6 \\ 4 & -1 & -3 & -7 \\ 9 & 2 & -10 & -4 \end{vmatrix} = -189
```

```math
C_{34} = (-1) \begin{vmatrix} -6 & 1 & 5 & -7 \\ 3 & 9 & 9 & -6 \\ 4 & 0 & -1 & -7 \\ 9 & 10 & 2 & -4 \end{vmatrix} = -3033
```

```math
C_{35} = (+1) \begin{vmatrix} -6 & 1 & 5 & 8 \\ 3 & 9 & 9 & -3 \\ 4 & 0 & -1 & -3 \\ 9 & 10 & 2 & -10 \end{vmatrix} = -639
```

```math
\det(A) = (6)(-3420) + (5)(-189) + (-10)(-3033) + (-5)(-639) = 12060
```

**Resultado:**

```math
\det(A) = 12060
```

### Ejercicio 30

**Problema:**

```math
\begin{vmatrix} -8 & -9 & 9 & 0 & 0 \\ 4 & -9 & 4 & -1 & 7 \\ 4 & -7 & -3 & 7 & -1 \\ 2 & 9 & 5 & 7 & -4 \\ -9 & -10 & 5 & -3 & 4 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 1 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{11} = (+1) \begin{vmatrix} -9 & 4 & -1 & 7 \\ -7 & -3 & 7 & -1 \\ 9 & 5 & 7 & -4 \\ -10 & 5 & -3 & 4 \end{vmatrix} = -4611
```

```math
C_{12} = (-1) \begin{vmatrix} 4 & 4 & -1 & 7 \\ 4 & -3 & 7 & -1 \\ 2 & 5 & 7 & -4 \\ -9 & 5 & -3 & 4 \end{vmatrix} = 4437
```

```math
C_{13} = (+1) \begin{vmatrix} 4 & -9 & -1 & 7 \\ 4 & -7 & 7 & -1 \\ 2 & 9 & 7 & -4 \\ -9 & -10 & -3 & 4 \end{vmatrix} = -5394
```

```math
\det(A) = (-8)(-4611) + (-9)(4437) + (9)(-5394) = -51591
```

**Resultado:**

```math
\det(A) = -51591
```

### Ejercicio 31

**Problema:**

```math
\begin{vmatrix} 3 & 2 & 7 & -8 & -10 \\ -1 & 6 & 6 & 0 & -2 \\ -1 & 5 & 2 & -9 & 2 \\ 0 & 3 & 5 & 2 & -7 \\ -2 & 8 & 0 & 9 & 10 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 2 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{21} = (-1) \begin{vmatrix} 2 & 7 & -8 & -10 \\ 5 & 2 & -9 & 2 \\ 3 & 5 & 2 & -7 \\ 8 & 0 & 9 & 10 \end{vmatrix} = 1419
```

```math
C_{22} = (+1) \begin{vmatrix} 3 & 7 & -8 & -10 \\ -1 & 2 & -9 & 2 \\ 0 & 5 & 2 & -7 \\ -2 & 0 & 9 & 10 \end{vmatrix} = 2111
```

```math
C_{23} = (-1) \begin{vmatrix} 3 & 2 & -8 & -10 \\ -1 & 5 & -9 & 2 \\ 0 & 3 & 2 & -7 \\ -2 & 8 & 9 & 10 \end{vmatrix} = -3217
```

```math
C_{25} = (-1) \begin{vmatrix} 3 & 2 & 7 & -8 \\ -1 & 5 & 2 & -9 \\ 0 & 3 & 5 & 2 \\ -2 & 8 & 0 & 9 \end{vmatrix} = -1396
```

```math
\det(A) = (-1)(1419) + (6)(2111) + (6)(-3217) + (-2)(-1396) = -5263
```

**Resultado:**

```math
\det(A) = -5263
```

### Ejercicio 32

**Problema:**

```math
\begin{vmatrix} -1 & -8 & -4 & 6 & -4 \\ -1 & -8 & 1 & -10 & 9 \\ 6 & -7 & 7 & 8 & 9 \\ -9 & 7 & 10 & 8 & 8 \\ -5 & 6 & 9 & 0 & 3 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 5 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{51} = (+1) \begin{vmatrix} -8 & -4 & 6 & -4 \\ -8 & 1 & -10 & 9 \\ -7 & 7 & 8 & 9 \\ 7 & 10 & 8 & 8 \end{vmatrix} = -2128
```

```math
C_{52} = (-1) \begin{vmatrix} -1 & -4 & 6 & -4 \\ -1 & 1 & -10 & 9 \\ 6 & 7 & 8 & 9 \\ -9 & 10 & 8 & 8 \end{vmatrix} = -10844
```

```math
C_{53} = (+1) \begin{vmatrix} -1 & -8 & 6 & -4 \\ -1 & -8 & -10 & 9 \\ 6 & -7 & 8 & 9 \\ -9 & 7 & 8 & 8 \end{vmatrix} = 32058
```

```math
C_{55} = (+1) \begin{vmatrix} -1 & -8 & -4 & 6 \\ -1 & -8 & 1 & -10 \\ 6 & -7 & 7 & 8 \\ -9 & 7 & 10 & 8 \end{vmatrix} = -23722
```

```math
\det(A) = (-5)(-2128) + (6)(-10844) + (9)(32058) + (3)(-23722) = 162932
```

**Resultado:**

```math
\det(A) = 162932
```

### Ejercicio 33

**Problema:**

```math
\begin{vmatrix} 10 & -10 & -2 & 4 & 4 \\ 2 & 4 & 9 & 2 & 2 \\ 2 & -5 & -3 & 6 & -8 \\ 5 & 10 & 6 & -3 & 4 \\ 1 & 8 & -4 & 2 & 3 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 1 (ninguna fila ni columna tiene ceros, se elige la primera) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{11} = (+1) \begin{vmatrix} 4 & 9 & 2 & 2 \\ -5 & -3 & 6 & -8 \\ 10 & 6 & -3 & 4 \\ 8 & -4 & 2 & 3 \end{vmatrix} = 3531
```

```math
C_{12} = (-1) \begin{vmatrix} 2 & 9 & 2 & 2 \\ 2 & -3 & 6 & -8 \\ 5 & 6 & -3 & 4 \\ 1 & -4 & 2 & 3 \end{vmatrix} = -2382
```

```math
C_{13} = (+1) \begin{vmatrix} 2 & 4 & 2 & 2 \\ 2 & -5 & 6 & -8 \\ 5 & 10 & -3 & 4 \\ 1 & 8 & 2 & 3 \end{vmatrix} = -738
```

```math
C_{14} = (-1) \begin{vmatrix} 2 & 4 & 9 & 2 \\ 2 & -5 & -3 & -8 \\ 5 & 10 & 6 & 4 \\ 1 & 8 & -4 & 3 \end{vmatrix} = 1089
```

```math
C_{15} = (+1) \begin{vmatrix} 2 & 4 & 9 & 2 \\ 2 & -5 & -3 & 6 \\ 5 & 10 & 6 & -3 \\ 1 & 8 & -4 & 2 \end{vmatrix} = 3465
```

```math
\det(A) = (10)(3531) + (-10)(-2382) + (-2)(-738) + (4)(1089) + (4)(3465) = 78822
```

**Resultado:**

```math
\det(A) = 78822
```

### Ejercicio 34

**Problema:**

```math
\begin{vmatrix} -5 & -9 & 10 & 8 & 0 \\ -5 & -9 & -2 & 0 & 10 \\ 3 & -4 & -5 & -10 & 2 \\ 1 & 8 & -6 & -4 & -6 \\ 7 & -3 & 3 & -1 & -3 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 1 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{11} = (+1) \begin{vmatrix} -9 & -2 & 0 & 10 \\ -4 & -5 & -10 & 2 \\ 8 & -6 & -4 & -6 \\ -3 & 3 & -1 & -3 \end{vmatrix} = -1942
```

```math
C_{12} = (-1) \begin{vmatrix} -5 & -2 & 0 & 10 \\ 3 & -5 & -10 & 2 \\ 1 & -6 & -4 & -6 \\ 7 & 3 & -1 & -3 \end{vmatrix} = -1704
```

```math
C_{13} = (+1) \begin{vmatrix} -5 & -9 & 0 & 10 \\ 3 & -4 & -10 & 2 \\ 1 & 8 & -4 & -6 \\ 7 & -3 & -1 & -3 \end{vmatrix} = 198
```

```math
C_{14} = (-1) \begin{vmatrix} -5 & -9 & -2 & 10 \\ 3 & -4 & -5 & 2 \\ 1 & 8 & -6 & -6 \\ 7 & -3 & 3 & -3 \end{vmatrix} = -493
```

```math
\det(A) = (-5)(-1942) + (-9)(-1704) + (10)(198) + (8)(-493) = 23082
```

**Resultado:**

```math
\det(A) = 23082
```

### Ejercicio 35

**Problema:**

```math
\begin{vmatrix} 2 & 0 & -5 & -4 & 0 \\ 8 & 10 & 8 & 10 & -5 \\ 10 & -9 & 3 & -4 & -3 \\ -3 & 9 & 4 & -8 & 3 \\ 2 & -8 & 2 & -1 & -6 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 1 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{11} = (+1) \begin{vmatrix} 10 & 8 & 10 & -5 \\ -9 & 3 & -4 & -3 \\ 9 & 4 & -8 & 3 \\ -8 & 2 & -1 & -6 \end{vmatrix} = 4505
```

```math
C_{13} = (+1) \begin{vmatrix} 8 & 10 & 10 & -5 \\ 10 & -9 & -4 & -3 \\ -3 & 9 & -8 & 3 \\ 2 & -8 & -1 & -6 \end{vmatrix} = -12905
```

```math
C_{14} = (-1) \begin{vmatrix} 8 & 10 & 8 & -5 \\ 10 & -9 & 3 & -3 \\ -3 & 9 & 4 & 3 \\ 2 & -8 & 2 & -6 \end{vmatrix} = -4900
```

```math
\det(A) = (2)(4505) + (-5)(-12905) + (-4)(-4900) = 93135
```

**Resultado:**

```math
\det(A) = 93135
```

### Ejercicio 36

**Problema:**

```math
\begin{vmatrix} -5 & -5 & -5 & -9 & -5 \\ -9 & 1 & -1 & -2 & -1 \\ 3 & 2 & -9 & 0 & 8 \\ -9 & -8 & -2 & -4 & -3 \\ 4 & 4 & 1 & 3 & 7 \end{vmatrix}
```

**Análisis:** Determinante $5 \times 5$ por cofactores. Se expande por la fila 3 (la que tiene más ceros) con $\det(A) = \sum a_{ij} C_{ij}$ y $C_{ij} = (-1)^{i+j} M_{ij}$.

**Desarrollo:**

```math
C_{31} = (+1) \begin{vmatrix} -5 & -5 & -9 & -5 \\ 1 & -1 & -2 & -1 \\ -8 & -2 & -4 & -3 \\ 4 & 1 & 3 & 7 \end{vmatrix} = -45
```

```math
C_{32} = (-1) \begin{vmatrix} -5 & -5 & -9 & -5 \\ -9 & -1 & -2 & -1 \\ -9 & -2 & -4 & -3 \\ 4 & 1 & 3 & 7 \end{vmatrix} = -9
```

```math
C_{33} = (+1) \begin{vmatrix} -5 & -5 & -9 & -5 \\ -9 & 1 & -2 & -1 \\ -9 & -8 & -4 & -3 \\ 4 & 4 & 3 & 7 \end{vmatrix} = -2709
```

```math
C_{35} = (+1) \begin{vmatrix} -5 & -5 & -5 & -9 \\ -9 & 1 & -1 & -2 \\ -9 & -8 & -2 & -4 \\ 4 & 4 & 1 & 3 \end{vmatrix} = -315
```

```math
\det(A) = (3)(-45) + (2)(-9) + (-9)(-2709) + (8)(-315) = 21708
```

**Resultado:**

```math
\det(A) = 21708
```
