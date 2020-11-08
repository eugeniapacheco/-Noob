using System;
/08.11.2020/

namespace #Noob
{
    // #LetTheGamesBegin
    /// <summary>Create an algorithm that defines and stores Player's nickname and it says "You’re such a Noob #Fiinz!
   // It's always good to have newbies around here!". Being #Fiinz, in this case,  the selected, name of the Player
    // <see cref="System.Console.WriteLine(System.String)"/> for information about output statements
    /// </summary>
 class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("What is your Name?");
            String name = Console.ReadLine();
            Console.WriteLine("You’re such a Noob " + name + "! It's always good to have newbies around here!");
        }
    }

