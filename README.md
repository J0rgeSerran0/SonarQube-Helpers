# **SonarQube Helpers**
SonarQube scripts and helpers that are useful when as DevOps or others, we need to upgrade SonarQube or operate with it under special conditions

## **Windows**

### Install and uninstall the SonarQube Windows Service
> These scripts should be put in the `bin/windows-x86-64` folder

[Windows (batch) script to **uninstall** the SonarQube Windows Service](https://github.com/J0rgeSerran0/SonarQube-Helpers/blob/main/helpers/windows/UninstallNTService.bat)

[Windows (batch) script to **install** the SonarQube Windows Service](https://github.com/J0rgeSerran0/SonarQube-Helpers/blob/main/helpers/windows/InstallNTService.bat)

### Kill SonarQube java instances
> This script should be put in the `bin/windows-x86-64` folder, and will kill the java instances of SonarQube
> 
> Sometimes, when we execute _StopNTService.bat_ and try to backup the db before migrate SonarQube for example, we get an error
> 
> In this point, we could kill the java instances, do the backup/restore and restart all

[Windows (batch) script to **kill/stop** SonarQube](https://github.com/J0rgeSerran0/SonarQube-Helpers/blob/main/helpers/windows/KillSonarQuebeJavaInstances.bat)
