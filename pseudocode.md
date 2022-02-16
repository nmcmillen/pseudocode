# Coffee Psuedo

1. **Turn on coffee maker**
- If the coffee maker is off, we need to turn on the coffee maker

2. **Get water**
- If we have no water, we need to add water until it is greater than or equal to 1 cup

3. **Get coffee**
- We need to get the coffee we are using to add to the coffee maker

4. **Get coffee scoop**
- We need to get the scoop we are going to use to add a set amount of scoops of coffee to the coffee maker

5. **Add coffee**
- Here, we will need to add 3 scoops off coffee to the coffee maker that will later combine with the water

6. **Select brew type**
- There will be multiple selections (an array) of brew types
- Brew type needs to be selected between strong, regular, espresso, or iced
- Once brew type is selected, it will display on screen element

7. **Brew the coffee and turn machine off**
- Needs to take the input from brew type
- Then combines both a cup of water and the 3 scoops of coffee
- Once the water and coffee are combined, the machine will then turn off

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