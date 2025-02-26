using System;

class Program
{
  static void Main()
  {
    // Solicita ao usuário que insira dois números inteiros
    Console.WriteLine("Digite o primeiro número:");
    int num1 = int.Parse(Console.ReadLine());

    Console.WriteLine("Digite o segundo número:");
    int num2 = int.Parse(Console.ReadLine());

    // Calcula a diferença
    int DIF = num1 - num2;

    // Exibe o resultado
    Console.WriteLine($"DIF = {DIF}");
  }
}
