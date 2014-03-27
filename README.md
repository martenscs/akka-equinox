akka-equinox
============

This project includes all the dependencies for executing the AKKA OSGi examples:
1. Target definition for Eclipse P2 repositories.
2. OSGi runtime launch with defined dependencies.
3. A P2 repository prepare module.

Steps for executing:
1. clone the git repo.
 git clone https://github.com/martenscs/akka-equinox.git
2. Create new Eclipse workspace and add git repo.
3. Import existing projects from cloned git working folder
	This should show three projects:
	a. akka-build
	b. akka-equinox
	c. net.martenscs.akka.framework.export
4. Expand the akka-build project and open the file akka.target
5. In the upper right corner select "Set as Target Platform"
   this should redefine your target for OSGi development.
6. Right-Click on AKKA Runner.launch file found in akka-build project and select "Run As" --> AKKA Runner
7. Validate that no errors where displayed and that the AKKA application is running
