# M27-code.github.io

## Intro
I am a student at Columbia College Chicago. This portfolio showcases my work from PROG-101 with Janell Baxter.

## Project Examples

### Adventure Game 2 - "Mansion Mayhem"
<img src="https://i.ibb.co/kVNz5Hgf/Mansion.png" alt="Mansion"></a>
> Compete to inherit a late millionaire’s estate by solving logic-based room puzzles. Search for clues from a deceptive widow, a cryptic but honest butler, and hints hidden in the mansion itself.
<br> <sub><ins> #C text-based game</ins></sub>

#### *FEATURES*
- Colored and rolling text 
- Input handling 
- ASCII Visuals

### Adventure Game 3 - "Operation: BIOTRACE"
<img src="https://i.ibb.co/kgZRzD7J/Screenshot-2025-05-11-174654.png" alt="Exoplanet"></a>
> Traverse across uncharted alien biomes and document extraterrestial life. Submit five findings to the Transitter Beacon to complete the mission.
<br> <sub><ins> #C WPF Visual point-and-click game</ins></sub>

#### *FEATURES*
- Visually interactive UI
- Randomized encounters
- Linear gameplay

## Expirimental Learning

### Cumlative Verse

<img src="https://i.ibb.co/79RJtYW/Screenshot-2025-05-12-143739.png" alt="12Days"></a>
> A program which properly generates the lyrics to *"The Twelve Days of Christmas"* in sequential order, including correct grammar in the fixed format.

     //"if the item is 0 (Partridge) and the day is greater than 1 (1st day of Christmas)"
    if (item == 0 && day > 1)
            Console.WriteLine("and " + items[item] + "."); //it's the Partridge line and requires an "and" and "."
    else
            Console.WriteLine(items[item] + (item == 0 ? "." : ",")); //"?" if the item is 0 place "." else place ","
<br><sup>*Logic used for syntax correction*</sup>


### Substitution Cipher

> A program which ciphers user input by shifting alphabetical order based on input value.

### Star Pyramid

> A program which produces a triangle of asterisks using loops.

    class Program
    {
        static void Main(string[] args) 
        {
            int height = 12; //pyramid height
    
            for (int i = 1; i <= height; i++) //outer loop
            {
                //increasing - between * each row down
                for (int j = 1; j <= height - i; j++)
                {
                    Console.Write("-");
                }
    
                //increase * by one
                for (int k = 1; k <= (2 * i - 1); k++)
                {
                    Console.Write("*");
                }
    
                //next line
                Console.WriteLine();
            }
        }
    }

:suspect:
