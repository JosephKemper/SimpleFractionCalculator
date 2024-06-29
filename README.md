# SimpleFractionCalculator
A Repository for the TechFirst Simple Fraction Calculator App

As this is part of our Simple app series, no data will ever be collected from the user's device. 

The goal of the Simple Fraction Calculator, is be able to add, subtract, multiply, and divide whole numbers, mixed numbers, and fractions with each other and get either a whole number, mixed number, or fraction back (as appropriate), and to have any fractions returned, be properly reduced. 

To collect input from the user, I plan to have a single numerical keyboard with numbers from 0 to 9 laid out in the standard position of a traditional keyboard. There will be no decimal input as I will not handle decimals with this calculator, only fractions and whole numbers. 

The number entry boxes will not be traditional text boxes, and will not likely be able to be interacted with directly (unless I can figure out how). Instead, I will have 3 radio buttons that you can select to direct where the number selected on the keypad will go to. The 0 key will not be selectable in any position (whole number, numerator, or denominator) as the first number, and will only be useable after at least one number has been entered. If either a numerator or denominator has been entered and the other does not have a value entered into its place, then I want to highlight the spot where the missing number would go when the user tries to enter an operator (+, -, *, /, or =) and ideally automatically change the radio button to the missing value either numerator or denominator as appropriate. 

Despite the safeguards I will put in for entering numbers, I will likely put in some checks to make sure that the values entered are legal for the way I want my fraction calculator to work. Initially, I will likely only show the answer, but eventually, I want to have the calculator show the work for each step along the way. The calculator on my phone has a limit of 40 operators entered before the equal sign, I will likely put a similar limit on operators for my calculator, though the actual limit will likely vary depending on performance of the app. 
