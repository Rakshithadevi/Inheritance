# Inheritance

## Aim:
To write a C# program to print some messages using hierarchical inheritance

## Algorithm:
## Step 1:
Create a base class Tyre.

## Step 2:
Create two child class.

## Step 3:
Create a constructor in the base class and print a message.

## Step 4:
create a function in child class to print a message.

## Step 5:
Run the program



## Program:
```
using System;
namespace vehi
{
    public class tyre
    {
        public tyre()
        {
            Console.WriteLine("Base class tyre:");
        }
        public virtual void Display()
        {
            Console.WriteLine("tyre");
        }

    }
    public class scooter : tyre
    {
        public scooter()
        {
            Console.WriteLine("for the Scooter");
        }
        public override void Display()
        {
            base.Display();
            Console.WriteLine("scooter");
        }
    }
    public class car : tyre
    {
        public car()
        {
            Console.WriteLine("for the car");
        }
        public override void Display()
        {
            base.Display();
            Console.WriteLine("car");
        }
    }
    public class abc
    {
        static void Main(string[] args)
        {
            car ar = new car();
            scooter sc = new scooter();
            ar.Display();
            sc.Display();

        }
    }


}
```


## Output:
![image](https://github.com/Rakshithadevi/Inheritance/assets/94165326/0bf6df09-6038-4c6c-9386-675282d23569)


## Result
C# program to print some messages using hierarchical inheritance is implemented successfully.
