using System;
using System.Globalization;


class URI {

static void Main(string[] args) {

int R = int.Parse(Console.ReadLine();
double pi = 3.14159;
double RaioCubo = Math.Pow(R,3);
double volume = (4.0/3)*pi*RaioCubo;

Console.WriteLine("VOLUME = " + volume.ToString("F3",CultureInfo.CreateSpecificCulture("en-US")));
Console.Read();
  
   }


}
