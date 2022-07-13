# Collectible Colors Client Version 1
Allows people to manage their Collectible Colors.

## Functions:
* Import Colors
* View Colors
* Create Color Collections
* Export Color Collections
* Export Color based on its Serial Number
* Health Check with Fix Fracked and Limbo
* Direct Send (Send Colors to another person directly)

## GUI of Client


### Dashboard Mode
* There is a list of all the current collections probably in a left payne. 
* The default collection called "Color Stockpile" is viewed upon start up. People can see their colors. Only a 20 by 20 grid is show. If the user wants to see more they must use the page forward or page backword button to see the next 24x24 grid.
* There is a button called "Import Colors". When clicked the Import context is shown. Colors are imported one at a time. (See Import image below)
* There is a button called "Import Collection". When clicked the Import context is shown. Colors are imported one at a time. (See Import image below)
* There is a button on the left payne that allows people to create a new collection.
* When the "New Collection" is pressed, the user is asked what they want to name the collection and are given a choice between 24x24, 16x16, 10x10, 8x8 or 6x6

### Collection Mode
* When in "Collection mode" the collection will be shown on the left (A grid that has the same dimentions as the user's specifications) and on the right will be the "Color Stockpile". Users can drag colors from the color stockpile to the collection and place them in a pixel. Every pixel must be a unique color. The stockpile will have pages to page through lots of colors.
* Collection mode includes a button to "Export Collection"
* Collection mode includes a button called "Health Check". When clicked the progam fixes one at a time. (See Health check image below)
* Collection mode includes a button called "Direct Send" which takes the person to the "Direct Send" screen.
* When a user clicks on a color in the "Stockpile" or in a collection, the color will pop up with details (Name, #FF8800 Hex code and decimal number)
* Each collection h

### Direct Send Mode
Form asks people for the server IP, shared secret. The program then tries to connect to the other person. When connected, the collection is sent. 




