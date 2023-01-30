Итоговая проверочная работа

1. Создать репозиторий на GitHub
2. Нарисовать блок-схему алгоритма
3. Снабдить репозиторий оформленным текстовым описанием решения README
4. Написать программу, решающую поставленную задачу
5. Использовать контроль версий, этапы 2, 3 и 4 должны быть расположены в разных коммитах

Задача: Написать программу, которая из имеющегося массива строк формирует массив из строк, длинна которых меньше или равна 3 символа. 
Первоначальный массив можно ввести с клавиатуры, либо задать на старте выполнения алгоритма. Сделать работу исключительно массивами. 

Пример: "Hello" "24" "for" "1" --> "24" "for" "1"

Решение:

1. Cоздаем строку, в который пользователь будет указывать сколько элементов массива он хочет вписать (Console.Readline()). Делаем примечание что " в массиве будут видны только строки с тремя символами" (Console.Writeline())
2. Пишем метод  создания ('Void createMassive') и заполнения массива (Void FillMassive)
3. Прописываем событие, когда ни один элемент не подходит ("Элементов удовлетворяющих условию не найдено") (if)
4. Прописываем событие, при котором полученный массив выводится на экран (Console.Writeline(massive))
5. Проверяем программу на наличие ошибок и недочетов. Ищем способы оптимизировать программу
6. Если все условия выполнены - сдаем работу