# Лабораторна робота 1. Створення макета, взаємодія з елементами UI

## Завдання 1. Розробити вітальну листівку з днем народження.

Листівка має містити гарний текст, фоновий колір і зображення.
Приклад листівки

<p align="center">
  <img src="img/img_02.png" />
</p>

## Завдання 2. Розробити гру Word Scramble

Суть гри полягає в такому:

1. Комп'ютер обирає випадкове слово зі списку слів, перемішує літери в цьому слові і показує гравцеві.
2) Гравець повинен здогадатися - яке слово вибрав комп'ютер і ввести його в поле введення.
3) Якщо гравець вгадав слово - гра починається заново.
4. Якщо слово невірне, комп'ютер повідомляє гравця про це і гра триває.
Гра може виглядати приблизно так

<p align="center">
  <img src="img/img_01.gif" />
</p>

## Завдання 3. Написати додаток для надсилання селфі на пошту

Суть додатка полягає в такому:

1. У додатку є кнопка "Take a shot", натискання на яку відкриває вікно камери для отримання фото;
2. Після того, як ви зняли селфі, ваш застосунок отримує результат роботи застосунку у вигляді посилання на зображення;
3) (опціонально) Також у застосунку має бути віджет ImageView, у якому показуватиметься результат селфі;
4. Також у застосунку є кнопка "Send a selfie". Після натискання на кнопку, ваш застосунок має відкрити застосунки для роботи з електронною поштою. Тема листа - "Android <група> <прізвище>". Наприклад, "Android АІ-201 Іванов". Вміст листа - файл із фотографією. Слати на пошту hodovychenko@op.edu.ua

Ваше селфі є підтвердженням того, що лабораторну зробили ви. Постарайтеся реалізувати функціонал за допомогою Activity Result API.