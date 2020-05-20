# ucd-project
This is for my UCD project.

This project was executed on an Intel(R) core(TM) i7-6600U CPU @ 2.60GHz 2.81GHz, with 16.0GB of RAM, under Windows 10 pro operating system.

The programming language were C++ and java. 

The developing environments are Eclipse java neon, Visual Studio 2015, with java-8.0-65. 

Used software versions are: gurobi-6.5.1-win64, pthread-x64,expat-2.2.9. 

Dependent libraries are: vns&\_&cpp/lib/Gurobi-6.5.1-win64/win64/bin/gurobi65.dll and vns&\_&cpp/lib/ pthread/lib/x64/pthreadVC2.dll.

Before executing the code, these settings mentioned above should be done. 

Also, if the user want to change input file, just open main.cpp in visual studio and change the file name, then compile it as a .dll file, 
the directory of this file should be added under the system PATH. Make sure that System.getProperty("java.library.path") contains this 
directory, then just run TestMain.java and the solution will write into relative file simultaneously. 

The easiest way to execute the program is to run the vns_cpp.exe in the submit/exe folder.

Here is the output on the console:

INSTANCE: TES99

[ KheGeneralSolve2014(0000001309000E90 TES99_XHSTT2011) div 0

  KheGeneralSolve2014 at start (0.01 secs elapsed):
	
  [ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 426.00000)
	
    Soln                              Defects          Cost
		
    -------------------------------------------------------
		
    SplitEventsMonitor                     64     213.00000
		
    DistributeSplitEventsMonitor           64     213.00000
		
    -------------------------------------------------------
		
    Total                                 128     426.00000
		
  ]
	
  KheGeneralSolve2014 after installing the matching (0.28 secs elapsed):
	
  [ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 806417.00000)
	
    Soln                              Defects          Cost
		
    -------------------------------------------------------
		
    AssignResourceMonitor                 142     417.00000
		
    AssignTimeMonitor                     308  806000.00000
		
    -------------------------------------------------------
		
    Total                                 450  806417.00000
		
  ]
	
  KheGeneralSolve2014 before time assignment (0.29 secs elapsed):
	
  [ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 806417.00000)
	
    Soln                              Defects          Cost
  
	-------------------------------------------------------

AssignResourceMonitor                 142     417.00000

AssignTimeMonitor                     308  806000.00000

-------------------------------------------------------

Total                                 450  806417.00000

]

KheGeneralSolve2014 after time assignment (13.51 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 425.00014)

Soln                              Defects          Cost

-------------------------------------------------------

AssignResourceMonitor                 142     417.00000

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   1       0.00002

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                 163     425.00014

]

KheGeneralSolve2014 after Class assignment (parts 1 and 2) (13.53 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 425.00014)

Soln                              Defects          Cost

-------------------------------------------------------

AssignResourceMonitor                 142     417.00000

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   1       0.00002

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                 163     425.00014

]

KheGeneralSolve2014 after Teacher assignment (parts 1 and 2) (13.67 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 317.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AssignResourceMonitor                 107     309.00000

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                 139     317.00116

]

KheGeneralSolve2014 after Room assignment (parts 1 and 2) (13.80 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 8.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                  32       8.00116

]

KheGeneralSolve2014 after Class assignment (part 3) (13.89 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 8.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                  32       8.00116

]

KheGeneralSolve2014 after Teacher assignment (part 3) (13.98 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 8.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                  32       8.00116

]

KheGeneralSolve2014 after Room assignment (part 3) (14.06 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 8.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

OrdinaryDemandMonitor                   4       4.00000

-------------------------------------------------------

Total                                  32       8.00116

]

KheGeneralSolve2014 before KheMergeMeets (14.12 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 4.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

-------------------------------------------------------

Total                                  28       4.00116

]

KheGeneralSolve2014 after KheMergeMeets (14.17 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 4.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

-------------------------------------------------------

Total                                  28       4.00116

]

KheGeneralSolve2014 at end (14.26 secs elapsed):

[ Soln (instance "TES99_XHSTT2011", diversifier 0, cost 4.00116)

Soln                              Defects          Cost

-------------------------------------------------------

AvoidSplitAssignmentsMonitor           10       0.00100

SpreadEventsMonitor                    12       0.00012

AvoidClashesMonitor                     4       4.00000

LimitBusyTimesMonitor                   2       0.00004

-------------------------------------------------------

Total                                  28       4.00116

]

] KheGeneralSolve2014 returning

INITIAL SOLN: (4, 116) 14 secs

ALGORITHM SOLN: (4, 116) 167 secs

