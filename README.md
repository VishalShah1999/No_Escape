# No_Escape

A game which is developed in c++ using graphics.h file.

If you want to run this file in CodeBlocks first you have to configure graphics.h file using followig steps:<br />
(i) first you have to copy two header files that provided by repo in CodeBlocks --> MinGW --> include folder<br />
(ii) Then you have to copy libbgi.a file and paste into CodeBlocks --> MinGW --> lib folder<br />
(iii) Then you have to open CodeBlocks and goto Settings --> Complier --> Linker settings and there you have to configure path of 
libbgi.a file into "Link Library" and then in "other  linker option" you have to paste this "-lbgi -lgdi32 -lcomdlg32 -luuid -loleaut32 -lole32"
and click to save and you're good to go with the graphics file in CodeBlocks
