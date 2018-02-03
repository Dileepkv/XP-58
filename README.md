# XP-58
CUPS filter for thermal printer Xprinter XP58IIH.
source from https://github.com/Zn4rK/xp58 thanks to Alexander

You need to make sure that you have cups installed. If you are compiling on linux, you probably need to run ''' sudo apt-get install libcups2-dev libcupsimage2-dev ''' to get the required header files.

Then create ''' xprinter ''' folder in the ''' /usr/share/cups/model/ ''' 
then copy ''' xp-58.ppd ''' should live in /usr/share/cups/model/xprinter

And the rastertoxp58 to filter
on macosx live in /usr/libexec/cups/filter 
on (some) linux based systems: /usr/lib/cups/filter.
