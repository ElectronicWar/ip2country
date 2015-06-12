# Installation #

### 1) Unzip the file: _ip2country.ver.1.06.zip_ ###
```xml


3 Files that are needed for the script to run:
--> ip2country.ver.1.06.mrc
--> ip2country.txt
--> ip2country.lookup.ini

* See note 7) below if a 4th file is needed (versions of mIRC < 7.01)
```
### 2) Where to Unzip the Files ###

```xml

Preferably unzip the files to the same folder that has MIRC.EXE
*UNLESS you are on VISTA or Windows7*
In VISTA or Windows7 unzip to the same folder as MIRC.INI_

You can open the folder that mIRC.ini is in by typing this line in your status window:

//run $+(",$nofile($mircini),")

When unzipping, a new subfolder folder will be created : _ip2country_
There will be 5 files in that _ip2country_ sub folder:

1: _readme_.txt
2: ip2country.lookup.ini
3: ip2country.txt
4: ip2country.ver.1.06.mrc
5: ip2c.bmp

If you are having trouble locating the folder where MIRC.EXE is located,
paste this line into your status window:

//run $+(",$nofile($mircexe),")

Then press the enter key, and the folder will open up.
```
### 3) Loading the Script ###
```xml

Please do ensure REMOTES are on.
You can check this by typing /remote
If remotes are off, type /remote on

a) To Load the script, type this in mIRC (the Status Window is fine):

//load -rs1 $+(",$nofile($mircexe),ip2country\ip2country.ver.1.06.mrc,")

For VISTA & Windows7
If in step 2) above you unzipped to the same location where MIRC.INI is located,
then type:

//load -rs1 $+(",$nofile($mircini),ip2country\ip2country.ver.1.06.mrc,")

b) Click YES to allowing the Initialization Commands.
c) _IMPORTANT NOTE_: If you do not click "YES" the script will run but in a terribly limited fashion.
d) If Remotes are off, you will not see the Initialization Commands request box.
```
### 4) Script & Filenames ###
```xml

Script - FILE NAME: ip2country.ver.1.06.mrc
Main DATABASE - FILE NAME: ip2country.txt
Secondary DATABASE - FILE NAME: ip2country.lookup.ini
```
### 5) Setup Options ###
```xml

Please check the DEFAULT RECOMMENDED settings by
right clicking in the Status Window, or a Channel, or a Message Window - and choose:

ip2c >> Settings & Options

BE AWARE THAT - not everything is turned on.
It is meant to be this way.
Only recommended functions are enabled
Feel free to explore all the options available.
```
### 6) IAL _(mIRC's Internal Address List)_ ###
```xml

If your IAL is off ( check by typing /IAL ) some features won't work.
What won't work is:
a) seeing all the country information of a channel
b) right clicking a nick in a channel and seeing their country
```

7) Note:-
```xml

The file ip2c.bmp is a small icon file for preloading in the Options & Settings dialog.
It is included as versions of mIRC 6.35 and lower have a small bug.
This bug is overcome by already having the icon in place rather than it being auto made by the script.
```