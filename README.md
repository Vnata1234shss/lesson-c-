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
