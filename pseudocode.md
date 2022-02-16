# Coffee Psuedo

## Turn coffee machine on
If coffee maker is off
turn coffee machine on
else do nothing

## Get water
If water is equal to zero
fill water reservoir to 12 cups

## Get coffee

## Get scoop

If coffee is equal to zero
add coffee to 3 scoops

## Get coffee cup
Place coffee cup in coffee machine

## Select brew type
If brew selection is equal to "strong" 
press brew button
else iterate until brew selection equals strong
then press brew button

## Remove full coffee cup
If coffee cup is full
remove coffee cup and coffee
else leave coffee cup in machine until full

## Turn coffee machine off
Turn off coffee machine if coffee cup is full

```Coffee Pseudo Code Format

Create coffee making variables
- coffee
- water
- coffee scoop
- coffee cup
- brew type (regular, strong, espresso, iced)

//Checks to see if coffee maker is on or off. Power on if it is off.

FUNCTION: powerCoffeeMaker()
    If coffee maker !== 1
        turn on coffee maker

//Function to check for water and fills the water to full 12 cup level if less than 1 cup

FUNCTION: addWater()
    If water < 1
        fill water until >= 1

//Function fills coffee 1 scoop at a time until machine has 3 scoops if less than 3 scoops

FUNCTION: addCoffee()
    If coffee < 3 scoops
        add 1 scoop until coffee === 3 scoops

//Function to allow user selection of brew type

FUNCTION: selectBrew()
    user selects from brew type
    display brew type on screen

//Function to brew the coffee once all requirements are met and brew type is selected. Adds 1 cup of water and 3 scoops of coffee together. Once coffee is made, turns power to off.

FUNCTION: brewCoffee()
    get input from selectBrew()
    add water until === 1 AND add coffee scoops until === 3
    then change powerCoffeeMaker() === 0
```