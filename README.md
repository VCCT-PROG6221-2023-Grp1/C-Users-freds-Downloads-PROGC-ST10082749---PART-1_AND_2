# C-Users-freds-Downloads-PROGC-ST10082749---PART-1_AND_2
README
This is a code snippet of an internal class Controller that manages a list of recipes. The class provides functionality to add, delete, and view recipes. It also allows scaling the ingredients of the recipes by a factor of 0.3, 2, or 3, or resetting the scaling to the original values.

Dependencies
The code does not have any external dependencies and should run on any system that supports C#.

Usage
Instantiate a Controller object.
Call the start() method to start the recipe management system.
Follow the prompts to add, delete, view, or scale recipes.
Methods
clearData(Recipe recipe)
This method clears the data of the specified recipe that the user inserted on the program.

addRecipe()
This method receives data of the recipes that are being added. It prompts the user to enter the recipe name, number of ingredients, and steps, and creates a new Recipe object. The Recipe object is added to the recipes list.

deleteRecipe(Recipe recipe)
This method deletes the specified recipe from the recipes list.

viewRecipes()
This method displays all the recipes in the recipes list. It shows the recipe name, ingredients, and steps.

viewSinglerecipe()
This method displays a single recipe from the recipes list. It prompts the user to select a recipe from a list of all recipes and then displays the selected recipe.

start()
This method is the main method that starts the recipe management system. It displays a menu of options to the user and prompts the user to select an option. The available options are to view all recipes, add a recipe, delete a recipe, scale the ingredients of all recipes, reset the scaling of all recipes, view a single recipe, or exit the program.
