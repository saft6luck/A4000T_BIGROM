# A4000_BIGROM
>:red_circle:  **This project is still a work in progress as there ares only my test results available yet!**

### What is it about?
The JED configuration in this project enables the original 1MB Kickstart ROM option seen on A4000T mainboards.
This option is also added to my modified versions of the A4000D mainboards.

### How to update the mainboard

To make use of this option you need a GAL like the ATF16V8B-10 for the unpopulated component P155 (BIGROM).
Use the JED file in the logic folder to program this GAL.
Then you need to remove the 2 resistors R155A and R155B and solder a PLCC-20 socket onto the board and insert the GAL.

![Amiga4000T_BIGROM](assets/Amiga4000T_BIGROM.jpg "Amiga4000T_BIGROM")

### How to create a 1MB Kickstart ROM for the A4000T

To create 1MB Kickstart ROMs for the latest Kickstart version I use capitoline. The steps to create a 1MB ROM are described here http://capitoline.twocatsblack.com/index.php/1mb-hyperion-rom.
