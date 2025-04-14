# getSMBLink
A shell script for an Automator Quick Action to create a link for a file on a file server.  
The automator file needs to be added to ~/Library/Services/.  
Then you can right click a file or folder on a file share and in the menu, select Quick Actions -> Get smb link.  
The action will run and put a link on your clipboard in the form smb://server/share/rest/of/the/path

Or to create your own, open Automator, select Quick Action, and then drag a Shell Script action into the workflow.  
The text of the script is in Quick Action Content.txt.
Also be sure to change the header to recieve files or folders in Finder.  
![A screen shot of the configured Automator window](./"Automator Screenshot.png")
