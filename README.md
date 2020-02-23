# Тут размещаются задания и оценки

## Комментарии преподавателя **в cpp файле** - для Вашего лучшего понимания проблем и ошибок!

# Обязательные требования ко всем лабам:

• Кодировка UNICODE   
• Текст задания, которое выполняется надо продублировать в первых строках решения как комментарий       
также стоит реализовать вывод условия задачи как один из пунктов в меню (если создание меню есть в условии задачи)     
• в main() только объявления переменных и вызовы функций. Вся реализация функций ОТДЕЛЬНО.        
• имена переменных и функций должны соответствовать общепринятым нормам.

## Задание на 14.02 ( )
0) Прочитать, скачать себе и распечатать хорошее краткое объяснение указателей с адреса http://www.math.spbu.ru/user/dlebedin/ncpp4.pdf
1) `(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файла с именем 0-1.cpp (тут решение задачи)`     
Условие задачи в прикрепленном файле "задание на вычисление сумм.pdf"     
Номер варианта - ваш порядковый номер в списке группы

## Задание на 27.02 (функции для работы с одномерными массивами в heap )     
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  файл с именем 1-1.cpp (тут подключение вашей библиотеки для работы с одномерными массивами`

Разработать программу для работы с одним или несколькими одномерными массивами в heap, предусмотрев в ней:     
•	Размер массива N запрашивать у пользователя;      
•	выделение и контроль динамической памяти **в отдельной функции**, а не в main;      
•	функции для инициализации, для ввода, для вывода массивов в heap;      
•	освобождение динамической памяти после её использования **обязательно в отдельной функции**;      
•	организация циклов **обязательно с использованием указателей**;     
• несколько функций для обработки массивов по условию задачи (для сортировки новый массив не создавать);

**Примерные прототипы функций:**     

* void giveMemory(int*&, int)//первый способ. Подумайте, почему обязательно надо тут &
* int* giveMemory(int)//второй способ. Подумайте, можно ли и безопасно ли тут напісать int*& giveMemory(...     
* void freeMemory(int*&,int)
* void initArray(int* ,int,int=0)
* void printArray(int* ,int)

1. В массиве размера N, заполненного случ.числами от -10 до 10, подсчитать количество элементов, встречающихся более одного раза.     
2. В массиве размера N, заполненного случ.числами от -10 до 20, определить максимальную длину последовательности равных элементов.     

## Задание на 28.02 (двумерные массивы в heap)
Выбираем одну задачу по работе с массивами **в heap** из списка ниже и реализуем её.      
`(в СВОЙ РЕПОЗИТОРИЙ записать  в _кодировке UNICODE_  1 файл с именами 2-1.cpp `      
**Попроще**       
• ( ________) В массиве А(N,М) найти номер строки, среднее арифметическое положительных элементов которой является наименьшим и поменять её с первой строкой.    
• (________) В массиве А(N,N) найти первую строку, не содержащую отрицательных элементов, и поменять её с последней строкой.       
• (________) В массиве А(N,М) найти строку, для которой количество перемен знаков максимально и поменять её с первой строкой.        
• (________) В массиве А(N,N) найти максимальные элементы нижнего и верхнего треугольников относительно главной диагонали и поменять местами строки в которых они находятся.       
•	(________) В массиве А(N,М) поменять местами строки, содержащие максимальный и минимальный элементы.        
•	(________) В массиве А(N,М) часть строк состоит из нулей. удалить нулевые строки.       
•	(________) В массиве А(N,М) сменить знаки минимальных элементов и удалить строку с минимальным произведением элементов.       
•	(________) В массиве А(N,М) расположить строки в порядке возрастания их максимальных элементов.        
•	(________) В массиве А(N,М) расположить строки в порядке возрастания количества минимальных элементов в каждой строке.    
•	(________) В массиве А(N,M) переставить строки в порядке возрастания элементов последнего столбца.     
•	(________) В массиве А(N,M) переставить строки так, чтобы строка с максимальной суммой элементов стала первой строкой, а остальные строки расположить в порядке возрастания элементов первого столбца.     

**Посложнее немножко**       
• (________) В массиве А(N,M) расположить строки, стоящие после строки с первым максимальным элементом матрицы, в порядке возрастания количества чётных элементов в строке.      
• (________) В массиве А(N,M) переставить столбцы так, чтобы столбец с максимальной суммой элементов стал первым, а остальные столбцы расположить в порядке возрастания элементов первой строки.        
• (________)	В массиве А(N,M) расположить столбцы по возрастанию количества чётных элементов в столбце.        
• (________)	В массиве А(N,M) расположить столбцы по возрастанию значений минимальных элементов столбцов. Если минимальные значения в двух столбцах - одинаковые, то первым должен быть тот у которого больше таких минимальных элементов.        
• (________) В массиве А(N,M) элементы столбцов, не содержащих нулевых элементов, расположить в порядке убывания, а сами столбцы расположить в порядке возрастания элементов первой строки.        
• (________)	В массиве А(N,M) расположить элементы каждого столбца в порядке возрастания модулей их отрицательных элементов, а сами столбцы расположить в порядке убывания  сумм их элементов.        
• (________)	В массиве А(N,M) расположить положительные элементы каждого столбца в порядке возрастания, а сами столбцы расположить в порядке убывания их первых максимальных элементов.        
• (________)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества нечётных элементов в столбце.        
• (________)	В массиве А(N,M) расположить в порядке возрастания элементы столбцов, максимальный элемент которых не превосходит заданную величину р, а сами столбцы расположить в порядке возрастания количества перемен знаков в каждом столбце.        
• (________)	В массиве А(N,M) расположить столбцы в порядке  возрастания количества нулевых элементов в каждом столбце.       
• (________)	В массиве А(N,М) "удалить" столбцы, все элементы которых являются простыми числами, сдвинув остальные.       
• (________)	В массиве А(N,М) столбец с минимальным количеством нечетных элементов поменять местами с столбцом c максимальным кол-вом таких элементов.       
• (________)	В каждом столбце массива А(N,М) после первого отрицательного элемента вставить максимальную цепочку из положительных элементов данного столбца. Расположить столбцы в порядке возрастания по количеству вставленных элементов. 
