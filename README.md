## Q and A

# How do I get this? (windows)

- download git from here / ensure you have git already installed: https://git-scm.com/download/win 
- open command prompt where you want the server folder to be installed. Paste this in and press enter: git clone https://github.com/BradleyHarper/minecraft-1.17.1.git
- click the start.bat after port forwarding and changing the IP in server.properties and wala, you have a working minecraft server.
- Linux users already have git. Just paste the "git clone blablah" from above. (I don't have a start script for linux yet)

# After running the start.bat script (either clicking on it or typing in "start start.bat" in the terminal). A message shows up stating that 'java' is not defined

- Download the Java JDK from here https://www.oracle.com/java/technologies/downloads/#jdk17-windows


# Change the allocated ram?

- open start.bat and change the 'xmx' and 'xms' values. Examples (xmx1024m is 1GB of memory allocated to the server. You want 8 gigs? 8 * 1024 = 8,192. Replace the number value in the xms and xmx string accordingly.


# How do I update the server?

- inside the minecraft-1.17.1 folder type this into your terminal "git pull origin master in your terminal"


# One of my friends wants to host the server instead

- Add the new progress from the world by typing in "git add ." followed by git commit -m "new progress". Finally, "git push origin master"


# aint nobody gonna read this so just send me a message if you need help

-thanks

# - Bradley
