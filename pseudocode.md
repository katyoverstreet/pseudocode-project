# Making the Perfect Cup of Coffee

## Objective:

Making a cup of coffee

PROGRAM makecupofcoffee
## Variables
cupSize - User selection of a small cup, a medium cup, or a large cup.
extraFlavor - Extras that can be added to coffee and similar drinks i.e. milk, sugar, creamer.
coffeeType - Different types of coffee the user can make a selection from.

## Objects
keurigBrewer - the machine used to heat water and brew coffee
water - liquid used in the brewing of coffee
coffeeCup - a cup used to hold the coffee
kCup - plastic cup containing a mixture of coffee beans and extra flavor additives, depending on the type of coffee
spoon - used to stir coffee to mix after addition of flavors
flavors - items added to coffee to give new flavor, more flavor, or change flavor.




START program

[//]: # (I should probably start with the choices the user needs to make first.)

If Keurig is plugged in, then move to step 2
    else Plug in the Keurig

GET power on
// this automatically starts the water heating process

WHILE you have insufficient water for the largest cup, then prompt user for more water
    // flashing lights indicates insufficient water. This prompts user to input more water
    // something like WHILE x<5 flash lights

user waits for water to become heated

WHILE water is below a certain temperature, flash power button light
//this shows that the machine is heating the water

IF water is finished heating the lights will stay on but stop flashing

IF the kcup holder is open, continue to next step, else use the handle to open the top where the kcup goes.

INPUT coffee cup of users choice.

When top is closed, light up cup size buttons.

User will place coffee mug on drip tray under the spout.

Wait for the user to press the button for the amount of coffee they want

Once the button is pressed, begin the brewing process.

The user will wait until the machine is finished filling the cup.

WHen the machine is finished, press the power button once to turn machine off.

The user will then select which flavors they want to add to their mug.

After adding the flavours, stir coffee

Let it cool off (normally about 5 minutes)

Drink the coffee

END program
