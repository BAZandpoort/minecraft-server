# minecraftServerTemplate

How to install on Windows:
1. install Java from the official Java site: https://www.java.com/en/download/
2. download and install git from the site : https://git-scm.com/
3. (optional) download Visual Studio Code from the site https://code.visualstudio.com/ or from the Microsoft store.
4.  When you have installed Git and opened git bash, clone this repository with the following command: 
        ```git clone https://github.com/J4spr/minecraft-Server-Template```
5. open terminal of choice and run the run.bat file by just typing ```run.bat```
6. Once you are in Minecraft, when you add the server, enter the PUBLIC ip. 
7. enjoy playing minecraft on your self hosted server :)  


How to install on Linux Debian:
1. First update and upgrade your linux packages with ```sudo apt update && sudo apt upgrade -y```
2. Then install Java for Linux. Here are some links where you can download the jdk version 18 from:
    Amazon Coretto: ```wget https://corretto.aws/downloads/latest/amazon-corretto-17-x64-linux-jdk.deb```
        install the .deb file with ```sudo dpkg --install https://corretto.aws/downloads/latest/amazon-corretto-17-x64-linux-jdk.deb```
        (You have to be in the same directory as the file)
    Openjdk: install with ```sudo apt-get install openjdk-18-jre```
3. Install git with the following command: "sudo apt install git"
4. Clone this repository into a new directory with the following command:
         ```git clone https://github.com/J4spr/minecraft-Server-Template```
5. finally run the run.sh file with ```bash run.sh```
6. When you are in minecraft, enter the PUBLIC ip of the computer where you are hosting the server on.
7. Enjoy playing minecraft on your self hosted server :)
