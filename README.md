Счастливым билетом будем называть такой билет, у которого
сумма первых трех цифр равна сумме последних трех цифр его номера.   
**Постановка задачи**: требуется найти количество счастливых билетов, 
если номера билетов находятся в диапазоне от 000000 до 999999.
**Ход решения**: сумма трех цифр не превосходит 27, поэтому для каждого числа
от 0 до 27 найдем количество троек цифр, сумма которых равна этому числу.
Количество таких троек для каждого числа i обозначим $\Omega_i$
Тогда, найдя для каждого i это значение, мы сможем сказать, что количество счастливых билетов,
в которых сумма первых трех цифр равна сумме последних трех цифр и, в свою очередь, равна i, 
равна $\Omega_i^{2}$.  
Таким образом, количество счастливых билетов равно
$\sum\limits_{i=1}^n\Omega_i^{2}$
