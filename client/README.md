CIConnect client
================


To install the client download the content of this directory to a directory in your path.
E.g.
mkdir ~/ciconnect
export PATH="$HOME/ciconnect:$PATH"


To use CIConnect client:

1. Connect login.osgconnect.net:
ciconnect-setup USERNAME
(ener the password when prompted)

2a. Run commands on login.osgconnect.net:
ciconnect ls -l
ciconnect SCRIPT short.sh

2b. Submit a script that will run on the nodes connected to login.osgconnect.net:
(this is equivalent to transfering the files, ssh to  login.osgconnect.net and submit a HTCondor job)
ciconnect-sub --infiles inputfile1,inoutfile2 myscript.sh

To see all the possible options invoke the commands with -h or --help

