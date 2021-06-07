Напиши тести для функції `getHumanAge`, яка приймає два цілих числа `catAge` і `dogAge` і перетворює 'тваринний' вік на 'людський'. Функція повертає масив, де першим елементом є 'людський' вік кота, а другим елементом є 'людський' вік собаки.

Для розрахунку 'людського' віку використовуються такі правила:
```
Вік кота:
15 людських років за перший рік кота
+9 людських років за другий рік кота
+4 людських роки за кожен наступний рік кота 

Вік собаки:
15 людських років за перший рік собаки
+9 людських років за другий рік собаки
+5 людських років за кожен наступний рік собаки
```

Примітка: кількість років у результаті округлюється в менший бік.

Приклади:
```
getHumanAge(9, 8) === [0, 0]
getHumanAge(15, 24) === [1, 2]
getHumanAge(28, 44) === [3, 6]
```

[Guideline](https://github.com/mate-academy/js_task-guideline/blob/master/README.md)

Read more about [Jest expectations](https://jestjs.io/uk/docs/expect)