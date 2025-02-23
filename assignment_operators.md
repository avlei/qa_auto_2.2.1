# Сокращенные операторы присваивания в JavaScript

| Оператор  | Эквивалентно | Описание |
|-----------|-------------|----------|
| `a += b`  | `a = a + b`  | Прибавляет значение `b` к `a` <br> ```js let a = 5; a += 2; console.log(a); // 7 ``` |
| `a -= b`  | `a = a - b`  | Вычитает `b` из `a` <br> ```js let a = 10; a -= 3; console.log(a); // 7 ``` |
| `a *= b`  | `a = a * b`  | Умножает `a` на `b` <br> ```js let a = 3; a *= 3; console.log(a); // 9 ``` |
| `a /= b`  | `a = a / b`  | Делит `a` на `b` <br> ```js let a = 9; a /= 3; console.log(a); // 3 ``` |
| `a %= b`  | `a = a % b`  | Остаток от деления `a` на `b` <br> ```js let a = 9; a %= 4; console.log(a); // 1 ``` |
| `a **= b` | `a = a ** b` | Возводит `a` в степень `b` <br> ```js let a = 5; a **= 2; console.log(a); // 25 ``` |
| `a &= b`  | `a = a & b`  | Побитовое И |
| `a |= b`  | `a = a | b`  | Побитовое ИЛИ |
| `a ^= b`  | `a = a ^ b`  | Побитовое исключающее ИЛИ |
| `a <<= b` | `a = a << b` | Побитовый сдвиг влево |
| `a >>= b` | `a = a >> b` | Побитовый сдвиг вправо |
| `a >>>= b` | `a = a >>> b` | Побитовый сдвиг вправо без знака |

# Функции инкремента и декремента 
## Функции инкремента и декремента в программировании связаны с операциями увеличения или уменьшения значения переменной.
### Инкремент – это операция увеличения значения переменной на 1.
js let a = 5; a++; // a теперь 6 console.log(a); // 6

### Декремент – это операция уменьшения значения переменной на 1.
js let b = 10; b--; // b теперь 9 console.log(b); // 9

