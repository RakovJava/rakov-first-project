# Учебный проект RakovJavaAQA
---
## Этот проект используется для учебы на курсе Yandex по автоматизации на *JAVA!*


Пробуем  
Перенести <br>
По строкам

- Пробуем
- Ненумерованный
- Список

1. Пробуем
2. Нумерованный
3. Список
---
Пробуем вставку кода


```JAVA
import java.util.ArrayList;


public class Praktikum {
public static void main(String[] args) {
ArrayList<Double> expenses = new ArrayList<>(); // создали список
expenses.add(120.47); // добавили элемент
expenses.add(290.24); // добавили элемент
expenses.add(420.78); // добавили элемент
System.out.println("Сейчас в списке: ");
for (int i = 0; i < expenses.size(); i++) { // i строго меньше размера списка
System.out.println("Трата " + i + ": " + expenses.get(i) + " руб.");
Шпаргалка: списки 4
// напечатали траты и их индексы в списке
}
}
}

```
