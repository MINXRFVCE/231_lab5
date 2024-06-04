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
    <title>1</title>
</head>
<body>
<script>
    let str = 'hdfgv';
    console.log(str[0]);
    console.log(str[2]);
    console.log(str[4]);
</script>
</body>
</html>
```

<h2 align = "center">Файл "2.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>2</title>
</head>
<body>
<script>
    let secondsInMinute = 60;
    let minutesInHour = 60;
    let secondsInHour = secondsInMinute * minutesInHour;
    console.log("Количество секунд в часе: " + secondsInHour);
</script>
</body>
</html>
```

<h2 align = "center">Файл "3.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>3</title>
</head>
<body>
<script>
    let num = 1;
    num += 12;
    num -= 14;
    num *= 5;
    num /= 7;
    num++;
    num--;
    alert(num);
</script>
</body>
</html>
```

<h2 align = "center">Файл "4.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>4</title>
</head>
<body>
<script>
    let num = 3;
    alert(num);
</script>
</body>
</html>
```

<h2 align = "center">Файл "5.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>5</title>
</head>
<body>
<script>
    let a = 10;
    let b = 2;

    let sum = a + b;
    let diff = a - b;
    let mult = a * b;
    let div = a / b;

    alert("Сумма: " + sum + "\nРазность: " + diff + "\nПроизведение: " + mult + "\nЧастное: " + div);
</script>
</body>
</html>
```

<h2 align = "center">Файл "6.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>6</title>
</head>
<body>
<script>
    let c = 15;
    let d = 2;
    let result = c + d;
    alert(result);
</script>
</body>
</html>
```

<h2 align = "center">Файл "7.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>7</title>
</head>
<body>
<script>
    let a = 10;
    let b = 2;
    let c = 5;
    let sum = a + b + c;
    console.log("a + b + c = " + sum);
</script>
</body>
</html>
```

<h2 align = "center">Файл "8.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>8</title>
</head>
<body>
<script>
    let a = 17;
    let b = 10;
    let c = a - b;
    let d = 7;
    let result = c + d;
    console.log("result: " + result);
</script>
</body>
</html>
```

<h2 align = "center">Файл "9.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>9</title>
</head>
<body>
<script>
    let secondsInHour = 60 * 60;
    console.log("Секунд в часе: " + secondsInHour);
    let secondsInDay = secondsInHour * 24;
    console.log("Секунд в сутках: " + secondsInDay);
    let daysInMonth = 30;
    let secondsInMonth = secondsInDay * daysInMonth;
    console.log("Секунд в месяце: " + secondsInMonth);
</script>
</body>
</html>
```

<h2 align = "center">Файл "10.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>10</title>
</head>
<body>
<script>
    let now = new Date();
    let hour = now.getHours();
    let minute = now.getMinutes();
    let second = now.getSeconds();
    let currentTime = hour + ":" + minute + ":" + second;
    alert("Текущее время: " + currentTime);
</script>
</body>
</html>
```

<h2 align = "center">Файл "11.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>11</title>
</head>
<body>
<script>
    let number = 5;
    let squaredNumber = number * number;
    console.log("Число в квадрате: " + squaredNumber);
</script>
</body>
</html>
```

<h2 align = "center">Файл "12.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>12</title>
</head>
<body>
<script>
    const arr = [2, 4, 6, 8, 10];
    const sumOfSqrt = arr.filter(num => num % 2 === 0).reduce((acc, curr) => acc + Math.sqrt(curr), 0);
    console.log(sumOfSqrt);
</script>
</body>
</html>
```

<h2 align = "center">Файл "13.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>13</title>
</head>
<body>
<script>
    const applePrice = 1.15;
    const orangePrice = 2.30;
    const total = applePrice + orangePrice;
    console.log("Сумма яблока и апельсина: " + total);
</script>
</body>
</html>
```

<h2 align = "center">Файл "14.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>14</title>
</head>
<body>
<script>
    let x = 5; 
    alert(x++); 
</script>
</body>
</html>
```

<h2 align = "center">Файл "15.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>15</title>
</head>
<body>
<script>
    console.log([ ] + false - null + true)
</script>
</body>
</html>
```

<h2 align = "center">Файл "16.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>16</title>
</head>
<body>
<script>
    let y = 1; 
    let x = y = 2; 
    console.log(x);
</script>
</body>
</html>
```

<h2 align = "center">Файл "17.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>17</title>
</head>
<body>
<script>
    console.log([ ] + 1 + 2)
</script>
</body>
</html>
```

<h2 align = "center">Файл "18.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>18</title>
</head>
<body>
<script>
    let a6 = 5 % 3;
    let a7 = 3 % 5;
    let a8 = 5 + '3';
    let a9 = '5' - 3;
    let a10 = 75 + 'кг';

    console.log(a6);
    console.log(a7);
    console.log(a8);
    console.log(a9);
    console.log(a10);
</script>
</body>
</html>
```

<h2 align = "center">Файл "19.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>19</title>
</head>
<body>
<script>
    let height = 23;
    let width = 10;
    let s = height * width;
    
    console.log("Площадь прямоугольника:", s, "см²");
</script>
</body>
</html>
```

<h2 align = "center">Файл "20.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>20</title>
</head>
<body>
<script>
    let heightC = 10;
    let dC = 4;
    let radius = dC / 2;
    let v = Math.PI * radius * radius * heightC;

    console.log("Объем цилиндра:", v, "кубических метров");
</script>
</body>
</html>
```

<h2 align = "center">Файл "21.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>21</title>
</head>
<body>
<script>
    let amount = 2000000;
    const years = 5;
    const p = 0.1;

    for (let i = 0; i < years; i++) {
        amount += amount * p;
    }
    console.log(amount)
</script>
</body>
</html>
```

<h2 align = "center">Файл "22.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>22</title>
</head>
<body>
<script>
    let str = "Привет";
    let num = 123;
    let flag = true;
    let txt = "true";

    console.log(typeof str);
    console.log(typeof num);
    console.log(typeof flag);
    console.log(typeof txt);
</script>
</body>
</html>
```

<h2 align = "center">Файл "23.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>23</title>
</head>
<body>
<script>
    let n = 10;
    function rev (num){
        return num * (-1);
    }
    alert(rev(n))
</script>
</body>
</html>
```

<h2 align = "center">Файл "24.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>24</title>
</head>
<body>
<script>
    function chromosomeCheck(sperm) {
        let message = "Congratulations! You're going to have a ";
        if (sperm.match(/Y/gi)?.length > 0) {
            return message + 'son.';
        }
        return message + 'daughter.';
    }
</script>
</body>
</html>
```

<h2 align = "center">Файл "25.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>25</title>
</head>
<body>
<script>
    function simpleMultiplication(number) {
        return !Boolean(number & 1) ? number * 8: number * 9;
    }
</script>
</body>
</html>
```

<h2 align = "center">Файл "26.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>26</title>
</head>
<body>
<script>
    function nearestSq(n) {
        const root = Math.floor(Math.sqrt(n));
        const lowerSquare = root * root;
        const upperSquare = (root + 1) * (root + 1);
        return (n - lowerSquare) < (upperSquare - n) ? lowerSquare : upperSquare;
    }
</script>
</body>
</html>
```

<h2 align = "center">Файл "27.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>27</title>
</head>
<body>
<script>
    function countSquares(cuts) {
    if (cuts === 0) return 1;
        return 6 * cuts * cuts + 2;
    }
</script>
</body>
</html>
```

<h2 align = "center">Файл "28.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>28</title>
</head>
<body>
<script>
    function periodIsLate(last, today, cycleLength) {
        const timeDiff = today.getTime() - last.getTime();
        const daysDiff = timeDiff / (1000 * 3600 * 24);
        return daysDiff > cycleLength;
    }
</script>
</body>
</html>
```

<h2 align = "center">Файл "29.html"</h2>

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>29</title>
</head>
<body>
<script>
    function noSpace(x) {
        return x.replace(/\s+/g, '');
    }
</script>
</body>
</html>
```

<h1 align = "center">Результат</h1>

<p align = "center"><img src="1.png" alt="result"></p>

<p align = "center"><img src="2.png" alt="result"></p>

<p align = "center"><img src="3.png" alt="result"></p>

<p align = "center"><img src="4.png" alt="result"></p>

<p align = "center"><img src="5.png" alt="result"></p>

<p align = "center"><img src="6.png" alt="result"></p>

<p align = "center"><img src="7.png" alt="result"></p>

<p align = "center"><img src="8.png" alt="result"></p>

<p align = "center"><img src="9.png" alt="result"></p>

<p align = "center"><img src="10.png" alt="result"></p>

<p align = "center"><img src="11.png" alt="result"></p>

<p align = "center"><img src="12.png" alt="result"></p>

<p align = "center"><img src="13.png" alt="result"></p>

<p align = "center"><img src="14.png" alt="result"></p>

<p align = "center"><img src="15.png" alt="result"></p>

<p align = "center"><img src="16.png" alt="result"></p>

<p align = "center"><img src="17.png" alt="result"></p>

<p align = "center"><img src="18.png" alt="result"></p>

<p align = "center"><img src="19.png" alt="result"></p>

<p align = "center"><img src="20.png" alt="result"></p>

<p align = "center"><img src="21.png" alt="result"></p>

<p align = "center"><img src="22.png" alt="result"></p>

<p align = "center"><img src="23.png" alt="result"></p>

<p align = "center"><img src="24.png" alt="result"></p>

<p align = "center"><img src="25.png" alt="result"></p>

<p align = "center"><img src="26.png" alt="result"></p>

<p align = "center"><img src="27.png" alt="result"></p>

<p align = "center"><img src="28.png" alt="result"></p>

<p align = "center"><img src="29.png" alt="result"></p>

<p align = "center">Итого мы получаем 29 программ, каждая из которых является решением соответсвующей задачи</p>

<h1 align = "center">Вывод</h1>
<p>По итогу проделанной лабораторной работы, я узнал о том, что такое JavaScript и использовал эти знания в решении задач.</p>
