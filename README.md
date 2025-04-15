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
📅 Updated Commit Progress:

📅 Current Progress: 372 commits
📊 Progress Bar:
█████████████████████████▒ 74.4% (372/500)

📌 Milestones:
✅ 100 commits
✅ 200 commits
✅ 300 commits
🔲 400 commits
🔲 500 commits (🎉)
🎯 Commit Progress Tracker

🚀 Goal: 500 commits in 2025
📅 Current Progress: 372 commits
