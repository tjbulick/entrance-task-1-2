## Запуск

```
$ npm install
$ npm run start
```

# Задание 1 — найденные ошибки
Здесь собраны найденные ошибки и ссылки на PR'ы

## Неправильный импорт из `map.js`
Решение: либо добавить `default` для экспортируемой функции, либо использовать деструктивное присваивание из ES6. Было выбрано второе из соображений гибкости
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/2)

## Не были заданы размеры родительского элемента карты
Родительский элемент не отображался из-за отсутствия высоты и ширины
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/3)

## Не был добавлен `objectManager` на карту
Забыли добавить `objectManager` на карту
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/4)

## Перепутаны местами широта и долгота
Из-за этого метки отображались совсем не там где нужно
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/6)

## Переопределен цвет кластеров вместо диаграм
Кластерам задавался зелёный цвет, переопределяя отображение диаграммами
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/7)

## Незакрытый тег `div` в `details.js` (некритично)
Работало и без закрытого тега, но так правильнее
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/8)

## Проблема с использованием `this` в стрелочных функциях в `details.js`
`this` в стрелочных фунциях и в обычных функциях ссылаются на разные объекты
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/8)

## Меняем диапазон Y-оси в `chart.js`
График находился вне указанного диапазона
[PR](https://github.com/tjbulick/entrance-task-1-2/pull/9)