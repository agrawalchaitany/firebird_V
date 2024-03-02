installation :
1) install atmel studio 6
note: make sure click on check button for file include before finish
IMPORTANT LINK:
https://elsi.e-yantra.org/resources

atmel :
1)Open atmel studio
2)click new project and select gcc c executable project
3)select ATmega2560 and click ok (note: you can also use search option on side search 2560)
4)you acn now place your code on this open window
5)after writing the code, click build then build solution
6)ater solution is build you will recieve this message at end
"""
Build succeeded.
========== Build: 1 succeeded or up-to-date, 0 failed, 0 skipped ==========
"""
7)This means your code is succesfully build
8)Right click on file name above your code and click open contengency folder
9)Open debug folder and their you will find ".hex" file 
10)open "AVRDUDE_ATMEGA2560" folder that we provided and you will find "sktrun.bat" file there 
11)open cmd in this directory and type "stkrun" and enter ".hex" file location 
12)attach firebird v with laptop through stk calble
13)On the firebird v robot and press enter in cmd
14)now your code will push to firebird and it will start working  

