Class - OOP
Game - Procedural

- UML standards
- HSC terminology ( no generalising )
- technical terms ( technical language on the HSC - Syllabus, course specs )
- optimal stage 

- structure chart represents game mechanics
- card design ( image, text, variables, datatypes ) = wireframe
- interface sketch ( wireframe ) = think about screen size, standardized methods, etc.
- graphing in line 
- documentation


# Assessment Task 2 - Object-Orineted Design Project - Car Comparison Game
Yuna Shin

## Plan
| Step | Why | Expected Result | Time |  
| --- | --- | --- | --- |
| 1. Part D | I will do this first in order to make sure that I know what attributes and classes I will need to create. | The design of my game, something to fix in the future and its appropriate structure chart. | 1 hour |
| 2. Part A | As soon as I have a an idea for my game, I will create my attrubutes and rank them. | My 6 attributes ranked with an explanation for each. | 2 hours |
| 3. Part B | I will design the classes so that I will be able to move onto the next step which will be rearranging them into a UML class diagram. | All my classes listed with their respective attributes, methods and its role in the system. | 2 hours |
| 4. Part C | After all my classes are finished, I will be able to create a UML class diagrams including all the relationships. | A finished UML class diagram. | 1 hour |
| 5. Part E | Now that the classes and their information is all finished and I have the my game set out, I will be able to design the card and the basic interface of my game. | Finished card and interface design with labels and annotations explaining my design choices, clear layout of my information and storyboards or a walk through. | 2 hours |
| 6. Part F | After everything is done, I will be able to write out my social, ethical and legal implications without a problem. | Answered all the questiona of the social, ethical and legal implications. | 3 hours |
| 7. Overall Review | After everything is done, I will need to make sure that my attributes, classes and the interface and card design all match my game. If they don't, I'll will slightly alter my game so that it will be able to match. | ASSESMENT TASK FINISHED !!| 1 hour |

## Part A - Data Selection and Game Attributes
Using car listings a inspiration:
- Select 6 attributes for your game (e.g. price, km, power)
- Rank them from most powerful to least powerful in the game mechanics
- Explain:
    - Why each attirbute was chosen
    - What makes an attribute fair or unfair in gameplay

6 attributes 
- price (19190 ~ 32000000)
- horsepower (1 ~ 15000)
- cool power (1500 ~ 15000)
- curb wight (59 ~ 4500)
- top speed (28 ~ 310)
- acceleration (0.4 ~ 30)

they would be fair as cars with low horsepower would take longer to accekerate but as the higher the number you win, having a card with a car with bad horsepower, prce, etc also has a chance of winning

rankl them based on thier range. so like acceleratuibn nmight differ grwatly between cars so that would be ranked first while cool power differ less so it will be ranked last


### 1. Acceleration
Acceleration is the most powerful attribute in the game because its range of 0.4 ~ 30 seconds is extremely wide and evenly distributed across many types of cars. This means the difference between the fastest and slowest cards is dramatic, making acceleration a highly decisive attribute when chosen. At first, acceleration might seem unfair since in real life, better cards accelerate faster, meaning a supercar with a 0.4 second time looks unbeatable. However, in the rules, the attribute with the highest number wins, which completely flips the logic. A car with a low price, low horsepower or generally a weak stats will usually has a slow acceleration time, and that slow time gives a higher number, meaning it can actually beat a supercar whose acceleration number is much lower. This makes acceleration both powerful and fair, because even the 'bad' cards have a real chance of winning against the strongest cards. The attribute stays impactful because the range is so large but it remains balanced because weaker card can outperform supercars under the scoring system of my game. 

### 2. Price

### 3. Horsepower

### 4. Cool Power

### 5. Curb Weight

### 6. Top Speed

## Part B - Class Design
Design the object-oriented structure of your game.
Required classes :
- Car
- Card
- Deck
- Player
- Game

For each class :
- List attributes
- List methods
- Describe its role in the system




## Part C - Class Diagram
Create a UML class diagram including :
- All classes
- Attributes and methods
- Relationships (association, aggregation, inheritance if used)

Must include :
- Clear structure
- Correct relationships
- At leat 2 annotated design decisions

## Part D - Game Mechanics Design
### How the game works :
1. All players (recommended 2~4) receive an equal pile of cards
2. The player to the left of the dealer goes first
3. Everyone flips over the top card of their pile
4. The starting player chooses the biggest attribute on their card and calls it out
5. All players read out their number for that same attribute
6. The player with the highest attribute value wins the round
7. They collect all the cards played in that round but must choose on of the two actions :
    - Add the cards to the middle pile 
    - Give the cards to the lowest scoring player
8. Then the next player on the left side of the previous starting player calls out their highest attribute
9. Again, the player with the highest attribute value wins that round
10. They collect all the cards played in that round and have a similar two options like the player before :
    - Add the cards to the middle pile
    - Give the cards, including the pile in the middle, to the lowest scoring player
11. The first person to lose all their cards wins

In the case of a draw :
A draw can occur in two cases. Either two players tie for the highest attribute or tie for the lowest attribute. In these cases, all the cards played in that round automatically go into the middle pile. 

Middle Pile (easier to understand) :
If the winner of that round chooses to add cards to the middle, the pile stays untouched until the next round's winner decides. They can either add the new round's cards to the pile again or give the entire pile including the round's cards to the lowest-scoring player. 

### Game Balance
There are many aspects in which my game is balanced including :
- Equal starting conditions (everyone beings with the same number of cards)
- Equal opportunity (everyone gets turns choosing an attribute)
- Unpredicatbility (the middle pile can go to anyone at anytime)
- Emotional tension (players feel excitement and fear as the pile grows)
- Late-game swings (even players close to winning can suddenly receive the pile)

### An Unfair Advantage + Solution
Players can intentionally target a player by continuously stakcing the cards in the middle pile, waiting until the end of the game the dumping the entire pile onto one chosen player. 

This could be fixed with a shield card that can prevent a player from receving the pile. A player may activate a shield when they are about to receive the pile but it comes with a cost. This might be :
- Taking one extra card from every player
- Losing the ability to add to the pile for the next two rounds

### Structure Chart


## Part E - Interface and Car Design ( storyboards )
Create :
- A card design (Top Trumps style)
- Basic game interface sketch

Must include :
- Labels and annotations explaining design choices
- Clear layout of information
- Storyboards and/or walk through

## Part F - Social, Ethical and Legal Implications
### Individual Impact
- How could you game influence user behaviour or decision-making?
- Could it encourage bias (e.g. favouring expensive or high-performance cars)?
- What respomsibilites do you have as a designer to present fairinformation?

### Social Impact
- How might your game reinforce stereotypes or inequalities (e.g. wealth, status, access to vehicles)?
- Does our system gavour certain types of users or cars?
- How could your design be made more inclusive or fair?

### Environmental Impact
- How could your game influence attitudes toward fuel use, emissions or sustainability?
- Does your attribute selection promote or ignore environmental considerations?
- What changes could you make to encourage more environmentally responsible thinking?

### Legal Considerations
- What legal issues could arise from using real-world car data (e.g. ownership, copyright, accuracy)?
- How would you ensure your system avoids misleading users?


questions i need to ask:
- what do tyou mean by a storyboard or a walk thorugh and how is that different from just explaining the game mechanics
- check my strucute chart
- check my uml class diagram