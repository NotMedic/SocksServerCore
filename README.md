# SocksServerCore

To compile for running on Linux:

Right click on the Project (not the solution) in the Solution Explorer pane and select "Publish" 
In the new window, click Configure
Select the Configuration specific to your environment
Select a Target Framework
Select Self-Contained as a Deployment Mode
Select the target runtime as linux-x64
Provide a Target Location

Zip up this folder and move it to a linux box
unzip it, and chmod 755 SharpSocksServerCore
run it with ./SharpSocksServerCore with the appropriate options:
  ./SharpSocksServerCore -l http://10.10.10.2:8081 -k Y/z8YmjExk7fO+QQ68MxVAp9G+TT17hRTYx64A01YTo=
