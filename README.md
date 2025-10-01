# Cooking an Egg in C#

## Description

This is a simple C# console program that demonstrates how to write step-by-step instructions using `Console.WriteLine`.  
It’s a fun way to practice programming fundamentals like sequence, conditional thinking, and basic syntax.

The algorithm is written in plain language, showing each step to cook an egg.  

---

## Algorithm 

1. Either buy or get an egg  
2. Go to the kitchen  
3. Look for a pan until you find one  
4. If you find a pan (1), place it on low heat  
5. If you don’t find one (0), ask your neighbor  
6. Put the pan on low heat  
7. Add one or two tablespoons of oil  
8. Crack the egg with a spoon  
9. Pour the egg into the pan  
10. Take the salt  
11. Add a pinch of salt to taste  
12. Wait until the egg starts to set  
13. Flip the egg  
14. Add a little more salt  
15. Wait until it becomes firmer  
16. If the egg is firm and cooked, turn off the heat  
17. Remove the egg from the pan  
18. If it’s too oily, dry it with a paper towel  
19. Place it on a plate  
20. Serve and enjoy

---

## C# Implementation 

The C# code can be found in the `/code` folder as `EggCooking.cs`.  
It simply prints the steps of the algorithm to the console.

```csharp
using System;

class Program
{
    static void Main()
    {
        Console.WriteLine("Step 1: Either buy or get an egg");
        Console.WriteLine("Step 2: Go to the kitchen");
        Console.WriteLine("Step 3: Look for a pan until you find one");
        Console.WriteLine("Step 4: If you find a pan, place it on low heat");
        Console.WriteLine("Step 5: If you don’t find one, ask your neighbor");
        Console.WriteLine("Step 6: Put the pan on low heat");
        Console.WriteLine("Step 7: Add one or two tablespoons of oil");
        Console.WriteLine("Step 8: Crack the egg with a spoon");
        Console.WriteLine("Step 9: Pour the egg into the pan");
        Console.WriteLine("Step 10: Take the salt");
        Console.WriteLine("Step 11: Add a pinch of salt to taste");
        Console.WriteLine("Step 12: Wait until the egg starts to set");
        Console.WriteLine("Step 13: Flip the egg");
        Console.WriteLine("Step 14: Add a little more salt");
        Console.WriteLine("Step 15: Wait until it becomes firmer");
        Console.WriteLine("Step 16: If the egg is firm and cooked, turn off the heat");
        Console.WriteLine("Step 17: Remove the egg from the pan");
        Console.WriteLine("Step 18: If it’s too oily, dry it with a paper towel");
        Console.WriteLine("Step 19: Place it on a plate");
        Console.WriteLine("Step 20: Serve and enjoy");
    }
}
