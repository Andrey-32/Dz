//1

Console.WriteLine("введите число a");
int numbera = int.Parse(Console.ReadLine());
Console.WriteLine("введите число b");
int numberb = int.Parse(Console.ReadLine());
if (
numbera < numberb
)
Console.WriteLine("max = b");
if (
numbera > numberb
)
Console.WriteLine("max = a");

//2

Console.WriteLine("введите число a");
int numbera = int.Parse(Console.ReadLine());
Console.WriteLine("введите число b");
int numberb = int.Parse(Console.ReadLine());
Console.WriteLine("введите число c");
int numberc = int.Parse(Console.ReadLine());
int max  = numbera;
if (numberb > max) 
   max = numberb;
if (numberc > max)
  max = numberc; 

Console.WriteLine($"max={max}");

//3

Console.WriteLine("Введите число: ");
 
int i = int.Parse(Console.ReadLine());
 
if (i % 2 == 0)
 
{
 
Console.WriteLine("Введенное число является четным");
 
Console.ReadLine();
 }
 
 if (i % 2 == 1)
 
{
 
Console.Write("Введенное число нечетное");
 
Console.ReadLine();
}

//4

Console.WriteLine("Введите число: ");
int n = int.Parse(Console.ReadLine());
int i = 1;   
while  (i <= n)
{
    int x = i % 2;
    if (x== 0)
    {
     Console.Write($"{i},");   
    }
    i = i + 1;
}


