# OSI

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
  <summary>Сдаём через гитхаб </summary>
  
  Время пришло познакомиться с профессиональными инструментами для контроля версий вашего кода. Теперь мы не сдаём домашние задания в реплите, а заливаем проект из идеи сразу же в публичный гитхаб-репозиторий. Одна задача - один репозиторий.
  
  Для того чтобы в репозитории не отслеживался всякий мусор, не забывайте добавлять `.gitignore`.
  В нём должны игнорироваться файлы идеи (правила `*.iml` и `.idea`), папки для автогенерируемых результатов сборки (`out`, позже - `target`).
  Этот файл должен находиться в корне вашего репозитория, а сам репозиторий должен быть инициализирован в корне вашего проекта.
  Т.е. открывая репозиторий вы должны сразу видеть папку `src`.
  Если вы забыли проигнорировать какие-либо файлы и они попали в репозиторий, используйте команду `git rm`.

</details>

<details>
  <summary> Работаем с мавен-проектами </summary>
  
  Эту и последующие задачи делаем в мавен-проектах. Gradle нельзя, как и сдавать без систем сборки.
  Убедитесь, что все нужные файлы закоммичены (`pom.xml`, `src`,..), а мусор проигнорирован (например, автосгенеренная `target`).

  ---
  
</details>

## Задача 1 (обязательная)
После выполнения этого задания вы научитесь создавать сервер, способный принимать подключения.  
А также клиента, который будет подключаться к подобному серверу.

Создайте сервер с использованием ServerSocket.   
При входящем соединении на сервер, примите его, прочитайте из него строку. Выведите её на экран вместе с номером порта, с которого это соединение пришло.

Вместе с этим в другом методе (это может быть другой класс со вторым main методом или отдельный поток) подключитесь к этому серверу и отправьте ему одну строку.

## Реализация
Запускаем сервер на определенном порту и принимаем соединение:

```java
try (ServerSocket serverSocket = new ServerSocket(port);) { // порт можете выбрать любой в доступном диапазоне 0-65536. Но чтобы не нарваться на уже занятый - рекомендуем использовать около 8080
  try (Socket clientSocket = serverSocket.accept(); // ждем подключения
       PrintWriter out = new PrintWriter(clientSocket.getOutputStream(), true);
       BufferedReader in = new BufferedReader(new InputStreamReader(clientSocket.getInputStream()));
      ) {
      // ваш код
  }
```

Читаем строку и выводим её на экран вместе с номером порта клиента, с которого пришло соединение:

```java
System.out.println("New connection accepted");

final String name = in.readLine();

out.println(String.format("Hi %s, your port is %d", name, clientSocket.getPort()));
```

Далее пишем клиента. Клиентом должна быть другая программа (просто ещё один метод `main` в другом классе, запускаемый параллельно, во время работы сервера) или второй поток. Обратите внимание, что хостом подключения будет `localhost` - это зарезервированный адрес для подключения к текущему компьютеру (то есть это ваш компьютер - там, где запущена программа). Также можно использовать `127.0.0.1` - это ip адрес, соответствующий доменному имени `localhost`  