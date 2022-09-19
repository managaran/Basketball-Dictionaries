# Basketball-Dictionaries

Assignment Tasks
Challenge 1: Update the Constructor
His class constructor so far looks like this:

class Player:
    def __init__(self, name, age, position, team):
        self.name = name
        self.age = age
        self.position = position
        self.team = team
copy
Update the constructor to accept a dictionary with a single player's information instead of individual arguments for the attributes.
Challenge 2: Create instances using individual player dictionaries.
Given these variables, create Player instances for each of the following dictionaries. Be sure to instantiate these outside the class definition, in the outer scope.

kevin = {
    	"name": "Kevin Durant", 
    	"age":34, 
    	"position": "small forward", 
    	"team": "Brooklyn Nets"
}
jason = {
    	"name": "Jason Tatum", 
    	"age":24, 
    	"position": "small forward", 
    	"team": "Boston Celtics"
}
kyrie = {
    	"name": "Kyrie Irving", 
    	"age":32, "position": "Point Guard", 
    	"team": "Brooklyn Nets"
}
    
# Create your Player instances here!
# player_jason = ???
copy
Challenge 3: Make a list of Player instances from a list of dictionaries
Finally, given the example list of players at the top of this module (the one with many players) write a for loop that will populate an empty list with Player objects from the original list of dictionaries.

# ... (class definition and large list of players here)
new_team = []
# Write your for loop here to populate the new_team variable with Player objects.
    copy
NINJA BONUS: Add a get_team(cls, team_list) @class method
Add an @class method called get_team(cls, team_list) that, given a list of dictionaries populates and returns a new list of Player objects. Be sure to test your method!

Set up a new file and add the Player class with the given constructor

Challenge 1: Update the constructor to accept a dictionary (player) as an argument and set the attributes using the dictionary

Complete challenge 2: Create 3 instances of the Player class using the given dictionaries

Complete challenge 3: Populate a new list with Player instances from the list of players.

Ninja Bonus: Add an @class method called get_team(cls, team_list) that, given a list of dictionaries populates and returns a new list of Player objects.
