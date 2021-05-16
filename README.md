Join our community Discord https://discord.gg/GNg3JUX
Find our website https://twohoursonelife.com
# OneLife

This is a modified version of OneLife https://github.com/jasonrohrer/OneLife<br>
Check out this forum thread to see what the mod can do and how to use it: https://onehouronelife.com/forums/viewtopic.php?pid=53465#p53465
<br>

<b>Table of Contents</b><br>
[- Installation](#heading-installation)<br>
[- Changes](#heading-changes)<br>
[- Compiling](#heading-compiling)<br>
[- Other Mods](#heading-other-mods)<br>

<h2 id="heading-installation">Installation:</h2>
you can download the executable here: https://github.com/hetuw/OneLife/releases<br>
for windows this would be "OneLifeApp_H_windows.exe"<br>
place this file inside your ohol folder and then start it.

<h2 id="heading-changes">Changes:</h2>
<h4>Help page</h2>
press H in game to show all the hotkeys and commands

#### Zoom
press -> (right-arrow-key) to zoom out <br>
press <- (left-arrow-key) to zoom in

#### Age
current age will be displayed on the bottom panel

#### Coordinates
coordinates will be displayed in the top left corner, they are relative to your birth location

#### Food-Value indicator
when you are holding a food item in your hand, it will show you how much food you will gain by eating it

#### Show player names
all player names will be written above the players, the color depends on your relationship with that person.<br>
your mother is green, your cousins are blue or purple, unrelated people are white.<br>
you can show only first names / full names or no names at all, press N to change it.

#### Death messages
if someone in your area dies you wll see a death message on your screen.<br>
telling you the name of the person that died, their age and gender.

#### Players in range panel
in the top right corner you can see how many people are in your range<br>
and how many of them are females under the age of 40.

#### Emotions
you can press 0-9 to make emotions<br>
you can also write an emotion in chat, than it will last permantly, you can stop it by pressing 0-9

### Keyboard Control

#### E
press E to eat what you are holding in hand

#### Q
press Q to put something in your backpack or take something out

#### SHIFT+Q
switch the item in your hand with an item inside your backpack

#### C
press C to pick up or drop a baby

#### WASD
you can use wasd to go up/left/down/right<br>
this makes it easier to avoid dangerous animals and it will open doors automatically 

#### SHIFT+WASD 
similar to left click, will pick up an item in the choosen direction

#### CTRL+WASD
similar to right click, for example: CTRL+W can be used to pick up an item from a basket that is 1 tile above you

#### SPACE
similar to left click, can be used to pick up items from the tile you are standing on

#### CTRL+SPACE
similar to right click on the tile you are standing on

#### F
press F to stop the camera from moving, with the default client you have to keep holding SPACE to achieve this effect

<h2 id="heading-compiling">Compiling:</h2>
The following instructions are for compiling this mod with linux.<br>
<br>
You will need to install the following:
<blockquote>
sudo apt-get install git g++ make imagemagick xclip libsdl1.2-dev libglu1-mesa-dev libgl1-mesa-dev
</blockquote>
Then download this script: <a href="https://raw.githubusercontent.com/hetuw/OneLife/master/scripts/hetuwScripts/hetuwPullLatest.sh">hetuwPullLatest.sh</a><br>
Put it inside an empty folder and open a terminal inside this folder.<br><br>
First set the executeable bit by writing:<br>
<blockquote>
chmod +x hetuwPullLatest.sh
</blockquote>
Then execute the script in order to download the latest version:<br>
<blockquote>
./hetuwPullLatest.sh linux 1
</blockquote>
You can also download it for windows, like this:<br>
<blockquote>
./hetuwPullLatest.sh windows 3
</blockquote>
In order to compile you can type:
<blockquote>
./hetuwCompileAll.sh
</blockquote>
To start it type:
<blockquote>
cd linux<br>
./OneLifeApp
</blockquote>
<br>
<b>more information about how to compile ohol:</b><br>
http://onehouronelife.com/compileNotes.php?nocounter=1<br>
https://onehouronelife.com/forums/viewtopic.php?id=1438<br>
https://onehouronelife.com/forums/viewtopic.php?id=423<br>
<br><br><a id="heading-other-mods"><b>other mods:</b></a><br>
https://github.com/Awbz/OneLife<br>
https://github.com/JustinLove/onelife-client-patches<br>
https://gitlab.com/_zed_/OneLife/<br>
https://github.com/PXshadow/OpenLife<br>
