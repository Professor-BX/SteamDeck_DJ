# SteamDeck_DJ
Various tools for DJ/Music software optimization and use of Serato on Steam Deck

These are various tools to use the Steam Deck with DJ software. 

Prerequisites:

You will need the following tools:

-Windows (sorry SteamOS fans, this is for users on Windows, not for DJ software on Proton)

-Steamdeck Windows Usermode Driver (for joystick mapping)

https://github.com/mKenfenheuer/steam-deck-windows-usermode-driver

-Chris Titus Optimizer utility (will provide instructions on what to use in later video)

https://github.com/ChrisTitusTech/winutil

(please note, not necessary if using a Windows Lite install, this is mainly for getting rid of the junk if using a standard Windows install as, well, there is a lot of junk that you don't need.)

-AMD APU Tuning Utility (V2.0.5.8, currrent XUTU beta does not work for enough users that you should just go for what we know works. You won't get anything extra that is necessary for this setup by using the new version anyway.)

https://github.com/JamesCJ60/AMD-APU-Tuning-Utility/releases/tag/2.0.5.8

Windows Download Shortcut: https://github.com/JamesCJ60/AMD-APU-Tuning-Utility/releases/download/2.0.5.8/AATU.Standard.zip

Load the AATU preset file above in your AATU folder after you unzip it but before first run. Then go to the "custom scripts" section and select the "HiTDP DJ" Preset from the drop down and apply. 
(Little note: the Steam Deck's version of TDP is weird. Honestly going above 15w doesn't really do much, but I've seen fewer dips when running at over 15w. Truthfully it could be just snake oil, but I choose to believe.....cue Mulder voice over.)

SWICD Key Map: for Serato DJ navigation/track load/browse use. 

***after installing SWICD, drop the folder above in your documents folder. We could also go with Windows Steam Deck Tools as a driver, but the key rempapping capabilities are not as comprehensive as in SWICD, and not suitable for use as a Serato Key Map navigation assistant.

-D-pad is up/down (fast) and switch between crates/browser (left/right)
-Y and A are single click (fine) up/down
-X/A are load to left/right decks
-3 line button loads selected track to prep crate
-2 square button by the D-pad is enter key (important if using with a Serato beta)
-R1 is the space bar to enter into browse view. Please note that, if within browser view, this function does not work and the user needs to toggle into full view first.
