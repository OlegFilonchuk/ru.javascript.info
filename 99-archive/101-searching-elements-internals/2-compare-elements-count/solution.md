Значение `aList1` изменится, потому что `getElementsByTagName` - *живая* коллекция. Она автоматически дополнится новым элементом `a` и её длина увеличится на 1.

А вот `querySelector`, наоборот, возвращает статичный список узлов. Он ссылается на те же самые элементы, что бы не происходило с документом. Поэтому длина `aList2.length` останется неизменной.

