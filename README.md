Ответы на 4 лабу ООП

1. Каково назначение перегрузки операторов?

Способ объявления новых операторов для типа

2. Как используется ключевое слово operator?

Определяет операторный метод, который, в свою очередь, определяет действие оператора относительно своего класса

3. Какие операции нельзя перегружать в C#?

[], ->, (), += -= *= /= и тд.

4. Можно ли перегрузкой отменить очередность выполнения операции?

Да

5. Истинно ли следующее утверждение: операция >= может быть перегружена.

Да

6. Сколько аргументов требуется для определения перегруженной унарной операции?

1

7. Можно ли перегружать операцию []?

индексатор

8. Можно ли перегружать операцию ->?

нет

9. Приведите пример оператора приведения типа

public static MyArr operator -(MyArr obj1, MyArr obj2)

{

MyArr arr = new MyArr();

arr.x = obj1.x - obj2.x;

arr.y = obj1.y - obj2.y;

arr.z = obj1.z - obj2.z;

return arr;

}

10. Что такое метод расширения? Как и где его можно использовать?

Методы расширения (extension methods) позволяют добавлять новые методы в уже существующие типы без создания нового производного класса.

11. Пусть дан фрагмент кода определения оператора преобразования типа. Определить форму преобразования.

public static implicit operator Point2D(Point3D a)

{/* код*/;}

12. Выберите верное утверждение. Метод расширения может:

1) получать доступ к public членам расширяемого класса

2) получать доступ к protected членам расширяемого класса

3) получать доступ к internal членам расширяемого класса

4) быть объявлен в любом классе

5) быть без параметров

13. Выберите из списка неверное правило перегрузки операторов для C#.

1) префиксные операции ++ и – – перегружаются парами

2) операции сравнения перегружаются парами: == и != ; < и >;<= и >=

3) перегруженные операции обязаны возвращать значения

4) должны объявляться как protected

5) true и false можно перегружать
