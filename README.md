# Тут размещаются задания и оценки

## Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

# Обязательные требования ко всем лабам:

• Кодировка UNICODE   
• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.        
• имена переменных и функций должны соответствовать общепринятым нормам.

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

1.	Определить, сколько слов в строке содержат хотя бы одну заданную букву. Вывести такие слова на экран.
2.	Определить количество слов в строке, которые начинаются на заданную букву. Вывести их на экран.
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
15.	В строке найти и удалить все слова максимальной длины.
16.	(Петращенко) Найти и удалить все слова строки, состоящие только из цифр.
17.	В строке найти и вывести на экран слова, длина которых - простое число. Вставить после первого слова, длина которого простое число, заданную подстроку, например  ”---”..
18.	В строке удалить все слова заданной длины, начинающиеся с цифры.
19. В строке после каждого слова с нечётной длиной, начинающегося с заданного символа, вставить заданную подстроку, например  (”---”..
20.	(7-8.) В строке найти все слова чётной длины, заканчивающиеся на заданную букву. Вывести их на экран, и вставить после них заданную подстроку, например  ”---”..
21.	(8) В строке удалить слова, в которых буквы упорядочены в алфавитном порядке и которые начинаются на большую букву.
26.	(8) В строке найти и вывести на экран слова, в которых буквы упорядочены в алфавитном порядке. Удалить все такие слова.
40.	(7-8 ) В строке найти и вывести на экран все слова, в которых буквы упорядочены в порядке, обратном алфавитному (TOK, zona).
22.	(7 ) В строке удалить все слова, содержащие заданную букву ровно два раза.
23.	(Устинов 6) В строке найти, вывести на экран и, затем, удалить из исходной строки фрагменты, заключённые в круглые скобки. Скобки расставлены верно. Проверять не надо.
13.	(6) В строке удалить слова, заключённые в круглые скобки и длина которых чётная.  Скобки расставлены верно. Проверять не надо.24.	(6) После каждого трёхбуквенного слова в строке вставить заданную подстроку, например  ”---”..
25.	В строке найти и вывести на экран все слова ”палиндромы” (пишутся одинаково слева направо и справа налево).
27.	(8-9) После каждого слова строки, оканчивающегося заданной подстрокой, вставить указанный символ.
28.	(7)В строке поменять местами первое слово минимальной длины и первое слово максимальной длины.
29.	(8-9 ) В строке в каждой паре слов поменять слова местами, если длины слов совпадают, иначе заменить их звёздочками.
30.	В каждом слове нечётной длины строки удалить буквы, стоящие на нечётных позициях.
31.	Преобразовать каждое слово в строке, удалив в нём заданную букву.
32.	Преобразовать каждое слово чётной длины в строке, удалив в нём стоящие рядом одинаковые символы, оставив по одному.
33.	Заменить все слова в строке  заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.
34.	(8) Если в строке есть слово, которое встречается k раз, удалить все такие слова кроме последнего.
36. (8-9) Назовём два слова, стоящие рядом, особой парой, если заданная буква встречается в них одинаковое число раз, и номера позиций, в которых она располагается и в том и в другом слове, одинаковы. Вывести на экран все особые пары и удалить их.
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
53.	(7-8) Заменить все слова в строке заданной подстрокой, если длина слова совпадает с длиной подстроки и слово содержит хотя бы одну цифру.
54. (7) Определить, сколько слов в строке состоит только из цифр. Вывести такие слова на экран и удалить после них следующее слово.
55.	(7) В строке найти слова, содержащие цифры, расположенные подряд, и заменить их  ---…-. Вставить перед такими словами заданную подстроку.
35.	(8)В строке найти слово (слова), содержащее максимальное количество цифр, расположенных подряд, и заменить их на ---…-. Вставить после таких слов заданную подстроку.
56.	(8-9 ) Найти и вывести на экран все слова строки, в которых все буквы различны. Вставить перед такими словами заданную подстроку.
