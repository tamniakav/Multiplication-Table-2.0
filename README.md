# Multiplication-Table-2.0
Just another repository
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace Multiplication_Table_2._0
{
    class Program
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());
            int multiplier = int.Parse(Console.ReadLine());

            if (multiplier < 10)
            {
                for (int i = multiplier; i <= 10; i++)
                {
                    int sum = i * n;
                    Console.WriteLine($"{n} X {i} = {sum}");
                }
            }
            else
            {
                int sum = multiplier * n;
                Console.WriteLine($"{n} X {multiplier} = {sum}");
            }
        }
    }
}
