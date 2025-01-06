# task1
https://docs.google.com/document/d/1f1n8wzcmIntV-zdbabWMxe9UogQ_Loq-qF7TMCxufaQ/edit?usp=sharing
#qustion1 code
namespace carpetcleeningservice
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Welcom to Islam's Carpet Cleaning Service ");
            double smallcarpetprice = 25;
            double largecarpetprice = 35;
            Console.WriteLine("Please enter the number of small carpets ");
            int smallCarpet = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine("Please enter the number of large carpets ");
            int largeCarpet = Convert.ToInt32(Console.ReadLine());
            Console.WriteLine($"Price per small room: $ {smallcarpetprice}");
            Console.WriteLine($"Price per large room: $ {largecarpetprice}");
            double cost = (smallCarpet * smallcarpetprice )+ (largeCarpet * largecarpetprice);
            double taxrate = 0.06;
            double total = (cost * taxrate)+cost;
            
            Console.WriteLine($"Cost : {cost}");
            Console.WriteLine($"Tax : {taxrate}");
            Console.WriteLine($"Total : {total}");
            Console.WriteLine("This estimate is valid for 30 days");


        }
    }
}
