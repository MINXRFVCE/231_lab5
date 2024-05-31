<p align = "center">МИНИСТЕРСТВО НАУКИ И ВЫСШЕГО ОБРАЗОВАНИЯ<br>
РОССИЙСКОЙ ФЕДЕРАЦИИ<br>
ФЕДЕРАЛЬНОЕ ГОСУДАРСТВЕННОЕ БЮДЖЕТНОЕ<br>
ОБРАЗОВАТЕЛЬНОЕ УЧРЕЖДЕНИЕ ВЫСШЕГО ОБРАЗОВАНИЯ<br>
«САХАЛИНСКИЙ ГОСУДАРСТВЕННЫЙ УНИВЕРСИТЕТ»</p>
<br><br><br><br><br><br>
<p align = "center">Институт естественных наук и техносферной безопасности<br>Кафедра информатики<br>Чернявский Роман Евгеньевич</p>
<br><br><br>
<p align = "center"><br><strong>Лабораторная работа №5.«JS»</strong><br>01.03.02 Прикладная математика и информатика</p>
<br><br><br><br><br><br><br><br><br><br><br><br>
<p align = "right">Научный руководитель<br>
Соболев Евгений Игоревич</p>
<br><br><br>
<p align = "center">г. Южно-Сахалинск<br>2024 г.</p>
<br><br><br><br><br><br><br><br><br><br><br><br>

<h1 align = "center">Введение</h1>

<p><b>Среда разработки html (HyperText Markup Language)</b> — это язык разметки, который используется для создания веб-страниц. HTML определяет структуру содержимого веб-страницы, такие как заголовки, параграфы, списки, ссылки и изображения. HTML состоит из набора тегов, которые определяют различные элементы страницы и их отображение в браузере.</p>

<p><b>JavaScript</b> — мультипарадигменный язык программирования. Поддерживает объектно-ориентированный, императивный и функциональный стили.</p>

<br>
<h1 align = "center">Цели и задачи</h1>


<p>Требуется выполнить задания, применяя полученные знания на лекциях и взятые из интернета.</p>

<p> 1.	Создайте переменную str и присвойте ей значение 'hdfgv'. Обращаясь к отдельным символам этой строки выведите на экран символ 'h', символ 'd', символ 'v'. </p>

<p>2.	Напишите скрипт, который считает количество секунд в часе.</p>

<p>3.	Переделайте приведенный код так, чтобы в нем использовались операции +=, -=, *=, /=, ++, --. Количество строк кода при этом не должно измениться. Код для переделки: </p>
<p>var num = 1;</p>
<p>num = num + 12;</p>
<p>num = num - 14;</p>
<p>num = num * 5;</p>
<p>num = num / 7;</p>
<p>num = num + 1;</p>
<p>num = num - 1;</p>
<p>alert(num);</p>

<p>4.	Создайте переменную num и присвойте ей значение 3. Выведите значение этой переменной на экран с помощью метода alert.</p>

<p>5.	Создайте переменные a=10 и b=2. Выведите на экран их сумму, разность, произведение и частное (результат деления).</p>

<p>6.	Создайте переменные c=15 и d=2. Просуммируйте их, а результат присвойте переменной result. Выведите на экран значение переменной result. </p>

<p>7.	Создайте переменные a=10, b=2 и c=5. Выведите на экран их сумму.</p>

<p>8.	Создайте переменные a=17 и b=10. Отнимите от a переменную b и результат присвойте переменной c. Затем создайте переменную d, присвойте ей значение 7. Сложите переменные c и d, а результат запишите в переменную result. Выведите на экран значение переменной result.</p>

<p>9.	Напишите скрипт, который считает количество секунд в часе, в сутках, в месяце.</p>

<p>10.	Создайте три переменные - час, минута, секунда. С их помощью выведите текущее время в формате 'час:минута:секунда'.</p>

<p>11.	Создайте переменную, присвойте ей число. Возведите это число в квадрат. Выведите его на экран.</p>

<p>12.	Напишите однострочное решение, которое вычисляет сумму квадратных корней для всех чётных чисел целочисленного массива.</p>

<p>13.	Яблоко стоит 1.15, апельсин стоит 2.30. Сколько они стоят вместе – чему равна сумма 1.15 + 2.30 с точки зрения JavaScript?</p>

<p>14.	Какое будет выведено значение: let x = 5; alert(x++); ?</p>

<p>15.	Чему равно такое выражение: [ ] + false - null + true ?</p>

<p>16.	Что выведет этот код: let y = 1; let x = y = 2; console.log(x); ?</p>

<p>17.	Чему равна сумма [ ] + 1 + 2?</p>

<p>18.	Создайте переменные a6, a7, a8, a9, a10. Поместите в них результат выражений:</p>
<p>5 % 3,</p>
<p>3 % 5,</p>
<p>5 + '3',</p>
<p>'5' - 3,</p>
<p>75 + 'кг'</p>
  
<p>19.	Напишите скрипт, который находит площадь прямоугольника высота 23см. (в числовую переменную height), шириной 10см (в числовую переменную width), значение площади должно хранится в числовой переменной s.</p>
<p>20.	Напиши скрипт, который находит объем цилиндра высотой 10м (переменная heightC) и диаметром основания 4м (dC), результат поместите в переменную v.</p>
<p>21.	Даны размер ипотечного кредита (S — 2 млн.руб), процентная ставка (p  — 10%), кол-во лет (years — 5). Найти переплату по кредиту, значение переплаты должно содержаться в переменной perepl.</p>
<p>22.	Определите переменные str, num, flag и txt со значениями «Привет», 123, true, «true». При помощи оператора определения типа убедитесь, что переменных принадлежат типам: string, number, boolean.</p>
<p>23.	Дано число, необходимо вернуть противоположное число.</p>


<p></p>



<h1 align = "center">Решение</h1>

<p>Для выполнения этой лабораторной работы, я пользовался материалом из интернета и того, что мы проходили на лекциях</p>

<h2 align = "center">Файл "1.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" type="text/css" href="1.css">
    <style>
        h4 {
            font-size: 18px;
        }
    </style>
    <title>"Лабораторная работа №3"</title>
  </head>
  <body>
    <h3>Внешнее подключение</h3>
    <h4>Внутреннее подключение</h4>
    <div style="color: red; font-size: 20px;">
        Встроенное подключение
    </div>
  </body>
</html>
```

<h2 align = "center">Файл "1.css"</h2>

```
h3 {
    font-size: 20px;
    color: brown;
}
```

<h2 align = "center">Файл "2.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        p {
            color: red;
        }
    </style>
</head>
<body>
    <p>Первый абзац</p>
    <p>Второй абзац</p>
    <p>Третий абзац</p>
</body>
</html>
```

<h2 align = "center">Файл "3, 4, 5.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        h1 {
            color: green;
        }
        h2 {
            color: blue;
        }
        h3 {
            color: orange;
        }
    </style>
</head>
<body>
    <h1>Заголовок уровня 1</h1>
    <h2>Заголовок уровня 2</h2>
    <h3>Заголовок уровня 3</h3>
    <h1>Другой заголовок уровня 1</h1>
    <h2>Другой заголовок уровня 2</h2>
    <h3>Другой заголовок уровня 3</h3>
</body>
</html>
```

<h2 align = "center">Файл "6, 7.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        p:first-of-type {
            color: green;
        }
        p:nth-of-type(2) {
            color: red;
        }
    </style>
</head>
<body>
    <p>Этот абзац будет зеленого цвета.</p>
    <p>Этот абзац будет красного цвета.</p>
    <p>Этот абзац будет стандартного цвета.</p>
</body>
</html>
```

<h2 align = "center">Файл "8.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        h2 {
            width: 300px;
        }
    </style>
</head>
<body>
    <h2>Первый заголовок</h2>
    <h2>Второй заголовок</h2>
    <h2>Третий заголовок</h2>
</body>
</html>
```

<h2 align = "center">Файл "9.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        table {
            width: 400px;
            height: 200px;
            border: 1px solid black;
            border-collapse: collapse;
        }
        td {
            border: 1px solid black;
            padding: 5px;
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td>Ячейка 1</td>
            <td>Ячейка 2</td>
        </tr>
        <tr>
            <td>Ячейка 3</td>
            <td>Ячейка 4</td>
        </tr>
    </table>
</body>
</html>
```

<h2 align = "center">Файл "10, 11.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        h1 {
            text-align: center;
        }
        h2 {
            text-align: right;
        }
    </style>
</head>
<body>
    <h1>Заголовок 1</h1>
    <h1>Еще один заголовок 1</h1>
    <h2>Подзаголовок 2</h2>
    <h2>Еще один подзаголовок 2</h2>
</body>
</html>
```

<h2 align = "center">Файл "12.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Выравнивание текста по обоим краям</title>
<style>
  table {
    width: 100%;
  }
  td {
    padding: 0;
    vertical-align: top;
  }
</style>
</head>
<body>

<table>
  <tr>
    <td><p>Этот текст будет выровнен по обоим краям.</p></td>
    <td><p>Этот текст будет выровнен по обоим краям.</p></td>
  </tr>
</table>

</body>
</html>
```

<h2 align = "center">Файл "13.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Выравнивание текста по центру</title>
</head>
<body>
    <p>Этот текст не выровнен.</p>
    <p style="text-align: center;">Этот текст выровнен по центру.</p>
</body>
</html>
```

<h2 align = "center">Файл "14.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Выравнивание th по левому краю</title>
<style>
    table {
            width: 400px;
            height: 200px;
            border: 1px solid black;
            border-collapse: collapse;
        }
    th {
        border: 1px solid black;
        padding: 5px;
        text-align: left;
    }
</style>
</head>
<body>
<table>
    <tr>
        <th>Заголовок</th>
        <th>Заголовок</th>
        <th>Заголовок</th>
    </tr>
    <tr>
        <td>Ячейка</td>
        <td>Ячейка</td>
        <td>Ячейка</td>
    </tr>
</table>
</body>
</html>
```

<h2 align = "center">Файл "15.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Выравнивание td по центру</title>
<style>
    table {
            width: 400px;
            height: 200px;
            border: 1px solid black;
            border-collapse: collapse;
        }
    td {
        border: 1px solid black;
        padding: 5px;
        text-align: center;
    }
</style>
</head>
<body>
    <table>
        <tr>
            <td>Ячейка 1</td>
            <td>Ячейка 2</td>
            <td>Ячейка 3</td>
        </tr>
        <tr>
            <td>Ячейка 4</td>
            <td>Ячейка 5</td>
            <td>Ячейка 6</td>
        </tr>
    </table>
</body>
</html>
```

<h2 align = "center">Файл "16.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Выравнивание td по центру</title>
<style>
    table {
            width: 400px;
            height: 200px;
            border: 1px solid black;
            border-collapse: collapse;
        }
    td {
        border: 1px solid black;
        padding: 5px;
        text-align: center;
        font-weight: bold;
    }
</style>
</head>
<body>
    <table>
        <tr>
            <td>Ячейка 1</td>
            <td>Ячейка 2</td>
            <td>Ячейка 3</td>
        </tr>
        <tr>
            <td>Ячейка 4</td>
            <td>Ячейка 5</td>
            <td>Ячейка 6</td>
        </tr>
    </table>
</body>
</html>
```

<h2 align = "center">Файл "17.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>H1 Not Bold</title>
  <style>
    h1 {
      font-weight: normal;
    }
  </style>
</head>
  <body>

    <h1>Нежирный заголовок</h1>

    <h2>Жирный заголовок</h2>
  </body>
</html>
```

<h2 align = "center">Файл "18.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Non-Bold TH, H1 and H2</title>
  <style>
    table {
            width: 400px;
            height: 200px;
            border: 1px solid black;
            border-collapse: collapse;
        }
    td {
        border: 1px solid black;
        padding: 5px;
        text-align: center;
    }
    th {
      font-weight: normal;
    } 
    h1, h2 {
      font-weight: normal;
    }
  </style>
</head>
<body>
  <table>
    <tr>
      <th>Нежирный заголовок таблицы</th>
    </tr>
    <tr>
      <td>Содержимое ячейки таблицы</td>
    </tr>
  </table>

  <h1>Нежирный заголовок H1</h1>
  <h2>Нежирный заголовок H2</h2>
</body>
</html>
```

<h2 align = "center">Файл "19.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>All H2s in Italics</title>
  <style>
    h2 {
      font-style: italic;
    }
  </style>
</head>
<body>

  <h2>Курсив</h2>
  <h3>Не курсив</h3>

</body>
</html>
```

<h2 align = "center">Файл "20.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="stylesheet" type="text/css" href="20.css">
    <title>Paragraph Styling</title>
</head>
<body>

    <p>Это первый абзац. Он не должен быть в курсиве.</p> 
    <p><i>Этот абзац должен быть в курсиве.</i></p> 
    <p><i>Третий абзац также в курсиве.</i></p>

</body>
</html>
```

<h2 align = "center">Файл "21.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>H2 - 20px</title>
    <style>
      h2 {
        font-size: 20px;
      }
    </style>
  </head>
  <body>
    <h2>Заголовок h2</h2>
    <h2>Еще один заголовок h2</h2>
    <h2>И еще один заголовок h2</h2>
  </body>
</html>
```

<h2 align = "center">Файл "22.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>P Styling</title>
  <style>
    p {
      font-size: 15px;
    }
  </style>
</head>
<body>
  <p>Это первый абзац.</p>
  <p>Это второй абзац.</p>
  <p>Это третий абзац.</p>
</body>
</html>
```

<h2 align = "center">Файл "23.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fonts</title>
  <style>
    p {
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>
  <p>Это первый абзац.</p>
  <p>Это второй абзац.</p>
  <p>Это третий абзац.</p>
</body>
</html>
```

<h2 align = "center">Файл "24.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fonts</title>
  <style>
    h2 {
      font-family: "Times New Roman", Times, serif;
    }
  </style>
</head>
<body>
  <h2>Заголовок h2</h2>
  <h2>Еще один заголовок h2</h2>
</body>
</html>
```

<h2 align = "center">Файл "25.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Fonts</title>
  <style>
    h3 {
      font-family: Arial, sans-serif;
    }
  </style>
</head>
<body>
  <h3>Заголовок h3</h3>
  <h3>Еще один заголовок h3</h3>
</body>
</html>
```

<h2 align = "center">Файл "26.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>line-height</title>
  <style>
    p {
      line-height: 30px;
    }
  </style>
</head>
<body>
  <p>Это первый абзац.</p>
  <p>Это второй абзац.</p>
</body>
</html>
```

<h2 align = "center">Файл "27.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Commented Styles</title>
  <style>
    p {
      /* line-height: 30px; */
      font-size: 16px; /* Добавленный стиль */
    }
  </style>
</head>
<body>
  <p>Это первый абзац.</p>
  <p>Это второй абзац.</p>
</body>
</html>
```

<h2 align = "center">Файл "28.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>P Styles</title>
  <style>
    p {
      font-family: Arial, sans-serif;
      font-size: 16px;
      font-style: italic;
      font-weight: bold;
      line-height: 30px;
    }
  </style>
</head>
<body>
  <p>Это текст с примененными стилями: шрифт Arial, 16 пикселей, курсив, жирный, межстрочный интервал 30px.</p>
</body>
</html>
```

<h2 align = "center">Файл "29.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>h1 styles</title>
  <style>
    h1 {
      font-family: Verdana, sans-serif;
      font-size: 20px;
      font-weight: normal;
    }
  </style>
</head>
<body>
  <h1>Заголовок h1 с нежирным шрифтом, размером 20 пикселей и шрифтом Verdana.</h1>
</body>
</html>
```

<h2 align = "center">Файл "30.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Красная строка в абзацах</title>
  <style>
    p {
      text-indent: 30px;
    }
  </style>
</head>
<body>
  <p>Это текст с красной строкой, установленной в 30px.</p>
  <p>Еще один абзац с красной строкой.</p>
</body>
</html>
```

<h2 align = "center">Файл "31.html"</h2>

```

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Remove Red Line</title>
  <style>
    p {
        margin-top: 0;
    }
    p:first-child {
        margin-top: 1em;
        text-indent: 30px;
    }
  </style>
</head>
<body>
  <p>Это первый абзац.</p>
  <p>Это второй абзац, и он будет начинаться без красной строки.</p>
</body>
</html>
```

<h2 align = "center">Файл "32.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vertical Align Top in Table Cells</title>
  <style>
    table {
        width: 100%;
        border-collapse: separate;
        border-spacing: 0;
    }
    th, td {
        padding: 10px;
        text-align: left;
        vertical-align: top;
        border: 1px solid #000;
    }
  </style>
</head>
<body>
  <table>
    <tr>
      <th>Заголовок 1</th>
      <th>Заголовок 2</th>
      <th>Заголовок 3</th>
    </tr>
    <tr>
      <td>Данные 1</td>
      <td>Данные 2</td>
      <td>Данные 3</td>
    </tr>
    <tr>
      <td>Данные 4</td>
      <td>Данные 5</td>
      <td>Данные 6</td>
    </tr>
  </table>
</body>
</html>
```

<h2 align = "center">Файл "33.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vertical Align Top in Table Cells</title>
  <style>
    th {
      position: relative;
      border: 1px solid #000;
    }   

    th::before {
      content: '';
      display: inline-block;
      height: 100%;
      vertical-align: middle;
      margin-right: -4px;
    }

    th > span {
      display: inline-block;
      vertical-align: middle;
    }
  </style>
</head>
<body>
  <table>
    <tr>
      <th><span>Заголовок 1</span></th>
      <th><span>Заголовок 2</span></th>
      <th><span>Заголовок 3</span></th>
    </tr>
  </table>
</body>
</html>
```

<h2 align = "center">Файл "34.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Same Page As Example</title>
    <style>
        p {
            text-indent: 25px;
            font-family: Calibri;
            text-align: justify;
        }
    </style>
</head>
<body>
    <div style="width: 300px">
        <p style="color: blue; font-weight: bold; font-size: 18px; text-align: center;text-indent:0;">
            Что такое CMS
        </p>

        <p><span style="color: red; font-weight: bold; ">CMS</span> - «система управления контентом» (<span style="color:red; font-weight: bold;">движок</span>) - написанная РНР-программистами основа
            для сайта, с помощью которой вы сможете управлять сайтом (добавлять контент, менять пункты меню и т.п.) не зная HTML и CSS.
        </p>
        <p>
            Однако, для того чтобы сделать сайт с
            помощью <span style="color: red; font-weight: bold; ">CMS</span> <span style="font-style: italic; color:blue">потребуются услуги</span> программиста, и дизайнера, и верстальщика. И капиталовложения.
        </p>
        <p style="color: blue; font-weight: bold; font-size: 18px; text-align: center;text-indent:0;">
            Какие бывают cms
        </p>
        <p>
            Бывают различные системы управления контентом: для интернет-магазинов, для блогов, для форумов и т.д.
        </p>
        <p style="color: blue; font-weight: bold; font-size: 18px; text-align: center;text-indent:0;">
            Примеры cms
        </p>
        <p>
            <span style="font-style: italic; color:blue">Примеры популярных CMS:</span> Joomla, WordPress (для блогов), PhpBB (для форумов).
        </p>
        <p>
            <span style="color: red; font-weight: bold; ">CMS-ки</span>
            бывают <span style="font-style: italic; color:blue">платные</span> и <span style="font-style: italic; color:blue">бесплатные.</span>
        </p>
    </div>


</body>
</html>
```

<h2 align = "center">Файл "35.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Same Page As Exapmle 2</title>
    <style>
        p {
            font-family: Calibri;
        }
    </style>
</head>
<body>
    <h1 style="text-indent: 40px; text-align: center;color: red">Что нужно знать, чтобы делать сайты</h1>
    <div style="width: 600px">
        <ol style="color: red">
            <li style="font-weight: bold">HTML</li>
            <li style="color: blue">CSS</li>
            <li>PHP</li>
            <li>SOL</li>
            <li>JavaScript</li>
            <li>jQuery</li>
            <li>Flash</li>
            <li>SEO</li>
        </ol>
        <h2 style="color:green">PHP и JavaScript</h2>
        <p>
            Языки программирования <span style="font-weight: bold; font-size: 25px; color: red">PHP</span> и <span style="font-weight: bold; font-size: 25px; color: red">JavaScript</span> позволяют сделать сайт динамичным, то есть реагирующим на действия пользователя. Например, можно сделать красивую выпадающую менюшку или слайдер
        </p>
        <h2 style="color:green">Виды скриптов</h2>
        <p>
            Для этого пишутся скрипты (англ. <span style="font-weight: bold; font-style: italic; color: blue">script</span> - «сценарий») - программы, позволяющие реагировать на действия пользователя. Скрипты бывают двух видов:
        </p>
        <ul style="color: brown">
            <li>те, которые выполняются на сервере, а результат их выполнения приходит в браузер к пользователю уже в готовом виде. Это скрипты, написанные на языке PHP. На нем пишутся CMS-ки - системы управления контентом.</li>
            <li>те, которые выполняются прямо в браузере пользователя. Это скрипты, написанные на языке JavaScript. Они чаще всего используются для, того чтобы сделать страницу более удобной и красивой.</li>
        </ul>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "36.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animated Button with CSS</title>
    <style>
        .button {
        background-color: #4CAF50;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        font-size: 16px;
        margin: 4px;
        transition: background-color 0.5s;
        cursor: pointer;
        }

        .button:hover {
            background-color: white;
        }

        .button:active {
            background-color: #3e8e41;
            transform: translateY(4px);
        }
    </style>
</head>
<body>
  <button class="button">Click Me!</button>
</body>
</html>
```

<h2 align = "center">Файл "37.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animated Button with CSS</title>
    <style>
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            grid-gap: 20px;
            padding: 20px;
        }

        .item {
            background-color: #f7f7f7;
            padding: 20px;
            border: 1px solid #ddd;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        .item-header {
            text-align: center;
            font-weight: bold;
            color: #333;
        }

        .item-content {
            text-align: justify;
            font-size: 16px;
            line-height: 1.5;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="item">
          <h2 class="item-header">Заголовок 1</h2>
          <div class="item-content">
            Контент элемента 1...
          </div>
        </div>
        <div class="item">
          <h2 class="item-header">Заголовок 2</h2>
          <div class="item-content">
            Контент элемента 2...
          </div>
        </div>
      </div>
</body>
</html>
```

<h2 align = "center">Файл "38.html"</h2>

```
<!DOCTYPE html>
<html>
<head>
    <title>Form Styling</title>
    <style>
        form {
            width: 70%;
            margin: 40px auto;
            padding: 20px;
            border: 1px solid #ccc;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        input[type="text"], input[type="email"], input[type="password"] {
            width: 90%;
            height: 40px;
            margin-bottom: 20px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
        }

        input[type="submit"] {
            width: 100%;
            height: 40px;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #4CAF50;
            color: #fff;
            cursor: pointer;
        }

        label {
            display: block;
            margin-bottom: 10px;
        }

        .error {
            color: red;
            font-size: 12px;
            margin-bottom: 10px;
        }
    </style>
</head>
<body>
    <form>
        <label for="name">Name:</label>
        <input type="text" id="name" name="name"><br><br>
        <label for="email">Email:</label>
        <input type="email" id="email" name="email"><br><br>
        <label for="password">Password:</label>
        <input type="password" id="password" name="password"><br><br>
        <input type="submit" value="Submit">
        <div class="error">Please fill in all fields</div>
    </form>
</body>
</html>
```

<h2 align = "center">Файл "39.html"</h2>

```
<!DOCTYPE html>
<html>
<head>
    <title>Animated Navigation Menu</title>
    <style>
        .nav {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 60px;
            background-color: #333;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 0 20px;
            z-index: 1000;
        }

        .nav ul {
            list-style: none;
            margin: 0;
            padding: 0;
            display: flex;
        }

        .nav li {
            margin-right: 20px;
        }

        .nav a {
            color: #fff;
            text-decoration: none;
            transition: color 0.2s ease;
        }

        .nav a:hover {
            color: #ccc;
        }

        .nav .hamburger {
            display: none;
        }

        @media (max-width: 767px) {
            .nav {
                height: 40px;
            }

            .nav ul {
                display: none;
            }

            .nav .hamburger {
                display: block;
                position: absolute;
                top: 10px;
                right: 20px;
                cursor: pointer;
            }

            .nav .hamburger span {
                display: block;
                width: 30px;
                height: 2px;
                background-color: #fff;
                margin-bottom: 5px;
                transition: transform 0.2s ease;
            }

            .nav .hamburger span:last-child {
                margin-bottom: 0;
            }

            .nav .hamburger.active span:first-child {
                transform: translateY(10px) rotate(45deg);
            }

            .nav .hamburger.active span:last-child {
                transform: translateY(-10px) rotate(-45deg);
            }

            .nav ul.active {
                display: block;
                position: absolute;
                top: 40px;
                left: 0;
                width: 100%;
                background-color: #333;
                padding: 20px;
            }

            .nav ul.active li {
                margin-bottom: 10px;
            }

            .nav ul.active a {
                color: #fff;
            }
        }
    </style>
</head>
<body>
    <nav class="nav">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
        <div class="hamburger">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </nav>

    <script>
        document.querySelector('.hamburger').addEventListener('click', function() {
            this.classList.toggle('active');
            document.querySelector('.nav ul').classList.toggle('active');
        });
    </script>
</body>
</html>
```

<h2 align = "center">Файл "40.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        /* Селектор по элементу */
        p {
            color: blue;
        }

        /* Селектор по классу */
        .my-class {
            font-weight: bold;
        }

        /* Селектор по идентификатору */
        #my-id {
            background-color: yellow;
        }

        /* Селектор по атрибуту */
        input[type="text"] {
            border: 1px solid gray;
        }

        /* Селектор потомка */
        div p {
            font-style: italic;
        }

        /* Селектор дочернего элемента */
        ul > li {
            list-style-type: square;
        }

        /* Селектор псевдокласса */
        a:hover {
            text-decoration: underline;
        }

        /* Селектор псевдоэлемента */
        p::first-line {
            text-transform: uppercase;
        }

        /* Селектор-брат */
        h2 + p {
            margin-top: 0;
        }
    </style>
</head>
<body>

    <p>Селектор по элементу.</p>

    <p class="my-class">Селектор по классу.</p>
    <div>
        <p>Это абзац внутри div с применением селектора потомка.</p>
    </div>

    <ul>
        <li>Первый пункт списка</li>
        <li>Второй пункт списка</li>
    </ul>

    <input type="text" placeholder="Это поле ввода с применением селектора по атрибуту">

    <a href="#">Ссылка</a>

    <h2>Заголовок</h2>
    <p>Это абзац, который следует непосредственно за заголовком второго уровня.</p>

    <p>Благодарим вас за проявленный интерес к нашей компании, основному производителю воздушных судов</p>
</body>
</html>
```

<h2 align = "center">Файл "41.html"</h2>

```
<!DOCTYPE html>
<html>
<head>
    <title>Gradient</title>
    <style>
        body {
            height: 100vh;
            background: linear-gradient(45deg, #4158D0 0%, #4158D0 30%, #C850C0 30%, #C850C0 60%, #FFCC70 60%, #FFCC70 100%);
        }
    </style>
</head>
<body>
    
</body>
</html>
```

<h2 align = "center">Файл "42.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>fonts</title>
    <style>
        .font-example {
            font-family: Arial, sans-serif;
            font-size: 20px;
            font-weight: bold;
            font-style: italic;
            color: #333;
            text-decoration: underline;
            text-transform: uppercase;
            letter-spacing: 2px;
            line-height: 1.5;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="font-example">
        Пример текста со стилизованным шрифтом
    </div>
</body>
</html>
```

<h2 align = "center">Файл "43.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Slider</title>
    <style>
        .slider {
            width: 500px;
            height: 300px;
            overflow: hidden;
            position: relative;
        }

        .slider-inner {
            width: 500%;
            height: 100%;
            display: flex;
            animation: slideAnimation 10s linear infinite;
        }

        .slide {
            width: 20%;
            height: 100%;
        }

        .slide img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }

        @keyframes slideAnimation {
            0% {
                transform: translateX(0);
            }

            25% {
                transform: translateX(-100%);
            }

            50% {
                transform: translateX(-200%);
            }

            75% {
                transform: translateX(-300%);
            }

            100% {
                transform: translateX(-400%);
            }
        }
    </style>
</head>
<body>


<div class="slider">
    <div class="slider-inner">
        <div class="slide">
            <img src="1.jpg" alt="Image 1">
        </div>
        <div class="slide">
            <img src="2.jpg" alt="Image 2">
        </div>
        <div class="slide">
            <img src="3.jpg" alt="Image 3">
        </div>
        <div class="slide">
            <img src="4.jpg" alt="Image 4">
        </div>
        <div class="slide">
            <img src="5.jpg" alt="Image 5">
        </div>
    </div>
</div>
</body>
</html>
```

<h2 align = "center">Файл "44.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style>
        .container {
            width: 400px;
            height: 300px;
            border: 1px solid black;
            position: relative;
        }

        .static {
            position: static;
            width: 150px;
            height: 150px;
            background-color: #8ed28c;
        }

        .relative {
            position: relative;
            top: 50px;
            left: 50px;
            width: 150px;
            height: 150px;
            background-color:limegreen;
        }

        .absolute {
            position: absolute;
            top: 100px;
            left: 100px;
            width: 150px;
            height: 150px;
            background-color:darkgreen;
        }

        .fixed {
            position: fixed;
            top: 20px;
            right: 20px;
            width: 150px;
            height: 150px;
            background-color:chocolate;
        }

        .sticky {
            position: sticky;
            top: 10px;

        }

        .float-left {
            float: left;
            width: 150px;
            height: 150px;
            background-color: violet;
            margin-right: 10px;
        }

        .float-right {
            float: right;
            width: 150px;
            height: 150px;
            background-color:aqua;
            margin-left: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="static">Static</div>
        <div class="relative">Relative</div>
        <div class="absolute">Absolute</div>
        <div class="fixed">Fixed</div>
        <div class="sticky">Sticky</div>
        <div class="float-left"></div>
        <div class="float-right"></div>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "45.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adaptive Layout Example</title>
    <link rel="stylesheet" href="45.css" media="all">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <section>
            <h1>Welcome to our website!</h1>
            <p>Спасибо, что посетили наш сайт</p>
        </section>
        <aside>
            <h2>Latest News</h2>
            <ul>
                <li><a href="#">News Item 1</a></li>
                <li><a href="#">News Item 2</a></li>
                <li><a href="#">News Item 3</a></li>
            </ul>
        </aside>
    </main>
    <footer>
        <p>&copy; 2024 Adaptive Layout Example</p>
    </footer>
</body>
</html>
```

<h2 align = "center">Файл "45.css"</h2>

```
body {
    font-size: 16px;
    margin: 0;
    padding: 0;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
}

nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: space-between;
}

nav li {
    margin-right: 20px;
}

main {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
}

section {
    flex-basis: 60%;
    padding: 2em;
}

aside {
    flex-basis: 30%;
    padding: 2em;
    background-color: #f7f7f7;
    border: 1px solid #ddd;
}

footer {
    background-color: #333;
    color: #fff;
    padding: 1em;
    text-align: center;
    clear: both;
}

@media (max-width: 480px) {
    body {
        font-size: 14px;
    }
    nav ul {
        flex-direction: column;
    }
    nav li {
        margin-right: 0;
    }
    main {
        flex-direction: column;
    }
    section {
        flex-basis: 100%;
    }
    aside {
        flex-basis: 100%;
        margin-top: 20px;
    }
}

/* Styles for tablets */
@media (min-width: 481px) and (max-width: 768px) {
    body {
        font-size: 16px;
    }
    nav ul {
        flex-direction: row;
    }
    main {
        flex-direction: row;
    }
    section {
        flex-basis: 70%;
    }
    aside {
        flex-basis: 30%;
    }
}

/* Styles for desktops */
@media (min-width: 769px) {
    body {
        font-size: 18px;
    }
    nav ul {
        flex-direction: row;
    }
    main {
        flex-direction: row;
    }
    section {
        flex-basis: 60%;
    }
    aside {
        flex-basis: 30%;
    }
}
```

<h2 align = "center">Файл "46.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Animations Example</title>
    <style>
        .disappear {
            animation: disappear 2s forwards;
        }
        @keyframes disappear {
            0% {
                opacity: 1;
            }
            100% {
                opacity: 0;
                visibility: hidden;
            }
        }

        .slide-in {
            animation: slide-in 2s;
        }
        @keyframes slide-in {
            0% {
                transform: translateX(-100%);
            }
            100% {
                transform: translateX(0);
            }
        }

        .rotate {
            animation: rotate 2s infinite;
        }
        @keyframes rotate {
            0% {
                transform: rotate(0deg);
            }
            100% {
                transform: rotate(360deg);
            }
        }

        .pulse {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0% {
                transform: scale(1);
            }
            50% {
                transform: scale(1.1);
            }
            100% {
                transform: scale(1);
            }
        }

        .typewriter {
            animation: typewriter 2s;
        }
        @keyframes typewriter {
            0% {
                width: 0;
            }
            100% {
                width: 100%;
            }
        }

        .bounce {
            animation: bounce 2s infinite;
        }
        @keyframes bounce {
            0% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
            100% {
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <button onclick="document.getElementById('disappearing-element').classList.add('disappear')">Make it disappear!</button>
    <div id="disappearing-element">
        <h1>I'm going to disappear!</h1>
    </div>
    <p class="slide-in">Slide-in Animation</p>
    <div class="rotate">
        <img src="rotate.jpg" alt="Rotate Icon">
    </div>
    <button class="pulse">Pulse Animation</button>
    <div class="typewriter">
        <p>This is a typewriter effect</p>
    </div>
    <div class="bounce">
        <img src="bounce.jpg" alt="Bounce Icon">
    </div>
</body>
</html>
```

<h2 align = "center">Файл "47.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Cards</title>
    <style>
        .card-container {
            width: 300px;
            background-color: #fff;
            padding: 20px;
            border: 1px solid #ddd;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin: 20px;
        }

        .card-container img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            border-radius: 10px 10px 0 0;
        }

        .card-container h2 {
            font-size: 18px;
            margin-top: 10px;
        }

        .card-container p {
            font-size: 14px;
            color: #666;
        }

        .card-container span {
            font-size: 16px;
            font-weight: bold;
            color: #333;
        }

        .card-container button {
            background-color: #333;
            color: #fff;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
        }

        .grid-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            grid-gap: 20px;
        }

        .card-container:hover {
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
        }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="card-container">
            <img src="product1.jpg" alt="Product 1 Image">
            <h2>Product 1</h2>
            <p>This is a description of product 1.</p>
            <span>Price: $19.99</span>
            <button>Add to Cart</button>
        </div>

        <div class="card-container">
            <img src="product2.png" alt="Product 2 Image">
            <h2>Product 2</h2>
            <p>This is a description of product 2.</p>
            <span>Price: $29.99</span>
            <button>Add to Cart</button>
        </div>

        <div class="card-container">
            <img src="product3.jpg" alt="Product 3 Image">
            <h2>Product 3</h2>
            <p>This is a description of product 3.</p>
            <span>Price: $39.99</span>
            <button>Add to Cart</button>
        </div>

        <div class="card-container">
            <img src="product4.jpg" alt="Product 4 Image">
            <h2>Product 4</h2>
            <p>This is a description of product 4.</p>
            <span>Price: $49.99</span>
            <button>Add to Cart</button>
        </div>

        <div class="card-container">
            <img src="product5.jpg" alt="Product 5 Image">
            <h2>Product 5</h2>
            <p>This is a description of product 5.</p>
            <span>Price: $59.99</span>
            <button>Add to Cart</button>
        </div>

        <div class="card-container">
            <img src="product6.png" alt="Product 6 Image">
            <h2>Product 6</h2>
            <p>This is a description of product 6.</p>
            <span>Price: $69.99</span>
            <button>Add to Cart</button>
        </div>
    </div>
</body>
</html>
```

<h2 align = "center">Файл "48.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Fonts</title>
</head>
<body>
    <div style="width: 300px; height: 200px; border: 1px solid black;"></div>
    <div style="width: 50%; height: 50%; background-color: red;"></div>
    <p style="font-size: 1.2em;">Этот текст имеет размер шрифта 1.2em.</p>
    <div style="font-size: 1.5rem;">Этот текст имеет размер шрифта 1.5rem.</div>
    <div style="width: 50vw; height: 70vh; background-color: blue;"></div>
    <div style="width: 3in; height: 2cm; border: 1px solid black;"></div>
    <div style="width: 30vw; height: 80vh; background-color:aquamarine;"></div>
</body>
</html>
```

<h2 align = "center">Файл "49.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Loading...</title>
    <style>
        .loading-container {
            position: fixed;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: rgba(255, 255, 255, 0.7);
            z-index: 1000;
        }

        .loading-container::before {
            content: '';
            display: block;
            width: 50px;
            height: 50px;
            margin: 100px auto;
            border-radius: 50%;
            border: 3px solid #fff;
            border-top: 3px solid #3498db;
            animation: spin 2s linear infinite;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
    </style>
</head>
<body>
    <div class="loading-container">
        <!-- Здесь может быть контент, если необходимо -->
    </div>
</body>
</html>
```

<h2 align = "center">Файл "50.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Shadows</title>
    <style>
        .box-shadow-example {
            width: 200px;
            height: 200px;
            background-color: #f1f1f1;
            box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        .inner-shadow-example {
            width: 200px;
            height: 200px;
            background-color: #f1f1f1;
            box-shadow: inset 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
        .gradient-shadow-example {
            width: 200px;
            height: 200px;
            background: linear-gradient(45deg, rgba(0, 0, 0, 0.3), transparent);
        }
        .drop-shadow-example {
            width: 200px;
            height: 200px;
            background-color: #f1f1f1;
            filter: drop-shadow(2px 2px 5px rgba(0, 0, 0, 0.3));
        }
        .text-shadow-example {
            font-size: 24px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }
    </style>
</head>
<body>
    <div class="box-shadow-example"></div>
    <div class="inner-shadow-example"></div>
    <div class="gradient-shadow-example"></div>
    <div class="drop-shadow-example"></div>
    <h1 class="text-shadow-example">TEXT</h1>
</body>
</html>
```

<h1 align = "center">Результат</h1>

<p align = "center">Итого мы получаем 29 программ, каждая из которых является решением соответсвующей задачи</p>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я узнал о том, что такое JavaScript и использовал эти знания в решении задач.</p>
