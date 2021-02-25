# 2D-Arrays  
  
short test of 2D Arrays.  
  
thx to the tutorials: https://www.youtube.com/channel/UCVdfgrCLfJQfO5EgPlzaYAQ  [German]  

```c#
using System;

namespace _2D_Arrays
{
    class Program
    {
        static void Main(string[] args)
            //Ein 2DArray ist eine Tabelle von Daten [1,3] [Zeilen,Spalten]
        {
            string[,] ProduktListe = new string[2, 2];
            //Zeile 1
            ProduktListe[0, 0] = "Senf";
            ProduktListe[0, 1] = "1 Euro";
            //Zeile 2
            ProduktListe[1, 0] = "Saft";
            ProduktListe[1, 1] = "2 Euro";

            Console.WriteLine("Produkte:  " + ProduktListe[0, 0]);
            Console.WriteLine("Preise:  " + ProduktListe[0, 1]);
            Console.WriteLine("Produkte:  " + ProduktListe[1, 0]);
            Console.WriteLine("Preise:  " + ProduktListe[1, 1]);

            Console.ReadKey();
        }
    }
}
```
