# Форма оплаты

Необходимо реализовать форму оплаты банковской картой.

## Макет

![payment_form](https://github.com/maxvipon/html-tasks/raw/master/payment_form.png)

Заполненный

![payment_form_filled](https://github.com/maxvipon/html-tasks/raw/master/payment_form_filled.png)

С размерами

![payment_form_filled](https://github.com/maxvipon/html-tasks/raw/master/payment_form_sizes.png)

## Требования

1. Номер карты по мере ввода должен разбиваться на группы по 4 цифры.
1. По номеру карты должна определится платежная система.
1. Поля формы должны валидироваться.

## Тех.данные

Цвет лицевой стороны ![#f0f0ee](https://placehold.it/9/f0f0ee/000?text=+) `#f0f0ee`  
Цвет оборотной стороны ![#e0ddd7](https://placehold.it/9/e0ddd7/000?text=+) `#e0ddd7`  
Цвет полоски на оборотной стороне ![#8e8b85](https://placehold.it/9/8e8b85/000?text=+) `#8e8b85`  
Цвет границы `rgba(0,0,0,.1)`

Поля ввода
* Размер шрифта `18px`  
* Граница:
  * обычное состояние – толщина `1px`, цвет `rgba(0,0,0,.2)`
  * фокус – толщина `2px`, цвет ![#ffdb4d](https://placehold.it/9/ffdb4d/000?text=+) `#ffdb4d`
  * ошибка ввода – толщина `2px`, цвет ![#ff6464](https://placehold.it/9/ff6464/000?text=+) `#ff6464`

### Иконки

* Visa `https://clck.ru/DHcqY`
* MasterCard `https://clck.ru/DHcqv`
* Maestro `https://clck.ru/DHcrB`
* Мир `https://clck.ru/DHcrX`
* Крестик `https://clck.ru/DHcrf`

### Номера платежных систем

* 2 – Мир
* 3 – Maestro
* 4 – VISA
* 5 – MasterCard



