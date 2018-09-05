### Пример: проверка за просто число. Оператор break

Да се провери дали едно число **n** е просто. Това ще направим като проверим дали **n** се дели на числата между 2 и √n.

Ето го алгоритъмът за проверка за просто число, разписан постъпково:

* Създаваме променливата **`n`**, на която присвояваме цяло число въведено от входа на конзолата.
* Създаваме булева променлива **`isPrime`** с начална стойност **`true`**. Приемаме, че едно число е просто до доказване на противното.
* Създаваме **`for`** цикъл, на който като начална стойност за променливата на цикъла задаваме 2, за условие **текущата ѝ стойност `<= √n`**. Стъпката на цикъла е 1.
* В **тялото на цикъла** проверяваме дали **`n`**, разделено на **текущата стойност** има остатък. Ако от делението **няма остатък**, то променяме **`isPrime`** на **`false`** и излизаме принудително от цикъла чрез оператор **`break`**.
* В зависимост от стойността на **`isPrime`** отпечатваме дали числото е просто (**`true`**) или съответно съставно (**`false`**).