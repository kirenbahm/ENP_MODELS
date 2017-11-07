=====================
V0201
=====================
2017-08-01 keb

added xsects to N-S canal
changed KU   in OL from 0 to 0.01
changed KR   in OL from 0 to 0.0001
changed KFpw in OL from 0 to 0.01
changed KBpw in OL from 0 to 0.0001
changed horizontal extent of OL WQ source TPaq  to be at 15 points in grid, not just the one in the depression
added OL WQ Source: TRACER, same OL extent as TPaq, strength of 1 g/day
xxx undone xxx changed L1 and L2 BCs to stage = 7.5 ft on the East boundary
changed OL/GW boundary/initial conditions - flux to fixed head, and stages - runs now but i'm not sure of what i have here now.....
The v0101 version did not have hardly any surface water, and didn't seem to have interaction between the different state variables of TP. So I was thinking I would raise the stages to get more transport of TP and tracer. after that, might need to change the state-change coefficients to get transfers to actually happen, and also add in dispersion coefficients if they were not there.

=====================
V0101
=====================

=====================
2017-02-16 keb
Renamed 00_WQ to 00WQ
Created new directory level so folder structure would match current scheme
Updated mzp file and created mzp template
Created INPUTFILES directory within model directory
Moved all referenced inputfiles that weren't in the folder into it
  (RF, ET, Soils)
Shortened time period on large rainfall file and renamed file
   (changed from 1997-2010 to just the year 2000)
Deleted unreferenced/unused model setup files
Changed inputfile names to more descriptive names, renamed items to match
Changed M11 model to output to Results folder instead of local directory
File names and paths updated in all model setup files


=====================
2016-00-00 git
Original M04 template created by GIT
