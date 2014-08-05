
 PENTETRATION TESTING FOR ANDROID                          
       2014 SimuDrone projects         
                                       
   P4A -v 1.0                          
   Benjamin Keil                       
   SimuDrone Projects                  
                                       

   
HELP MENU:
  
What this System needs!:
      
- Rooted Android Device

- Botbrew Anise
  https://play.google.com/store/apps
  /details?id=com.inportb.botbrew&hl
  =en

- python 2.7

- nmap

- tcpdump

- ncurses

- libpcap

- Terminal Emulator
  https://play.google.com/store/apps
  /details?
  id=jackpal.androidterm&hl=en

- Busybox
  https://play.google.com/store/apps/
  details?id=stericson.busybox

- theHarvester
  ( is in Program Folder )

- metaGoofil  
  ( is in Program Folder )

- Sqlmap      
  ( is in Program Folder )

- Ettercap 
  will need to be installed in system/bin
       
  

INSTALLATION GUIDE:
 
 HOW TO INSTALL ettercap:
 
- open ettercap folder
  mark all files contained
  in folder and copy them

- navigate to system/bin
  and paste the files into it

- open terminal emulator
  and navigate to system/bin
  cd /system/bin
- enter: su
- enter: chmod 777 ettercap
  If you get an error check 
  that you have root accsess 
  other wise make sure that your
  system is mounted as read write
  see google for more info.

BEFORE YOU CAN USE THIS SYSTEM:
   
1. Download and install 
   Botbrew Anise a packaget 
   manager freely available 
   on the Google Play Store
   follow the Installation guide
   and proceed.
   Don't worry if GUI fails
   everything will be done 
   from the console in terminal
    
2. Save  Pentest main folder in
   in root of sdcard
   
3. Open Terminal Emulator
   type: su 
   this will give the shell super
   user permissions!
   
   type: botbrew
   this starts botbrew
   
   type: opkg install nmap
   this will install nmap binaries
   to botbrews bin folder.
   
   type opkg install tcpdump
   this will install tcpdump
   to to botbrews bin folder.
	      
   type opkg install python 2.7
   this will install python 2.7
   on your Android device 
   needed for Python suite.
  
  SIDE NOTE:
   
     It also supports a 
     interactive shell which
     is pretty cool...
     You can start it 
     simply by typing python.

Usage:  
   
   Open Terminal Emulator and 
   type: su
   type: botbrew
   In order for p4a to work 
   properly you must start it
   from the Pentest folder
   saved in the root of sdcard.
   type: cd /sdcard/Pentest/
   type: sh StartMenu.sh
   
   At start up p4a will check that
   all dependancies are installed
   properly should one or two 
   be missing the system will Inform
   you which ones are missing!
   and display this help message.
   
   if you get a permission error
   when trying to run p4a        
   don't worry we'll will
   make executable
   type: chmod 777 p4a.sh
   try again : sh p4a.sh
   and voila..
   You are now greeted by a 
   comfortable GUI and all you
   need to do is follow the 
   Instructions on the Screen.

   To move DOWN on the
   the GUI-INTERFACE hold
   <volume> down and press P

   To move UP on the
   the GUI-INTERFACE hold
   <volume> down and press N

   To move RIGHT on the
   the GUI-INTERFACE hold
   <volume> down and press D 

   To move LEFT on the
   the GUI-INTERFACE hold
   <volume> down and press A

   CHAT USAGE:

   p4a comes with a simple CHAT
   fascility that uses ncat to
   communicate over specified ports!
   Default port is < 4720 >
   however I recommend strongly to
   change this to another port.
   The application will prompt you 
   to either use the default or custom
   port.

   To start chatting with a another
   user while conducting Pentest
   or whatever you are doing, simply             
   open terminal emulator and press
   the plus button on the upper right 
   right of your terminal emulator
   to open a secondterminal!
   I added two chatServer scripts
   one is for nc on GNU based systems and 
   the other is for nc on BSD systems
   Play around and figure out which one
   will start a server for you!
   
   To Start
   
   - Type su
   - Type botbrew
   - type cd sdcard/Pentest/MultiMedia

   You have now two OPTIONS:

   OPTION 1:

    - If you want to act as a
      CHAT SERVER 
      type  sh chatServerBSD.sh
        -OR sh chatServerGNU.sh
      you will be prompted to either
      use default port < 4270 >
      or enter a custom port
      choose either and press enter 
      you are ready to act as CHAT SERVER

   OPTION 2:
    - If you want to connect to a 
      Chat Server  
      type sh chatCon.sh
      or   sh chatCon.sh
      you will be prompted to enter
      the IP adress of the Server
      enter it.
      you will be prompted to either
      use default port < 4270 >
      or enter a custom port
      choose either and press enter 
      YOU should now be able to chat
      with another fellow user on the same
      network!


   Enjoy and remember I am
   not responsible for the
   headache you AND/OR other
   may experience from the use 
   of this tool...
        
Congratulations you sucsessfully
Installed Penetration Testing for Android

Trouble Shooting:

 Should you experience trouble
 installing and/or using this tool
 Ask someone who is Qualified to help you!
 or send me an email:
 itsfeckingobvious@gmail.com


Special Thanks to:

 - The lads at botbrew.com
 
 - Christian Martorella 
   @Edge-Security.com
   
 - SQLMAP developer's
 
 - ETTERCAP deveoper's
   
 - Scott Duncan and his SimuDrones
       2014 SimuDrone projects         
                                       
   P4A -v 1.0                          
   Benjamin Keil                       
   SimuDrone Projects                  
                                       

   
