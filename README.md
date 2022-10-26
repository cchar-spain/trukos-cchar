# Trukos cchar


# Tipos de datos
```
int edadClient = 13;
double d1 = 3.5;
float f1 = 2.5;
string messageStop = "Es un demo";
bool elSolBrilla = true;
```

# Hola Mundo
```
using System;
namespace demo01integer
{
    class Program
    {
        static void Main(string[] args)
        {
            // Numeros enteros
            int num1 = 13;
            Console.WriteLine("Hola Mundo "+ num1);
            Console.Read();
        }
    }
}
```

# Cambiar color a la consola
```
using System;

namespace demo01integer
{
    class Program
    {
        static void Main(string[] args)
        {
            Console.ForegroundColor = ConsoleColor.DarkBlue;
            Console.BackgroundColor = ConsoleColor.Yellow;
            Console.Clear();
            Console.WriteLine("Hola Mundo");
            Console.Read();
        }
    }
}
```
# Conversiones de datos
```
// 1- Conversion Implicita
int num = 12212;
long numg = num;
              

// 2 - Conversion de tipo
bool elSolBrilla = true;
string miSolString = elSolBrilla.ToString();
Console.WriteLine("Hola Mundo");
Console.Read();
```
