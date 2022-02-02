# Football-Analysis-3
Football Analysis using NetworkX


Let's consider the formation and relative disposition of the Genoa team on the pitch:

(1,{"nome": "Perin"}), (55,{"nome": "Masiello"}),(21,{"nome": "Radovanovic"}),(4,{"nome": "Criscito"}),
(99,{"nome": "Czyborra"}),(20,{"nome": " Strootman"}),(47,{"nome": " Badelj"}),(16,{"nome": "Zajic"}),
(77,{"nome": "Zappacosta"}),(9,{"nome": "Scamacca"}),(23,{"nome": "Destro"})

Let's consider the following statistics on passing the ball between team players:
(1,55,21.0),(55,1,34.0),(1,21,54.0),(21,1,43.0),(1,4,23.0),(4,1,12.0),(4,55,56.0),(55,4,23.0),(21,55,10.0),
(55,21,34.0),(21,4,34.0),(4,21,44.0),(1,99,21.0),(99,1,5.0),(99,55,3.0),(55,99,6.0),(99,21,47.0),
(99,21,47.0),(20,21,15.0),(20,47,80.0),(20,99,16.0),(20,77,35.0),(16,21,5.0),(16,20,34.0),(16,47,45.0),
(16,77,22.0),(16,4,15.0),(16,9,15.0),(16,23,25.0),(16,21,12.0),(77,21,10.0),(77,47,35.0),(77,9,28.0),
(77,23,25.0),(77,16,25.0),(77,20,32.0),(23,9,15.0),(9,23,12.0),(23,77,12.0),(9,77,11.0),(9,16,15.0),
(23,16,21.0),(23,20,2.0),(23,21,4.0),(23,47,15.0),(23,99,11.0),(1,23,25.0),(1,9,14.0),(21,9,8.0),
(21,23,15.0),(4,9,5.0),(4,23,4.0),(47,9,15.0),(47,23,15.0)

For example (1,4,23.0) indicates that Perin has passed the ball 23 times to Criscito.

I uesed NetworkX to create a direct graph where the nodes are the 11 players of the base formation, and the weighted arcs represent the number of passes between each two players.

In this project I answered the following questions:

    - Find out the total number of passes efected and recieved by each player
    
    - Find the central players in the game
    
    - Find the players who facilitate the passage of the ball between players
    
    - Find the number of in & out passes
    
    - Find the players who passed the ball to more players in descending order
    
    - Find the players who received more passes from other players in descending order
