# Hero vs Dragon Game

![alt text](https://cinemasiren.com/wp-content/uploads/2014/06/Viking-vs-Dragon.jpg "Mighty Hero vs Evil Dragon")

## This is a game that you need to complete

Please describe the rules in this list:
######Rules of the game
The game consist on a fight between a dragon and a hero. 
1. They are given an amount of  points that in the code are defined with the input statements. dragon_hp, for the dragon and hero_hp, for the hero. The first one that have hp below 0 will lose.
2. With the function hero_max_dmg and dragon_max_dmg, we are defining the maximum damage that the hero and the dragon can make to each other. For example, if we type here 10, the dragon can only rest 10 points to the hero_hp.
3. In order to play, we should introduce numbers for the hp and damage for both dragon and hero, if we do not use an integer, the game won't work and it will tell us that something is done incorrectly (except ValueError), however, when correct integers are introduced,it will display the amount of hp that both hero and dragon have (finally function) 
4. The next step consists on creating a while True loop that will run until the game is ended.
5. The dragon starts attacking; random.randint will take a value lower than the one that we have set in dragon_max_dmg (maximum damage the dragon can make the hero)
6. After, the damage caused by the dragon will be subtracted from the total points the hero has at the beginning.
7. The same process is repeated with the hero. First the dragon attack, and then the hero.
8. The if statements indicate that when the hero or the dragon have less than 0 points, one will be death and the game will be finished (input("Round over. Press any key"))
