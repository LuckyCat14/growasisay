# growasisay
По мотивам Конвея

Этап 1. Оно должно вырасти

Начинаем с цветочного горшка 3х10

10 | _  _  _  |
 9 | _  _  _  |
 8 | _  _  _  |
 7 | _  _  _  |
 6 | _  _  _  |
 5 | _  _  _  |
 4 | _  _  _  |
 3 | Ж  +  Ж  |
 2 | Ж  Ж  Ж  |
 1 | Ж  Ж  Ж  |
   -==========-
     A  B  C

Нижние 3 этажа - земля, остальное - воздух.
В точке B3 находится Семечко.

Задача 1-го этапа получить что-то вроде

 5 | _  _  _  |
 4 | _  С  _  |
 3 | Ж  +  Ж  |
 2 | Ж  К  Ж  |
 1 | Ж  Ж  Ж  |
   -==========-
     A  B  C

Т.е. чтобы из семечка вниз спустился корень, а вверх поднялся стебель

Семечко имеет достаточный запас для этого, то есть оно может лежать на земле, в воде - все равно корнь и стебель вылезут на 1 клетку.

Дальше корень должен получать из среды питательные вещества и передавать их остальному растению.

Интересно настроить каждый вид ткани так, чтобы рост происходил автоматически.

Ядро
1) если не соединено с корнем, то выпусти корень
2) иначе
     если нет стебля, то выпусти корень

