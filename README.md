//Напишите программу, которая принимает на вход число и проверяет, кратно ли оно одновременно 7 и 23.
Console.Clear();
Console.Write("Введите 1 -ое число: ");
int n = Convert.ToInt32(Console.ReadLine());

if  (n  % 7 ==0  && n % 23 ==0 ) {
     Console.WriteLine("yes"); 
}
    else 
    {
      Console.WriteLine("no");
}
 
 
// Напишите программу, которая принимает на вход координаты точки (X и Y), 
// причём X ≠ 0 и Y ≠ 0 и выдаёт номер координатной четверти плоскости, в которой находится эта точка.

Console.Clear();
Console.Write("Введите точку X: ");
int x = int.Parse(Console.ReadLine()!);
Console.Write("Введите точку Y: ");
int y = int.Parse(Console.ReadLine()!);
 if( x > 0 && y > 0) {
    Console.WriteLine("1");
 }
  if( x < 0 && y > 0) {
    Console.WriteLine("2");
 }
  if( x < 0 && y < 0) {
    Console.WriteLine("3");
 }
  if( x > 0 && y < 0) {
    Console.WriteLine("4");
 }
 else
 Console.WriteLine("Точка находится на оси координат");

 
