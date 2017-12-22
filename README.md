# PeaceMap_MathModel_1
MathModel from ORANGE_5, V_3d, V_3e and data files

V_3d is little plot

V_3e is BIG plot

BOTH HAVE BUG THAT ORIGINALLY LARGER BOX, MADE SMALLER AFTER A CACLULATION, ARE STILL *GHOSTS* THAT CAN BE CLICKED ON


**HOW TO RUN THESE PROGRAMS**


Run Python Scripts in this order:

	1. orange_V_3d/e.py (this only needs to be done once)


For little plot then run python script:

	2. orangeclass_V_3d

	3. orange_V_3d


For BIG PLOT then run python script:

	2. orangeclass_V_3e

	3. orange_V_3e


The data files: b8.txt, b105.txt, c8.txt, c105.txt, ic8.txt, ic105.txt, m8.txt, m105.txt, btextbxy8.txt, and btextbxy105.txt need to be in the same directory that the programs are using

When asked for "ONLY NUMBER n and I will find cn.txt, etc. (#/a, Def=a)"

	type either: 105 (return) or 8 (return)

		105=24 factor model
		8=6 factor model

When asked for "Want to CHANGE parameters (y/n), def=n"
	
	type: (return)


NOTE: for OS10.9.5 or Linux the programs should run, but for WINDOWS you may need to change the comment in orangeclass APP: 

        # self.mainloop() TO THE EXECUTABLE STATEMENT self.root.mainloop()
	
	
TO CHANGE INITIAL CONDITIONS: use the left hand entry widgets and ENTER

TO CHANGE THE CONNECTION MATRIX: click on a textbox, use the left hand entry widget, and ENTER (this will also show only the links into and out of that textbox, use ALL Cij to show all the links)

TO RUN THE CALCULATION: use CALCULATE

TO SWITCH FROM THE LINKS TO THE INITIAL CONDITIONS use IC on the links input

TO RESTORE THE ORIGINAL INITIAL CONDITIONS use ORIGINAL on the initial conditions input
	
