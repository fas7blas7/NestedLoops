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
### 📅 Updated Commit Progress:

📅 Current Progress: 368 commits
📊 Progress Bar:
████████████████████████▒ 73.6% (368/500)

📌 Milestones: ✅ 100 commits
✅ 200 commits
✅ 300 commits
🔲 400 commits
🔲 500 commits (🎉)
🎯 Commit Progress Tracker

🚀 Goal: 500 commits in 2025  
📅 Current Progress: 368 commits
