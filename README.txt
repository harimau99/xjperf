********************************************
*        COMPILATION INSTRUCTIONS          *
********************************************

* Go to the 'utilities' directory
* run the following command (Apache ANT has to be installed on the system) :  
	
xjperf/utilities$ ant release

This script will create a JPerf distribution into the 'release' directory.


**************************************
*        LAUNCH INSTRUCTIONS         *
**************************************

* On windows systems,
	- The 'javaw' (JRE 1.5+) executable have to be into the system path
	- run the following script : jperf.bat

* On Linux / OS X systems, run the following script : 
	- The 'java' (JRE 2.0) executable have to be into the system path (Cannot have run low rather than this version if not 
	  there will be an error during using it)
	- Don't forget to set execution permissions on the jperf.sh script (execute 'chmod u+x jperf.sh')
	- run the following script : jperf.sh
