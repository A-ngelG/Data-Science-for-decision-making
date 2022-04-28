There is no need to download data files
Just run all the code and everything should automatically be executed and shown.
Open read.me file to see the correct shape of table containing examples.

When running the IHDP.ipynb the resulting ATE test and PEHE test for the models should be shown in a table with the following values:


Method				ATE test	PEHE test
0	SVR			2.486985	2.647361
1	SVR GS			0.161609	0.893808
2	SVR (IPW)		2.171886	2.362368
3	SVR (IPW) GS		0.022090	0.855347
4	T-Learner (RF)		0.144957	0.623375
5	T-Learner (RF) GS	0.040479	0.578961

When running the JOBS.ipynb the resulting ATT test and Policy Risk should be shown in a table with the following values:

	Method			ATT test	Policy Risk
0	RF			0.046802	0.267170
1	RF GS			0.046802	0.267170
2	RF (IPW)		0.009066	0.276589
3	RF (IPW) GS		0.009802	0.308502
4	CF (RF)			0.019135	0.257185
