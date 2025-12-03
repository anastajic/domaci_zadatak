#  Домаћи задатак из Техничке документације
## Задатак 
Програм који на основу унете дужине странице квадрата a израчунава полупречник 
уписаног круга r.

$r = \frac{a}{2}$

### Алгоритамска шема 

## Решење 
``` cs
using System;
namespace ConsoleApp1
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.Write("Unesite duzinu strane kvadrata a: ");
        double a = double.Parse(Console.ReadLine());

        double r = a / 2;

        Console.WriteLine("Poluprecnik upisanog kruga je: " + r);

        Console.WriteLine("Pritisnite bilo koji taster za izlaz...");
        Console.ReadKey();
        }
    }
}
```
### Тест примери
Тест пример 1:

``` text
Unesite duzinu strane kvadrata a: 10
Poluprecnik upisanog kruga je: 5
Pritisnite bilo koji taster za izlaz...
```

Тест пример 2:

``` text
Unesite duzinu strane kvadrata a: 20
Poluprecnik upisanog kruga je: 10
Pritisnite bilo koji taster za izlaz...
```
### Објекти 
| Редни број | Променљива | Тип променљиве |
| ---------- | ---------- | -------------- |
| 1.         | `a`        | `double`       |
| 2.         | `r`        | `double`       |
