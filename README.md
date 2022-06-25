### EX NO : 08
### DATE  : 01.06.2022
# <p align="center">Inheritance</p>

## Aim:
To write a C# program to print some messages using hierarchical inheritance.
## Algorithm:
### step 1: 
Create a base class.

### step 2:
Create two child class.

### step 3:
Create a constructor in the base class and print a message.

### step 4:
create a function in child class to print a message.

<br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/><br/>

## Program:
```c#
using System;
namespace Wheel{
    public class Tyre{
        public Tyre(){
            Console.WriteLine("Tyre for Vehicles");
        }  
    }
    public class Scooter: Tyre{
        public void DisplayScooter(){
            Console.WriteLine("2 Tyre for scooters");
        }
    }
    public class Car: Tyre{
        public void DisplayCar(){
            Console.WriteLine("4 Tyre for Car");
        }
    }
    public class Program{
        public static void Main(string[] args){
            Car c = new Car();
            c.DisplayCar();
            Console.WriteLine();
            Scooter s = new Scooter();
            s.DisplayScooter();   
        }
    }
}
```
## Output:
![Capture](https://user-images.githubusercontent.com/75235747/173222996-c47ba8c6-b10c-4f79-94c2-bf797012f26b.JPG)

## Result
C# program to print some messages using hierarchical inheritance is implemented successfully.
