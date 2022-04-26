PRINT OFF THESE INSTRUCTIONS BEFORE CONTINUING

Included below is a STATA version 7 program of the adjusted survival program.

It produces 6 curves (2 crude, 2 mean, 2 weighted) and is called diradj.ado (for direct adjustment, like direct standardization).

STEP 1: PREPARATIONS

Download quest menus for STATA, instructions can be found on the STATA website: www.stata.com/support/quest
Find personal ado directory on computer. This should be c:\ado\personal, if the directory does not exist create a folder “ado” on the c drive with a folder “personal” in the ado folder. You can also check in stata what directory is used for personal ado files by typing: sysdir
STEP 2: DOWNLOADS

Click on diradj and save as diradj.txt in your personal ado directory for STATA (i.e. c:\ado\personal).
Click on sample and click save file to save it to your computer.
Click on clean and save as clean.txt to your computer
STEP 3: OPENING THE DATASET

Open Stata and type quest in the command window
Type set memory 100m in the command window
Type set matsize 800 in the command window
Open the do file editor and open diradj.txt, save as diradj.ado (make sure save type as is ado files and that you save it in your c:\ado\personal folder)
Open clean.txt in the do file editor and save as clean.do (make sure save as type is do files)
Click on STATA again
Click on file and Import Ascii and open sample1.txt
Run clean.do
Type diradj Diab creat CHF male and hit enter, the program should run and display a graph.