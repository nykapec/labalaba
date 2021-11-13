using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;


namespace laba1
{
    class Program
    {
        static void Main(string [] args)
        {        
            System.Console.WriteLine("The current date and time is " + System.DateTime.Now);
            Console.WriteLine("Input x=\r");
            double x = 
            Convert.ToDouble(Console.ReadLine());
            double y = 3.7*Math.Sqrt(5 - x)*Math.Cos(3.5 - x)-Math.Pow(5 - x,1/5);
            Console.WriteLine("x = {0} \t y = {1}", x,y);
            Console.ReadKey();
        }
    }
}
