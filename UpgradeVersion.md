# Upgrading Only #

If you are upgrading - this is how you might do it.

1) Right click in a Status window and in the popup select:
> ip2c >> Utilities >> Unload script
2) Confirm that you want to unload the script by clicking: Yes

3) You should see something similar to the following 4 lines:
> ip2c: Thank you for having used ip2country.ver.1.05.mrc
> ip2c: To reload the script, paste in the following line:
> /load -rs1 "D:\mIRC\ip2country\ip2country.ver.1.05.mrc"

> `*` Unloaded script 'D:\mWin\ip2country\ip2country.ver.1.05.mrc'
4) Unzip the downloaded file ( ip2country.ver.1.06.zip ) to the same directory you see in those lines, in the case shown above it is:
> D:\mIRC\ip2country\ - Let it OVERWRITE any files already there.

5) Load the new script by changing the (in this case) 1.05 to 1.06 - so from the above example:
> /load -rs1 "D:\mIRC\ip2country\ip2country.ver.1.06.mrc"
> (Remember to use YOUR folder path - the above is an example)
6) Update the new 2nd Level Domains: Rebuilding is done by right clicking and in the menu popup:
> ip2c >> Settings & Options >> Update Domains >> Rebuild Domains Button

> _(2nd level Domains have to be manually updated this way because of the facility of your being able to add your own known 2nd Level Domains (that are stored in the file: ip2country.lookup.personal.ini). Click the help button on that tab for more info on completing this update.)_


