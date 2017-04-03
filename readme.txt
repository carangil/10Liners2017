10Liners 2017
Mark Sherman m@mwsherman.com

 
TRS-80 Color Computer 2 with Extended Color Basic or Disk Extended Color Basic.  
* Plain 'Color Basic' will not work!
* Color Computer 1 will not work, unless it has been upgraded.

Preferred Emulator: XROAR
Preferred ROMs: Color Basic 1.3, Extended Color Basic 1.1 
http://www.colorcomputerarchive.com/coco/ROMs/XRoar/CoCo/BASIC_OS/   (bas13.rom and extbas11.rom)
A sample xroar.conf file is provided for convenience. 

To run in xroar:  
When XROAR is configured properly, it should read "EXTENDED COLOR BASIC 1.1"  If you get a "COLOR BASIC 1.x" greeting instead, not all the ROMs are being loaded correctly.

In XROAR, Go to the File Menu and Select Load.  Choose the KABOOM-10.BAS file.  This loads the file in the virtual cassette buffer.
In the emulator type CLOAD.  The screen should say 'BASIC F', pause for a bit, and then give you back to an OK prompt.  Type RUN.  Note:  Sometime CLOAD will give an IO error.  Try File/Load again, and it will probably work.  I think XROAR has a bug!


KABOOM - 'Missle Command' clone

kaboom-10.bas : Condensed, 10 line version
kaboom-detailed.bas : Normal version, functionally identical, about 100 lines.

Use WASD to move cursor, and SPACE to fire. 




