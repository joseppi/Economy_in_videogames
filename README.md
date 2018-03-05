
I am [Josep Pi](<https://www.linkedin.com/in/josep-serra-409431146>), student of the [Bachelor’s Degree in Video Games by UPC at CITM](<https://www.citm.upc.edu/ing/estudis/graus-videojocs/>). This content is generated for the second year’s subject Project 2, under supervision of lecturer [Ricard Pillosu](<https://es.linkedin.com/in/ricardpillosu>).

# Economy in Videogames
## How could we define Economy in a game?
Economy is a game mechanic that can create a strong joint between all the other mechanics that the game has to offer giving you a strong sense of progress in lots of differents aspects and feeling of acomplishment. It also does motivate you to keep improving and it's a really powerful mechanic that lets you have a set of tools that will improve the player's experience.

## Sense of progress
So, the main concern is, how can we archive that sense of progress in which the player will be hooked to our game for a while. First, we need to separate both RTS and RPG games, since their need different kinds of economies.

![image_progress](https://github.com/joseppi/Economy_in_videogames/blob/master/Wiki%20Economy%20Images/Example%20of%20progress%20graph.PNG?raw=true)

*Graph created using a polynomical function with the help of Marc Garcia and Lluis Uescas*

### RPG
The economic progress is one of the strongest bases of the RPGs in general. Some of them even go one step further and make the entire game revolve in their economy mechanic such as EVE or Tibia.
We can use maths in order to create an interesting curve and to have a reference when we want to create that progression. 
With the help of Marc Garcia and Lluis Uescas we've created a tool in which you can get some reference in order to create an interesting economic curve for the user.

Note the curve you want to create should be aiming for earning low money at the begining and a lot at the end of the game so it keeps the interest of the player in the process.

You can always spice things up a bit by letting the player from time to time earn some valuables items in which will boost his economic income and make them feel they've earned a lot. If you can give it as a reward for something really hard to acomplish or taking high risk (or even better, making them feel they are taking a high risk) the more difference is between the ammount they win and how much they've got, the better they will feel. But this will cause some trouble that we will explain later on.

### RTS
The players profiles that usually are atracted to this games are the killers, the archiever and some explorers. The economic mechanics will display different features in order to keep them happy. 

Here the progression instead of begin based how weak you are at the begining and how strong you are at the end (which is a strong point, but no the main concern), the real deal is how much stronger you are based on the enemies you're facing. Begin able to actively doing something to make you as strong as possible in the less ammount of time (archievers) and while doing so, begin able to make your enemies weaker by attacking the enemy bases and choosing the right units(killers) while you choose the optimal strategy against the enemy units that you previously have begin researched by the others(explorers) is what the economy is all about.

#### Types of Economic Mechanics based on the players profiles.
* **The killers** want to be able to destroy eficiently their enemy bases. If they can acomplish that, one good way to reward them economically is to let them use or get their resources in order to establish dominance during the fight against the others. The fun relies in how much can they get stronger than their enemies during the fight.

* **The Archievers** want to grow as fast as possible to keep improving their skills. The optimal way to make them feel they have full control of their empire with the tools you give them. Let them know that economically wise, they are making the good decisions by showing them they are progresing as fast as possible by having just enough resources to keep progressing all the time and have everything calculated.

* **The Explorers** They make the experience for the others more enjoyable. Having a really deep economy with lots of different choices to be made are the only way to make them happy. Decisions that will matter during the fight and complex relationships between the units and the economic buildings with tons of posibilities.

## So, we give them money, now what?
Of course, why would you like to have money if you can't spend it? Finding ways to make those players use that money is as important as how much they earn during the game. The things they can spend the money on should be more than the ammount they earn. That way, they will always want more money in order to get what they are aiming for. Those reasons needs to have a big impact in their economic or military power making them a resonable choice when improving your characters/empire. They also need to be equally important having a realtionship between the the damage you can make/the money you can earn while doing the investmen.
![money_flow](https://github.com/joseppi/Economy_in_videogames/blob/master/Wiki%20Economy%20Images/Flow%20of%20money%20in%20an%20MMORPG.PNG?raw=true)

*Credits to Stephan Börzsönyi for his work in macroeconomics in virtual worlds. Link down below.*

Each week, 24.7 million gold is introduced to the game for 700 players. The avarage of money per player is 35714 gold. This will cause trouble.

## But giving that much money may cause some trouble...
Yes, it can cause inflation in the game. It means that the value of the currency used inside the game will be diminished between the players and the prices will keep growing up to the point is not worth anything and people will start using more valuable objects instead. Defeating all the purpose of the currency you've implemented.

The inflation of a game is the avarage of the money people has saved.

## But, what price should we put in those upgrade which seem fair?
Lots of different studies have been done in this aspect and still, we can't find a method in which we can follow in order to have a balanced progression economy. What we can do is, again, use maths in order to make decisions about this subject. Items price should have a relation with its stats. A good start point for swords would be something like this:

Price = Damage done + Damage prevented + Damage Healed.

Now, we have 5 variables there if we also take in to account the time you use for that object. Lets go one by one and see how much they can change based on other variables (yay more variables!)

Damage Done = enemy type + number of enemies + player skill + stats of the item + time.
Damage Prevented = enemy type + number of enemies + player skill + stats of the item + time.
Damage Healed = player skill + stats of the item + time.

![attack-defense-heling](https://github.com/joseppi/Economy_in_videogames/blob/master/Wiki%20Economy%20Images/Damage-Defense-Heal.PNG?raw=true)

*Credits to Matthew Steinke, responsable of the economy behind the game The Witcher 3.*

See where I'm going? We can make a scene with the same enemy type, number of enemies, player and stats. Record the those variables during the same period of time and make an estimate. Note that this is not a perfect method, but it's the closes you can get in order to balance things based on price.

In order to put a price to the special caracteristic of an item we would use the same method, for example. Armor: each time an enemy attacks you with this armor on, a 25% of the enemy damage will return to them. This will be added to the total damage the item will do during the fight and will be taken in to account when puting a price tag to the item.

## Why should I even bother? Is it really that worth the effort?
Remember that graph that you've seen like a thousen times already? The one that shows the pacing in a story? Well games are exactly the same. That curve means everything for the developers who are trying to make their players stick to their game for a while. The economy plays a big role in this chart along side with other mechanics. It also makes the experience more pleasant over all since they feel they've acomplish something when they finish the game, looking back and seen how they progress.

![pacing_curve](https://github.com/joseppi/Economy_in_videogames/blob/master/Wiki%20Economy%20Images/Pacing%20Curve.PNG?raw=true)

*Credits to Extra Credits for showing me this graph, althought the original creator is unknown*

## Tool
You can find the tool mentioned above here: [Click me](https://docs.google.com/spreadsheets/d/10UDd0ExogH29ZdufqrceJjp1WT0-Bghc0ELqBsWkkNU/edit?usp=sharing)


## Bibliography
Extra Credits How to Manage Inflation in Virtual Economies
https://www.youtube.com/watch?v=W39TtF14i8I&t=4s

Extra Credits MMO Economies - Hyperinflation, Reserve Currencies
https://www.youtube.com/watch?v=sumZLwFXJqE

Extra Credits Balancing MMO Ecosystem
https://www.youtube.com/watch?v=1drDuaQXm_U

GDC inside The Witcher 3’s Crafting-Based Economy
https://www.youtube.com/watch?v=SdYSRkXqhyk&t=5s

Gamers Toolkit - What Capcom Didn't Tell You About Resident Evil 4
https://www.youtube.com/watch?v=zFv6KAdQ5SE

Pacing - Extra Credits
https://www.youtube.com/watch?v=5LScL4CWe5E

Insight into the in-game economy of Tibia: Macroeconomics of a Virtual World (Master's Thesis by CipSoft founder, Stephan Börzsönyi)
https://www.scribd.com/document/370272928/Macroeconomics-English?secret_password=FwKM9SIzD6aBHGzdJdKE

Game Mechanics, Incentives & Recognition by Dr. Michael Wu, PHD
http://theirf.org/research/game-mechanics-incentives-recognition/130/
