# never-ending-sushi-game
A sushi conveyor belt game created for COMP401.

This game is a semester-long Java project for UNC's COMP401 class. The game consists of a conveyor belt of sushi that you and four other chefs create and place sushi for sale. The goal of the game is to be the most profitable and most popular chef. You may filter the scoreboard based on most amount of profit, least spoiled food, or highest amount of sushi consumed. The game utilizes the MVC architectural pattern along with the use of interfaces, polymorphism, encapsulation, abstraction, inheritance, delegation, design patterns, and exceptions.

Plates: Each plate is a different price. 
  Red Plate: $1.00; 
  Green Plate: $2.00; 
  Blue Plate: $4.00; 
  Gold Plate: $5.00+ (if you select a gold plate, you must specify a cost).

Sushi: Sashimi, choose the type of seafood, plate type, and plate position then click "Create sushi!".
       Nigiri, rice is already included, so the same directions for sashimi apply for nigiri. 
       Roll, select any ingredients and specify their amount in ounces. Select plate type and plate position, then click "Create roll!"
       
Ingredients: Info about ingredients such as cost, ounces, vegetarian and shellfish status can be located in the attached image. 

DISCLAIMER! Credit to my professor must also be given, as he wrote the following files:
sushigame.controller
sushigame.game
ChefViewListener and RotationRequestListener in sushigame.view
Chefsbelt, Customer, HistoricalPlate, HistoricalPlateImpl, InsufficientBalance, PlateConsumedEvent, RandomCustomer, RotateEvent, SushiGameModel, and TimedPlate/Impl in sushigame.model.
