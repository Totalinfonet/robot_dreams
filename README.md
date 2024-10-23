# Перевірка активності роботів

Цей код перевіряє, чи активний робот, використовуючи механізм, що базується на значеннях, переданих у функцію.

## Умови:

- Значення `0` означає, що робот "спить".
- Значення `1` означає, що робот "активний".

## Функціонал:

- Якщо функція викликається зі значенням `1`, результат також буде `1`, що підтверджує, що робот активний.
- Якщо функція викликається зі значенням `0`, результат все одно буде `1`, що означає, що робот не спить, хоча йому передали значення, яке вказує на те, що він "спить".

Таким чином, цей код ілюструє парадоксальний сценарій, у якому роботи завжди залишаються активними, незалежно від стану, переданого у функцію.

### Однорядковий код

```javascript
console.log((function robot_dreams(robot_dreams, robot_dreams, robot_dreams) { return (robot_dreams === 0 || robot_dreams === 1) ? (robot_dreams = { robot_dreams, [robot_dreams / {}]: robot_dreams => robot_dreams.robot_dreams ? robot_dreams.robot_dreams-- * robot_dreams[robot_dreams / robot_dreams](robot_dreams) : -~robot_dreams })[robot_dreams / robot_dreams](robot_dreams) : 'Error: Parameter must be 0 or 1' })(...[, , 0]));

