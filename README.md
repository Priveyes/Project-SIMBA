# Project-SIMBA
A Crypto currency AI trading bot and Arbitrage

PROJECT SIMBA 
founding architect: Matthew Bennett | mbennett24@student.gsu.edu
co founder: Addison Amiri
contributors: Shayan Khan 

______________

OVERVIEW Entry Date 2-24-2014 
-----------------------------
The overall intent of this project is to have a library of JAVA methods that can be used to assemble a automated trading bot. SIMBA currently only supports BTC-e trading exchange, However more exchanges might be added in the future but consistency will continue to be the main focus.

CURRENT STATUS
--------------
There are currently two main parts of SIMBA Library, a set of classes and methods for a Arbitrage between currency pairs. 
  
  *The Arbitrage 
    the program was first built in one class with the ability to check for exploits surrounding a single crypto currency tested and tweaked until successful profitable trading sequences where made semi consistently. Then the methods where separated into classes where multiple crypto currencies pairs could be checked for exploits at once, Due to multi threading and static variables the multi threaded version of the arbitrage functionality is much less consistent. 

  *The AI 

    the program is built in a single class file with the intent to get a semi consistent output before separating methods into class files. After multiple builds and tweaking a consistent profitable output as not be tuned yet, however the data pulling methods work consistently. PROJECT FILE NAME "simba1.5.java

  *The API 
    SIMBA is built on top of the API built by Brain Waters, located here 
    https://github.com/abwaters/btce-api

EXAMPLES OF EXPLOITS 
--------------------
These are the examples of exploits i have found this far however I am sure more exist!
https://github.com/matthewbennett/Project-SIMBA/blob/master/example.png

CONTRIBUTERS GUIDE
------------------


_______________________________________________________________________________
Project SIMBA, a crypto currency AI trading bot 
Copyright (C) 2014  Matthew Bennett 

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program; if not, write to the Free Software
Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301, USA.



