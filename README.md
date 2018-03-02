
I am [Josep Pi](<https://www.linkedin.com/in/josep-serra-409431146>), student of the [Bachelor’s Degree in Video Games by UPC at CITM](<https://www.citm.upc.edu/ing/estudis/graus-videojocs/>). This content is generated for the second year’s subject Project 2, under supervision of lecturer [Ricard Pillosu](<https://es.linkedin.com/in/ricardpillosu>).

# Economy in Videogames
## How could we define Economy in a game?
Economy is a game mechanic that can create a strong joint between all the other mechanics that the game has to offer giving you a strong sense of progress in lots of differents aspects and feeling of acomplishment. It also does motivate you to keep improving and it's a really powerful mechanic that lets you have a set of tools that will improve the player's experience.

## Sense of progress
So, the main concern is, how can we archive that sense of progress in which the player will be hooked to our game for a while. First, we need to separate both RTS and RPG games, since their need different kinds of economies. 

### RPG
The economic progress is one of the strongest bases of the RPGs in general. Some of them even go one step further and make the entire game revolve in their economy mechanic such as EVE or Tibia.
We can use maths in order to create an interesting curve and to have a reference when we want to create that progression. 
I've created a very simple tool in which you can get some reference in order to create an interestinc economic curve for the user.
You can find this tool here: [Click me](https://docs.google.com/spreadsheets/d/10UDd0ExogH29ZdufqrceJjp1WT0-Bghc0ELqBsWkkNU/edit#gid=0)

Note the curve you want to create should be aiming for earning low money at the begining and a lot at the end of the game so it keeps.

You can always spice things up a bit by letting the player from time to time earn some valuables items in which will boos his economyc income and make them feel they've earned a lot. If you can give it as a reward for something really hard to acomplish or taking high risk (or even better, making them feel they are taking a high risk) the more difference is the ammount they win by who much they've got, the better they will feel. But this will cause some trouble.

### RTS
The players profiles that usually are atracted to this games are the killers, the archiever and some explorers. The economic mechanics will display different features in order to keep them happy. 

Here the progression instead of begin based how weak you are at the begining and how strong you are at the end (which is a strong point, but no the main concern), the real deal is how much stronger you are based on the enemies you're facing. Begin able to actively doing something to make you as strong as possible in the less ammount of time (archievers) and while doing so, begin able to make your enemies weaker by attacking the enemy bases and choosing the right units(killers) while you choose the optimal strategy against the enemy units that you previously have begin researched by the others(explorers) is what the economy is all about.

#### Types of Economic Mechanics based on the players profiles.
* **The killers** want to be able to destroy eficiently their enemy bases. If they can acomplish that, one good way to reward them economically is to let them use or get their resources in order to establish dominance during the fight against the others. The fun relies in how much can they get stronger than their enemies during the fight.

* **The Archievers** want to grow as fast as possible to keep improving their skills. The optimal way to make them feel they have full control of their empire with the tools you give them. Let them know that economically wise, they are making the good decisions by showing them they are progresing as fast as possible by having just enough resources to keep progressing all the time and have everything calculated.

* **The Explorers** are not as common in this kind of games, but it's worth mentioning them because they make the experience for the others more enjoyable. Having a really deep economy with lots of different choices they can take are the only way to make them happy. Decisions that will matter during the fight and complex relationships between the units and the economic buildings.

## So, we give them money, now what?
Of course, why would you like to have money if you can't spend it? Finding ways to make those players use that money is as important as how much they earn during the game. The things they can spend the money on should be more than the ammount they earn. That way, they will always want more money in order to get what they are aiming for. Those reasons needs to have a big impact in their economic or military power making them a resonable choice when improving your characters/empire. They also need to be equally important having a realtionship between the the damage you can make/the money you can earn while doing the investmen.

## But, what price should we put in those upgrade which seem fair?
Lots of different studies have been done in this aspect and still, we can't find a method in which we can follow in order to have a balanced progression economy. What we can do is, again, use maths in order to make decisions about this subject. Items price should have a relation with its stats. A good start point for swords would be something like this:

Price = Damage done + Damage prevented + Damage Healed.

Now, we have 5 variables there if we also take in to account the time you use for that object. Lets go one by one and see how much they can change based on other variables (yay more variables!)

Damage Done = enemy type + number of enemies + player skill + stats of the item + time.
Damage Prevented = enemy type + number of enemies + player skill + stats of the item + time.
Damage Healed = player skill + stats of the item + time.

See where I'm going? We can make a scene with the same enemy type, number of enemies, player and stats. Record the those variables during the same period of time and make an estimate. Note that this is not a perfect method, but it's the closes you can get in order to balance things based on price.

In order to put a price to the special caracteristic of an item we would use the same method, for example. Armor: each time an enemy attacks you with this armor on, a 25% of the enemy damage will return to them. This will be added to the total damage the item will do during the fight and will be taken in to account when puting a price tag to the item.

