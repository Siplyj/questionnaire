# Анкета

Моя реализация тестового задания от компании lun.ua
Реализация здесь: http://emptywall.design/lun/index.html

<b>Задание:</b>

В рамках данного задания Вам предлагается реализовать одностраничный сайт, предназначенный для анкетирования пользователей. Анкета заполняется в четыре шага, после чего выводится итоговая “страница” (экран).

<b>Первый шаг</b>

На первом шаге пользователь вводит свои имя и e-mail.

<b>Второй шаг</b>

На втором шаге анкетирования пользователь выбирает из выпадающего списка свою страну, а также город, в котором он живет.
К реализации этого шага предъявляются следующие требования:
<br>- данные для этих полей ввода находятся в файлах countries.json и cities.json;
<br>- список городов должен соответствовать выбранной стране;
<br>- плюсом будет возможность выбора города используя автодополнение текстового ввода (реализация данного пункта не является обязательной, но только поощряется).

<b>Третий шаг</b>

На третьем шаге пользователь из предложенного ему списка отмечает социальные сети, которыми он пользуется, и вводит соответствующие ссылки на страницы своих профилей в этих сетях. Отображать текстовое поле для ввода ссылки на страницу профиля нужно только для выбранных соц. сетей (когда соответствующий checkbox был отмечен пользователем).

<b>Четвертый шаг</b>

На четвертом шаге пользователь должен выбрать картинку, на которой изображен кот. В случае, если пользователь выбрал изображение, на котором изображено что-то иное, но только не кот, у него нету возможности перейти на итоговый экран анкетирования.

<b>Итоговый экран</b>

На итоговом экране необходимо вывести пользователю все данные, которые он ввел, а также дать ему возможность пройти анкету заново, нажав на соответствующую кнопку.

<b>Общие требования к реализации тестового задания</b>

К реализации всего задания предъявляются следующие требования:
<br>- все действия пользователя, совершаемые им на любом из шагов анкетирования, не должны приводить к перезагрузке страницы в браузере;
<br>- все вводимые пользователем данные должны проходить проверку на корректность;
<br>- на всех экранах (“страницах”) шагов анкеты должны присутствовать активные элементы для навигации: кнопки “вперед” и “назад”, а также кнопки каждого из шагов по-отдельности: “1-2-3-4”;
<br>- у пользователя не должно быть возможности перейти на следующий шаг анкетирования, не заполнив все предыдущие. Однако при этом он может вернуться на любой из уже пройденных им ранее шагов и изменить данные, которые он ввел;
<br>- верстка анкеты должна быть адаптивной, корректно отображаться и работать на мобильных устройствах (смартфонах и планшетах).

Допускается использование любых CSS- и JS-фреймворков, ровно как и реализация данного задания без использования каких-либо фреймворков.
