CONTENTS OF THIS FILE
---------------------

 * Introduction
 * Requirements
 * Recommended modules
 * Installation
 * Configuration


INTRODUCTION
------------
The idea is a simple version of the World Clock that most mobile devices have an app for these days.

To keep it simple, The following cities and UTC offsets are hardcode.

Los Angeles / -7h
New York / -4h
London / 1h
Paris / 2h
Dubai / 4h
New Delhi / 5.5h
Beijing / 8h
Tokyo / 9h
Brisbane / 10h
Auckland / 12h
Source: https://www.timeanddate.com/

The main features of the project are:

1. The app will work the same in any timezone (based on the current computer's system settings) without needing to 
   manually configure anything.

2. The city background/foreground colours will change to indicate whether it is presently night or day in that city.
   For the purposes of this project I assume that is it daytime if it is between 6:00am and 6:00pm inclusive.

3. The offset of the local timezone from UTC is showing.

4. The offset of each city from the *current* timezone is showing with each city.
   For instance:
   The UTC time for Auckland/ New Zealand is +12h
   The UTC time for Brisbane (Queensland)/ Australia is +10h
   Source: https://www.timeanddate.com/
   
   If you run app in Auckland/ New Zealand then the UTC time in the list for 
   Brisbane (Queensland)/ Australia is -2h
   Auckland/ New Zealand is 0h
   Source: https://www.worldtimebuddy.com/

5. Date formats is using the current computer's system settings.


REQUIREMENTS
------------
This project implemented by pure 4D (v15.6).

RECOMMENDED MODULES
-------------------
This project requires no plugin outside of 4D core.

INSTALLATION
------------
Install as you would normally install 4D and then open the project.
For downloading 4D, please see https://download.4d.com/Products/Archives/

CONFIGURATION
-------------
The project has no modifiable settings. There is no configuration.