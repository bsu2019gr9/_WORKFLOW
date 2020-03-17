# Тут размещаются задания и оценки

## Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

# Обязательные требования ко всем лабам:

• Кодировка UNICODE   
• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.        
• имена переменных и функций должны соответствовать общепринятым нормам.

|Прозвішча               |  экз|ХЗ1  | ХЗ2 | ХЗ3 | ХЗ4 | ХЗ5 | ХЗ6  | ХЗ7 |    |    | iтог |комментарии |
|:-----------------------|:---:|----:|:---:|----:|----:|----:|:----:|----:|---:|---:|-----:|-----------:|
|Градович Лиза           |  6  |     |     |     |     |     |      |  •  |    |    |      |            |
|Гранева  Аня            |  6  |     |     |     |     |     |      |  •  |    |    |      |            |
|Денисенко Лёша          |  4  |     |     |     |     |     |      |  •  |    |    |      |            |
|Ефремов Рома            |  5  |     |     |     |     |     |      |  •  |    |    |      |            |
|Кузьков Артем           |  9  |     |     |     |     |     |      |  •  |    |    |      |            |
|Матвееня Рома           |  5  |     |     |     |     |     |      |  •  |    |    |      |            |
|Пахомович Ксюша         |  7  |     |     |     |     |     |      |  •  |    |    |      |            |
|Протосовицкий Слава     |  5  |     |     |     |     |     |      |  •  |    |    |      |            |
|Сарнацкая Даша          |  5  |     |     |     |     |     |      |  •  |    |    |      |            |
|Скадорва Ваня           |  6  |     |     |     |     |     |      |  •  |    |    |      |            |
|Стасенко Таня           |  9  |     |     |     |     |     |      |  •  |    |    |      |            |
|Толстик Никита          |  9  |     |     |     |     |     |      |  •  |    |    |      |            |
|Филинкова Даша          |  6  |     |     |     |     |     |      |  •  |    |    |      |            |

## Задание на 14.02 (вычисление сумм, разложение в ряды )
0) Прочитать, скачать себе и распечатать хорошее краткое объяснение указателей с адреса http://www.math.spbu.ru/user/dlebedin/ncpp4.pdf
1) `(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файла с именем 0-1.cpp (тут решение задачи)`     
Условие задачи в прикрепленном файле "задание на вычисление сумм.pdf"     
Номер варианта - ваш порядковый номер в списке группы

## Задание на 27.02 (функции для работы с одномерными массивами в heap )     
`в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файл с именем 1-1.cpp (в этом файле - подключение вашей библиотеки для работы с одномерными массивами)`

Разработать программу для работы с одним или несколькими одномерными массивами в heap, предусмотрев в ней:     
•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**, а не в main;      
•	функции для инициализации, для ввода, для вывода массивов в heap;      
•	освобождение динамической памяти после её использования **обязательно в отдельной функции**;      
•	организация циклов **обязательно с использованием указателей**;     
• несколько функций для обработки массивов по условию задачи (для сортировки новый массив не создавать);

**Примерные прототипы функций: Подробнее и правильнее было обсуждение на практическом занятии**     

* void giveMemory(int*&, int)//первый способ. Подумайте, почему обязательно надо тут &
* int* giveMemory(int)//второй способ. Подумайте, можно ли и безопасно ли тут напісать int*& giveMemory(...     
* void freeMemory(int*&,int)
* void initArray(int* ,int,int=0)
* void printArray(int* ,int)

1. В массиве размера N, заполненного случ.числами от -10 до 10, подсчитать количество элементов, встречающихся более одного раза.     
2. В массиве размера N, заполненного случ.числами от -10 до 20, определить максимальную длину последовательности равных элементов.     

## Задание на 28.02 (двумерные массивы в heap)
Выбираем одну задачу по работе с массивами **в heap** из списка ниже и реализуем её.      
`в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  1 файл с именами 2-1.cpp `      

В программе:     
•	Размеры массива N,M запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**;      
•	функции для инициализации, для ввода, для вывода массивов;      
•	освобождение динамической памяти после её использования **обязательно в отдельной функции**;      
•	организация циклов **обязательно с использованием указателей**;     
• несколько функций для обработки массивов по условию задачи (а алгоритмах новые двумерные массивы не создавать);

**Попроще**       
• ( Скадорва ) В массиве А(N,М) найти строку, среднее арифметическое положительных элементов которой является наименьшим и поменять её с первой строкой.    
• (Гранёва) В массиве А(N,N) найти первую строку, не содержащую отрицательных элементов, и поменять её с последней строкой.       
• (________) В массиве А(N,М) найти строку, для которой количество перемен знаков максимально и поменять её с первой строкой.        
• (________) В массиве А(N,N) найти максимальные элементы нижнего и верхнего треугольников относительно главной диагонали и поменять местами строки в которых они находятся.       
•	(Пахомович) В массиве А(N,М) поменять местами строки, содержащие максимальный и минимальный элементы.        
•	(Градович) В массиве А(N,М) часть строк состоит из нулей. удалить нулевые строки.       
•	(________) В массиве А(N,М) сменить знаки минимальных элементов и удалить строку с минимальным произведением элементов.       
•	(Сарнацкая) В массиве А(N,М) расположить строки в порядке возрастания их максимальных элементов.        
•	(________) В массиве А(N,М) расположить строки в порядке возрастания количества минимальных элементов в каждой строке.    
•	(Филинкова) В массиве А(N,M) переставить строки в порядке возрастания элементов последнего столбца.     
•	(________) В массиве А(N,M) переставить строки так, чтобы строка с максимальной суммой элементов стала первой строкой, а остальные строки расположить в порядке возрастания элементов первого столбца.     

**Посложнее немножко**       
• (________) В массиве А(N,M) расположить строки, стоящие после строки с первым максимальным элементом матрицы, в порядке возрастания количества чётных элементов в строке.      
• (Стасенко) В массиве А(N,M) переставить столбцы так, чтобы столбец с максимальной суммой элементов стал первым, а остальные столбцы расположить в порядке возрастания элементов первой строки.        
• (Ефремов)	В массиве А(N,M) расположить столбцы по возрастанию количества чётных элементов в столбце.        
• (________)	В массиве А(N,M) расположить столбцы по возрастанию значений минимальных элементов столбцов. Если минимальные значения в двух столбцах - одинаковые, то первым должен быть тот у которого больше таких минимальных элементов.        
• (________) В массиве А(N,M) элементы столбцов, не содержащих нулевых элементов, расположить в порядке убывания, а сами столбцы расположить в порядке возрастания элементов первой строки.        
• (________)	В массиве А(N,M) расположить элементы каждого столбца в порядке возрастания модулей их отрицательных элементов, а сами столбцы расположить в порядке убывания  сумм их элементов.        
• (________)	В массиве А(N,M) расположить положительные элементы каждого столбца в порядке возрастания, а сами столбцы расположить в порядке убывания их первых максимальных элементов.        
• (________)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества нечётных элементов в столбце.        
• (________)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества перемен знаков в каждом столбце.        
• (________)	В массиве А(N,M) расположить столбцы в порядке  возрастания количества нулевых элементов в каждом столбце.       
• (________)	В массиве А(N,М) "удалить" столбцы, все элементы которых являются простыми числами, сдвинув остальные.       
• (Кузьков)	В массиве А(N,М) столбец с минимальным количеством нечетных элементов поменять местами с столбцом c максимальным кол-вом таких элементов.       
• (________)	В каждом столбце массива А(N,М) после первого отрицательного элемента вставить максимальную цепочку из положительных элементов данного столбца. Расположить столбцы в порядке возрастания по количеству вставленных элементов. 

## Задание на 13.03 (работа с строкой)
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файл с именем 3-1.cpp)`

1.	(Гранёва)Определить, сколько слов в строке содержат хотя бы одну заданную букву. Вывести такие слова на экран.
2.	(Сарнацкая)Определить количество слов в строке, которые начинаются на заданную букву. Вывести их на экран.
3.	Определить, сколько слов в строке начинается с прописной буквы. Вывести их на экран.
4.	Определить, сколько раз стоящие рядом два слова в строке начинаются на одну и ту же букву. Вывести эти слова на экран.
5.	Определить длину первого и последнего слова в строке. Если длины совпадают, то заменить их заданной подстрокой, например  ”---”.
6.	Определить, каких слов больше в строке, с чётной длиной или нечётной. Удалить первое слово с чётной длиной.
7.	Определить, каких слов меньше в строке, четырёхсимвольных или пятисимвольных. Вставить после первого четырёхсимвольного слова заданную подстроку, например  ”---”.
8.	Вывести первое и последнее слова на экран. Определить, каких слов больше в строке, совпадающих с первым или последним. Вставить после первого слова заданную подстроку, например  ”---”.
9.	Найти и вывести на экран все слова строки, в которых первый и последний символы совпадают и длина которых чётная. Вывести такие слова на экран. Заменить первое такое слово заданной подстрокой, например  ”---”. (На выбор –удалить все такие слова).
10.	Определить, сколько в строке 4-символьных слов. Вывести такие слова на экран. Заменить последнее такое слово на заданную подстроку, например  ”---”..
11.	Определить, сколько слов в строке совпадает с заданным словом. Вывести такие слова на экран. Удалить первое такое слово.
12.	После каждого слова чётной длины в строке вставить заданную подстроку, например  ”---”.
14.	(6)В строке найти и удалить все слова, начинающиеся и заканчивающиеся гласной буквой.
15.В строке найти и удалить все слова максимальной длины.
16.	 Найти и удалить все слова строки, состоящие только из цифр.
17.	В строке найти и вывести на экран слова, длина которых - простое число. Вставить после первого слова, длина которого простое число, заданную подстроку, например  ”---”..
18.	В строке удалить все слова заданной длины, начинающиеся с цифры.
19. В строке после каждого слова с нечётной длиной, начинающегося с заданного символа, вставить заданную подстроку, например  (”---”..
20.	(7-8.) В строке найти все слова чётной длины, заканчивающиеся на заданную букву. Вывести их на экран, и вставить после них заданную подстроку, например  ”---”..
21.	(8) В строке удалить слова, в которых буквы упорядочены в алфавитном порядке и которые начинаются на большую букву.
26.	(8) В строке найти и вывести на экран слова, в которых буквы упорядочены в алфавитном порядке. Удалить все такие слова.
40.	(7-8 ) В строке найти и вывести на экран все слова, в которых буквы упорядочены в порядке, обратном алфавитному (TOK, zona).
22.	(7 ) В строке удалить все слова, содержащие заданную букву ровно два раза.
23.	(6) В строке найти, вывести на экран и, затем, удалить из исходной строки фрагменты, заключённые в круглые скобки. Скобки расставлены верно. Проверять не надо.
13.	(6) В строке удалить слова, заключённые в круглые скобки и длина которых чётная.  Скобки расставлены верно. Проверять не надо.24.	(6) После каждого трёхбуквенного слова в строке вставить заданную подстроку, например  ”---”..
25.	В строке найти и вывести на экран все слова ”палиндромы” (пишутся одинаково слева направо и справа налево).
27.	(8-9 Пахомович) После каждого слова строки, оканчивающегося заданной подстрокой, вставить указанный символ.
28.	(7)В строке поменять местами первое слово минимальной длины и первое слово максимальной длины.
29.	(8-9 Градович) В строке в каждой паре слов поменять слова местами, если длины слов совпадают, иначе заменить их звёздочками.
30.	В каждом слове нечётной длины строки удалить буквы, стоящие на нечётных позициях.
31.(Филинкова)	Преобразовать каждое слово в строке, удалив в нём заданную букву.
32.	Преобразовать каждое слово чётной длины в строке, удалив в нём стоящие рядом одинаковые символы, оставив по одному.
33.	Заменить все слова в строке  заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.
34.	(8) Если в строке есть слово, которое встречается k раз, удалить все такие слова кроме последнего.
36. (8-9 Ефремов) Назовём два слова, стоящие рядом, особой парой, если заданная буква встречается в них одинаковое число раз, и номера позиций, в которых она располагается и в том и в другом слове, одинаковы. Вывести на экран все особые пары и удалить их.
37.	(7) Найти и удалить все слова  в  тексте,  содержащие 1 слог. Вывести все такие слова на экран.
38.	(8)В строке найти и вывести на экран все слова максимальной длины,  и удалить за ними следующее слово.
39.	(7-8) В строке найти слова-палиндромы c нечётной длиной (radar, ANANA), и вставить после них заданную подстроку .
41.	(7-8) В строке найти слова, длина которых простое число, и заменить слово на  ---…- .  Количество  -  должно соответствовать длине слова.
42.	Поменять местами в строке первое слово и последнее (длины слов могут не совпадать), второе и предпоследнее и т.д. Заменить потом в последнем слове все вхождения заданного символа заданной подстрокой.
43.	(7) В строке удалить лишние пробелы и поменять местами слова минимальной и максимальной длины (если таких слов несколько, то брать первое;  длины слов могут не совпадать).
44.	В строке удалить лишние пробелы и слова максимальной длины, начинающиеся и заканчивающиеся заданными символами.
45.	Заданы две строки S1 и S2. Удалить из строки S1 первое и последнее вхождения подстроки S2.
46.	(6)Определить, сколько слов в строке содержат хотя бы одну букву A. Вывести такие слова на экран.
47.	(7) Определить, сколько слов в строке имеют одинаковую длину. Вывести такие слова на экран.
48.	(6) В строке найти сумму цифр, содержащихся во всех словах и слово с максимальной суммой цифр.
49.	(7)В строке удалить лишние пробелы и найти слово, которое содержит максимальное количество заданной буквы.
50.	(6) Определить, сколько слов в строке имеют заданную длину. Вывести такие слова на экран. Вставить перед такими словами заданную подстроку.
51.	(5-6) В строке после каждого слова заданной длины, начинающегося с цифры, вставить заданную подстроку.
52.	(6-7) Определить, сколько слов в строке начинаются заданным символом. Вывести такие слова на экран. После первого такого слова удалить следующее слово.
53.	(Скадорва)(7-8) Заменить все слова в строке заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.
54. (7) Определить, сколько слов в строке состоит только из цифр. Вывести такие слова на экран и удалить после них следующее слово.
55.	(7) В строке найти слова, содержащие цифры, расположенные подряд, и заменить их  ---…-. Вставить перед такими словами заданную подстроку.
35.	(8)В строке найти слово (слова), содержащее максимальное количество цифр, расположенных подряд, и заменить их на ---…-. Вставить после таких слов заданную подстроку.
56.	(8-9 Стасенко ) Найти и вывести на экран все слова строки, в которых все буквы различны. Вставить перед такими словами заданную подстроку.


## Задание на 29.03 (для желающих получить >8 баллов работа с массивами строк)
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файл с именем 4-1.cpp)`

Выбрать ОДНО задание из списка ниже и разработать программу, предусмотрев в ней:     
•	последовательное чтение строк **из входного текстового файла** (ПОСТРОЧНОЕ, а не весь файл целиком или побайтово);    
### Программа тестируется на текстовом файле "Война и мир" (100500строк) ###     
•	использование указателей при работе со строками;     
•	использование библиотечных функций <cstring> для работы со строками (т.е. нельзя в программе обратиться к символам строки как str[1] или str[i]);     
•	создание нескольких собственных функций для обработки строк;     
•	вывод результатов **в новый текстовый файл (result.txt)**;     
•	поощряется использование меню на массиве указателей на функции.

**Попроще итоговая оценка меньше 8. Файл не большой <500 строк**    
1.	Отсортировать строки по количеству слов, содержащих цифры.
2.	(Скадорва) Отсортировать строки по количеству слов заданной длины.
3.	Отсортировать строки по количеству слов с двумя слогами.
4.	Отсортировать строки по количеству слов-палиндромов.
5.	Отсортировать строки по количеству слов, в которых все буквы различны.
6.	Отсортировать строки по количеству слов, в которых буквы упорядочены в алфавитном порядке.
7.	Отсортировать строки по возрастанию длин слов максимальной длины.
8.	Отсортировать строки по количеству слов, длины которых - простые числа.
9.	Отсортировать строки по количеству слов, состоящих только из цифр.
10.	Отсортировать строки по количеству предложений, заканчивающихся восклицательным знаком.
11.	Определить, каких слов больше в каждой строке, первого или последнего. Если больше первого, отсортировать строки в алфавитном порядке по первому слову, иначе – по последнему.
12.	Отсортировать строки по количеству слов, в которых первый и последний символы совпадают и длина которых чётная.
13. После каждого слова чётой длины в каждой строке вставить заданную подстроку, например  ”---”. Отсортировать строки по количеству вставленных подстрок.
14.	В каждой строке после слов, заканчивающихся заданной буквой, вставить подстроку, состоящую из  звёздочек, количество которых соответствует длине слова. Отсортировать строки по количеству вставленных подстрок.

15.(Сарнацкая)После каждого трёхбуквенного слова в строке вставить заданную подстроку. Отсортировать строки по количеству вставленных подстрок.

16. В каждой строке удалить все слова заданной длины, начинающиеся с цифры. Отсортировать строки по количеству удалённых слов.
17.	В каждой строке удалить все слова нечётной длины, начинающиеся на заданную букву. Отсортировать строки по количеству удалённых слов.
18.	В каждой строке удалить все слова чётной длины, заканчивающиеся на заданную букву. Отсортировать строки по количеству удалённых слов.
19. В каждой строке удалить слова, в которых буквы упорядочены в алфавитном порядке и которые начинаются на большую букву. Отсортировать строки по количеству удалённых слов.
20.	В каждой строке удалить все слова, содержащие заданную букву два раза. Отсортировать строки по количеству удалённых слов.
21.	В каждой строке удалить слова (а не выражения), заключённые в круглые скобки. Скобки могут быть расставлены неправильно!!! Отсортировать строки по количеству удалённых слов.
22.  Преобразовать каждое слово в строках, удалив в них заданную букву. Отсортировать строки по количеству удалённых букв.
23.	Преобразовать каждое слово чётной длины в строках, удалив в них стоящие рядом одинаковые символы, оставив по одному. Отсортировать строки по количеству удалённых символов.
24. Заменить все слова в строках заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит несколько цифр. Отсортировать строки по количеству замен.
25.	В каждой строке найти слова, содержащие максимальное количество цифр, расположенных подряд, и заменить их на ---…-. Отсортировать строки по количеству таких слов.
26.	Назовём два слова особой парой, если заданная буква встречается в них одинаковое число раз, и номера позиций, в которых она располагается и в том и в другом слове, одинаковы. Отсортировать строки по количеству таких слов.
27.	В каждой строке поменять местами соседние слова, если их длины совпадают, иначе удалить эти слова. Отсортировать строки по количеству удалённых пар слов.

**Посложнее. Файл большой >100000 строк**    
28. (Ефремов) В тексте выбрать все слова, начинающиеся с заданной буквы, и расположить их в порядке убывания количества букв в слове.     
29.	В тексте выбрать все слова, начинающиеся с гласных букв, и расположить их в порядке возрастания количества букв в слове.     
30.	(Стасенко)В тексте выбрать все слова-палиндромы и расположить их в порядке возрастания их длин.      
31.	Для каждого слова из заданного списка определить, сколько раз оно встречается в тексте, и рассортировать их в порядке убывания найденных количеств.      
32.	Найти и вывести без повторений все слова заданной длины, содержащиеся в восклицательных предложениях текста. Отсортировать все найденные слова в алфавитном порядке.      
33. В тексте отсортировать **строки**, по количеству слов, начинающихся на заданную букву. Отсортировать все слова алфавитном порядке того **предложения** в котором  наибольшее количеству слов, начинающихся на заданную букву.      
34.	Найти все предложения текста, в которых есть одинаковые слова. Отсортировать их в алфавитном порядке по первому слову.      
35.	Во всех вопросительных предложений текста выбрать слова заданной длины. Отсортировать их в алфавитном порядке.      
36. Найти в каждой строке вопросительные предложения, содержащие чётное количество слов. Отсортировать строки по количеству таких слов в вопросительных предложениях.      
37. В каждой строке удалить восклицательные предложения. Отсортировать строки по количеству удалённых предложений.      
38.	В каждой строке выбрать самые длинные предложения. Отсортировать их по первому слову ( последнему) в алфавитном порядке.    
39. (Пахомович) В строках текста удалить фрагменты, заключённые в круглые скобки.   
40. В тексте удалить фрагменты, заключённые в круглые скобки (скобка может начинаться в одной строке, а заканчиваться -  другой. Могут быть вложенные скобки, но они всегда верно расставлены. Т.е. нет ситуации "(...(...)..()" ).     
41. Определить есть ли в тексте слово, которое встречается ровно k раз, удалить все такие слова кроме последнего.     
42.	В тексте найти и вывести все слова максимальной длины, и удалить за ними следующее слово.В тексте поменять местами слова минимальной и максимальной длины (если таких слов несколько, то брать первое).  

```
// Прочитать файл "date1.txt".
// К концу каждой строки добавить "***"  и записать в новый файл "date2.txt".
#include<iostream>
#include<fstream> 		                 // подключение библиотеки файлового ввода/вывода через потоки
using namespace std;
int main(){
const int N=200;
 char *buff = new char[N];
 ifstream fffff("d:\\date1.txt"); // отсюда читаем (поток типа ifstream= input file stream)
 ofstream ggggg("d:\\date2.txt");//сюда пишем (поток типа ofstream= output file stream)
 if (!fffff){cout<<"No file d:\\date1.txt. Can't open\n"; exit(1);}
 if (!ggggg){cout<<"   file d:\\date2.txt. Can't create\n"; exit(1);}

int count=0;
while(1){
    fffff.getline(buff, N-1); //читаем ПОСТРОЧНО.
//Если будет в строке файла больше N-1 символов, то getline() поместит в буфер N-1 символов, в конец поместит '\0', установит флаг ошибки (failbit), поток станет нерабочим, не введённое останется в очереди ввода.
    if (fffff.fail()) fffff.clear(); //getline при переполнении выставляет бит состояния =1. Его проверяем fail'ом. А потом подчищаем буфер
    cout<<buff<<'\n'; //на экран
    ggggg<<buff<<"***";//в файл
    count++;

    if(fffff.eof()) break; //читаем пока не кончится исходный файл. Т.е. пока не прочитаем EOF.
    ggggg<<'\n';//переход на новую строку пишем в date2.txt только, если в строке 16 мы прочитали действительно СТРОКУ (до endl), а не последнюю строку афйла в которой EOF, а не endl
 }
cout<<"-----In file "<<count<<" lines";
delete [] buff;
fffff.close();//закрыли файл
ggggg.close();//закрыли файл
system("pause");
}
``` 
