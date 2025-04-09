int a, b, c, somarAB;
Console.WriteLine("digite o numero A:");
a = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("digite o numero B:");
b = Convert.ToInt32(Console.ReadLine());

Console.WriteLine("digite o numero C:");
c = Convert.ToInt32(Console.ReadLine());

somarAB = a + b;

if (somarAB < c)
{
    Console.WriteLine("a soma de A e B é menor que c");
}
else
{
    Console.WriteLine("a soma de a e b e maior ou igual a C");

}

