# Перевірка активності роботів

Цей код перевіряє, чи активний робот, використовуючи механізм, що базується на значеннях, переданих у функцію.

## Умови:

- Значення `0` означає, що робот "спить".
- Значення `1` означає, що робот "активний".

## Функціонал:

- Якщо функція викликається зі значенням `1`, результат також буде `1`, що підтверджує, що робот активний.
- Якщо функція викликається зі значенням `0`, результат все одно буде `1`, що означає, що робот не спить, хоча йому передали значення, яке вказує на те, що він "спить".

Таким чином, цей код ілюструє парадоксальний сценарій, у якому роботи завжди залишаються активними, незалежно від стану, переданого у функцію.

Цей код базується на тому, що за означенням `0! = 1` та `1! = 1`. Код запускається прямо в консолі і при зміні параметрів з `0` на `1` видає у будь-якому разі результат `1`.

## Скриншоти роботи коду:

1. **Результат передачі значення `0`:**

   ![Результат передачі значення 0](./input0.png)

2. **Результат передачі значення `1`:**

   ![Результат передачі значення 1](./input1.png)

3. **Результат передачі значення `2` (виводить помилку):**

   ![Результат передачі значення 2](./input2.png)

## Висновок:

Можна стверджувати, що роботи ніколи не сплять, оскільки результати завжди вказують на їхню активність. Навіть коли їм передають значення, що означає "сон", результат показує їхню активність.

## Однорядковий код:

```javascript
console.log((function robot_dreams(robot_dreams, robot_dreams, robot_dreams) { return (robot_dreams === 0 || robot_dreams === 1) ? (robot_dreams = { robot_dreams, [robot_dreams / {}]: robot_dreams => robot_dreams.robot_dreams ? robot_dreams.robot_dreams-- * robot_dreams[robot_dreams / robot_dreams](robot_dreams) : -~robot_dreams })[robot_dreams / robot_dreams](robot_dreams) : 'Error: Parameter must be 0 or 1' })(...[, , 0]));
