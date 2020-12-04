
 ### Теория по блоку "Базовый синтаксис"
 
 #### 1. Что такое виртуальная машина? 
 Виртуальная машина это программа выполняющая наше написанное ПО под конкретную платформу. 
 Т.е. переводит наш скомпилированный байт-код в машинные операции.

 
 #### 2. К какому типу языка программирования относится Java?
 Язык Java это компилируемо-интерпретируемый язык. Написанный нами код компилируется в так называемый байт-код,
 а он в свою очередь уже подается в интерпретатор(Виртуальная машина) 
 
 #### 3. Из каких компонентов состоит Java (JDK, JRE, JVM)?
 Java состоит из компилятора языка, виртуальной машины и различных библиотек и утилит.
 
 #### 4. Для чего используется JDK?
 JDK - это Java Development Kit, т.е. набор для разработки ПО. Он включает в себя
 компилятор(javac), JRE (Java runtime environment) - виртуальная машина и набор библиотек.
 Т.е. JDK используется для разработки и запуска пограммного обеспечения.
 
 #### 5. Для чего используется JRE?
 JRE(Java runtime environment) - обеспечивает выполнение Java-программы на любой аппаратной платформе и на любой ОС.
 Включает в себя виртуальную машину(VM) и набо стандартных библиотек.
 
 #### 6. Для чего используется VM?
 VM (Virtual Machine) - виртуальная машина служит для запуска Java-программы на конкретной платформе пользователя.
 
 #### 7. Расскажите про примитивные типы.
 Примитивные: boolean, byte, short, char, int, long, float, double.
 
 Это типы хранящие заданное значение, они никуда не ссылают и ни на что не указывают просто содержат данные.
 Они разделяются на логичекий тип(boolean), целочисленные(short, byte, int, long), с плавающей точкой(float, double)
 и символьный(char).
 
 Ссылочные типы - это типы которые указывают на что-либо(на объект). 
 Т.е. они содержат адрес в памяти где лежит объект на который ссылаются.
 
 #### 8. Опишите шаги для компиляции и запуска приложения в консоли (javac java).
 Создаем класс - файл с классом с расширением *.java.
 Запускаем компилятор javac, где указываем что компилируем и куда отправть результат.
 На выходе получаем файл с таким же названием как на входе, но с расширением *.class - это и есть байт код.
 
 #### 9. Что такое "оператор условия"?
 Это операторы(ключевые слова языка) создающие ветвление алгоритма программ.
 #### 10. Какие типы операторов условия существуют?
 В языке программирования Java существует три условных оператора:
 
 if() — если…, оно же основное логическое условие;
 else if() — альтернативное условие, выполняется если не выполнилось основное;
 else — иначе…, выполняется в случае, если ни одно из вышеприведённых условий не было выполнено.
 В круглых скобках указывается логическое условие. В else круглые скобки не требуются, так как это условие выполняется в случае, если ни одно из условий выполнено не было.
 
 Условные операторы помещаются в условный блок.
 Условный блок — это контейнер, содержащий в себе набор условных операторов и логических выражений.
 Условных блоков (контейнеров) в программе может быть сколько угодно.
 Для каждого условного блока существуют следующие правила:
 
 if() — только один и является обязательным, требуется логическое выражение в скобках;
 else if() — сколько угодно и обязательным не является, требуется логическое выражение в скобках;
 else — только один и обязательным не является, логическое выражение не требуется;
 #### 11. Расскажите про булевы операции || &&?  Расскажите элементы таблицы истинности?
 || - логическое ИЛИ, результат будет True хотя бы один операнд True.
 && - логическое И, результат будет False хотя бы один операнд False.
 
 #### 12. Что такое тернарное условие?
 Тернарный оператор (от латинского слова ternarius — тройной)- это оператор, состоящий из двух символов '?' и ':', 
 который формирует условную тернарную операцию, возвращающую свой второй или третий операнд в зависимости от 
 выполнения или невыполнения определённого условия, или другими словами от результата логического выражения.
 
 #### 13. Что такое циклы и для чего они используются?
 Цикл — это конструкция, содержащая в себе программный код, который должен быть выполнен определённое количество раз.
 Ипоьзуются они, когда нужно выполнить какое-то действие определенное количество раз.
 #### 14. Для чего используется цикл for?
 Цикл for еще называют цикл "со счетчиком". Используется он для повторения действия, когда заранее известно количество 
 повторений.
 
 #### 15. Для чего используется цикл foreach?
 Цикл используется при работе с массивами, коллекциями и другии объектами.
 При этом цикл выполняется кол-во раз равное кол-ву элементов.
 
 #### 16. Для чего используется цикл while?
 Цикл Выполняется пока условие Истино.
 Нужен для многократного повторения, когда мы не значем требуемого кол-ва итераций, а дожидаемся не определенного
 условия.
 
 #### 17. Для чего используется цикл do while?
 Этот цикл выполняется так же, если мы не знаем требуемое кол-во итераций.
 Но этот цикл с пост условием, т.е. тело цикло выполнится хотя бы один раз.
 
 #### 18. Что такое массив?
 Массив — это структура данных, в которой хранятся элементы одного типа. Его можно представить, как набор 
 пронумерованных ячеек, в каждую из которых можно поместить какие-то данные (один элемент данных в одну ячейку). 
 Доступ к конкретной ячейке осуществляется через её номер. Номер элемента в массиве также называют индексом. 
 
 #### 19. Как создать массив?
 
Создаем переменную ссылочного типа на массив и ссылаем её на созданный объект массива 10 элементов.
int[] array = new int[10];
Так же можно не указывать кол-в элементов, а сразу их объявить.
int[] array = new int[]{1, 2, 3};

 #### 20. Как присвоить значение ячейке массива?
 Для заполнения ячейки массива используется следующая конструкция.
 Имя_Переменной_Массива[Индекс] = Значение;
 nums[0] = 2006;
 nums[1] = 2010; 
 То есть, нужно обратиться к ячейке по ее индексу.
 
 #### 21. Как можно пройти по всем элементам массива?
 С помощью цикла foreach
 
 #### 22. Как можно найти элемент в массиве?
 С помощью цикла и условных операторов.
 
 #### 23. Что будет, если записывать элемент по индексу -1?
 Выход за границу массива. Программа выдаст ошибку.
 
 #### 24. Как удалить ячейку в массиве?
 Ячейку удалить нельзя, но можно обнулить ее значение или ссылку на объект, которую она содержала.
 
 #### 25. Как отредактировать ячейку в массиве?
 Так же как и присвоить ей значение.
 Обратиться к массиву по индексу и присвоить значение. Индексирование массива начинается с нуля.
 
 array[0] = 10;
 array[0] = 20;
 
 [Тестовое задание по итогам блока] (https://github.com/ShalopaykaQA/games_oop_javafx/commit/13b73911c578c50ea0934040f3fcdd1ccb8846b7)
