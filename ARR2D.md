# Многомерные массивы

## Памятка к домашнему заданию
Перед тем, как отправить своё решение на проверку преподавателю, сверьтесь с чеклистом

<details>
  <summary> Что делать, если возникли сложности? </summary>
  
  И это здорово! Если их преодолевать правильно, то можно получить большую образовательную пользу для себя. Периодическое возникновение вопросов, недопонимание пройденного материала - нормальная и неотъемлемая часть обучения. А мы здесь, чтобы помочь вам пройти этот путь.
  
  ### Что делать, если непонятна теория?
  1. Если подобный вопрос разбирался на лекции, посмотрите еще раз раздел с этой темой в видеозаписи.
  1. Если вопрос не решился, попробуйте поискать ответ самостоятельно в интернете, этот навык пригодится вам в работе.
  1. Если самостоятельно разобраться не удалось, задайте вопрос в общем чате, мы обязательно поможем.

  ### Что делать, если непонятно условие задания?
  1. Прежде чем задать вопрос по условию задачи, перечитайте его ещё раз и убедитесь, что в тексте условия нет прямого ответа на этот вопрос. Умение работать с текстом - важный навык работы с информацией.
  1. Если ответа на свой вопрос в тексте условия не увидели, задайте его в общем чате, мы раскроем детали условия подробнее. Не забудьте при этом скинуть и ссылку на условие задания, про которую у вас вопрос.

  ### Что делать,если не получается задача?
Если ваша проблема это **ошибка компиляции** (подчёркивает красным, не даёт запустить программу), сборки проекта, CI и прочие подобные ошибки, то:
  1. Найдите и прочитайте текст ошибки, который вам подсвечивает реплит, идея (или логи); "подчёркивает красным" - это не описание ошибки.
  1. Попробуйте понять текст ошибки, при необходимости воспользуйтесь переводчиком. Нестрашно, если вы переведёте неточно, тут главное сам процесс: со временем и с нашей помощью вы будете это делать лучше и лучше, но, пропуская этот этап, вы не сможете научиться это делать.
  1. Если не получилось понять ошибку по её тексту, попробуйте её загуглить и изучить подобную ошибку у других людей. Попробуйте примерить решения их проблем на свой код. Соотнесите найденные описания ошибки с пройденной теорией.
  1. Если все равно вашу трудности не разрешились, напишите в общий чат, обязательно указав:
      1. Название задачи и ссылку на условие
      1. Ссылку на вашу работу
      1. Текст и скриншот (не фотография) ошибки.
      1. Ваши размышления и описание шагов, которые вы совершили для решения.

Если ваша проблема это **ошибка исполнения** (программа умирает уже после запуска) или она **отрабатывает неправильно**, то:
  1. Воспользуйтесь отладчиком для пошагового анализа работы вашей программы. Так вы либо убедитесь в неправильности придуманного вами алгоритма или найдёте конкретное место, где ожидаемое поведение программы разошлось с фактическим.
  1. Если проблему найти не получилось, напишите в общий чат, обязательно указав:
      1. Название задачи и ссылку на условие
      1. Ссылку на вашу работу
      1. Конкретное и подробное описание проблемы или затруднения при решении задачи ("Помогите что не так" - это не описание)
      1. Подробное описание вашего анализа программы с помощью отладчика вместе со скринами
      1. Ваши размышления и описание шагов, которые вы совершили для решения.
  ---
  
</details>

<details>
  <summary> В решении выполнены все требования задания </summary>
  
  Убедитесь, что все требования задания выполнены. Для этого перед отправкой внимательно прочтите весь текст условия задания и соотнесите сказанное в нём с вашим решением. Навык самопроверки работы перед ревью пригодится вам как при обучении, так и на работе.

  ---
  
</details>

<details>
  <summary>Пишем в идее, сдаём в реплите</summary>
  
  Теперь вы знакомы с профессиональным редактором кода - [Intellij IDEA Community Version](https://www.jetbrains.com/idea/download/). Все задачи теперь должны выполняться в нём.
  
  Как минимум перед каждой отправкой работы на проверку (а лучше - вегда) форматируйте код. Ячейки, а именно локальные переменные, параметры, поля и тп должны быть названы камелкейсом с маленькой буквы, а классы и интерфейсы камелкейсом с большой буквы. Правила, связанные с отступами можно доверить самой идее - выберите в меню Code -> Reformat code чтобы отформатировать код в текущем файле.

  При этом задание сдаётся через [реплит](https://replit.com/). Обратите внимание на то, что на реплит ваш код следует добавлять через загрузку файлов, а не через копирование текста; при копировании и вставке кода в окно реплита форматирование может поехать. Тут алгоритм один и тот же: в пустом проекте удаляете `Main.java` (`Delete` в меню действий над файлом) и выбираете в меню что повыше пункт `Upload file` (англ. Загрузить файл) и загружаете `Main.java` с вашего компьютера из папки вашего проекта, после чего нажимаете в том же меню `Upload folder` (англ. Загрузить папку) и загружаете папки-пакеты с .java-файлами если они вам нужны. 
  
![](https://u.netology.ngcdn.ru/backend/uploads/markdown_images/image/30569/image.png)

При любой же проблеме с поведением кода теперь необходимо рассказывать про ваш анализ отладчиком вашей программы.

</details>

## Задача 1 (обязательная)

Вам надо написать симулятор пандемии. Перед вами поле - двумерный интовый массив, который вы создаёте в `main`.
Каждая ячейка соответствует степени заражения участка карты; изначально там везде стоят нули.
Разамеры карты - 5 на 5.
Таким образом наше поле можно описать как `int[][] field`.

В начале программы, в main, вы задаёте ещё один двумерный массив - перечисление пар координат, в которых находится заражённый агент.
Возьмите следующий массив для демонстрации работы программы: `int[][] agents = { {1, 4}, {0, 1}, {4, 2}, {4, 3}, {4, 3}, {0, 1}, {0, 2}, {4, 3} };`.
Т.е. каждый внутренний массив двумерного массива это координата нахождения одного агента; первая координата это номер строки, вторая - столбца. Агенты могут повторяться.

Напишите статический метод, который принимает двумерный массив поля (заполненного нулями), двумерный массив агентов заражения и возвращает поле с заполненными степенями заражения по следующим правилу: если клетка поля является агентом заражения, то её степень заражения увеличивается на 1 если она встретилась в первый раз среди агентов, иначе увеличивается в 2 раза.

В `main` вызовите этот метод и выведите на экран получившееся поле. Вывод сделайте в виде вызова ещё одного своего статического метода, который принимает двумерный массив и выводит его на экран в виде таблицы.

В итоге должно получиться так:
```java
public class Main {

    public static void main(String[] args) {
        int[][] field = new int[5][5];
        int[][] agents = { {1, 4}, {0, 1}, {4, 2}, {4, 3}, {4, 3}, {0, 1}, {0, 2}, {4, 3} };
        int[][] result = pandemic(field, agents);
        print(result);
    }
    
    ...
}
```

### Пример работы
```
0 2 1 0 0 
0 0 0 0 1 
0 0 0 0 0 
0 0 0 0 0 
0 0 1 4 0 
```

### Подсказки
Пройдитесь по агентам циклом for-each.

Каждый агент описывается одномерным массивом размером 2, где в первой ячейке номер строки, во второй - столбца. Извлеките эти номера из массива и сохраните в переменные (здесь и далее описание итерации цикла for-each).

Загляните в ячейку поля с извлечёнными координатами. Если там 0, то запишите туда 1; если там не 0, то увеличьте значение ячейки в 2 раза.
