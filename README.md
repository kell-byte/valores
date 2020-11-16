# Valores







using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace valores
{
    class Program
    {
        static void Main(string[] args)
        {
            int  maior1=0;
            int  maior2=0;
            Console.WriteLine("Digite um número:");
            maior1 = int.Parse(Console.ReadLine());
            Console.WriteLine("Digite um segundo número:");
            maior2 = int.Parse(Console.ReadLine());
            
            if (maior1 > maior2)
                Console.WriteLine(" O primeiro valor é o maior" +  maior1);
            else
            Console.WriteLine(" O maior valor informado é o segundo número" +  maior2);
            Console.ReadLine();
        }
    }
}
