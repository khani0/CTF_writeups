# Hotdog_Stand

## Задание

![Untitled](Hotdog_Stand_Img/Untitled.png)

Взглянем на сайт.

![Untitled](Hotdog_Stand_Img/Untitled1.png)

Главная страница представляет собой базовую аутентификацию, посмотрим есть ли на сервере что-что кроме этой страницы.

## Решение

![Untitled](Hotdog_Stand_Img/Untitled2.png)

Заметим, что на сервере присутствует файл robots.txt, в нем можно увидеть базу данных, которую можно скачать. Откроем ее.

![Untitled](Hotdog_Stand_Img/Untitled3.png)

Написав SQL запрос, получаем логин и пароль. Проходим аутентификацию и получаем флаг.

![Untitled](Hotdog_Stand_Img/Untitled4.png)

```jsx
sun{5l1c3d_p1cKl35_4nd_0N10N2}
```
