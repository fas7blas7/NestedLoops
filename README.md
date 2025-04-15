1️⃣ Countdown Apples 🍎  
Namespace: _1_CountdownApples  
📌 Description:  
Reads an integer and prints a countdown from that number down to 1.

📝 Code:
```csharp
int number = int.Parse(Console.ReadLine());

for (int apples = number; apples >= 1; apples--)
{
    Console.WriteLine(apples);
}
```
2️⃣ Even Powers of 2 🔋
Namespace: _2_EvenPowersOf2
📌 Description:
Reads an integer n and prints all even powers of 2 from 2^0 up to 2^n.

📝 Code:
```
namespace _2_EvenPowersOf2
{
    internal class EvenPowers
    {
        static void Main(string[] args)
        {
            int n = int.Parse(Console.ReadLine());         
            for (int i = 0; i <= n; i += 2)
            {
                Console.WriteLine(Math.Pow(2, i));
            }
        }
    }
}
```
3️⃣ TriangleOfStars ⭐
Namespace: _3_TriangleOfStars
📌 Description:
Reads an integer n and prints a triangle of stars with n rows.

📝 Code:
```
int n = int.Parse(Console.ReadLine());

for (int row = 1; row <= n; row++)
{
    for (int col = 1; col <= row; col++)
    {
        Console.Write("*");
    }

    Console.WriteLine();
}
```
4️⃣ Building 🏢
Namespace: _4_Building
📌 Description:
Reads the number of floors and rooms, and prints a building layout with special labels for the top floor and alternating labels for the rest.

📝 Code:
```
int countOfFloors = int.Parse(Console.ReadLine());
int countOfRooms = int.Parse(Console.ReadLine());

for (int floor = countOfFloors; floor >= 1; floor--)
{
    for (int room = 0; room < countOfRooms; room++)
    {
        if (floor == countOfFloors)
        {
            Console.Write($"L{floor}{room} ");
        }
        else if (floor % 2 == 0)
        {
            Console.Write($"O{floor}{room} ");
        }
        else if (floor % 2 == 1)
        {
            Console.Write($"A{floor}{room} ");
        }
    }

    Console.WriteLine();
}
```
5️⃣ PrimePyramid ⛰️
Namespace: _5_PrimePyramid
📌 Description:
Prints a pyramid of incrementing numbers up to a given number, one layer at a time.

📝 Code:
```
int end = int.Parse(Console.ReadLine());
int currentNum = 1;

for (int i = 1; i <= end; i++)
{
    for (int j = 1; j <= i; j++)
    {
        Console.Write(currentNum + " ");
        currentNum++;

        if (currentNum > end)
        {
            break;
        }
    }

    Console.WriteLine();

    if (currentNum > end)
    {
        break;
    }
}
```
6️⃣ TravelSavings 💰✈️
Namespace: _6_TravelSavings
📌 Description:
Saves money for each destination and announces once enough has been collected.

📝 Code:
```
string destination = Console.ReadLine();

while (destination != "End")
{
    double neededMoney = double.Parse(Console.ReadLine());
    double savedMoney = 0;

    while (savedMoney < neededMoney)
    {
        double currentMoney = double.Parse(Console.ReadLine());
        savedMoney += currentMoney;

        Console.WriteLine($"Collected: {savedMoney:F2}");
    }

    Console.WriteLine($"Going to {destination}!");

    destination = Console.ReadLine();
}
```
7️⃣ SumOfDigits 🔢
Namespace: _7_SumOfDigits
📌 Description:
Calculates and displays the sum of digits of each entered number until "End" is typed.

📝 Code:
```
string input = Console.ReadLine();

while (input != "End")
{
    int number = int.Parse(input);
    int sum = 0;

    while (number > 0)
    {
        int lastDigit = number % 10;
        sum += lastDigit;
        number /= 10;
    }

    Console.WriteLine($"Sum of digits = {sum}");

    input = Console.ReadLine();
}

Console.WriteLine("Goodbye");
```
8️⃣ PrimeNumbers 🔍
Namespace: _8_PrimeNumbers
📌 Description:
Prints all prime numbers within a user-specified range.

📝 Code:
```
int start = int.Parse(Console.ReadLine()); 
int end = int.Parse(Console.ReadLine());   

for (int num = start; num <= end; num++)
{
    int primeCounter = 0;

    for (int i = 1; i <= num; i++)
    {
        if (num % i == 0)
        {
            primeCounter++;
        }
    }

    if (primeCounter == 2)
    {
        Console.Write($"{num} ");
    }
}
```
📅 Updated Commit Progress:

📅 Current Progress: 377 commits
📊 Progress Bar:
██████████████████████████░ 75.4% (377/500)

📌 Milestones:
✅ 100 commits
✅ 200 commits
✅ 300 commits
🔲 400 commits
🔲 500 commits (🎉)
🎯 Commit Progress Tracker

🚀 Goal: 500 commits in 2025
📅 Current Progress: 377 commits
