Brief Description of what's going on in the game.

Game has two main agents:
Farmer and Baker
Farmer harvest wheat and deliver 1 set of wheat to windmill.

Baker bakes bread and needs 2 units of flour to make bread. 
Baker then delviers 5 set of bread to market place. 
He waits for farmer to stock 5 units of wheat.
Then he collects those 5 units of wheat and bring it to bakery where he bakes bread untill he has 5 stocks of bread.
Then he delivers thos bread to market.

Windmill and Bakers production and stock is visible on inventories of left top of the game.


-------------------------------------------------------------------------------------------------------------------------
GOAP - As I discussed in my presentation, I have used GOAP to create the above AI. It was good amount of learning. GOAP doesn't work on FSM but creates on GOAP queue based on priority and cost.

In AI Folder, there are two folder FSM, GOAP
In FSM Folder there is 
In GOAP folder there are 4 classes.
GoapAction, GoapAgent, GoapPlanner, IGoap.