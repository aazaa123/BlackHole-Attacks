### BlackHole-Attacks ###
View of how black hole attacks affect nodes in an adhoc network.

When the program is open there will be information on both sides of a black square intially.
On the left side is all the parameters being used to both be able to see a blackhole attack and see how data is being sent throgh
the adhoc network. The right side is used to setup the nodes so they are able to communicate with each other. The goal is to
allow the nodes to be able to communicate to a central node that is situated in the middle of the screen.

Parameters:
Num-Nodes declares how many nodes will be seen on the stage.
Comm-Range declares the max range a node can communicate.
BlackNodes declares whether there will be corrupt nodes or not.
BlackNodeDensity tell what percentage of nodes within the network will be corrupted if BlackNodes is turned on.
BlackNodeAttack will determine if the blacknodes are passive or aggressive. Whether they will let data through or drop it.

To setup the program after parameters have been set:#
Press Setup
Press SelectNodes
Press either Flooding multiple times till all nodes are blue or Flooding with the two arrows to do it in an instant
Press SettingStage
Press SendPackets until communication has reached the centre or a blacknode has disrupted communication

