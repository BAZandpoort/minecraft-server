# Minecraft Server Template

How to install on Windows:
1. Install Amazon's Java version 'Corretto 17' from the official Amazon site: [Amazon Corretto](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/downloads-list.html)
2. Download and install Git from: [git-scm.cm](https://git-scm.com/)
3. (Optional) Download Visual Studio Code from: [code.visualstudio.com](https://code.visualstudio.com/Download).
4.  When you have installed Git and opened Git Bash, clone this repository with the following command: 
```git clone https://github.com/BAZandpoort/minecraft-server```
5. Open a terminal of choice and run the run.bat file by typing `./run.bat` in the cloned folder.
6. Once you are in Minecraft, when you add the server, enter the PUBLIC ip.
7. Enjoy playing minecraft on your self hosted server :)  


How to install on Linux Debian:
1. First update and upgrade your linux packages with ```sudo apt update && sudo apt upgrade -y```
2. Install Amazon's Java version 'Corretto 17' from the official Amazon site: [Amazon Corretto](https://docs.aws.amazon.com/corretto/latest/corretto-17-ug/downloads-list.html)
    ```wget https://corretto.aws/downloads/latest/amazon-corretto-17-x64-linux-jdk.deb```
3. install the .deb file with ```sudo dpkg --install https://corretto.aws/downloads/latest/amazon-corretto-17-x64-linux-jdk.deb``` (within the same directory of the file)
4. Install git with the following command: "sudo apt install git"
5. Clone this repository into a new directory with the following command:
         `git clone https://github.com/BAZandpoort/minecraft-server`
6. Finally run the run.sh file with ```bash ./run.sh```
7. When you are in minecraft, enter the PUBLIC ip of the computer where you are hosting the server on.
8. Enjoy playing minecraft on your self hosted server :)
