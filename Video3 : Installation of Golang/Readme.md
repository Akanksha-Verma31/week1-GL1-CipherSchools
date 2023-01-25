# TOPIC : Installation of Golang
## Objective :
- How to check the Preinstalled Go Language Version?
- Downloading and Installing Go

## How to check the Preinstalled Go Language Version?
Before we begin with the installation of Go, it is good to check if it might be already installed on your System. To check if your device is preinstalled with Golang or not, just go to the Command line(For Windows, search for cmd in the Run dialog( + R).

Now run the following command:
```
{
 go version
```
If Golang is already installed, it will generate a message with all the details of the Golang’s version available, otherwise, if Golang is not installed then an error will arise stating Bad command or file name

## Downloading and Installing Go
Before starting with the installation process, you need to download it. For that, all versions of Go for Windows are available on golang.org
Step 1: After downloading, unzip the downloaded archive file. After unzipping you will get a folder named go in the current directory.
Step 2: Now copy and paste the extracted folder wherever you want to install this. Here we are installing in C drive.
Step 3: Now set the environment variables. Right click on My PC and select Properties. Choose the Advanced System Settings from the left side and click on Environment Variables.
Step 4: Click on Path from the system variables and then click Edit. Then Click New and then add the Path with bin directory where you have pasted the Go folder. Here we are editing the path C:\go\bin and click Ok.
Step 5: Now create a new user variable which tells Go command where Golang libraries are present. For that click on New on User Variables.

Now fill the Variable name as GOROOT and Variable value is the path of your Golang folder. So here Variable Value is C:\go\. After Filling click OK.
After that Click Ok on Environment Variables and your setup is completed. Now Let’s check the Golang version by using the command go version on command prompt.
After completing the installation process, any IDE or text editor can be used to write Golang Codes and Run them on the IDE or the Command prompt with the use of command:
```
go run filename.go
```