----------------------------------
M01_V1001_00WM_CAL
----------------------------------

M01 model using M06 network, model performance is yet to be evaluated

M01 model is copied from M06, the domain and OLB code files changed, and the M11 river network changed as follows:
	removed all beginning with _ except mainpark road
	removed CTT, CLR, CMP, CORD, S343A&B, L28, Tamiami, Ingraham
	removed culvert 25-29
	L29 closed BC added at chainage 0

Main differences from WM model used in ECOLAB (M01_V0920_00WM) are:
  M01 domain extended to the East to match M06
  M01 grid shifted 100 meters west and 100 meters south
  Uses M06 network
  5 layers instead of 3
  M11 timestepping and major parameters are from M06
  No floodcodes in this model
  WM, AD, and WQ are all contained within the same .she file instead of separate files. only a few checkboxed need to be changed to switch between these.

	