# Primer reto <u>Undefined</u>

Este será el primero de una serie de retos enfocados a ver qué tanto se nos da solucionar problemas de lógica o de maquetación (esto dependerá del reto) y de paso divertirnos un poco entre la comunidad.

Este reto tendrá dos ganadores, ya que tendremos dos categorías.

1. El código más eficiente, o sea, el código que ejecute la solución en menor tiempo.
2. La solución más creativa, sí, la solución que al ver el código nos haga pensar ¡Wow, jamás creí que se podía resolver así!

Dejando de lado la introducción, pasemos a hablar de qué tratará este reto.

## Artemisa a Diana

Los números romanos están representados por siete simbolos diferentes que son: `I`, `V`, `X`, `L`, `C`, `D` y `M`.

| Símbolo | Valor |
| ------- | ----- |
| I       | 1     |
| V       | 5     |
| X       | 10    |
| L       | 50    |
| C       | 100   |
| D       | 500   |
| M       | 1000  |

Por ejemplo, `2`es escrito como `II` en numeros romanos, simplemente escribiendo dos unos, uno a un lado del otro. `12`es escrito como `XII`, lo que es `X + II`, etcétera.

Los números romanos regularmente se escriben del más grande al mas pequeño, de izquierda a derecha. Pero el número `4` por ejemplo, no es `IIII`. En lugar de eso, este número se representa como `IV`. Esto es porque sí el `1` esta antes del `5` esto quiere decir que se le resta al `5`dando como resultado `4`. Esto también aplica al `9`, el cual se escribe como `IX`.

Te dejamos seis intancias en donde la resta es usada para representar un número:

- `I` se puedo poner antes del `V` (5) y del `X` (10) para tener `4` y `9`.
- `X` se puedo poner antes del `L` (50) y del `C` (100) para tener `40` y `90`.
- `C` se puedo poner antes del `D` (500) y del `M` (1000) para tener `400` y `900`.

### 🏆 Tu reto

Dado un número entero, conviértelo a un número romano.

Ejemplos

No. 01

```
Input: num = 3
Output: "III"
```

No. 02

```
Input: num = 4
Output: "IV"
```

No. 03

```
Input: num = 9
Output: "IX"
```

No. 04

```
Input: num = 58
Output: "LVIII"
Explicación: L = 50, V = 5, III = 3
```

No. 05

```
Input: num = 1994
Output: "MCMXCIV"
Explicación: M = 1000, CM = 900, XC = 90 and IV = 4
```

### ❌ Restricciones

Este reto puede ser desarrollado en el lenguaje de tu preferencia.

Ten en cuenta que `num`estará delimitado por:

```
1 <= num <= 3999
```

### 🚀 Empieza desde aquí

JavaScript

```js
/**
 * @param {number} num
 * @return {string}
 */
var intToRoman = function(num) {

};
```

Python

```py
class Solution:
    def intToRoman(self, num: int) -> str:
```
