# -C-Program-to-Check-whether-the-Entered-Number-is-Even-or-Odd
C# Basic Programming 

using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace _1EvenOdd
{
	class Program
	{
		static void Main(string[] args)
		{
			int i;
			Console.WriteLine("\n Enter a number to check it is even or odd:");
			i = int.Parse(Console.ReadLine());
			if(i %2 == 0)
			{
				Console.WriteLine("\n Entered number is even");
				Console.ReadLine();
			}
			else
			{
				Console.WriteLine("\n Entered number is odd");
				Console.ReadLine();
			}
		}
	}
}
