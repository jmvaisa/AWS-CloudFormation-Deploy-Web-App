To build the system do the following:
Uzip the files.
Using a Windows command line change directories to the unzipped folder location.
to build the environment start with:
./create.bat udagramnw network.yml nw-param.json
Once that has completed, do the following to build out the rest of the environment:
./create.bat udagramserver server.yml server-param.json 
Once that has completed follow the link in the output of the server build. 

To delete the stack do the following
Run 
./delete.bat udagramserver
Then once that has completed run
./delete.bat udagramnw


![Image of Arch Diagram](https://github.com/jmvaisa/AWS-CloudFormation-Deploy-Web-App/blob/master/Udacity%20Project%20Udagram.jpeg)
