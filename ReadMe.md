# JavaAPCSA Section 5 Practice

* Part A - Determining color in the visible spectrum
* Part B - Determining the next color for a stop light
* Part C - Determining the next color for a stop light using switch


## Part A

### Problem 1: Determining color in the visible spectrum

#### Overview

In the  ColorRange.java file, write a program which when given a wavelength in nanometers will return the corresponding
color in the visible spectrum.

**Color**       **Wavelength (nm)**
Violet               380-450
Blue                 450-495
Green                495-570
Yellow               570-590
Orange               590-620
Red                  620-750




#### Task

You must implement the following using a suitable if decision statement.

1 Prompt the user to enter the wavelength, the wavelength should be of type double.
2. For each range (e.g. 380-450) the number on the left is included in the range, but the number on the right is not included in the
   range.
3. If the input value is not found on the visible spectrum then state that the wavelength is not within the visible spectrum.
4. Expected Output Example:
 
   * Enter a color code: 630
   The color is Red
    
   * Enter a color code: 25.0
   The entered wavelength is not a part of the visible spectrum
    
   * Enter a color code: 750.5
   The entered wavelength is not a part of the visible spectrum


## Part B

### Problem 2: Determining the next color for a stop light

#### Overview

The normal behavior for a stop light is to cycle from Red to Green to Yellow to Red (and continues with this pattern). Write a java
program in TrafficLightChecker.java, which will determine the next color of a stop light in this pattern, Red to Green to Yellow to
Red based on the current stop light provided by the user.

#### Task

You must implement the following using a suitable if decision statement.

1. Have the user enter the value for the currentColor.
2. Compute the next color stop light based on the currentColor.
3. Alert the user for any invalid value of color.

### Expected Output Example:

   * Enter a color code: 1
   Next Traffic Light is green

   * Enter a color code: 3
   Next Traffic Light is red

   * Enter a color code: 0
   Invalid color

   * Enter a color code: 4
   Invalid color

## Part C

### Problem 3: Determining the next color for a stop light using switch

#### Overview

Re-write practice 5-2 using switch statement in TrafficLightSwitch.java

### Task
Implement practice 5-2 using switch statement and ensure the program alert users if they’ve entered an invalid value.