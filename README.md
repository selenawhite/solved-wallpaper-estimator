Download Link: https://assignmentchef.com/product/solved-wallpaper-estimator
<br>
5/5 - (2 votes)

Suppose a family wants to remodel a room in their house by adding wallpaper to the 9 foot high walls.You are given the task of writing a program to determine how much the supplies will cost, as follows.



Fill in the comments at the top of the program to include a program descriptionand your name as the author.

And be sure to use the proper naming conventions and provide descriptive names for any constants or variables that you define.

(1) Add a Scanner variable, and two double type variables to hold the room’s width and the wall area.Prompt the user for the room’s length and width in feet and read the values.Display one blank line after reading the input, then calculate and output the total the wall area of the 4 walls.(You figure out what computations are required to calculate this).

Note: This zyLab outputs a newline after each user-input prompt.For convenience in the examples below, the user’s input value is shown on the next line,but such values don’t actually appear as output when the program runs.

Program to calculate wallpapering costs

Enter the room’s length (in feet):12Enter the room’s width (in feet):15

Total wall area is 486.0 square feet

To clarify, since the input and output are not interleaved, the actual zyLab input for this section would be:

1215

And the actual output zyLab output would be:

Program to calculate wallpapering costs

Enter the room’s length (in feet):Enter the room’s width (in feet):

Total wall area is 486.0 square feet

(2) After accounting for cutting and trimming losses, assume a single roll of wallpaper will cover 25.5 square feet.And each tub of wallpaper glue will adhere up to 9.8 rolls of wallpaper.Store these values as double type constants.

Extend the program to also calculate and output the number of whole rolls of wallpaper needed and the the number of whole tubs of glue needed.HINT: Use a Math function to round the value up to the whole rolls and tubs (and store the values in double type variables for later use).

Program to calculate wallpapering costs

Enter the room’s length (in feet):12Enter the room’s width (in feet):15

Total wall area is 486.0 square feet20.0 rolls of wallpaper needed3.0 tubs of glue needed

(3) Each single roll of the wallpaper costs $29.25 and a tub of glue costs $10.25.Store these values using double constants.Extend the program to output a blank line and then calculate and output the costs of wallpaper and glue (and store the values in double type variables for later use).

Program to calculate wallpapering costs

Enter the room’s length (in feet):12Enter the room’s width (in feet):15

Total wall area is 486.0 square feet20.0 rolls of wallpaper needed3.0 tubs of glue needed

Wallpaper cost is 585.0 and glue cost is 30.75

(4) Extend the program to calculate and output the total costs of the remodel, as follows:First create a character constant and assign its value to be the dollar sign character.Then when you output the total cost of the remodel, use the constant to output the dollar sign character in the output.

Program to calculate wallpapering costs

Enter the room’s length (in feet):12Enter the room’s width (in feet):15

Total wall area is 486.0 square feet20.0 rolls of wallpaper needed3.0 tubs of glue needed

Wallpaper cost is 585.0 and glue cost is 30.75Total remodel cost is $615.75/** Program description* Author: your name*/

import java.util.Scanner; // Note: Needed for user input

public class WallpaperCostEstimator {

public static void main(String[] args) {final int WALL_HEIGHT = 9; // feet// FIXME: Define additional required constants here

double wallLength = 0.0;// FIXME: Define additional needed variables here

System.out.println(“Program to calculate wallpapering costs”);System.out.println();

// FIXME (1a): Prompt for and read input wall’s length and width

// FIXME (1b): Calculate and output total wall area

System.out.println(“Total wall area”); // FIXME (1b): Finish the output statement

// FIXME (2): Calculate and output the wallpaper and glue needed, rounded up to nearest integer

// FIXME (3): Calculate and output the wallpaper and glue costs

// FIXME (4): Calculate and output the total costs, using constant character in output