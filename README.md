
# AnnDroidInAlgotihmLand
Jessie Alcalan
Xavier Zavala

collaborative effort to get this game kicking

## Code Analysis
STEP 1

1. the src folder contains the package "level1", this package contains all of the classes for the program.

2. the content folder contains all of the material, no code, only info like pictures, gifs, audio and text.

3. the UML contains a tree for the developer to understand the framework and roles of the classes and materials.

4. content is intended to be pulled from and modified, while the code is intended to be the heart and muscle of the program. the code works with the material, the intention seperates them both into different folders. (it looks nicer too)


STEP 2

1. the main class contains the main method.

2. looking into the documentation, it prepares a window for the program, sets a name, and tinkers with other parameters.

3. the main class establishes an AppRouter, allowing the main menu to queue.

STEP 3:

1. looking through the different instances of menus and screens, i believe the classes for the instance itself, draws components.

2. the assets class definitely handles loading files and content.

3. the AppRouter updates the instance, switching from one class to another, like from main menu to the rabbit game.

STEP 4:

1, the UML clearly states the roles each class takes, intention and title.

2. the AppRouter seems to do the most work.

3. all of the panels depend on the AppRouter, they interact with the Assets.

Step 5: 

1. LeaderBoard Repository stores the scores.

2. an arraylist is used

3. it would make most sense to add them in the Leaderboard Algorithms class.
