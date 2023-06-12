# Homework4
// Напишите цикл, который принимает на вход два числа (A и B) и возводит число A в натуральную степень B.

int num1 = ReadLine();
int A = Res(a);
Console.WriteLine(A);
int num2 = ReadLine();
int B = Res(b);
Console.WriteLine(B);
int res (int Res)
{
    int A=1;
    for (i=0; i<B;i++)
    {
        res*=A
    }
return res
}
int ReadLine()
Console.WriteLine("Введите число A"); 
string input = Console.ReadLine();
int A = Convert.ToInt32(input);

int ReadLine()
Console.WriteLine("Введите число B"); 
string input = Console.ReadLine();
int B = Convert.ToInt32(input);
return Res;

//Напишите программу, которая принимает на вход число и выдаёт сумму цифр в числе.

int number = ReadLine();
int sum = Sum (number);
Console.WriteLine(sum);

int Sum (int n)
{
    int sum = 0;
    while (number!=0)
    {
        int i=number%10;
        sum+=i;
        number/=10;
    }
    return sum;
}
int ReadLine()
{
Console.Writeline ("Введите число");
string input = Console.ReadLine();
int number = Convert.ToInt32(input);
return number;
}

// Напишите программу, которая задаёт массив из 8 элементов и выводит их на экран.

int[] array = {1,12,31,4,18,15,16,17};
int RandomNumber();
int[] RandomNumber();
{
    for (int i=1; i<array.Length; i++);
    {
    array[i] = new Random(); Next(2);
    Console.WriteLine(array[i]);
    }
    return array;
   }
  int[]array = RandomNumber();
