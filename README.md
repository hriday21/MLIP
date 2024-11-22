# MLIP
Collaboration project on MLIPs with Dr. Mudit Dixit

Week 1 objective : To simulate a layered oxide file in fully sodiated and fully desodiated state 

Error while running python file :
Traceback (most recent call last):
File "/Users/hridayjasani/Desktop/MLIP/Sravan_P2_gulp_calculations_fully_sodiated.py", line 201, in
gulp = GULP(label='NaMgLiNiMnO') # Label can be customized
File "/Users/hridayjasani/ase-env/lib/python3.10/site-packages/ase/calculators/gulp.py", line 77, in init
self.library_check()
File "/Users/hridayjasani/ase-env/lib/python3.10/site-packages/ase/calculators/gulp.py", line 277, in library_check
raise RuntimeError("Be sure to have set correctly $GULP_LIB "
RuntimeError: Be sure to have set correctly $GULP_LIB or to have the force field library.
