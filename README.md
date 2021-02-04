# TF2-Tower-Defense
TF2 Tower Defense


Basic off - https://github.com/tf2td/towerdefense
===========================================================================================================
TF2 Tower Defense is a modification to Valve's game Team Fortress 2. Basically you have to stop enemies from crossing a map by buying towers and building up defenses.

Authors
TF2 Tower Defense was originally created by floube and mani. It is currently maintained by Hurp Durp.

Plugin - floube, Benedevil, Hurp Durp

Maps - mani, fatboy, Berry

Requirements
Dedicated Team Fortress 2 server (windows or linux)
MySQL/MariaDB server
Metamod + Sourcemod
Socket
TF2Items
Steamtools
TF2Attributes
Installation
Create a dedicated TF2 server and install metamod + sourcemod, and the extensions and plugins above. Ensure that the server and plugins work before continuing.

Download the latest release of TF2TD.

On your MySQL/MariaDB server, create a new towerdefense database and user. Import the tf2td.sql file from the download into your database.

Add the database information to your sourcemod databases.cfg file (an example can be found [https://github.com/tf2td/towerdefense/blob/master/addons/sourcemod/configs/databases_example.cfg]).

Copy towerdefense.cfg to your server's tf/cfg folder. This file has settings that need to be executed when the server starts. Add the following to the end of your server's cfg/server.cfg file to do so:

exec towerdefense

Copy the tf2tdcustom/ folder and its contents into your server's tf/custom/ directory.

Copy towerdefense.smx to your sourcemod tf/addons/sourcemod/plugins folder.

Start your server with the map td_firstone_v11b. You should be able to connect and play if everything was set up correctly.
