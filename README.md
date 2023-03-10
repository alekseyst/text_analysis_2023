# Современные методы текстового анализа

Это репозиторий курса Современные методы текстового анализа программы «Востоковедение» в 2023 году. В нём будут храниться все материалы курса. Ссылки на материалы будут появляться в таблице ниже.

## Программа

|  Дата 	|   Тема	|  Материалы 	|   [Записи лекций](https://disk.yandex.ru/d/iumxLgZ2x99hzg)	| Проверочное |
|:---:	|---	|:---:	|:---:	|:---:	|
|  03.02 	|  Введение. Обзор направлений в текстовом анализе. Предмет лингвистики. Digital humanities. 	|  [Лекция 1](https://docs.google.com/presentation/d/1UXCk2H2Z8kbeQgOwy7ZCf5PcvoxEBQBsAks9GgEQFyg/edit?usp=sharing) [Семинар 1](https://github.com/alekseyst/text_analysis_2023/blob/main/Seminar_1/Seminar_1_Instr.md) 	|  [Лекция 1](https://disk.yandex.ru/d/HcdEYEyKlvF5tQ) 	|
|  10.02	|  Корпусная лингвистика 1 	|   [Лекция 2](https://docs.google.com/presentation/d/1OVS8osiPMM5LICnTd71RMUx3xgcCHge02KLeK1pHT90/edit?usp=sharing) [Семинар 2](https://github.com/alekseyst/text_analysis_2023/blob/main/Seminar_2/Seminar_2_Instr.md)	|  [Лекция 2](https://disk.yandex.ru/d/xOqV7NqSHMFAiw) 	|
|  17.02	|  Корпусная лингвистика 2	|   [Лекция 3](https://docs.google.com/presentation/d/1dYBRLoxZdqLsKu9naNcgkMu3jo1AHejuJS27tFRG-L0/edit?usp=sharing) [Семинар 3](https://github.com/alekseyst/text_analysis_2023/blob/main/Seminar_3/Seminar_3_AntConc.md)	|  [Лекция 3](https://disk.yandex.ru/d/kX8ymTpgBDsKUw)	| Квиз 1, неудачный |
|   24.02	|  праздники — лекции нет 	|   [Семинар 4](https://github.com/alekseyst/text_analysis_2023/blob/main/Seminar_4/Seminar_4_InternetParsing.ipynb)	|   	|
|  03.03	|  Частотностные характеристики текста: Визуализация 	|   [Лекция 4](https://docs.google.com/presentation/d/1l4vIN7wn99zz1C4vHZ_eY71GT8_wOVkqRO2wS5a9A00/edit?usp=sharing) [Семинар 5](https://github.com/alekseyst/text_analysis_2023/blob/main/Seminar_5/Seminar_5_Annotation.ipynb)	|   [Лекция 4](https://disk.yandex.ru/d/a0W3vdrYX0ktng)	| Квиз 2 |
|   10.03	|  Частотностные характеристики текста: Базовые инструменты статистического анализа	| [Лекция 5](https://docs.google.com/presentation/d/1NYbKJ8WXo-jdoBYTse562DOFg1v0vYfAvHHDRWA0OwA/edit?usp=sharing) [Семинар 6](https://github.com/alekseyst/text_analysis_2023/blob/main/Seminar_6/Seminar_6_Visualization.ipynb)  	|  [Лекция 5](https://disk.yandex.ru/d/Kc23T6DI1GUcXQ) 	 	| Выдача ДЗ |
|   17.03	|  Инструменты компьютерной лингвистики 1: Именованные сущности, семантические вектора, анализ тональности	|   	|   | Квиз 3<br>Сдача ДЗ,<br>дедлайн — 16 марта |
|  24.03 	|  Инструменты компьютерной лингвистики 2: Что под обшивкой — машинное обучение и нейросети	|   	|   	|Квиз 4 |

## Домашнее задание

Единственное домашнее курса уже выслано каждому студенту на корпоративную почту. Дедлайн задания — 16 марта, четверг, 23.59. 

## Телеграм-чат

https://t.me/+Q4djsSCs2UgzNWRi

## Формула оценки

_Накопленная оценка_ = _0.5_ $\times$ _ДЗ_ + _0.5_ $\times$ _Квизы_

_Итоговая оценка_ = _0.7_ $\times$ _Накопленная оценка_ + _0.3_ $\times$ _Экзамен_

## Примеры вопросов квиза

1. В мультимедийном корпусе, в отличие от остальных, не бывает никакой аннотации.

Варианты ответа:

- Верно
- Неверно

<details>
  <summary>Ответ</summary>
  
   Неверно
  
</details>

2. Вне контекста словоформа _мыла_ может соответствовать больше, чем одной лемме (словарной форме). Сколько всего таких лемм?

Варианты ответа:

- 2
- 3
- 4
- в задании неточность, на самом деле словоформе соответствует только одна лемма

<details>
  <summary>Ответ</summary>
  
   2
    <br>  
   Пояснение: существительное _мыло_ и глагол _мыть_
  
</details>

3. Что из перечисленного относится к метаразметке? Вы можете выбрать один или несколько ответов.

- автор текста
- грамматический род существительных
- год рождения автора текста
- год создания корпуса

<details>
  <summary>Ответ</summary>
  
   автор текста и год рождения автора текста
  
</details>

Как, по материалу Национального корпуса русского языка (основной подкорпус), соотносятся частотности слов _черепаха_, _шляпа_ и _ибо_? (производите поиск по лемме)
- черепаха, шляпа, ибо
- шляпа, черепаха, ибо
- шляпа, ибо, черепаха
- ибо, шляпа, черепаха

<details>
  <summary>Ответ</summary>
  ибо, шляпа, черепаха
       <br>
 Пояснение: <em>черепаха</em> — 2331 вхождений, <em>шляпа</em> — 19954 вхождений, <em>ибо</em> — 83478 вхождений
</details>

Сколько всего текстов А. С. Пушкина есть в основном подкорпусе Национального корпуса русского языка?

- 138
- 429
- 573
- 682

<details>
  <summary>Ответ</summary>
  
   682
       <br>
   Пояснение: Подкорпус — Задать — Автор: А. С. Пушкин — количество текстов высвечивается наверху страницы

</details>


