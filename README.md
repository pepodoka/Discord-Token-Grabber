# Discord-Token-Grabber
Sends embed to discord webhook containing Discord token, PC Name, Username, Local ip and public ip.


# How to use?
Clone this repo and inside PrintAllInfo.cs you should see a url string, publish as onefile and you are good to go.

# Bypassing?
Ran program in virustotal, bypassed every single antivirus "No security vendors and no sandboxes flagged this file as malicious
" Windows defender warning will popup while trying to run, but thats about it.

# Flexibility?
Tested only on windows.

# About
Not tested very well, spent like two days filtering possible tokens.

# Want a smaller file?
(Visual Studio Only)
Right click the .csproj file, click publish, click folder, click next, click folder, then next, specify your path where you the file, click finish. Then you should see some light blue text saying "Show all settings" click it, in Deployment mode, select Self contained, and in target runtime select whatever bit you're targeting, then click on File publish options and select Produce single file, Enable Ready To Run Compilation and trim unused code. When published this should decrease the size drastically (75%). 👍



Skidded some code from another outdated token grabber that throws errors.
