using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
    class Program
    {
        static void Main(string[] args)
        {
            string a;
            float c;

            a = Console.ReadLine();
            c = Convert.ToSingle(a);

            Console.WriteLine(2 * (Math.Pow(Math.Sin((3 * Math.PI) - (2 * c)), 2) - Math.Pow(Math.Cos((5 * Math.PI) - (2 * c)), 2)));

            Console.ReadLine();
        }
    }
}
