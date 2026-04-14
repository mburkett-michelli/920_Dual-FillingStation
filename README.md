# 920_Dual-FillingStation
2 versions
Customer wants to run either automatically or manually.
User can select the mode using a Hand - Off - Auto switch

When in Automatic
Before starting the user can select:
Starting Bin
Product Weight / Targets
Can press 'Start' to start the process

Once started the user can Stop the process
Once stopped the user can Resume the process or Reset it.

When system switches bins:
--------------------------
Disengage current belt direction
wait for 1 second (user selectable)
Enage next belt direction

Future Development:
-------------------
Each product will have a db entry that contains:
Product Name
Target Weight
Pre-Act Weight - Weight at which scale stops filling the tote

Will use the Fort Boise Onion Bagging system as a base for this program

